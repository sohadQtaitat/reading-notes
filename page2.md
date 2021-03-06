# Text editors and Commands

#### Hello, This is Fatima. You can view my Markdown webpage using the following [link](https://fati-ma.github.io/reading-notes/page2)
### You can go back to the Home page using the following [link](https://fati-ma.github.io/reading-notes).

### In this blog I will do a summary of the following topics: :smile:
:arrow_right: - [Choosing A Text Editor](https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf)

:arrow_right: - [The Command Line!](https://ryanstutorials.net/linuxtutorial/commandline.php)

:arrow_right: - [Basic Navigation!](https://ryanstutorials.net/linuxtutorial/navigation.php)

:arrow_right: - [More About Files!](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)


### For the first topic **Choosing A Text Editor**

A **text editor** is _a piece of software that you download and install on
your computer, or you access online through your web browser, that
allows you to write and manage text, especially the text that you write
to build a web site_. The text editor has to be one of the ***most
important tools*** you can use as an aspiring web developer.

One of its features is **syntax
highlighting**. Syntax highlighting is a feature that takes the text you
type, and makes it _more noticeable_ by colorizing the text. Attributes
are a different color than elements. And elements are a different color
than copy. This makes it so much easier when you’re looking for an
error and you can’t find it. As well as making your text easier to read.

![highlit](https://codehighlight.com/img/javascript-with-syntax-highlighting.png)

#### Some Third-Party Options: 

1. Atom
2. Notepad++
3. Visula Studio Code

### For the second topic **The Command Line!**

A **command line**, or _terminal_, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

#### The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands. Here is an example:

``` 
user@bash: ls -l /home/ryan
total 3
drwxr-xr-x  2 ryan users 4096 Mar 23 13:34 bin
drwxr-xr-x 18 ryan users 4096 Feb 17 09:12 Documents
drwxr-xr-x  2 ryan users 4096 May 05 17:25 public_html
user@bash:
```

#### Opening a Terminal:

- If you're on a **Mac** then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up.
- If on **Linux** then you will probably find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'.
- If you are on **Windows** and intend to remotely log into another machine then you will need an SSH client. A rather good one is [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) (free) .



### For the third topic **Basic Navigation!**

The first command is **pwd** which stands for *Print Working Directory*. 
The command does just that. It tells you what your current or present working directory is.

```
user@bash: pwd
/home/ryan
user@bash:
```

The second command is **ls** it tells What's in your current location

```
user@bash: ls
bin Documents public_html
user@bash:
```
#### Paths

There are *2 types of paths* we can use, **absolute and relative**. Whenever we refer to a file or directory we are using one of these paths. 

***File system under linux is a hierarchical structure.*** At the very top of the structure is what's called the **root** directory. It is denoted by a single slash ( / ). 
It has subdirectories, they have subdirectories and so on. Files may reside in any of these directories.
**Absolute paths** _specify a location (file or directory) in relation to the **root** directory._ You can identify them as they always **begin with a forward slash ( / )**
**Relative paths** _specify a location (file or directory) in relation to **where we currently are** in the system._ They **will not begin with a slash**.

### For the fourth topic **More About Files!**

In **linux**  *everything is actually a file*. 
A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only).
In **Windows** the _extension of file is important_ and the system uses it to determine what type of file it is. 
Under **Linux** the system actually _ignores the extension_ and looks inside the file to determine what type of file it is. 
There is a command called file which we can use to find this out.

```
file [path]
```

Systems such as *Windows* are _case insensitive_ when it comes to referring to files. 
**Linux** is _not like this_. As such it is possible to have two or more files and directories with the same name but letters of different case.

#### As a summary
| Windows      | Linux |
| ----------- | ----------- |
| File extension is important      | File extension is not important       |
| Case insensitive_   | Case sensitive_        |
