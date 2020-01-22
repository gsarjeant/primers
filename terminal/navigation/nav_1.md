When you first launch the terminal, you will see a prompt with a cursor that looks something like this:

```
> █ 
```

Please note that the character may be different and there may be some text ahead of it. 

This is known as the __terminal prompt__. It is where you enter commands. To start, let's get oriented.

The terminal always opens to your __home directory__. This is the default location for all of your personal files on the computer. For our first command, we'll find the location of your home directory.

Enter the following text at your command prompt and press [Enter] or [Return] to execute the command:

```
pwd
```

![pwd](https://i.imgur.com/Y8JnuHh.gif)

Congratulations! You've entered your first terminal command. The `pwd` command prints the location of the current working directory to the screen. Since we just opened the terminal, it returned the location of your home directory. In my case, this is:

```
/Users/gregsarjeant
```

So now that we know where we are, how do we know what is in this directory? You can list the contents of any directory using the `ls` command. Let's try it:

```
ls
```

![ls](https://i.imgur.com/GNjSqlf.gif)

This will show you a list of the files and directories in the current directory. In my case, it returned the following (your list will be different):

```
Desktop     Downloads   Library     Music       Pictures    applescript projects
Documents   Dropbox     Movies      OneDrive    Public      primers     utils
```

If you set up this repo on your local system as described in this section's [README](./README.md), then you should see a `primers` directory listed amongst the contents. If it's not there, go back to the README and follow those steps and then come back here.

We want to be working out of the `primers` directory, so how can we do that? In order to change your working directory, you use the `cd` command, followed by the name of the directory that you want to change to. Let's try it:

```
cd primers
```

![cd](https://i.imgur.com/OQEL5d4.gif)

Mow let's use the previous two commands to print our new working directory and list the contents

```
pwd
ls
```

![pwdls](https://i.imgur.com/IHKmyyi.gif)

You should see that you are in the `primers` subdirectory of your home directory, and `ls` should have shown you the contents of the repository (these will likely be different from the image, because I'll be adding to it after making the recording, but this hould give you an idea of what to expect).

If you've done all this, you've successfully switched to a new directory and displayed its contents. Let's recap the commands we've introduced so far:

1. `pwd` - prints the current working directory to the screen
1. `ls` - lists the contents of the current working directory to the screen
1. `cd` - changes to a new directory

You now know the basics of navigating your computer from the terminal. Let's extend this knowledge with some more common navigation commands.