## Command Line Basics

In contrast to a GUI, or graphical user interface, the command line lets us tell our computer exactly what we want it to do using successive lines of text. 

The command line is one of the primary ways of using Git on your computer. We're going to learn this method first so we can really grasp the concepts of Git (and feel like we have computational superpowers, making files appear out of thin air). 

### Open your Terminal. 

Mac: press the space bar and the command key at the same time and type in "terminal."
Windows: launch the command prompt from the run window. 

### Go to your Desktop.

`cd [name of directory or folder]` will let you navigate inside a directory of your choosing.

Type `cd Desktop` and hit enter.

Now, `cd ~` lets you go back a directory.

Practice going back and forth between your Desktop and your home directory. Experiment! The more you type the more natural the command line will feel. 

Got lost?

`pwd` or "print working directory" will tell you where you are if you get a little lost.

End on your Desktop. 

### Make a new folder on your Desktop.

`mkdir` makes a new directory.

Type `mkdir GitPractice` and hit enter. 

Click around to go check out your desktop and see your new folder. 

### Initialize Git. 

Using `cd`, navigate inside the folder 'GitPractice.' 

Type `git init` and hit enter.

This initializes the Git repository. Now, by using commands like `git add` and `git commit`, you can track changes to your documents.

### Add a file to your folder. 

Back in the command line, we're going to make a plain text markdown file.

Make sure you're navigated inside your GitPractice folder. Use `cd` or `cd ~` as needed.
 
Now, type `touch [name].md` The '.md' extension means "markdown." You can use `touch` to create other types of files, too.

### Edit your file.

`open [name].[extension]` will let you get started.

Whatever text editor pops up should be the one that you set in your `git config`. To change this, edit the `.git/config`. I use [TextWrangler](http://www.barebones.com/products/textwrangler/). Write and save as usual. Remember how to open files (described right above!).
