# Hide Files in the file tree

Easily focus on the task at hand by hiding irrelevantly files and directories.

## Feature
* hide file or directory
* unhide all hidden files

## Usage
* Hiding
  * hide file or directory from context menu in tree view
  * hide file by using
    * Mac: `SHIFT + CMD + H`
    * Windows/Linux: 'SHIFT + CTRL + H'
* Unhide everything
  * unhide by using with the command bar or keys:
    * Mac: `SHIFT + CMD + U`
    * Windows/Linux: `SHIFT + CTRL + U`
* Unhide children of a directory
  * unhide by right clicking a directory and selecting "Unhide Children"

* Hide files specified in .hideInTxtEd
 ```
 #this is an example .hideInTxtEd file
 #empty lines are ignored

 #any matching file/dir path (relative to the current dir) will be hidden:
 somedir
 foo.txt
 bar.txt
 otherdir/baz.txt
 otherdir/yetanotherdir
 #hide this file also
 .hideInTxtEd
 ```
