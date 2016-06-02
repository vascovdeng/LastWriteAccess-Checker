# LastWriteAccess-Checker
A program to mass check for changes in directories or files

For my final project during my second internship I was tasked to create a program to check all files or directories inside a given path. The user can tell the program what it needs to do:

..*Wether to check files or directoories. This is set with the *totalize* option. If the user wants to totalize or not is set with "J" or "N".
..*The minimum amount of megabytes the directories/files need to be in order to pass the check.
..*Between now and how many hours ago the check needs to go through.
..*The path of the scan.

During the check, the program executes the following actins:

..*Is the file/directory bigger than the minimal file size?
..*Has the file/directory been changed in the given time?

If the answer to both questions is true, then the file/directory shall be passed in a list, together with the path location and the last edited time. This list is then saved in a .txt file.
