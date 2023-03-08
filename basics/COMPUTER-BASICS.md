# Computer basics

## The computer is good at following orders
Yes, the computer is very good at following orders, but those orders have to be 
very specific and specify all steps needed. Unlike a person, if you tell it to 
go outside and play, you'll have to tell it that first it needs to open the door,
or it will be stuck inside forever.

## There are different operating systems
Just as you may have an iPhone that has **ios** or a Motorola that has **Android**,
there are different operating systems for the computer. The most common nowadays are
- Windows
- Linux
- Unix
- MacOS (which is a Unix variant)

## The files in your computer are organized in folders
Some call them directories, but the idea is the same: you have folders that can
have files or more folders, that can have more files or folders, etc.
Typically, we use forward slashes `/` or back slashes `\` to represent a path.

### Linux an Unix
In Linux and Unix everything is directories and we use forward slashes. 
For example, your user directory is located at 
```
/home/<your-username>/
```
and if you save a file there, its path would be
```
/home/<your-username>/awesome_pic.jpg
```

### Windows
In windows we use back slashes and there's the concept of **drive**, which originally was mapped to 
floppy disks as **A:** or **B:** (google an image of floppy disk) but now 
it usually refers to your storage unit, which typically would be **C:**, but could also be other letter. 
For example, your "documents" are probably stored at
```
C:\Users\<your-username>\Documents
```

## A programmer must know how to use a terminal
If you're serious about programming, you must know how to do a few things in a terminal

A terminal is that black window that you see in the movies where hackers do their stuff.
There, you can only type commands (and select with your mouse to copy text). 

There are different types of terminals. To open a terminal in windows, use "Ctrl + Esc", and then 
type cmd. That will bring up a command prompt, which is one of the most basic ones. A few useful commands
```
dir                   <--- show the contents of the current directory
cd <some directory>   <--- we use this to change directory to a specific folders
cd ..                 <--- change directory to one level above
mkdir <dir name>      <--- creates a directory (or folder)
rmdir <dir name>      <--- deletes a directory
```
### Exercise:
1. Open a command prompt and try to navigate to your documents directory using only **cd** (hint: see the previous section)
2. There, create a directory
3. Use **dir** to see that your directory is there
4. Type `explorer .` and see what it does
5. Return to your terminal, and delete the directory
6. Use **dir** to verify that the directory is no longer there. Look in your explorer 

**Bonus** use the up and down arrows to navigate to your previous commands.
