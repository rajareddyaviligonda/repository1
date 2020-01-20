# repository1
devopsdemo
-----

DEVOPS:

Port:42006
AuthURL:https://rajareddyavilig.centralus.cloudapp.azure.com:42001/guacamole
UserName:rajareddyavilig
Password:dyavilig0A@cmv5f


CREATED A GITHUB ACCT:

https://github.com/rajareddyaviligonda/repository1.git

rajareddyaviligonda/$Nanimaggi01




https://cfsigned.simplilearn.com/MP4/default/Cloud/Devops-Practitioner-july2017-update/course_materials/DevOps_Practitioner_CourseResource1.zip

https://codeload.github.com/anujdevopslearn/InterviewQuestions/zip/master
https://raw.githubusercontent.com/anujdevopslearn/InterviewQuestions/master/Demos/Lesson-Wise-Demos.zip

Created Account in GIT:

PUTTY:

rajareddyavilig@rajareddyavilig:~$ git --version
git version 2.7.4
rajareddyavilig@rajareddyavilig:~# sudo su -

root@rajareddyavilig:~# mkdir gitrepo

root@rajareddyavilig:~/gitrepo# ls -lart
total 8
drwx------ 24 root root 4096 Jan 12 15:03 ..
drwxr-xr-x  2 root root 4096 Jan 12 15:03 .

root@rajareddyavilig:~/gitrepo# git init
Initialized empty Git repository in /root/gitrepo/.git/

root@rajareddyavilig:~/gitrepo# ls -lart
total 12
drwx------ 24 root root 4096 Jan 12 15:03 ..
drwxr-xr-x  3 root root 4096 Jan 12 15:05 .
drwxr-xr-x  7 root root 4096 Jan 12 15:05 .git
	
root@rajareddyavilig:~/gitrepo# git status
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
root@rajareddyavilig:~/gitrepo#


root@rajareddyavilig:~/gitrepo# echo "Firt File" >> Readme.txt
root@rajareddyavilig:~/gitrepo# cat Readme.txt
Firt File
root@rajareddyavilig:~/gitrepo#

root@rajareddyavilig:~/gitrepo# ls -lart
total 16
drwx------ 24 root root 4096 Jan 12 15:03 ..
drwxr-xr-x  7 root root 4096 Jan 12 15:16 .git
-rw-r--r--  1 root root   10 Jan 12 15:21 Readme.txt
drwxr-xr-x  3 root root 4096 Jan 12 15:21 .
root@rajareddyavilig:~/gitrepo#


root@rajareddyavilig:~/gitrepo# git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        Readme.txt

nothing added to commit but untracked files present (use "git add" to track)
root@rajareddyavilig:~/gitrepo#


root@rajareddyavilig:~/gitrepo# git add Readme.txt
root@rajareddyavilig:~/gitrepo# git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   Readme.txt

root@rajareddyavilig:~/gitrepo#



root@rajareddyavilig:~/gitrepo# git commit -m "first commit"
[master (root-commit) dfca4f0] first commit
 Committer: root <root@rajareddyavilig.2ixuiwc5jiietgirs5j01u5oqf.gx.internal.cloudapp.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 Readme.txt
root@rajareddyavilig:~/gitrepo# git status
On branch master
nothing to commit, working directory clean

root@rajareddyavilig:~/gitrepo#git log

root@rajareddyavilig:~/gitrepo#git show 0229bfbd1c3fa223e5baa02c95c2e7f9630ace33 
	

root@rajareddyavilig:~# git reset --hard




root@rajareddyavilig:~# git add Readme.txt
root@rajareddyavilig:~# git commit -m "second commit"
[master ed9306e] second commit
 Committer: root <root@rajareddyavilig.2ixuiwc5jiietgirs5j01u5oqf.gx.internal.cloudapp.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
root@rajareddyavilig:~# git log
commit ed9306e067cc98a50fc0ac1a2bcf0cb6fff204f0
Author: root <root@rajareddyavilig.2ixuiwc5jiietgirs5j01u5oqf.gx.internal.cloudapp.net>
Date:   Sun Jan 12 16:35:00 2020 +0000

    second commit

commit 0229bfbd1c3fa223e5baa02c95c2e7f9630ace33
Author: root <root@rajareddyavilig.2ixuiwc5jiietgirs5j01u5oqf.gx.internal.cloudapp.net>
Date:   Sun Jan 12 16:17:54 2020 +0000

    first commit
root@rajareddyavilig:~#

root@rajareddyavilig:~# git revert ed9306e067cc98a50fc0ac1a2bcf0cb6fff204f0            (second commit)



let suppose i have  1000 commits. i just wnat to revert last 5 commits. what i have to do for that? 
from Rsvelavan to All Participants:
syntax pls
from Anuj Sharma to All Participants:
git reset --hard HEAD~5




BRANCH

root@rajareddyavilig:~# git branch -l

root@rajareddyavilig:~# git branch develop
root@rajareddyavilig:~# git branch -l
  develop
* master
root@rajareddyavilig:~#

root@rajareddyavilig:~# git checkout develop
Switched to branch 'develop'

root@rajareddyavilig:~# git branch -l
* develop
  master
root@rajareddyavilig:~#

TIP : you can also use: git checkout -b develop  to create the branch and then switch to it automatically




root@rajareddyavilig:~# git branch -l
* develop
  master
root@rajareddyavilig:~# echo "develop branchFile" >> Readme.txt
root@rajareddyavilig:~# cat Readme.txt
First File
develop branchFile
root@rajareddyavilig:~# git add Readme.txt
root@rajareddyavilig:~# git commit -m "developbranch  commit"
[develop 019af7e] developbranch  commit
 Committer: root <root@rajareddyavilig.2ixuiwc5jiietgirs5j01u5oqf.gx.internal.cloudapp.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
root@rajareddyavilig:~# git branch -l
* develop
  master
root@rajareddyavilig:~#

git branch -D develop    ---to delete


REMOTE

git remote add github https://github.com/rajareddyaviligonda/repository1.git
git fetch github
git remote -v
	github  https://github.com/rajareddyaviligonda/repository1.git (fetch)
	github  https://github.com/rajareddyaviligonda/repository1.git (push)

 git remote add pb https://github.com/rajareddyaviligonda/repository1.git
 
 root@rajareddyavilig:~#  git remote -v
github  https://github.com/rajareddyaviligonda/repository1.git (fetch)
github  https://github.com/rajareddyaviligonda/repository1.git (push)
pb      https://github.com/rajareddyaviligonda/repository1.git (fetch)
pb      https://github.com/rajareddyaviligonda/repository1.git (push)


root@rajareddyavilig:~# git fetch pb
From https://github.com/rajareddyaviligonda/repository1
 * [new branch]      master     -> pb/master
root@rajareddyavilig:~#


Fetching and Pulling from Your Remotes
As you just saw, to get data from your remote projects, you can run:

$ git fetch https://github.com/rajareddyaviligonda/repository1


root@rajareddyavilig:~# git fetch pb
root@rajareddyavilig:~# git fetch https://github.com/rajareddyaviligonda/repository1

root@rajareddyavilig:~# git pull pb master


root@rajareddyavilig:~# git push pb master





JENKINS:

https://jenkins.io/download/

To Install Jenkins:

from Anuj Sharma to All Participants:]

wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
echo "deb https://pkg.jenkins.io/debian-stable binary/" > /etc/apt/sources.list.d/jenkins.list
apt update
apt install openjdk-8-jdk jenkins

service jenkins status


launch the screen :

http://rajareddyavilig.centralus.cloudapp.azure.com:8080/

from Anuj Sharma to All Participants:
cat /var/lib/jenkins/secrets/initialAdminPassword    ====== for password


git configuration in jenkins::
https://github.com/anujdevopslearn/MavenBuild.git


from Anuj Sharma to All Participants:
https://github.com/web3j/sample-project-maven.git



POSTBUILD: Files to active: target/*.war
emailnotification: <>




ANT:

https://github.com/anujdevopslearn/AntProject.git

NODE:

https://github.com/contentful/the-example-app.nodejs.git

FROM PUTTY: install below cmds for node project
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
sudo apt-get install -y nodejs
----

Jenkins:::::::URL

npm install
npm build
npm test
===============================================================
for continius Build: webhook

http://anujsharma401ya.centralus.cloudapp.azure.com:8080/github-webhook



from Erdemdenizli to All Participants:
Build Triggers
    GitHub hook trigger for GITScm polling
Git repo - Settings - Webhooks
    add Webhook
    payload URL - http://erdemdenizliyah.centralus.cloudapp.azure.com:8080/github-webhook/
    Secret - get this from Jenkins - Manage Jenkins - Manage Users - Admin Account - Configure - API Token - Add new token - copy this and paste it to Github webhooks secret
    Select
        just the push event
        active
from Yashbantm to All Participants:



pandeeswari - this needs to be configured in github - settings 
from Email2kal.kalyan to All Attendees:
here are the standard steps to follow to set webhook btw Jenkins and Github
from Email2kal.kalyan to All Attendees:
Configuring GitHub
 
Step 1: go to your GitHub repository and click on ‘Settings’.
 
integrating jenkins and github
 
Step 2: Click on Webhooks and then click on ‘Add webhook’.
 
add github to your ci
 
Step 3: in the ‘Payload URL’ field, paste your Jenkins environment URL. At the end of this URL add /github-webhook/. In the ‘Content type’ select ‘application/json’ and leave the ‘Secret’ field empty.
 
jenkins and gihutb integration tutorial
 
Step 4: in the ‘Which events would you like to trigger this webhook?’ choose ‘Let me select individual events.’ Then, check ‘Pull Requests’ and ‘Pushes’. At the end of this option, make sure that ‘Active’ is checked and click on ‘Add webhook’.
 
jenkins and github integration guide
 
configure github for CI integration
 
We're done with the configuration on GitHub’s side! Now let's move on to Jenkins.
 
Configuring Jenkins
 
Step 5: In Jenkins, click on ‘New Item’ to create a n
from Pritpal.singh to All Participants:
and then in jenkins user --> Get a new token copy and paste to the github webhook 
from Email2kal.kalyan to All Attendees:
Step 6: Give your project a name, them choose ‘Freestyle project’ and finally click on ‘OK’.
 
jenkins ci, github scm
 
Step 7: Click on the ‘Source Code Management’ tab.
 
adding your scm to continuous integration
 
Step 8: Click on Git and paste your GitHub repository URL in the ‘Repository URL’ field.
 
GitHub and Jenkins combination
 
Step 9: Click on the ‘Build Triggers’ tab and then on the ‘GitHub hook trigger for GITScm polling’. Or, choose the trigger of your choice.
 
triggering builds in jenkins
 
That's it! Your GitHub repository is integrated with your Jenkins project. You can now use any of the files found in the GitHub repository and trigger the Jenkins job to run with every code commit.
 
For example, I will show you how to run a Taurus script that I uploaded to my GitHub repository from my Jenkins project.
 
Triggering the Jenkins Job to Run with Every Code Commit
 
Step 10: Click on the ‘Build’ tab, then c
from Email2kal.kalyan to All Attendees:
Step 11: To run a Taurus test, simply use the ‘bzt’ command, followed by the name of your YML file and click on ‘Save’.
 
run taurus in jenkins
 
Step 12: Go back to your GitHub repository, edit the Taurus script and commit the changes. We will now see how Jenkins ran the script after the commit.
 
run jenkins script after commit
 
Step 13: Go back to your Jenkins project and you'll see that a new job was triggered automatically from the commit we made at the previous step. Click on the little arrow next to the job and choose ‘Console Output’.
 
jenkins project with github
 
Step 14: You can see that Jenkins was able to pull the Taurus script and run it!
 
pull a script from github and run it
 
Congratulations! Every time you publish your changes to Github, GitHub will trigger your new Jenkins job.
from Pritpal.singh to All Participants:
Thanks Kalyan 





junit test:::

https://github.com/ThomasJaspers/java-junit-sample

mvn clean test



selenium::::
https://github.com/anujdevopslearn/Maven-Selenium.git
mvn clean test
---------
