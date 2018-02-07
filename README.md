Each week this repository will be updated when I add the Weekly Session N.ipynb file, so it will be ideal if we practice forking and syncing on GitHub.

### How to get started:

1.  On the GitHub GUI (graphical user interface) - __Login to your GitHub account - and set your default shell to Git Bash.__  

2.  Fork this repository to your GitHub account - this will make a copy on your account - it will be a public repo, 
    NOT on the Physics-PacU page.  My new fork is named: 

    https://github.com/PacU-student/Weekly-Sessions 

    __Note it is NOT named:__

    https://github.com/Physics-PacU/Weekly-Sessions/
    
    *This is an important difference - you don't have permission to modify the original repository.*
   
3.  Clone/download the repo to your local machine.  You can do two ways:
    * GUI - click the Clone/Download button on GitHub (as last week) - *unfortunately the GUI interface is hard to understand.  It doesn't always work as I expect, and the clone doesn't always end up in the directory I want it to.*
    * Terminal - this works!  
       * Open the Git Shell
       * Navigate to the directory you save your files in using the cd (change directory) command: 
       
           $ cd Documents/GitHub/Test_Student
       * Clone the directory using the GitHub command: 
       
           $ git clone https://github.com/PacU-student/Weekly-Sessions.git
         
         *Again, notice I used the forked copy*

4.  Just as last week, you have a directory full of documents you can modify.  However, the difference is that the permissions are set so that you can push your changes back to GitHub.  This is the basic workflow for putting those changes back on GitHub.

    * In the terminal type:
    
          $ git status
    * This will give you a list of files that have been modified must be added - they will be red in color.  You need to add them.  
    
          $ git add (type file names here)
    * Now you must "commit" those changes 
   
          $ git commit -m "Add a message about your changes"
      
    * Finally send them to your online repository
    
          $ git push origin master
     
4.  Check online, you should see your changes uploaded on GitHub.

Next time, we'll work on syncing with the master branch in the upstream repository, where I will be adding files.

### How to sync:
There are two help guides that make this a straighforward process (assuming all above went well.)

1.  First configure your fork to sync with the Physics-PacU repo: 
    https://help.github.com/articles/configuring-a-remote-for-a-fork/
    So for my fork I typed: 
    
        $ git remote add upstream https://github.com/Physics-PacU/Weekly-Sessions.git
      
2.  Now get the updated files from the Physics-PacU repo:
    https://help.github.com/articles/syncing-a-fork/
    So for my fork I typed: 
    
        $ git fetch upstream
        $ git merge upstream/master
    
