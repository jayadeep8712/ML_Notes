# ML_Notes

> ###  *Git - Notes*

- cd E:/Sem7 ( cd .. <- previous folder, clear <- in Gitbash & cls <- in cmd prompt for clear)
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
   - rm 'css/about.css'
   - rm 'css/general.css'
 
- - - -

### *How to clone a git repo to an existing folder (not empty)*
 
1. **Navigate to the Existing Directory**:
   ```bash
   $ cd my/folder/
   ```

2. **Initialize a New Git Repository**:
   ```bash
   $ git init
   ```

3. **Review and Create a `.gitignore` File**:
   - Identify which files or directories should be excluded from version control.
   - Edit the `.gitignore` file accordingly.

4. **Create Your First Commit Locally**:
   ```bash
   $ git add .
   $ git commit -m 'My first commit'
   ```

5. **Add a Remote Repository (Origin)**:
   ```bash
   $ git remote add origin https|ssh:path/to/the/repository.git
   ```

6. **To verify that it has been added correctly, run**:
   ```bash
   $ git remote -v
   ```

7.  git push --set-upstream origin main


8.**Using --allow-unrelated-histories**:
   This magical flag tells Git, “Hey, it’s okay if the histories are unrelated; go ahead and merge anyway!”
   ```bash
   git pull origin main --allow-unrelated-histories
   ```


9. **Pull and Merge with the Remote Repository**:
   ```bash
   $ git pull origin main
   ```

 
