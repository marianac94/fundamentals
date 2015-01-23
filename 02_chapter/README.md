**WDI Fundamentals Chapter 2**

---

>**NOTE**: By the end of this Unit, you'll be able to:
>* - Define a version control system and it's benefits
>* Describe how Git works
>* Identify the Git commands used to set up a local respository and to record snapshots
>* Update a remote repository with local changes to a text file, from the command line

---


#Version Control

When you’re working on something, say a painting, software or an autobiography, there comes a time when you wish you had a reset button.

You might already have a system in place to deal with this problem –maybe you save your document multiple times with different names, so that you can return to a different stage of the project.

![Version Control](../assets/chapter2/version-control.gif)

Developers call this process a “version control system”.

The tool we'll be using for version control is called Git.  

Git saves a history of the changes you make for you –no need to keep multiple versions of a file on hand. 

Aptly named, Git is not too bright.  It needs you to tell it which files to track and how often to save a version.


How it works is this: you put Git in a folder and tell it which files to track (or to track all of the files in the folder)...


...and then every time you want to save a version –when you’ve completed the first chapter in your book –you tell Git to ‘commit’ that version to memory.


If you want to revert to an old version you can do that.  If you want to view the difference between two versions of a file, you can do that too.

###Example
Imagine you are working on a piece of code.  Let's call it version 1:

```js
var eureka = "The meaning of life is the following number"
var meaning_of_life = 42
console.log("Guys, I've figured it out. \(eureka) is \(meaning_of_life)!")
```




