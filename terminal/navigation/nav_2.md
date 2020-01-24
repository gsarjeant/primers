In the previous exercise, we navigated to the `primers` subdirectory. It's common to want to return to the home directory, so how could we do that?

We can always use the `cd` command followed by the path to the home directory as long as we remember it, but it's not always easy to remember, and the path to the directory is a bit long. This is a bit inconvenient.

Fortunately, the terminal provides a shorthand for the home directory. The tilde symbol (`~`) refes to the home directory. So, to navigate back to the home directory, you can enter `cd ~`. Let's try that now:

![nav-home](https://i.imgur.com/TpfDd4g.gif)

As you can see when we enter `pwd` after `cd ~`, we are now back in the home directory. 

We'd like to get back to the `primers` directory now. Again, we could enter `cd primers` to get back there. But we can also use another bit of terminal shorthand.

The dash (`-`) symbol refers to the previous working directory. So since we just came from the `primers` directory to get to the home directory, we can enter `cd -` to get back to the `primers` directory. Give it a try:

![nav-previous](https://i.imgur.com/dUvqQlq.gif)

As you can see, we're back in the `primers` directory. What do you think will happen if we enter `cd -` again? Let's see:

![nav-back-home](https://i.imgur.com/oY5JApT.gif)

We're back in the home directory. Because `cd -` always returns us to the previous working directory, and we were previously in the home directory, entering it again took us back home. Let's get back to `primers`. As you may have guessed, we can do this by just entering `cd -` again, since we were just in the `primers` directory.

![nav-back-primers](https://i.imgur.com/ajwsJz6.gif)

There's one more bit of common directory navigation shorthand. Frequently, you will want to move one level back in the directory hierarchy. What does that mean? Consider the location of the `primers` directory:

```
/Users/gsarjeant/primers/
```

What this means is that the `primers` directory is a subdirectory of the `/Users/gsarjeant/` directory, or that `/Users/gsarjeant` is the parent directory of the `primers` directory. As you know by now, `/Users/gsarjeant/` is my home directory. So, I could also get back to the home directory by telling the terminal to move me to the parent directory of my current working directory, or to move one directory up in the hierarchy.

In the terminal, the `..` symbol refers to the directory that is one level up from where I am now. So, if I want to move up one directory in the hierarchy, I can enter `cd ..`. Let's try that now to use a different way to get back to the home directory from the `primers` directory:

![nav-one-up](https://i.imgur.com/DUkVKvW.gif)

As you can see, we're back in the home directory. Looking at the directory path may help clarify the concept of being one directory up the hierarchy.

`primers` directory path: `/Users/gsarjeant/primers/`
home directory path: `/Users/gsarjeant/`

So, `/Users/gsarjeant/` is the parent directory of `/Users/gsarjeant/primers/`, and we used the `cd ..` command from `/Users/gsarjeant/primers` to navigate one level up, to the parent of `/Users/gsarjeant/primers/`, which is `/Users/gsarjeant`.

Now, the last thing we want to do is get back to the `primers` directory so we can continue the exercises. Since we were just there, we can again use our old friend the `cd -` command to get back to it:

![nav-final-primers](https://i.imgur.com/RtT0k1P.gif)

And we're back in the `primers` direcory. With the commands you've learned in the last two lessons, you can easily navigate your filesystem from the terminal. Let's review what we've learned and then move on to some more commands.

### Recap

1. `cd ~` - returns you to the home directory
1. `cd -` - returns you to the prvious directory
1. `cd ..` - takes you one level up the directory hierarchy