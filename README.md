Each week this repository will be updated when I add the Weekly Session N.ipynb file, so it will be ideal if we practice forking and syncing on GitHub.

1.  On the GitHub GUI (graphical user interface) - Login to your GitHub account - and set your default shell to Git Bash.  *This is different on Linux and Mac.*

2.  Fork this repository to your GitHub account - this will make a copy on your account - it will be a public repo, NOT on the Physics-PacU page.  My new fork is named: 

https://github.com/PacU-student/Weekly-Sessions 

Note it is NOT named: 

https://github.com/Physics-PacU/Weekly-Sessions/

3.  Clone/download the repo to your local machine.  You can do two ways:
    * GUI - click the Clone/Download button on GitHub (as last week) - *unfortunately this doesn't always work as I expect, or end up in the directory I want it to.*
    * Terminal - this works!  
       * Open the Git Shell
       * Navigate to the directory you save your files in using the cd (change directory) command: 
         $ cd Documents/GitHub/Test_Student
       * Clone the directory using the GitHub command: 
         $ git clone https://github.com/Physics-PacU/Weekly-Sessions.git
4.  Just as last week, you have a directory full of documents you can modify.  However, the difference is that the permissions are set so that you can push your changes back to GitHub.  
    * In the terminal type:
    
      $ git status
    * This will give you a list of files that have been modified must be added.
    
      $ git add <files>
    * Now you must "commit" those changes 
   
      $ git commit -m "Add a message about your changes"
    * Finally send them to your online repository
    
      $ git push origin master
     
4.  Check online, you should see your changes uploaded on GitHub.

Next time, we'll work on syncing with the master branch in the upstream repository, where I will be adding files.

    
    
