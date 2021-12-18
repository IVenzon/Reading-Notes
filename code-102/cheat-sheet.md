# Cheat Sheet

## Chosing a Text Editor:

While there are a lot of text editors out there to choose from, there is no definitive "best". The best text editor for you is the one you enjoy using the most.

Some important factors to consider when choosing a text editor are code completion, syntax highlighting, colors/themes, and extension compatibility.

- Code completion is sort of like an auto-correct/auto-complete function. When you start typing something, it will give you options to auto-complete based on what you have typed, which can save you time and prevent typos. Some text editors will even close tags, brackets, or quotation marks for you, which is great quality of life.
- Syntax highlighting helps distinguish each element of your text by using certain colors for each type. For instance, tags may be colored orange, while regular text is colored white. This makes it easier to see what's in your text, and also makes it easier to spot potential sources of error.
- Colors and Themes will help relieve eye stress by using darker colors, but are also just fun ways to personalize your experience.
- Extensions can add extra functionality to your text editor, which can increase your productivity and quality of life.

## The Command Line:

The command line (or terminal) is a text-based interface with the system. It allows you to directly input commands to the computer.

Within the terminal, there is something called the shell. The shell is the part of the OS that defines how the command line will behave and react to your commands. While there are lots of shells, the most common one is bash (which stands for Bourne again shell).

### Paths

One important aspect of using the command line is the concept of paths.

Within the terminal, there two types of paths: absolute and relative.

The file system under linux is hierarchical. That is, at the very top of the structure lies the root directory. It is denoted by a slash (/), and has many tiers of subdirectories. Files can reside in any of these directories.

Absolute paths specify a location in relation the root directory. They are easily identifiable, as they always begin with a forward slash (/).

Relative paths specify a location in relation to our current location in the system. They do not begin with a slash.

Here are some important things to keep in mind when using paths:

- the tilde key (~) is a shortcut for your home directory.
- the period/dot key (.) is a reference to your current directory.
- two periods/dots (..) reference the parent directory. Using this several times allows us to keep going up the directory hierachy.

### Files

In linux, everything is a file. This includes text files, directories, and in a way, even the physical components of your computer.

Linux is also an extensionless system. While in other OS use file extensions to determine the type of file you are looking at, linux ignores them and just looks inside of the file itself. Using the file command can help us determine exactly what type of file we are looking at.

Linux is also sensitive to formating, such as capitalization and spaces.

When it comes to capitalization, Linux is case sensitive. This means that you can have two files with the same name, but if they have different capitalization (say file1.txt and File1.txt) Linux will treat them as two distinct files.

When it comes to spaces in directories, there are two main ways to get around them.

1. Use quotes around the item name (ex. cd 'My Homework'). Anything inside quotes is treated as a single item.
2. Use an escape character, which in this case is backslash (\). Using backslash before the space (or any special character) nullfies the meaning of the next character. (ex. cd My\ Homework)

If we want to see hidden files within a directory, we can modify the ls command with the option -a (ex. ls -a Documents). This will show us any hidden files/directories.

### Commands

There are many important commands which allow us to properly utilize the terminal, such as:

- The echo command displays messages. For instance, if you want to know what shell you are using, typing 'echo $SHELL' will tell you.
- The pwd command (print working directory) tells you what your current working directory is. Since we will be moving around a lot while using the terminal, this is an important command to help keep yourself oriented.
- The ls command (list) tells ur our current location. Unlike the pwd command, the ls command can accept arguments, which allows us to do much more with it. For example, typing ls -a will show any hidden files/directories.
- The cd command (change directory) allows us to move around our system. Typing cd [location] moves us into the desired directory.
- The file command tells us the file type of our specified file. Typing file [path] will tell us the file type of the file in the path.

### Shortcuts

There are also several useful shortcuts to keep in mind when using the terminal, such as:

- Use the up/down arrows to traverse the command line history. Since all commands are stored, this is easier than re-entering a command.
- Running the cd command without any arguments will always take you back to your home directory
- Tab completion allows us to auto-complete path names. If the first tab does nothing, whis means there are multiple possibilities, and hitting tab more times will try to auto-complete again based on these options. In the case where there is a space in the directory name, using tab completion before the space occurs will automatically escape/nullify any spaces in the name for you.
