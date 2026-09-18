Git is software that allows you to save files and the history of saves of such files 

GitHub is a place where users can create a directory and upload things to it, and view the current and historic versions of the directory. 

VSCode is an application that assists you in writing code by providing a place to write code, access to related directories, various plugins to perform other tasks, and more.



\# USING GITHUB

\## ESTABLISH LINK BETWEEN WORKING DIRECTORY AND GITHUB REPO

1\. download git: https://git-scm.com/install/

2\. create a directory that you later want to be synced with GitHub

3\. creates git folder within created directory to document past changes

&#x09;- open terminal and navigate to created directory

&#x09;- once there, type "git init"

4\. create GitHub account

5\. create GitHub repository

&#x09;- go to https://github.com/

&#x09;- click green button labeled "new" in top left of screen

&#x09;- fill in details, then click create repository

&#x09;- copy link in white box, which is in the blue box

&#x09;	https://github.com/\[username]/\[name of project]

6\. Link Git repo and GitHub repo

&#x09;- go back to terminal

&#x09;- type "git remote add origin \[copied link]

\## PUSH CHANGES TO GITHUB

7\. go to terminal

8\. type "git add .", enter

9\. type "git commit -m "\[message]"

10\. type "git push -u origin master"

\-- PULL CHANGES FROM GITHUB --

11\. go to terminal

12\. type "git pull origin master"



\# USING VSCODE

\## GETTING TO DIRECTORY

\- in top left, click on three horizontal bars

\- then in the new dropdown menu, click on "File"

\- then in the newer dropdown menu, click on "Open Folder"

\- navigate to directory in pop-up window, then click "Select Folder"



\## CODE

\- you should now see your opened folder name in the top left under "Explorer"

\- hover over the folder name, then click on the newly appeared button titled "New File..."

\- name file and include correct file extension on the end

\- a text editor should appear in main part of screen, this is the newly created file

\- you can type code in this text editor, then to save to file press "Ctrl + S"



\## MORE

\- if you want, there are more plugins that you can access by getting to the extensions page by clicking the button titled "Extensions" on the left sidebar



\# DEFINITIONS

**Branch:** a named pointer to a specific commit

**Clone:** downloads a repository and its history

**Commit:** a command to save a file or files to local memory.

**Fetch:** pulls the file or files in GitHub to local memory, but not to working directory

**GIT:** is software that allows you to save files and the history of saves of such files either in the cloud(to GitHub) or your storage.

**GitHub:** a place where users can save and view the historic versions of their files in the cloud. every user has their own place to upload their own files, but users can collaborate and share the same upload place. users can browse other users upload places.

**Merge:** combines branches

**Merge Conflict:** when merge doesn't work because it isn't clear which version is preferred

**Push:** a command to push the current saved files or files in local memory to cloud storage.

**Pull:** a command to pull the current saved files or file in the cloud storage to the local memory.

**Remote:** establishes a route between local memory and GitHub cloud repository

**Repository:** essentially a folder

