# ML_Notes

# *Git - Notes*

- cd E:/Sem7
- ls                                                  <- means list of items in that folder
- git clone https://github.com/jayadeep8712/ML_Notes.git 
- *o/p ->  Cloning into 'ML_Notes'...*
- cd ML_Notes
- ls
- git add .                                           <- '.' means add all files in the folder
- git commit -m "add files"
- git push

//-----------

- mkdir ml_lab-5                                      <- creates a folder (Directory)
- git add .
- git commit -m "empty file"
- #^ *o/p -> Your branch is up to date with 'origin/main'*
- *o/p -> nothing to commit, working tree clean*
- cd *lab-5                                           <- means select that file which has something on the left side of the * but lab-5 present on the folder name
- Ex :  cd my*                                        <- means the folder name starts with my and remaining name what ever let it be select that file
- touch .gitkeep                                      <- means creates a  .gitkeep file to a newly made folder (directory) which is empty. so to add such empty directories we use this
- git add .
- git commit -m "new files"
- *o/p -> create mode 100644 my-new-directory/.gitkeep*
- git push


- git rm --cached ml_lab-1                            <- means to remove that directory (only works for repos delection)
- git submodule add <url> ml_lab-1                    <- If you meant to add a submodule, we use this

