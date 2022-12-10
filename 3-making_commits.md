# Making Commits (and what makes a good commit / commit message)
## What makes a good commit
Whenever completing a task, whether it is fixing a bug, adding a new feature, completing any other task or ending your work for the day, it is a good practice to create a commit. 
This makes it possible to retrace the development process of your project, which can help anybody to understand it. 
Before committing your progress, it is necessary to add all the files you want to commit to your stack. 
By then using the commit command, the changes are saved onto the stack. 

The following command can be used to add individual files and second is used to add all changed files that are tracked. 

    $ git add <filename> 
    $ git add .

The following command is used to commit the changes to the stack. 

    $ git commit -m "commit message"












## What makes a good commit message
it should desrcribe what you have changed compared to the last commit.
It shouldn't be too long.
In your Git you have a list with all the commits you did.
In this List you see the commit message and should understand just with this message what the changes have been.
When there is a mistake you can trace where you changed things according to the mistake.













