# Users and Permissions Exercise

## Learning Objectives
- Understand the concepts and principles of user and permission management in Linux system

### Estimated Time: 1 hour

## Exercise
These exercises should help you practice your knowledge of user and permission management in Linux. Good luck!

### Instructions
IMPORTANT NOTE: Read all instructions carefully before starting the exercise.

- Create a new user account named `testuser` with a home directory of `/home/testuser`.
- Grant `testuser` read and write permissions for a file named `testfile.txt` located in the `/var/www/html` directory.
- Create a new group named `developers` and add `testuser` to this group.
- Grant the `developers` group read and write permissions for a directory named `/opt/develop`.
- Change the ownership of a file named `important.txt` to `testuser`.
- Revoke all permissions for a file named `private.txt` so that only the owner can access it.
- Use the `chmod` command to grant read and execute permissions to the owner and group for a script named `myscript.sh`.
- Use the `chown` command to change the ownership of a directory named `/var/log` to `root`.
- Use the `ls` command to view the permissions and ownership of a file named `data.txt`.
- Remove a user account named `olduser` and ensure that all files owned by this user are also deleted.

### Submit your work
- Create a document with the answers/commands you used to complete the exercise.
- Add screenshots of the output of the commands you used to complete the exercise.
- Submit your work on the slack channel for this activity.

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change.](https://github.com/cloudessencegithub/Acceler8/issues/new)_
