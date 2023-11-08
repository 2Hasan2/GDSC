# Command Line Basics

This document provides a list of essential command lines frequently used in various operating systems.

## List of Important Command Lines

1. **cd (Change Directory):** Allows you to change the current directory.
```
cd /path/to/directory
```


2. **ls (List):** Lists the contents of a directory.
```
ls
```



3. **pwd (Print Working Directory):** Displays the current directory path.
```
pwd
```



4. **mkdir (Make Directory):** Creates a new directory.
```
mkdir new_directory
```



5. **rm (Remove):** Deletes files or directories.
```
rm filename
rm -r directoryname
```



6. **cp (Copy):** Copies files or directories from one location to another.
```
cp file1 file2
```


7. **mv (Move):** Moves or renames files and directories.
```
mv file1 file2
```

8. **touch:** Creates a new file.
 ```
touch filename
 ```

9. **grep (Global Regular Expression Print):** Searches for a specific string in files.
```
grep "search_string" filename
```

10. **chmod (Change Mode):** Changes permissions of files and directories.
 ```
 chmod permissions filename
 ```

11. **sudo (Super User Do):** Executes a command with administrative privileges.
 ```
 sudo command
 ```

12. **apt (Advanced Package Tool):** Package manager for Debian-based systems like Ubuntu. Helps install, update, and remove software packages.
 ```
 sudo apt-get install package_name
 ```

13. **echo:** Prints a string to the terminal or a file.
 ```
 echo "Hello World"
 echo "Hello World" > filename
 ```

14. **ssh (Secure Shell):** Connects to a remote machine securely.
 ```
 ssh username@hostname
 ```

15. **man (Manual):** Displays the manual pages for a command.
 ```
 man command_name
 ```

16. **exit:** Exits the current shell.
 ```
 exit
```

17. **clear:** Clears the terminal screen.
 ```
 clear
 ```

18. **cat (Concatenate):** Displays the contents of a file.
 ```
    cat filename
```

19. **head:** Displays the first 10 lines of a file.
 ```
 head filename
 ```

20. **tail:** Displays the last 10 lines of a file.
 ```
    tail filename
```

21. **wc (Word Count):** Displays the number of lines, words, and characters in a file.
 ```
 wc filename
 wc -l filename
 wc -w filename
 wc -c filename
 ```

22. **sort:** Sorts the contents of a file alphabetically.
 ```
    sort filename
```

## git commands

1. **git init:** Initializes a new git repository.
 ```
 git init
 ```

2. **git clone:** Clones a remote git repository.
 ```
 git clone 
 ```

3. **git add:** Adds files to the staging area or * for all files.
 ```
 git add filename 
 git add *
 ```

4. **git commit:** Commits changes to head for deployment.
 ```
 git commit -m "Commit message"
 ```

5. **git push:** Pushes changes to remote repository.
 ```
 git push origin master
 ```

6. **git pull:** Pulls latest changes from remote repository.
 ```
 git pull
 ```

7. **git status:** Displays the status of the working directory.
 ```
 git status
 ```

8. **git branch:** Lists all the branches in the current repository.
 ```
 git branch
 ```

9. **git checkout:** Switches to the specified branch and updates the working directory.
 ```
 git checkout branch_name
 ```

10. **git merge:** Merges the specified branch’s history into the current branch.
 ```
 git merge branch_name
 ```

11. **git reset:** Resets the working directory to the last git commit.
 ```
 git reset --hard HEAD
 ```

12. **git stash:** Temporarily saves changes that you don’t want to commit immediately.
 ```
 git stash
 ```

 13. **get fetch:** Fetches all the objects from the remote repository that don’t currently reside in the local working directory.
 ```
 git fetch origin
 ```

14. **git remote:** Shows all the remote versions of your repository.
 ```
 git remote -v
 ```

15. **git log:** Shows a listing of commits on a branch including the corresponding details.
 ```
 git log
 ```