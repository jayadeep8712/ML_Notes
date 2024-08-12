# ML_Notes

> ###  *Git - Notes*

- cd E:/Sem7
- ls                                                  <- means list of items in that folder
- git clone https://github.com/jayadeep8712/ML_Notes.git 
   1. ***o/p ->  Cloning into 'ML_Notes'...***
- cd ML_Notes
- ls
- git add .                                           <- '.' means add all files in the folder
- git commit -m "add files"
- git push

  - - - -
> ### *To add an empty dir to my repo*
- mkdir ml_lab-5                                      <- creates a folder (Directory)
<!-- - git add .
- git commit -m "empty file"
  1. ***o/p -> Your branch is up to date with 'origin/main'***
  2. ***o/p -> nothing to commit, working tree clean*** -->
- cd *lab-5                                           <- means select that file which has something on the left side of the * but lab-5 present on the folder name
- Ex :  cd my*                                        <- means the folder name starts with my and remaining name what ever let it be select that file
- touch .gitkeep                                      <- means creates a  .gitkeep file to a newly made folder (directory) which is empty. so to add such empty directories we use this
- git add .
- git commit -m "new files"
  1. ***o/p -> create mode 100644 my-new-directory/.gitkeep***
- git push

  ![picture alt]( https://itknowledgeexchange.techtarget.com/coffee-talk/files/2020/09/what-is-gitkeep-example.png ".gitkeep")

- git rm --cached ml_lab-1                            <- means to remove that directory (only works for repos delection)
- git submodule add <url> ml_lab-1                    <- If you meant to add a submodule, we use this


- git rm file.txt                                     <- To remove a file both from the Git repository and the filesystem, you can use  git rm without any parameters (except for the file's name, of course)
- git rm file2.txt --cached                           <- If you only want to remove the file from the repository, but keep it on the filesystem, you can add the --cached flag
- git rm css/* --dry-run                              <- When trying to delete multiple files in a directory or via a glob pattern, you might want to perform a "dry-run" first and see which files would be removed
  rm 'css/about.css'
  rm 'css/general.css'
 
