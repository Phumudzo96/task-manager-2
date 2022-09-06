# Task manager 2
Create a copy of your previous Capstone project (task_manager.py) and
save it in the Dropbox folder for this project. Also, copy and paste the text
ﬁles (user.txt and tasks.txt) that accompanied the previous Capstone
project to this folder. Modify this program as follows:
●
Modify the code of your previous project so that functions are used.
Adding functions will improve the modularity of your code. Your program
should include at least the following functions:
o
reg_user — that is called when the user selects ‘r’ to register a user.
o
add_task — that is called when a user selects ‘a’ to add a new task.
o
view_all — that is called when users type ‘ va’ to view all the tasks
listed in ‘tasks.txt’.
o
view_mine — that is called when users type ‘ vm’ to view all the
tasks that have been assigned to them.
●
Modify the function called reg_user to make sure that you don’t duplicate
usernames when you add a new user to user.txt. If a user tries to add a
username that already exists in user.txt, provide a relevant error message
and allow them to try to add a user with a different username.
●
Add the following functionality when the user selects ‘ vm’ to view all the
tasks assigned to them:
o
Display all tasks in a manner that is easy to read. Make sure that
each task is displayed with a corresponding number which can be
used to identify the task.
o
Allow the user to select either a speciﬁc task by entering a number
or input ‘-1’ to return to the main menu.
o
If the user selects a speciﬁc task, they should be able to choose to
either mark the task as complete or edit the task. If the user
chooses to mark a task as complete, the ‘Yes’/ ’No’ value that
describes whether the task has been completed or not should be
changed to ‘Yes’. When the user chooses to edit a task, the
username of the person to whom the task is assigned or the due
date of the task can be edited. The task can only be edited if it has
not yet been completed.
