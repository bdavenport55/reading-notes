# Lab 03 Revisions and the Cloud

This exercise has taught me that, like code itself, the text editor and terminal will do exactly what you tell it to, nothing less and nothing more.  If you expect a certain change to be made or certain thing to happen, you must explicitly write the command to do so.

## Read 03

### What is Git?

Git is a "Distributed Version Contol System", which is a way for dispersed users to collaborate on one piece of work.  For example, if persons A, B, and C are working on the same project from different terminals, they all have access to the most recent version of the project, can see the changes that have been made to it, and can make changes themselves, all of which are accessible by the other users.
The main points of it are:

* Local Operations - code is written and manipulated on a user's local terminal
* Tracking Changes - Every change made to a file or directory is tracked by Git
* Loss of Data - The multiple points of storage, the "distributed" nature of Git, greatly decreases the chance of losing data
* States - Files can exist in three different states

  * Committed - Data is securely stored in a local database
  * Modified - A file has been changed but not committed
  * Staged - Identifies which files/directories are going to be committed, a "queue" of sorts

### Local vs. Remote

Diving more into the distributed nature of Git, there is the concept of local vs. remote. Something local is something stored on one's terminal, i.e. on your computer.  Something stored remotely is something accessible to other users on some sort of holding container.  One of the most common and popular remote locations is GitHub. Git can be created in either location and copied to, or "cloned", to the other.  When changes are made in one, steps must be taken to update the other with the changes.  That is where modifiying, staging, and committing comes into play.

### Git Lifecycle

Say you want to edit a file and you are working on your local terminal.  In your chosen text editor, you make changes to a file, you *modify* it.  You want these changes to reflect in the remote so everybody else can see them, too. So next, you need to choose the file(s) you changed and declare that you want to publish them, or, *stage* them.  Then, you enact the changes, or, *commit* them. Finally, you *push* the changes, or send the information to the remote so it can be displayed there.

<br>

### [Back](reading-notes/102/102-TOC.html)