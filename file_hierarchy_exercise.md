# File system hierarchy and organization Exercise

## Learning Objectives
- Understand the usefullness of the file system hierarchy and organization in Linux system

### Estimated Time: 1 hour

## Exercise
These exercises should help you practice your knowledge of file system hierarchy and organization in Linux. Good luck!

### Instructions
IMPORTANT NOTE: Read all instructions carefully before starting the exercise.

- Using the command line, navigate to the /etc directory and list its contents. Then, navigate to the /usr/bin directory and list its contents. What are the differences between the two directories in terms of their contents?
- Create a new directory called "testdir" in your home directory, and then create a new file called "testfile.txt" within this directory. Change the permissions of the file so that only the owner has read and write permissions. Finally, rename the file to "newtestfile.txt".
- Create a new file called "secret.txt" in the testdir directory you created in Exercise 2. Change the permissions of the file so that only the owner has read and write permissions, while all other users have no access to the file. Try to access the file as a different user, and observe what happens.
- Move the "newtestfile.txt" from the testdir directory to the /tmp directory, and then make a copy of this file in the same directory with a different name. Finally, delete the original file from the testdir directory.
- Create a symbolic link from the /var/log directory to the testdir directory. Then, create a new file within the testdir directory, and observe where it appears in the file system hierarchy.

### Submit your work
- Create a document with the answers/commands you used to complete the exercise.
- Submit your work on the slack channel for this activity.

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change.](https://github.com/cloudessencegithub/Acceler8/issues/new)_