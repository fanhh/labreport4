step 4
key pressed: ```ssh x6ding@ieng6.ucsd.edu```
![Image](step4.png)
In step 4, I utilized the SSH command by entering ```ssh x6ding@ieng6.ucsd.edu```, which allowed me secure access to the virtual machine hosted by the university. This command established an encrypted connection to the server, enabling me to work on the server as if I were directly logged into it.


step 5
key pressed: ```git clone git@github.com:fanhh/lab7.git```
![Image](step5.png)
For step 5, I executed the command git clone git@github.com:fanhh/lab7.git. This command cloned the repository into my virtual machine, creating a local copy of the lab7 project. Cloning the repository allowed me to work on the project files locally on the virtual machine, facilitating easier access and manipulation of the project's files.



step 6
key pressed: ```vim lab7/*```  ```:e test.sh``` ```!bash test.sh```
![Image](step6.png)
During step 6, I navigated to the lab7 directory and ran ```vim lab7/* :e test.sh !bash test.sh```. This sequence of commands opened the Vim editor within the context of the lab7 repository. I then used the :e test.sh command to edit the test.sh script file directly in Vim. After making the necessary changes or reviews, I executed !bash test.sh from within Vim, which runs the script in the Bash shell. Running the test.sh script allowed me to execute the automated tests defined within it, verifying the functionality and correctness of the lab7 project directly from the Vim editor.

step 7
key pressed: ```:e ListExamples.java``` ```<UP><UP><UP><UP><UP><UP><Right><Right><Right> <Right><Right>``` ```i``` ```<delete>2``` ```ese``` ```:wq<enter>```
![Image](step7.png)
In step 7, I executed a series of commands within Vim to edit a specific Java file. The process began with opening the file for editing by using the command ```:e``` ListExamples.java. Once the file was open, I navigated through the document by moving the cursor up 6 times and to the right 5 times to reach a specific location in the code. Upon reaching the desired point, I entered insert mode with i, which allowed me to make edits directly in the text. In this case, I deleted the number 1 and replaced it with 2, then typed ese to include specific code or comment changes. After completing the edits, I exited insert mode and saved my changes, then quit the editor by typing ```:wq``` and pressing <enter>. This series of actions modified the Java file according to the project requirements.

step 8
key pressed: ```:e test.sh``` ```!bash test.sh```
![Image](step8.png)
For step 8, I focused on executing and testing the shell script file test.sh. I reopened the Vim editor for this file using ```:e test.sh``` and directly ran the test script from within Vim using ```!bash test.sh```. This command executed the shell script, allowing me to verify the changes made to the project and ensure everything was functioning as expected.



step 9
key pressed: ```!git status``` ```!git add .``` ```!git commit -m'edit files'``` ```!git push```
![Image](step9.png)
![Image](step9.1.png)
In step 9, I performed a series of Git commands to commit and push the modifications to the repository. Starting with !git status, I checked the current state of the repo to see the changes. Then, I added all modified files to the staging area with ```!git add .```. Following this, I committed the changes with ```!git commit -m 'edit files'```, attaching a message to describe the nature of the updates. Finally, I pushed the commits to the remote repository using ```!git push```, effectively updating the project on GitHub. These commands were crucial for version control and ensuring that all changes were properly documented and shared with the team or project collaborators.

