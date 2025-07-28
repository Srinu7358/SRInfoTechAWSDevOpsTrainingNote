
# SRInfoTechAWSDevOpsTrainingNote




08/06/2025_Demo::
================

In Demo session we have Overview the all CI/CD tools 

![image](https://github.com/user-attachments/assets/8f472413-8ba3-45ae-85c0-a391ec46886a)



13/06/2025_Tools Overview::
==============================

1. Overview about the all CI/CD & AWSDevOps Training flow
2. Discussed about the all the DevOps roles

DevOps::
======

DevOps is a software development and operations (DevOps) methodology that combines these two to improve efficiency and speed up project deliverables, It's very important because it helps businesses/deliver software faster and with higher quality.

What is the key purpose of DevOps?
The primary goal of DevOps is to bridge the gap between development and operations teams. It creates a streamlined, efficient workflow that delivers software faster and with higher quality.
DevOps is a set of practices,tools that automate and integrate the processes between software development and IT teams.

Devops engineer is a key role responsibility::
================================================

![image](https://github.com/user-attachments/assets/80dbb098-c083-463c-a178-36e265e84767)

1)The devops engineer was responsibility to release the product to the market as soon as possible
2)  release the product speed to the market
3)Devops engineer was give continues feedback to the developers
4) Devops engineer responsibility start from git and end with production

Benefits of DevOps ::
===================

•	Faster software delivery: Reduces lead times and speeds up the software delivery process 
•	Higher software quality: Addresses bugs quicker and improves software quality 
•	Better collaboration: Unifies development and operations teams, enhancing collaboration and efficiency 
•	Competitive advantage: Creates a more nimble software development lifecycle that gives businesses an advantage over their competitors 



13/06/2025::
==============

What is Git?

Git is a free, open-source version control system (VCS) that helps developers manage their code. It's the most widely used tool VCS(version control system) Git is fast for committing, branching, merging, and comparing past versions Git is very high Performance and Flexibility,Security.


Integrate Git & Github::
========================


![image](https://github.com/user-attachments/assets/39bb9c3a-f7d5-48e6-8a91-0aff6e34be3e)



Install Git in you local machine::
====================================

https://git-scm.com/downloads/win

Please download the ---64-bit Git for Windows Setup.

Once download the git .exe file , double click and install the git on your machine

once installed right click on your local machine you can found Open Git batch here option, means git is installed successfully in your machine.

![image](https://github.com/user-attachments/assets/46c6f47d-55f2-4df7-83ae-14a7bbeab67e)


GitHub account creation::
=============================

For creating github account EmailId is Required

go to link --https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home

Enter Email & password ,Username click continue ---Account will create successfully image


![image](https://github.com/user-attachments/assets/4f0bd13c-21df-42f0-9ad0-e4671b367cfb)


![image](https://github.com/user-attachments/assets/44333ed2-0d4a-41b2-9bb5-66c7c5456551)


Github::Github is a one of the SCM(Source code management) tool and store the Project code.

Repository: storage area of your source code. Create a Repository on GitHub

click Repositories

![image](https://github.com/user-attachments/assets/725cdcfb-7472-46d8-b7a8-46de06f3cbf6)


Click New

![image](https://github.com/user-attachments/assets/e9a689f5-7c6e-4b7f-9442-96d8a17021f5)


Enter Repository Name::SRINFOTECHDEMO

![image](https://github.com/user-attachments/assets/f230a5b0-b1b4-4b46-8def-ebd601347749)


Public:: Anyone on the internet can see this repository.


![image](https://github.com/user-attachments/assets/9fb81a79-9cc9-4428-96cd-c9bd3d17e37b)


Private:: You choose who can see and commit to this repository.

select Add a README file 


![image](https://github.com/user-attachments/assets/4ba5ac39-6736-412c-906d-ebed138f8a86)


Click Create Repository


![image](https://github.com/user-attachments/assets/6a91de9f-a2f3-4b03-9740-a870bf2cb972)




Repository Created SUccessfully with Default branch main


![image](https://github.com/user-attachments/assets/f3435b4a-cf60-4a3a-ba92-eb5a5a4ca02d)





Github Introduction::
===============

GitHub is a web-based platform for version control and collaboration, allowing developers to store and manage their code in repositories.

Version Control: ::
GitHub uses Git, a distributed version control system, to track changes in code. This allows multiple people to work on the same project without overwriting each other's contributions.

Repositories::: where you can store your project files and track the history of changes made to those files.Public and private repos can be created depending on accessibility needs.



16/06/2025::
=============

Git & Github Integration::
=======================

git and github communication happend via SSH keys

![image](https://github.com/user-attachments/assets/805b0fae-f387-47cb-a5d0-b66d474967dd)

Generate SSHKeys::
====================
 open gitbash and run the below command

 ![image](https://github.com/user-attachments/assets/0e42b0cc-0ee2-4cac-8cb9-dbbcbe23189a)


syntax::ssh-keygen -t ed25519 -C "your_email@example.com"

>ssh-keygen -t ed25519 -C "srinfotechbatch2@gmail.com"

![image](https://github.com/user-attachments/assets/b802d3d8-d678-425e-9bcf-1a8e59dfa35b)

HP@DESKTOP-E518Q66 MINGW64 ~
$ ssh-keygen -t ed25519 -C "srinfotechbatch2@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/HP/.ssh/id_ed25519):
/c/Users/HP/.ssh/id_ed25519 already exists.
Overwrite (y/n)? y
Enter passphrase for "/c/Users/HP/.ssh/id_ed25519" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/HP/.ssh/id_ed25519
Your public key has been saved in /c/Users/HP/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:CqROf7Z/FpbjGWy8/vMYGCS6Uq1ttFi/dKY2iAuBprg srinfotechbatch2@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|                 |
|                 |
|    .   . .      |
|   +   o o       |
|  = o o So..     |
|.= . + O oXo     |
|o . + B.+=+*+    |
| .   =.o..O=.o   |
|E     oo.=+ooo.  |
+----[SHA256]-----+


Please follow below links for more understanding::
===================================================

https://docs.github.com/en/authentication/connecting-to-github-with-ssh

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Once genearted the keys (public/private) and copy public key to Github Account::
================================================================================

steps::

Your public key has been saved in /c/Users/HP/.ssh/id_ed25519.pub


![image](https://github.com/user-attachments/assets/3655eb5a-3b08-4644-98b2-cea22ecfaacd)

right click and open id_ed25519.pub, and copy public key to Github Account

Go to -->Your Copilot OR settings, click your copilot


![image](https://github.com/user-attachments/assets/ac133e40-b38c-4483-bfbb-fde5d729747d)


Click SSH and GPG Keys

![image](https://github.com/user-attachments/assets/bde7e964-cbbe-42d1-aced-a1646d6bf5d3)


click New SSH Key


![image](https://github.com/user-attachments/assets/f2996ed0-5afc-494c-a45f-eebc5b78b8e4)


Add new SSH Key and click Add SSH Key

![image](https://github.com/user-attachments/assets/1b229cda-b319-4565-b937-7a259dbd2f2a)


ssh public key is added in github account


![image](https://github.com/user-attachments/assets/1a327a82-3df8-41ea-994b-cc9aa20dd582)



Clone repository/Project from github to local machine steps::
==================================================================

Fork::
============

Fork means to make a copy of the repository into my own github account A fork is a copy of a repository


first we need to create the repository

Go to Repositories

![image](https://github.com/user-attachments/assets/c295c1cb-8690-49db-93cf-766d695d0526)

Click New

![image](https://github.com/user-attachments/assets/c0ba9848-bb5c-461e-8f9b-c1cd332ab5dd)

Enter Repository Name

![image](https://github.com/user-attachments/assets/cd6ae1c3-6160-4a5e-a159-5347469fb1b6)


select public

select Readmefile.md

![image](https://github.com/user-attachments/assets/e631f9a4-eda5-4e93-8f31-629cda9e6d17)

Click Create Repository


Empty repository Created

![image](https://github.com/user-attachments/assets/a838f321-7d0a-46a8-bc1c-e90d12ba5acf)


Now I'm Going to clone the Empty Repository from Remote to Local::
====================================================================
Steps::
=======



1.git clone git@github.com:srinfotechbatch2/SRINfotechDemo.git

2.cd SRINfotechDemo

3.git status

4.git add --all

5.git status

6.git commit -m "i have added hellow world project files"

7.git push   ---->from local changes pushed to remote

8.git pull   --->remote to local

above steps to push some changes from Local to remote repository

Create New Branch::
==============

![image](https://github.com/user-attachments/assets/7d0f763e-da1f-4ce6-bb96-009f9bf83865)


Go to Repositories 

Click Branch

![image](https://github.com/user-attachments/assets/3a29d487-f8f9-4c36-8a22-674203b9a564)


Click New Branch

![image](https://github.com/user-attachments/assets/2538e705-3ff3-4cb3-8644-cd3a8ff8e65e)


New feature Branch Formate----> feature/YYYY.MM.DD

feature/2025.06.22

![image](https://github.com/user-attachments/assets/2b55ea32-030c-45d2-becd-d94b047515c1)


Branch Created Successfully


![image](https://github.com/user-attachments/assets/3b5a575e-2c0d-4f81-8b19-1444780514c7)

once branch created in github , we need to pull the new branch from Remote to Local

> git pull

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git pull
From github.com:srinfotechbatch2/SRINfotechDemo
 * [new branch]      feature/2025.06.22 -> origin/feature/2025.06.22
Already up to date.

Switch one branch to another branch using git checkout command

>git checkout <branchName>

>git checkout feature/2025.06.22

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git checkout feature/2025.06.22
branch 'feature/2025.06.22' set up to track 'origin/feature/2025.06.22'.
Switched to a new branch 'feature/2025.06.22'

please make some changes in source code like Jenkinsfile and try to push changes to github repository, please follow below steps

1.git status

2.git add --all

3.git status

4.git commit -m "i have added hellow world project files"

5.git push



Lab Practice::
==================
HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps
$ git clone git@github.com:srinfotechbatch2/SRINfotechDemo.git
Cloning into 'SRINfotechDemo'...
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps
$ cd SRINfotechDemo/

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        .whitesource
        Jenkinsfile
        pom.xml
        src/

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git add --all
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.whitesource', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'pom.xml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/main/java/hello/Greeter.java', LF will be replaced by CRLF the next time G
it touches it
warning: in the working copy of 'src/main/java/hello/HelloWorld.java', LF will be replaced by CRLF the next tim
e Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   .whitesource
        new file:   Jenkinsfile
        modified:   README.md
        new file:   pom.xml
        new file:   src/main/java/hello/Greeter.java
        new file:   src/main/java/hello/HelloWorld.java


HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git commit -m "i have added hello world project files"
[main 2f04570] i have added hello world project files
 7 files changed, 367 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 .whitesource
 create mode 100644 Jenkinsfile
 create mode 100644 pom.xml
 create mode 100644 src/main/java/hello/Greeter.java
 create mode 100644 src/main/java/hello/HelloWorld.java

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git push
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 4 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (13/13), 5.42 KiB | 793.00 KiB/s, done.
Total 13 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:srinfotechbatch2/SRINfotechDemo.git
   03b032f..2f04570  main -> main

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git pull
From github.com:srinfotechbatch2/SRINfotechDemo
 * [new branch]      feature/2025.06.22 -> origin/feature/2025.06.22
Already up to date.

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git checkout feature/2025.06.22
branch 'feature/2025.06.22' set up to track 'origin/feature/2025.06.22'.
Switched to a new branch 'feature/2025.06.22'

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git status
On branch feature/2025.06.22
Your branch is up to date with 'origin/feature/2025.06.22'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Jenkinsfile

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git add --all
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git commit -m "modified jenkinsfile"
[feature/2025.06.22 9bb0cbe] modified jenkinsfile
 1 file changed, 13 deletions(-)

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 290 bytes | 145.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:srinfotechbatch2/SRINfotechDemo.git
   2f04570..9bb0cbe  feature/2025.06.22 -> feature/2025.06.22

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git status
On branch feature/2025.06.22
Your branch is up to date with 'origin/feature/2025.06.22'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Jenkinsfile

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git add --all
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git commit -m "modified jenkinsfile"
[feature/2025.06.22 aff43d0] modified jenkinsfile
 1 file changed, 13 insertions(+)

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 527 bytes | 263.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:srinfotechbatch2/SRINfotechDemo.git
   9bb0cbe..aff43d0  feature/2025.06.22 -> feature/2025.06.22

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git status
On branch feature/2025.06.22
Your branch is up to date with 'origin/feature/2025.06.22'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Jenkinsfile

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git add --all
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git status
On branch feature/2025.06.22
Your branch is up to date with 'origin/feature/2025.06.22'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Jenkinsfile


HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git commit -m "modified jenkinsfile"
[feature/2025.06.22 41147f7] modified jenkinsfile
 1 file changed, 1 insertion(+), 12 deletions(-)

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 291 bytes | 291.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:srinfotechbatch2/SRINfotechDemo.git
   aff43d0..41147f7  feature/2025.06.22 -> feature/2025.06.22




17/06/2025::
================

Github Branching Model::
=======================

A GitHub branching model is a structured way of organizing branches in a Git repository to manage development workflows effectively. It helps teams work collaboratively, isolate features, manage releases, and deploy code more efficiently.


![image](https://github.com/user-attachments/assets/2b5b48a9-9236-444e-a990-b512bc5ff581)

Sample Repository Hello-World Project::
=========================================

https://github.com/srinfotechbatch2/SRINfotechDemo


Branches:
==========
main (or master): Always production-ready.

feature/*: Used for new features.

release/*: Prepares for a new production release.

main or master branch:: This is default branch and whenever we created the empty Repository by defauly main or master branche is created automatically.
main or master branch always stable and live code 

feature branch:: It could be a new feature, an improvement of existing features, bug fixes, or any other changes. A feature branch is a type of branch in Git typically used to develop new features for the software.feature branch will created from main or master OR feature branch created from latest release branch always based on the release cycle

formate:: feature/YYYY.MM.DD
 feature/2025.06.22

release branch:: Based on the release we have created release branch accourdingly and starts the next release cycle.
always release branch created from master only and master have stable and live code and post release we shold merged code changes to master branch only

release/2025.07.20

hotfix branch:: always created from main or master branch only for production fixes.once production fix done we should merged directly to main or master branch only.

always created this hotfix branch for production issues fixes

bugfix:: this branch is created from release branch to fix the LLE(lower level environemnt)/Pre-Prod/UAT/Non-Prod issues and once LLE issues fixed ,we should pushed their changes to release branch only.


Raise PR (Pull Request) ::
=========================
Merge the code from one branch to another branch that is called pull request

below are the steps to raise PR::

Go to -->Pull requests and click

![image](https://github.com/user-attachments/assets/f2848a77-e095-4f56-917c-af9105d1e0bb)

Click New Pull Request::

![image](https://github.com/user-attachments/assets/1369f202-d7fd-4279-ac9d-b4b2eb7702ed)

Compare & pull Request

![image](https://github.com/user-attachments/assets/bac984dd-12b1-4cf0-b00d-e5b49db165f6)

select base & compare options

![image](https://github.com/user-attachments/assets/13e46ee9-db46-4eb0-a505-e4580e4a92ff)


Raise PR(Pull Request) from feature to release branch


![image](https://github.com/user-attachments/assets/e4e939a3-a286-4264-a51d-3c1c7df59be4)


please select base & compare branches so here base branch is release/2025.06.29 and compare branch is feature/2025.06.22

i'm going to merge code changes from feature branch to release branch 



![image](https://github.com/user-attachments/assets/15c01632-b97a-4ede-bb55-2ef0bcea5105)


click create pull request

![image](https://github.com/user-attachments/assets/6b91e62d-9aee-4328-b759-bd20ec6f2a1d)

![image](https://github.com/user-attachments/assets/60876946-a09b-4245-bc4b-835bff15fe87)

click merge request

confirm merge

![image](https://github.com/user-attachments/assets/3ae9c358-accc-4a73-92c5-4aa21b2d78c4)


merged 1 commit into release/2025.06.29 from feature/2025.06.22  Copied!

![image](https://github.com/user-attachments/assets/fc0f68b5-b263-4267-ad07-0ea7a2bcf026)



18/06/2025::
==================


Avoide conflicts in RealTime Scenarious::
=================

If multiple developers OR DevOps Engineers are working on same Project/MOdules, if they tried to commits thier code changes to Repository, it will faces the  conflicts issues and how to resolved those conflicts issues in real time projects 


![image](https://github.com/user-attachments/assets/f2ebe341-83c5-486d-ba0d-329854190105)



>git pull --->git pull command is use, copies changes from a remote repository directly into your working directory (local directory) and merged code changes from remote repository to local repository 
>git fetch ---->The git fetch command only fetch the changes into your local Git repo and it will not merged anything. just fetch the details

Please create developer1,developer2,developer3 directories in your local machine and clone the project code separately 

![image](https://github.com/user-attachments/assets/a0345422-a025-4c3a-84c5-737b98244a6a)


![image](https://github.com/user-attachments/assets/3296003f-c8c7-42c8-bdca-3270576aaa57)


![image](https://github.com/user-attachments/assets/7e786310-5092-4975-9eb9-7b18801353d8)

Editor steps for Resolved the conflicts::

resolved conflicts::

>git pull

opend the editor

1.presh the i from your keyboard

2.esc

3.swift+:

4.wq

5.enter

Developer1 Activity::
=====================

 git checkout feature/2025.02.27
error: pathspec 'feature/2025.02.27' did not match any file(s) known to git

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (main)
$ git pull
From github.com:parasa7358/spring-petclinic
 * [new branch]      feature/2025.02.27 -> origin/feature/2025.02.27
Already up to date.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (main)
$ git checkout feature/2025.02.27
branch 'feature/2025.02.27' set up to track 'origin/feature/2025.02.27'.
Switched to a new branch 'feature/2025.02.27'

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is up to date with 'origin/feature/2025.02.27'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Jenkinsfile

nothing added to commit but untracked files present (use "git add" to track)

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git add --all
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is up to date with 'origin/feature/2025.02.27'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Jenkinsfile


HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git commit -m "Added jenkins file for Feb Release"
[feature/2025.02.27 9ad4ee0] Added jenkins file for Feb Release
 1 file changed, 22 insertions(+)
 create mode 100644 Jenkinsfile

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 483 bytes | 241.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:parasa7358/spring-petclinic.git
   e4b9aa2..9ad4ee0  feature/2025.02.27 -> feature/2025.02.27


Developer2  Activity::
=========================

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git pull
Already up to date.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is ahead of 'origin/feature/2025.02.27' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 586 bytes | 293.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To github.com:parasa7358/spring-petclinic.git
   9ad4ee0..ed57c5e  feature/2025.02.27 -> feature/2025.02.27


Developer3  Activity::
========================

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/C/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is ahead of 'origin/feature/2025.02.27' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/C/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 33, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 4 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (13/13), 1.14 KiB | 233.00 KiB/s, done.
Total 13 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 5 local objects.
To github.com:parasa7358/spring-petclinic.git
   ed57c5e..80681f1  feature


   Please be practice above 3 developers activity in real time bases 

>git fetch--->just fetch

>git pull -->fetch+merged


Git All the Commands::
==========================

Git commands::
==============
1.git clone git@github.com:srinfotechbatch2/SRINfotechDemo.git

2.cd SRINfotechDemo

3.git status

4.git add --all

5.git status

6.git commit -m "i have added hellow world project files"

7.git push   ---->from local changes pushed to remote

8.git pull   --->remote to local

9.git checkout <branchname>

   git checkout feature/2025.06.22
   
10.git pull  --->every devlioper beforre pushing their changes we should make sure git pull the every time   
  

clone      Clone a repository into a new directory

add        Add files

status     Show the working tree status

commit     Record changes to the repository

 pull       Fetch from and integrate with another repository or a local branch
 
 push       Update remote refs along with associated objects



19/06/2025::
==================


1.install git
2.introcuction about git-->VCS
3.github-->SCM
4.introduction about github
5.github account
6.create repositories
7.integarte git & github via SSH keys--->ssh-keygen -t ed25519
8.how to created branch in github
9.how to rasie PR-->pull requests--->feature branch to release
10.
git commands::

1.git clone
2.cd 
3.git checkout 
4.git status
5.git add -all
6.git commit
7.git push
8.git pull
9.git fetch
10.
>git pull

opend the editor

1.presh the i from your keyboard
2.esc
3.swift+:
4.wq
5.enter

10.how to resolved the git conflicts
11.github branching model/stargety
12.end to end flow of git & github


Jenkins Introductiion::
============================
Jenkins is a free and open source automation server/tool. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery.

Jenkins is a Orchestration tool

Jenkins is a CI/CD tool

Jenkins is a Schedular

Jenkins is a crone job schedular


![image](https://github.com/user-attachments/assets/bf52c5e8-bdc3-473a-acfe-9d78f9e05257)

![image](https://github.com/user-attachments/assets/8f101b62-5313-47c2-a870-56483b7ad68f)

Roles And Responsibilities::
================================
1)The devops engineer was responsibility to release the product to the market as soon as possible 
2)release the product speed to the market 
3)Devops engineer was give continues feedback to the developers 4) Devops engineer responsibility start from git and end with production

A) when your activity start from git and end with production environment(production servers)Continues deployment 
when your activity start from git to LLE(lower level environment,testing environment,pre-prod…et) environment(pre-production servers)Continues delivery non-production environment

Tutorials::

https://www.tutorialspoint.com/jenkins/jenkins_overview.htm https://www.geeksforgeeks.org/jenkins-tutorial/#prerequisites

Download JDK 17 ::

https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html

Windows x64 Installer 153.92 MB

Windows x64 Compressed Archive	172.87 MB	
https://download.oracle.com/java/17/archive/jdk-17.0.12_windows-x64_bin.zip (sha256 )

JDK 17 Environment setup::
==============================

Go to Search box & type Edit the system environemnt variables and click

It will navigate to System properties

![image](https://github.com/user-attachments/assets/2de9b257-9029-43f7-af30-4f4f4827731a)

Click Environment Variables


![image](https://github.com/user-attachments/assets/0b02d209-cb85-4afd-869f-923df054b7de)

![image](https://github.com/user-attachments/assets/88adc878-dedd-4150-9ee8-f01c75677ab2)

User variables::
================

![image](https://github.com/user-attachments/assets/d6bfe193-6a5c-4a8b-a21a-fa77c07a4bbc)

Click New

Variable Name:: JAVA_HOME

Variable Value:: C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12

![image](https://github.com/user-attachments/assets/5743966a-8e88-4502-bd3a-904f1a839a01)

Click OK

![image](https://github.com/user-attachments/assets/1af67329-3601-4e23-855e-b69cf5763d95)


System variable::
=================

![image](https://github.com/user-attachments/assets/0cecde24-19be-4989-98c5-c3eb9c20734c)

Edit Path

![image](https://github.com/user-attachments/assets/5f302184-84cb-4e66-b17a-3ce4792fa45c)

Click New and give Java Installed path till \bin

C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12\bin

![image](https://github.com/user-attachments/assets/d918df00-9c10-424f-b155-7a22e925d291)

Click OK

You Can verify Java is Installed Or Not

Go to command Prompt

![image](https://github.com/user-attachments/assets/773f6318-d8a5-4d2c-803b-e504d84e24e1)

![image](https://github.com/user-attachments/assets/aee76eab-4f27-4fce-af69-f28a872d37dc)


>java --version

C:\Users\HP>java --version
java 17.0.12 2024-07-16 LTS
Java(TM) SE Runtime Environment (build 17.0.12+8-LTS-286)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.12+8-LTS-286, mixed mode, sharing)

![image](https://github.com/user-attachments/assets/92e49e72-2f7c-464c-b8f1-2a30e6ebe702)

Above Screeenshot JDK17 setup is done




Installed jenkins in Windows::
================================

https://www.jenkins.io/download/

Go to google search -->download jenkins war file for windows

click below Jenkins version

Download Jenkins 2.515 for:

![image](https://github.com/user-attachments/assets/eaac3392-c1ce-498f-8a85-7a5fecabeb6b)

Jenkins.war file is downloaded

![image](https://github.com/user-attachments/assets/70e676a4-9a05-4748-b8d5-2373bf8ac189)



20/06/2025::
==============

MAven Environment setup::
==============================

Maven::
=========

Maven is a powerful build automation tool used primarily for Java projects. Developed by the Apache.

it helps developers manage a project's build, dependencies, documentation, and more—all using a single configuration file called pom.xml

![image](https://github.com/user-attachments/assets/7455b09b-d334-4974-84da-60c76c45cdc0)


Common Maven Commands OR Maven Goals::
======================================


1) mvn clean	  ------------> Deletes target/ directory (clean build).

2) mvn compile	-----------> Compiles the source code.
   
3) mvn test	   ------------> Runs tests.
   
4) mvn package	------------> Creates a JAR/WAR.
  
5) mvn install	------------> Installs package into your local repository.
  
6) mvn deploy	-------------> Deploys package to a remote repository.



Maven Download link

https://maven.apache.org/download.cgi

Please download below zip file

Binary zip archive	apache-maven-3.9.10-bin.zip

![image](https://github.com/user-attachments/assets/819bec59-4a6d-4eca-a0da-dffe83019b34)

Downloaded Zip file

![image](https://github.com/user-attachments/assets/e719ecd4-e291-4e4e-a8d7-f4f947b2723c)

Please extract the file

![image](https://github.com/user-attachments/assets/b12246c2-8695-4494-a801-837540cf1bc2)


Go to Search box & type Edit the system environemnt variables and click

It will navigate to System properties

![image](https://github.com/user-attachments/assets/2de9b257-9029-43f7-af30-4f4f4827731a)

Click Environment Variables


![image](https://github.com/user-attachments/assets/0b02d209-cb85-4afd-869f-923df054b7de)

![image](https://github.com/user-attachments/assets/88adc878-dedd-4150-9ee8-f01c75677ab2)

User variables::
================

![image](https://github.com/user-attachments/assets/d6bfe193-6a5c-4a8b-a21a-fa77c07a4bbc)

Click New

Variable Name:: MAVEN_HOME

Variable Value:: C:\Users\HP\Downloads\apache-maven-3.9.10

![image](https://github.com/user-attachments/assets/0f7829be-f1c7-4e96-b2ed-51aea69c0497)


Click OK

![image](https://github.com/user-attachments/assets/0c8f1a15-fc5f-4073-98f5-5416df90f071)



System variable::
=================

![image](https://github.com/user-attachments/assets/0cecde24-19be-4989-98c5-c3eb9c20734c)

Edit Path

![image](https://githubmvn -v.com/user-attachments/assets/5f302184-84cb-4e66-b17a-3ce4792fa45c)

Click New and give maven Installed path till \bin

C:\Users\HP\Downloads\apache-maven-3.9.10\bin


![image](https://github.com/user-attachments/assets/27d2d50a-845d-4c0f-9559-50e7779c08b2)


Click OK

![image](https://github.com/user-attachments/assets/7dd7e183-7d6d-424a-8b95-5b288e859af0)


You Can verify maven is Installed Or Not


Go to command Prompt

![image](https://github.com/user-attachments/assets/bf6571b4-cd62-4899-969b-abaec6d0ef8c)

>mvn -v

![image](https://github.com/user-attachments/assets/93472b9c-b6b0-4bd4-acac-41d28e2031d9)

C:\Users\HP>mvn -v


Apache Maven 3.9.10 (5f519b97e944483d878815739f519b2eade0a91d)
Maven home: C:\Users\HP\Downloads\apache-maven-3.9.10
Java version: 17.0.12, vendor: Oracle Corporation, runtime: C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12
Default locale: en_IN, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"

![image](https://github.com/user-attachments/assets/cc1d10c5-9c62-498f-9a58-b0f14e84438f)


Above Screeenshot maven setup is done



Installed jenkins in Windows::
================================

Please follow the below link steps to installed jenkins in your windows machines

https://www.jenkins.io/doc/book/installing/war-file/


https://www.jenkins.io/download/

Go to google search -->download jenkins war file for windows

click below Jenkins version

Download Jenkins 2.515 for:

![image](https://github.com/user-attachments/assets/eaac3392-c1ce-498f-8a85-7a5fecabeb6b)

Jenkins.war file is downloaded

![image](https://github.com/user-attachments/assets/70e676a4-9a05-4748-b8d5-2373bf8ac189)


Steps::

https://www.jenkins.io/download/

1. First download the jenkins.war file and right click -->open gitbash here
   

 ![image](https://github.com/user-attachments/assets/77ca0550-974b-463f-953a-d81c9603d69a)

  
2. run the command  -->java -jar jenkins.war --httpPort=9090

![image](https://github.com/user-attachments/assets/93cc2393-8a20-485f-ab8c-23451a64ccd3)

![image](https://github.com/user-attachments/assets/75e03c2f-0ccf-4da0-90cf-d92de22903c3)

we can see Jenkins is fully up and running

![image](https://github.com/user-attachments/assets/b0e26f12-f202-4e69-8672-223e6947d379)


Browse to http://localhost:9090 and wait until the Unlock Jenkins page appears

Installed the default suggested plugins

![image](https://github.com/user-attachments/assets/081c44fc-a6a3-46fa-82e3-7b34c2dc2dd6)

click on continue 

Need to create jenkins user profile 

USER Name--->admin (any name you can provide)

PASSWORD  -->admin  (any password as your wish but make sure you should remembered the these credentials)

![image](https://github.com/user-attachments/assets/f0458a88-da81-4d32-9f87-42458fd214a1)


Steps::

1.first we need to create New repository in Github

2.please Clone the Empty Repositoy in your local system

3.copy the Spring-petclinic project code to in your repository 

4.once done we need to push project code to github repository 

5. we need to integarte Github to Jenkins

we need to create Sample demo Project in Jenkins

Create sample Freestyle project::
============================

Click New Item

![image](https://github.com/user-attachments/assets/d9e7f707-aa00-4c74-b9ca-30489ded6f55)


Configuration stages::

1.General

2.Source code management (SCM)

3.Triggres

4.Environment

5.Build Steps

6.Post Build Actions


![image](https://github.com/user-attachments/assets/b7b5caf1-3d81-4de0-aebc-c2dc5080f916)


General Section provide the Project/job description 


At SCM stage level select the Git and provide the github details

Below url is spring-petclinic Project and everyone Should please Fork to your github account

Github Project URL::
=====================

https://github.com/srinfotechbatch2/spring-petclinic


https://github.com/srinfotechbatch2/spring-petclinic.git

![image](https://github.com/user-attachments/assets/827c5b34-8a6e-41ad-b6e1-4899348730d6)

Branches to build

![image](https://github.com/user-attachments/assets/51cf678c-afbd-40bc-bbb5-fae55e4c5537)


![image](https://github.com/user-attachments/assets/7bab6e2d-7868-460e-bd42-b2697195f3fe)

Build steps::select the Invoke top-level Maven targets
Goals section
>mvn clean install

Maven goals::

>mvn test

>mvn install


>mvn clean install


>mvn clean


>mvn package

![image](https://github.com/user-attachments/assets/53d49170-9dfe-4cad-abc0-50bf268e96c7)


Job will be created

Click Build Now


Buils is Inprogress

![image](https://github.com/user-attachments/assets/c6e399ce-ac52-47de-94a3-b4d6d156dce5)

Success Builds

![image](https://github.com/user-attachments/assets/df198c5f-ce69-45a8-a9e5-607ba2e39b34)







23/06/2025::
=================

Poll SCM ::Jenkins server ask git if there is any changes in git server or not, if changes there Jenkins server build/package the changes , every change build happened like 5 mints ,means every 5 minutes verify the Jenkins server to git if there is any changes 


![image](https://github.com/user-attachments/assets/0c4e554e-e2b4-4894-a99a-5848552cc084)


POLL SCM ----* * * * * --every minute when every commit 

Chrone JObs Formate LInk::
=============================

https://crontab.guru/examples.html


Create one sample POLL SCM jenkins job::
===========================================
Go to jenkins Dashboard
click New Item

![image](https://github.com/user-attachments/assets/1c62657f-935b-4eed-b032-08842fb09a57)

Description

![image](https://github.com/user-attachments/assets/8385086f-ae72-4630-baa2-38e16e9866c2)



Provide the Git URL

Onlinebookstore Project::
=========================

https://github.com/srinfotechbatch2/onlinebookstore.git


![image](https://github.com/user-attachments/assets/647ef983-c76e-4c48-b928-e43ab5d47570)



Branch buiild

![image](https://github.com/user-attachments/assets/cd011371-c6c5-40d6-a44a-b51186d0e3af)


POLL SCM:: * * * * *

every minute build was trigger when new commits happend in github repository


![image](https://github.com/user-attachments/assets/899495ff-ce8c-4381-a012-5d058584809a)



Build Steps::

Select Invoke top-level Maven targets


![image](https://github.com/user-attachments/assets/8a818614-ba02-45d5-a98d-8d94adbe68f7)

![image](https://github.com/user-attachments/assets/20a1d9cd-1412-41fa-8f6e-62e94024f936)


Once New Commits Happend in Github , Automatically Build is triggered in The Jenkins Server this Called CI (Continuous Integration)



Check Your Workspace::
========================== 

once build success we can bale to see the /target folder under the Workspace


![image](https://github.com/user-attachments/assets/d860064f-6f5f-4ef2-aa93-363bf45e47c5)


1.To check a job's workspace:

2.Navigate to the job in the Jenkins UI.

3.Click on "Workspace" in the left sidebar.

![image](https://github.com/user-attachments/assets/f5ab670a-e7aa-4372-bbea-c3a1c130fe3a)



Under Target Folder we can able to see the all .ear/war/jar/zip Artifacts Formates


![image](https://github.com/user-attachments/assets/369fe791-fb6e-4a59-8fb1-99a14df190c3)


PLease try to execute the Project with below Maven Goals and see the difference 


Common Maven Commands OR Maven Goals::
======================================

https://github.com/srinfotechbatch2/onlinebookstore.git

https://github.com/srinfotechbatch2/spring-petclinic.git

1) mvn clean	  ------------> Deletes target/ directory (clean build).

2) mvn compile	-----------> Compiles the source code.
   
3) mvn test	   ------------> Runs tests.
   
4) mvn package	------------> Creates a JAR/WAR.
  
5) mvn install	------------> Installs package into your local repository.
  
6) mvn deploy	-------------> Deploys package to a remote repository.




24/06/2025::
===================



![image](https://github.com/user-attachments/assets/f204a3a2-d9ac-45fd-8497-e71d0c8bf82b)

Poll SCM ::
================

Jenkins server ask git if there is any changes in git server or not, if changes there Jenkins server build/package the changes , every change build happened like 5 mints ,means every 5 minutes verify the Jenkins server to git if there is any changes 

![image](https://github.com/user-attachments/assets/6f436ad6-e92a-40e3-831a-23219c288217)

POLL SCM ----* * * * * --every minute when every commit 

Build Periodically:::	
============================

H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 


Please create a New Jenkins jobs both POLL SCM & Build Periodically 

https://github.com/srinfotechbatch2/spring-petclinic.git
https://github.com/srinfotechbatch2/onlinebookstore.git

Automatically Discard Old Builds:::
==============================
To automate the process of discarding old builds, you can configure the job’s settings to automatically delete old builds based on criteria such as the number of builds to keep or the age of the builds.

Follow these steps:

Open the Jenkins job (project).
Click on Configure (on the left-hand side).
Scroll down to the Build Discarder section (usually under the Build Triggers section).
Check Discard old builds.
Specify the following options:
Max # of builds to keep: Set the maximum number of builds to keep.
Max days to keep builds: Set the maximum age for builds to keep.
Save the configuration by clicking Save.


![image](https://github.com/user-attachments/assets/8d8c9cf9-988a-41e4-b052-539ef601171f)



Execute the Jobs in Parallel::
==============================


1.By Default execute the Jenkins build jobs are sequence way,one by one 

2.Don’t do 2 projects build parallel  this is real time scenario but we can do parallel builds as well one job

Jenkins build parallel setup

Go job ---> configure ----> Generall ---> Execute concurrent builds if necessary


![image](https://github.com/user-attachments/assets/3216a68f-b10b-44cd-83b5-b62c27525296)


![image](https://github.com/user-attachments/assets/909edd87-548d-4ded-a862-29cf850fac05)


Here 5 builds execute parallel ,I kept executor is 5 this is same machine 

![image](https://github.com/user-attachments/assets/a840a224-5cbb-43cc-92c1-d135db4ce00f)


Build Periodically:::	H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 

Create Sample Build peridiocally jenkins job::
=============================================

Description

![image](https://github.com/user-attachments/assets/5ad69478-039e-4ef7-a35f-cb18ed8364f1)

Git url::

![image](https://github.com/user-attachments/assets/b2cbdb7c-14ac-4fae-a240-90cc7a82c78d)

Build the branch

![image](https://github.com/user-attachments/assets/94230c57-b88f-4ab1-b894-151f30fa6d53)

every 5 mints build will trigger

Build Periodically:::	H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 
![image](https://github.com/user-attachments/assets/a5321109-944b-4e79-9294-e28c2adfea0d)

click save 





25/06/2025::
==================

Email Notifications::
=======================

1.Setting up Jenkins Email Notifications allows you to alert your team when a build passes, fails, or encounters issues. Here's a step-by-step guide to configure it

2. give continues Feedback to the Dev team via Email when a build passes, fails

![image](https://github.com/user-attachments/assets/b60b42e4-5365-4197-a090-778e1023aba6)

Steps::

Go to mail 


![image](https://github.com/user-attachments/assets/e6764012-c4e8-43ab-bea7-0fcf11c61f5e)

Click manage your google account

![image](https://github.com/user-attachments/assets/b2b0e9e5-66ff-4713-b95b-0cc3cc2ecf42)


Click Security


![image](https://github.com/user-attachments/assets/acc069d3-2944-43d7-a0d0-a0ae17b478d6)


Click protect your account


![image](https://github.com/user-attachments/assets/a80aa65d-210c-4920-ac59-bff59d001048)

Click Add phone number

![image](https://github.com/user-attachments/assets/d3839125-e302-40a0-a942-497f50f2e08a)

Click add phone

![image](https://github.com/user-attachments/assets/758cb87d-c0df-43d1-890a-6539046b86f7)

![image](https://github.com/user-attachments/assets/e532e1dd-fef8-4ed6-b46c-075d97cdd10d)

![image](https://github.com/user-attachments/assets/96dde956-0cb9-4125-bc16-9b18b5a47883)

Make sure your account is protected 

![image](https://github.com/user-attachments/assets/ef101b4f-f98a-4941-83bb-e99c98a7b583)


Make sure 2-steps Verification is ON


![image](https://github.com/user-attachments/assets/eb82b19f-0ae0-4df4-8c79-463769e0f2cf)


Credentials:

In search box App Password


![image](https://github.com/user-attachments/assets/20789330-ae4d-407d-b55c-201452435d33)

![image](https://github.com/user-attachments/assets/45634fa0-7198-4a55-9ce3-bd5c7c7b4c2d)


![image](https://github.com/user-attachments/assets/d9e2b041-0e63-42de-96be-0b2406113328)


![image](https://github.com/user-attachments/assets/814dc39c-290f-4035-bec8-6871cfd44467)


Zvqxxvplduhrlffv   --we should provide this password in Jenkins Email configuration level


![image](https://github.com/user-attachments/assets/b1cde092-d3ed-4ae8-b9fb-e3fd32095fce)


Go to Jenkins  ---> Manage Jenkins

System configurations


![image](https://github.com/user-attachments/assets/e3467726-c6f8-45f5-b728-5012e2e906f3)



Go to Extended E-mail Notification



![image](https://github.com/user-attachments/assets/11351c43-ecf5-4327-86d9-a4bcde391589)


SMTP server  :: smtp.gmail.com

SMTP Port:: 465

Credentials::
Username:: Your Email
Password::Zvqxxvplduhrlffv

![image](https://github.com/user-attachments/assets/7e8c5e1a-785f-4b0e-b85c-f37b6f1123ce)



Select Use SSL

Default content type HTML

![image](https://github.com/user-attachments/assets/742a4252-a704-4a0c-ad2b-ae35e9c2a2e0)


Default Triggers

![image](https://github.com/user-attachments/assets/67d1fe48-b3f0-4d59-a842-054b11a3ed70)

E-mail Notification


![image](https://github.com/user-attachments/assets/dc3dfcd8-1454-434b-a88b-44acf32a3f56)


![image](https://github.com/user-attachments/assets/37414d6d-d388-4f21-840e-899b8c3e3bf1)


Use SMTP Authentication? –should selected

Use SSL select

Port 465

![image](https://github.com/user-attachments/assets/0c8e8c73-69bc-4a2b-a19e-f130e81f8c16)


Test configuration by sending test e-mail

![image](https://github.com/user-attachments/assets/b48d366e-5a52-458c-b80d-1c45b803e3ce)


Connection success

![image](https://github.com/user-attachments/assets/28f7fd8a-c85e-486a-b2f4-64af53b1db0a)


 Post build action


![image](https://github.com/user-attachments/assets/d386a9c7-a5cf-4a48-a6ab-5030c96288e0)


![image](https://github.com/user-attachments/assets/d200565f-7356-4470-b080-8ba7f731837c)


![image](https://github.com/user-attachments/assets/7cddd9fa-8498-47fa-a86b-5066ae058700)


![image](https://github.com/user-attachments/assets/60b129a8-5adf-43b1-9639-a293c59d929c)





26/06/2025::
==================

Published Artifacts & Test Results::
=============================

![image](https://github.com/user-attachments/assets/591cddf5-eb86-4942-91a7-1dc5bfbb0f72)


![image](https://github.com/user-attachments/assets/23f6cd8e-1aac-4597-9900-a4c759ad4b8a)

Post build Action i want to published artifacts & test results

![image](https://github.com/user-attachments/assets/fcd3ea28-a352-431f-8e1b-86758787fe7a)

I'm going to created one free style job and configured Post-build Actions

In post build Action select the option Archive the artifacts

>target/*.war  OR target/*.jar  OR target/*.zip  OR target/*.ear

![image](https://github.com/user-attachments/assets/44f88d03-d9c8-4800-88e2-06217f721d5c)

![image](https://github.com/user-attachments/assets/7ed9efc9-6a45-4eff-a789-0b7fe50c6024)


In post build Action select the option Publish JUnit test result report for to published the test results

>target/surefire-reports/*.xml


![image](https://github.com/user-attachments/assets/e3c17557-410c-4915-bec3-2ec5edee6526)



I want to show test results ::
=================================


>ls target 

Post build action stage

Select archive the artifact
--target/*.jar

Junit test results::
--target/surefire-reports/*.xml

See test results & antifactory ::
===================================


![image](https://github.com/user-attachments/assets/819809c2-3611-45e0-abd0-0139b29d166b)




3.For every company will do sequence build on one project this is recommended approach



General  ---just descriptin

SCM

where is your project--github, bitbucket

Triggere

whenever code changes i want build the project given time

Environmant

--all about workspaces folders

Build Steps

dev team will tell which tool we are using in current project


Post Build

devops engineer is aim is given continue feedback to dev team via email notification




27/06/2025::
=================


Parameterized Jenkins Jobs ::

Run the same job with different inputs without modifying the configuration manually

Go To New Item

![image](https://github.com/user-attachments/assets/695a7137-6283-462b-8ff7-37ffb4f6ff68)


Enter Job Name, Free style project and click ok

![image](https://github.com/user-attachments/assets/da12fe42-db98-40e1-af80-1ba335b50596)



Enter the description

![image](https://github.com/user-attachments/assets/cd3c1d8f-d403-4694-a830-1084796c80ad)


Select the option This project is parameterised

![image](https://github.com/user-attachments/assets/e2fb86d9-ea5b-4981-a3ee-81d4645d06c1)


Click Add Parameter

![image](https://github.com/user-attachments/assets/2702952d-1e31-4432-a405-88f509bfc58c)


Select optiions String parameter or choise parameter or boolean parameter you can select the ny options based on your requirement 

![image](https://github.com/user-attachments/assets/1b18b622-c141-4988-bdc3-785359a04e99)


select string parameter

![image](https://github.com/user-attachments/assets/33215729-9b13-46bf-bbbb-b08416979dd6)


Select Choise Parameter

![image](https://github.com/user-attachments/assets/59b8db99-1196-4024-9cdf-b3a80a358f81)


choise parameter

![image](https://github.com/user-attachments/assets/952de313-ebde-4b39-be7b-c31c6b0ca283)


Click Save

![image](https://github.com/user-attachments/assets/4f19f2ba-c85b-4adf-9dd0-16da436011dd)


You Can observed this project is parameterized 

![image](https://github.com/user-attachments/assets/fef0f526-c9f2-4dec-8d0e-960efc94d09c)


Click Build with parameter

![image](https://github.com/user-attachments/assets/1cbeb32c-bd23-4d87-87be-8e6d010bb968)


select deployment environment

![image](https://github.com/user-attachments/assets/af62b4d7-b107-4856-b567-d010efb3a11a)


select which versioj you want to deployment like tis you can configured real time parameterized project in jenkins

![image](https://github.com/user-attachments/assets/506da743-2efd-4e19-8082-67592c3c24b1)


Click Build

![image](https://github.com/user-attachments/assets/9554cd4a-ba9a-4821-af2e-638d554632a8)


![image](https://github.com/user-attachments/assets/28afabd9-1c84-4313-95c6-1ec8bd50488d)



I want Build a 3 projects ::
===========================

I want a build 3 projects ,one project build is success then it will start 2nd project & once 2nd project build is success then it will start 3rd Project, without manually interventions we need setup these 3 projects configurations.

![image](https://github.com/user-attachments/assets/5d043ea2-97c3-4b8f-8b56-95703e1adf95)





30/06/2025::
=============

I want Build a 3 projects ::
===========================

I want a build 3 projects ,one project build is success then it will start 2nd project & once 2nd project build is success then it will start 3rd Project, without manually interventions we need setup these 3 projects configurations.

![image](https://github.com/user-attachments/assets/5d043ea2-97c3-4b8f-8b56-95703e1adf95)



![image](https://github.com/user-attachments/assets/b2dfde9d-e397-46b8-a8cb-67ab3711b141)


Project-A, Projec -B, Projec - C 

Once Project-A build is done, then it will start Project-B build and once Project-B build SUccess then it will start Project-C build ---for this we need to select Add post-build action and select "Build other projects" in drop down and provide Project-B details.


![image](https://github.com/user-attachments/assets/048a99bc-bcf6-47ca-9b27-ef23152eab97)


Projec A is  (Downstream project is ---Projec B)

Projec B is (UP Stream project is ----Projec A)

Projec C is (downstream project of --Projec B)

i created 3 free style project in jenkins 

Project-A ::
==============

Github URL::: https://github.com/parasa7358/spring-petclinic.git

![image](https://github.com/user-attachments/assets/e8073061-b815-4945-bd7f-c20b3a6576e2)


Post Build Action , select the option Build Other Project  Project-B


![image](https://github.com/user-attachments/assets/ef75f777-c273-4255-b063-f9853072dfcb)

Project -B ::
=============

Github URL:::https://github.com/parasa7358/onlinebookstore.git


![image](https://github.com/user-attachments/assets/2ee62e92-e677-4717-93be-77d6dd1ecbf9)


Post Build Action , select the option Build Other Project Project-C


![image](https://github.com/user-attachments/assets/ec7cfc18-002b-4dc3-8438-a75b12b9a438)


Project-C::
============


Github URL:::https://github.com/srinfotechbatch2/devOpsWeb.git


Pipelines Introduction:::

A Jenkins pipeline is a series of automated steps or stages that define the process of continuous integration/continuous delivery (CI/CD) for your code. Jenkins, being a popular open-source automation server, uses pipelines to automate tasks like building, testing, and deploying code.

There are two types of Jenkins pipelines:

1. Declarative Pipeline
2. Scripted Pipeline

1. Declarative Pipeline::
The declarative pipeline syntax is simpler and more structured. It's the recommended style for most users because it's easy to read and maintain

Create Pipeline Project::
=======================

Steps

Click +New Item


![image](https://github.com/user-attachments/assets/43694be8-ac77-41a1-9d90-30175a91443f)

Enter the Project Name And Click OK

![image](https://github.com/user-attachments/assets/b21659a3-ff70-46ff-86b0-7a965b48197a)

At General Section Provide the Description

![image](https://github.com/user-attachments/assets/e0c5db89-597c-439e-91e1-7722bd4d5467)


At Definition, We need to select the Pipeline Script 

![image](https://github.com/user-attachments/assets/f9b35819-0b40-4d71-9678-949d35a4cd3e)



Here's an example of a simple declarative pipeline: Syntax

pipeline{

agent any

stages{

Stage ('Clone'){

steps{

// write code
}
}

Stage ('Build'){
steps{

// write code
}
// write code

}

Stage ('Test'){

steps{

// write code
}
// write code

}
Stage ('Execute test casea and get the results'){

steps{

// write code
}
// write code

}

Stage ('Generated Artifact'){

steps{

// write code
}
// write code

}

Stage ('Deploy'){

steps{

// write code
}
// write code

}

// write code

}

}

Please try to create one pipeline job in jenkinsfile and execute the below Declarative pipeline example:;


pipeline {

   agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/srinfotech7358/spring-petclinic.git'
            }
        }
        
          stage('Build') {
            steps {
               bat 'mvn clean install'
            }
        }
          stage('Test') {
            steps {
               bat 'mvn test'
            }
        }
          
    }
}


Plugins::
===============

Plugins in Jenkins are essential components that extend its core functionality, allowing you to customize Jenkins to meet specific CI/CD needs. Jenkins has a vast plugin ecosystem that supports building, deploying, and automating software projects across various platforms and tools

Install Plugins in Jenkins::
==============================

Step-by-Step:
Log in to Jenkins as an administrator.

Navigate to Manage Jenkins (usually on the left sidebar).

Click on Manage Plugins.

(Image reference from Jenkins documentation)

Go to the Available tab.

Use the search box to find the plugin you want.

Check the box next to the plugin name.

Click:

Pipeline: Stage View::
=================

Pipeline: Stage View Plugin in Jenkins
The Pipeline: Stage View plugin is a visualization tool in Jenkins that allows users to see a graphical view of each stage in a pipeline. It provides a real-time and historical overview of pipeline execution per stage, making it easier to debug, monitor, and analyze performance.


Click the Build Now and we can triggered the pipeline

![image](https://github.com/user-attachments/assets/4e211efb-fafe-4598-b29c-bb4bd5d488f2)



![image](https://github.com/user-attachments/assets/04315f1c-44ff-4078-952b-38320fec68c8)


Success all the stages & Steps


![image](https://github.com/user-attachments/assets/318c9d53-56fc-4815-9205-74d4dac0bf28)


Key elements in the declarative pipeline:::
======================================
pipeline: This is the top-level structure.

agent: Specifies where the pipeline will run, such as on any available agent, a specific node, or a Docker container.

stages: Defines the different steps or stages in the pipeline (e.g., Build, Test, Deploy).

steps: Commands to be executed in each stage.



02/07/2025::
===============

Please try to create one pipeline job in jenkinsfile and execute the below Declarative pipeline example:;

pipeline {

agent any

stages {
    stage('Clone') {
        steps {
            git branch: 'main', url: 'https://github.com/srinfotech7358/spring-petclinic.git'
        }
    }
    
      stage('Build') {
        steps {
           bat 'mvn clean install'
        }
    }
      stage('Test') {
        steps {
           bat 'mvn test'
        }
    }
    
      stage('Generate Junit Test Results') {
        steps {
           junit 'target/surefire-reports/*.xml'
        }
    }
    
      stage('Generate Artifacts') {
        steps {
           archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
        }
    }
}
}


See test results & antifactory ::
================================

archive the artifact :: target/*.jar

Junit test results:: target/surefire-reports/*.xml

![image](https://github.com/user-attachments/assets/0649e7f3-4c6e-4767-8588-d561c5f9e685)


Pipeline as Code::
===================

Both declarative and scripted pipelines are stored as Jenkinsfiles, which you place in your source code repository. This allows you to version control your pipeline and keep it aligned with your application code.

![image](https://github.com/user-attachments/assets/7d3b20e8-e72f-41ff-94ce-0c912f51a93d)

![image](https://github.com/user-attachments/assets/edd96e0c-ac4d-438e-8a5b-97ae99ed1fda)




03/07/2025::
==================


Pipeline as Code::
==================
Both declarative and scripted pipelines are stored as Jenkinsfiles, which you place in your source code repository. This allows you to version control your pipeline and keep it aligned with your application code.

Declarative pipeline with Jenkinsfile::
===============================

pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'git@github.com:parasa7358/spring-petclinic.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
        
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Test Results Reports') {
            steps {
                junit 'target/surefire-reports/*.xml'
            }
        }
        
        stage('Artifacts') {
            steps {
                archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}


This pipeline:::

1 Checks out the source code from your Git repository.

2. Builds the project using Maven.
   
3.Runs unit tests.

4.Deploys the application using a custom script.

JOb creation::

![image](https://github.com/user-attachments/assets/dacaf03a-5557-44ce-88ba-0b230ed061cb)

Branches to build

![image](https://github.com/user-attachments/assets/64065ba7-534e-4771-a667-00d5f64e5a4b)

Script Path::: This path is Jenkinsfiles where we maintained in github source code level

![image](https://github.com/user-attachments/assets/3b4783f0-c613-45d1-81a7-00712a79f5ad)


Scripted pipeline with Jenkinsfile::
===============================


node{

    stage('clone'){
        git branch: 'main', url: 'https://github.com/srinfotechbatch2/spring-petclinic.git'

    }

     stage('build'){

        bat 'mvn clean install'
    }

     stage('Test'){
      bat 'mvn test'
        
    }
     stage('Artifacts'){
     archiveArtifacts artifacts: 'target/*.jar', followSymlinks: false
        
    }
     stage('generated test reports'){
    junit 'target/surefire-reports/*.xml'
        
    }
}



![image](https://github.com/user-attachments/assets/90db8ef7-ded5-473a-bb1c-78fcd7c68f2f)


github sourcecode jenkinsfile 

![image](https://github.com/user-attachments/assets/44f93ca7-1d95-4efb-afad-cc262de61dbe)



Tomcat Web Server: Introduction
=============================

Apache Tomcat is an open-source web server and servlet container developed by the Apache Software Foundation. It is primarily used to serve Java applications and is one of the most popular servlet containers in the world.

Tomcat is an essential tool for anyone working with Java web applications. It provides a simple, reliable platform for deploying and managing Java Servlets and JSPs and is widely used in both development and production environments. Its ease of use, combined with powerful features and flexibility, makes it an ideal choice for many developers working on Java-based web applications.

Apache Tomcat is an open-source web server and servlet container that is primarily used to serve Java-based web applications. It implements several Java EE (Enterprise Edition) specifications, such as Java Servlet, JavaServer Pages (JSP), and WebSocket, among others. Tomcat is often used to run Java applications on the web because it's lightweight, easy to configure, and widely supported.

Here are some key points about Tomcat:

1. **Servlet Container**: Tomcat is a servlet container, meaning it manages the lifecycle of Java Servlets, which are small Java programs that run on a web server.
  
2. **JSP Support**: Tomcat also supports JavaServer Pages (JSP), a technology that allows for embedding Java code within HTML pages.

3. **Configuration**: It’s highly configurable through XML files, like `server.xml` for server settings, `web.xml` for application settings, and others.

4. **Lightweight**: Unlike full-fledged application servers like WildFly (formerly JBoss) or GlassFish, Tomcat is primarily a servlet and JSP container, which makes it lighter and easier to deploy for simpler Java web applications.

5. **Performance**: It’s known for good performance in handling static content, making it a popular choice for Java web developers.



Integrate Tomcat  with Jenkins::
==============================


![image](https://github.com/user-attachments/assets/7e336e86-1278-4a6b-bea8-8c77a5c062dc)



04/07/2025::
=============


Tomcat Download link::
--------------------

https://tomcat.apache.org/download-90.cgi


64-bit Windows zip

![image](https://github.com/user-attachments/assets/bba6eafd-95c3-4963-a862-b4b97bb8cd24)


Integrate Tomcat Jenkins::
==============================



![image](https://github.com/user-attachments/assets/7155f817-58cd-4f85-93e8-405b7c96fd7b)



![image](https://github.com/user-attachments/assets/88c760fe-9f55-4d8e-9003-66ace1bf9db7)


Integrating Tomcat with Jenkins is a common use case for automating the deployment of Java-based web applications. Jenkins can be set up to deploy a web application to a Tomcat server whenever a new build is triggered.

Prerequisites:

Apache Tomcat should be installed and running on your server.
Jenkins should be installed and running.

Steps to integrate Jenkins with Tomcat:

1. Install the "Deploy to Container" Plugin in Jenkins:
The easiest way to deploy to Tomcat from Jenkins is by using the Deploy to Container plugin. This plugin allows Jenkins to deploy WAR files to a Tomcat server.

Go to your Jenkins dashboard.
Click on Manage Jenkins > Manage Plugins.
In the Available tab, search for Deploy to Container Plugin and install it.
Once installed, restart Jenkins to apply the plugin.

2. Configure Tomcat Server in Jenkins:
Now you need to tell Jenkins where your Tomcat server is running.

In Jenkins, go to Manage Jenkins > Configure System.
Scroll down to the Deploy to container section.
Click Add Tomcat Server.

Provide the necessary information:
Name: Give the Tomcat server a name (Tomcat9).
URL: The URL of your Tomcat server (e.g., http://localhost:8080).
Username: The username for Tomcat's manager app (usually admin).
Password: The password for that username (set in Tomcat's tomcat-users.xml).
Save the configuration.

3. Configure Tomcat’s tomcat-users.xml:
Make sure Tomcat is set up to allow Jenkins to deploy the application by editing the tomcat-users.xml file.

https://stackoverflow.com/questions/7763560/401-unauthorized-error-while-logging-in-manager-app-of-tomcat

tomcat-users.xml file::
=========================

![image](https://github.com/user-attachments/assets/61a0b6ae-1e6c-47d0-8852-b226d65f38a4)



  <role rolename="manager-gui"/>
  <role rolename="manager-script"/>
  <role rolename="manager-jmx"/>
  <role rolename="manager-status"/>
  <role rolename="admin-gui"/>
  <role rolename="admin-script"/>
  <user username="admin" password="admin" roles="manager-gui, manager-script, manager-jmx, manager-status, admin-gui, admin-script"/>




Restart Tomcat to apply the changes.

4. Create a Jenkins Job to Build and Deploy the Application:
Next, you need to create a Jenkins job that will build your web application (e.g., a WAR file) and deploy it to Tomcat.

From the Jenkins dashboard, click New Item.

Select Freestyle Project, give it a name, and click OK.

In the job configuration, go to the Build section and configure your build step, such as building a Maven project For Maven, you can use:

> mvn clean install

In the Post-build Actions section, add Deploy war/ear to a container.

In the WAR/EAR files field, provide the path to your WAR file (e.g., target/my-app.war).
In the Container field, choose the Tomcat server you configured earlier.
Set the Context Path (e.g., IfocusAWSDevOpsTraining), which is the URL path where the application will be accessible on Tomcat.
If you want Jenkins to deploy automatically after every successful build, check the option Deploy after every successful build.
Save the job.

5. Trigger the Build and Deployment:
Go to the Jenkins job you just created and click Build Now to trigger a build.
After the build completes, Jenkins should deploy the WAR file to your Tomcat server.

You can access your application by going to http://<tomcat_host>:<tomcat_port>/<context_path>

example::  http://localhost:8080/IfocusApplication/

POLL SCM:: * * * * * (every minute automatic build & deployment happend when new commits happend in github)
This setup will allow Jenkins to automatically build and deploy your Java web application to Tomcat with each new build


Polling SCM (Source Code Management) and webhooks are two common methods used for integrating continuous integration (CI) systems or automating tasks based on changes in repositories.

1. Polling SCM
Polling SCM is a method where a system (like Jenkins, GitLab CI, etc.) periodically checks the source code repository for changes. If it detects changes, it triggers the build process or some other automated task.

How it works:

A job is set up to check the SCM (like GitHub, GitLab, Bitbucket, etc.) at regular intervals (e.g., every minute or hour).

The CI server pulls the repository to see if there are any new commits since the last poll.

If changes are detected, it triggers the CI/CD pipeline to build, test, or deploy the application.

2. Webhooks
Webhooks provide a more efficient method for triggering actions based on changes in the repository. Rather than the CI system polling for changes, the source control platform sends an HTTP POST request (webhook) to the CI system when an event (like a commit or pull request) occurs.

![image](https://github.com/user-attachments/assets/59e3f392-4da9-4fe3-8238-d2bd2fee5fc3)



CI/CD::
==============

Github Project URL:::

https://github.com/srinfotech7358/onlinebookstore.git


![image](https://github.com/user-attachments/assets/73aa8ffc-90f2-4d45-9d39-8cf6ff7358a0)

TomcatIntegarteWithJenkins::

![image](https://github.com/user-attachments/assets/747c3c66-3f12-4048-84c5-02a87119463e)

![image](https://github.com/user-attachments/assets/3df4e76b-15b0-4da5-88eb-d83a8f5982ad)

![image](https://github.com/user-attachments/assets/5fc161ca-106f-442c-9938-1ea4c840e919)

POLL SCM

![image](https://github.com/user-attachments/assets/451a29ca-845b-4ec8-a4c2-f0325386aca4)

Build Steps

![image](https://github.com/user-attachments/assets/82271c03-60b4-4383-b0cd-429f1d24226a)

Post-build Actions

Deploy war/ear to a container

WAR/EAR files ----> target/*.war

Context path ---> SRinfotechAWSTraing

![image](https://github.com/user-attachments/assets/b15d3751-a792-49f8-a590-05a7e9761c92)

Tomcat 9.x Remote

![image](https://github.com/user-attachments/assets/de1c2aae-8c08-4f98-aead-a6829e01c24d)

Tomcat URL:: http://localhost:8080

![image](https://github.com/user-attachments/assets/aeed88d6-aec3-4aef-8880-ff871e1d6345)




07/07/2025::
=================


CI/CD::
==========

Continuous Integration & Continutes Deployment & COntinuoues Delivery::
=======================================================================

Continuous Integration(CI)::the practice of automating the integration of code changes from multiple Developers into a single software project. It's a primary DevOps best practice, allowing developers to frequently merge code changes into a central repository,after which automated builds and tests are run automatically.

developers frequently commit to a shared repository using a version control system such as Git,A continuous integration automatically builds and runs unit tests on the new code changes to immediately using jenkins Orchestration.


![image](https://github.com/user-attachments/assets/2713a0f0-ab19-4228-bb6c-2380259ebe7e)


Continuous Deployment(CD) :: Continuous Deployment is an extension of continuous delivery. With continuous deployment, every change that passes through the automated tests and builds is automatically deployed to production without any human intervention. The deployment process is fully automated.

Continuous Delivery (CD)::Continuous Delivery is a software development practice in which code changes are automatically built, tested, and prepared for release to production in a consistent and reliable manner. The key distinction of continuous delivery is that the process of deploying the code to production is done manually by a human decision-maker.



Deploy Onlinebookstore/spring-petclinic applications to target server (Tomcat)::
=====================================================================================================================

please create one new pipeline job

Provide the Description

![image](https://github.com/user-attachments/assets/458b8076-ebce-4ac0-932e-64ee5a6e460b)

Enabled POLL SCM

![image](https://github.com/user-attachments/assets/5b5ae6d9-987a-4c54-9450-c3a89497be29)

In Pipeline Section write groovy script using Declarative style 


![image](https://github.com/user-attachments/assets/5d624b7b-9224-4d20-863f-0f3e4671916e)


Generate Deploy pipeline script::
====================================




Script::
=======

pipeline
{
    agent any

    tools{

        maven 'maven'
    }

stages{
stage('Git checkout'){

    steps{

        git branch: 'main' url: 'https://github.com/parasa7358/Petclinic.git'

    }
}

stage('clean and install'){

    steps{

      sh 'mvn clean install'

    }
}

stage('Package'){

    steps{

      sh 'mvn package'

    }
}

stage('Archive the Artifacts'){

    steps{

      sh 'mvn clean install'
    }
    post{
        success{

            archiveArtifacts artifacts: '**target/*.war'
        }
    }

    }


stage('Test Cases'){

    steps{

      sh 'mvn test'

    }
}


stage('Deploy to tomcat server'){

    steps{

      deploy adapters: [tomcat9(credentialsId: 'tomcat9credentials', path: '', url: 'http://localhost:8080/')], contextPath: 'SRINFOTECH', war: '**/*.war'

    }
}

}
}


Run the job


![image](https://github.com/user-attachments/assets/f240a720-41dd-4bc0-955d-a247b1cf8918)

![image](https://github.com/user-attachments/assets/369955cf-0f1c-4ae1-bae3-3870edc0e282)

Integrate Jenkins with Tomcat using Declarative Approach::
============================================

To integrate Jenkins with Tomcat using the Declarative Pipeline approach, you'll be using Jenkins Pipeline syntax to automate the deployment process to a Tomcat server. This process typically involves building the application, packaging it, and then deploying it to Tomcat.

1. Jenkinsfile Configuration (Declarative Pipeline)

In your Jenkins project, you'll create a Jenkinsfile, which contains the Declarative Pipeline syntax. This file defines the steps involved in the CI/CD pipeline.

Please execute below script in jenkins pipeline job using Declarative style

pipeline
{
    agent any

    tools{

        maven 'maven'
    }

stages{
stage('Git checkout'){

    steps{

        git branch: 'main', url: 'https://github.com/srinfotechbatch2/Petclinic.git'

    }
}

stage('clean and install'){

    steps{

      bat 'mvn clean install'

    }
}

stage('Package'){

    steps{

      bat 'mvn package'

    }
}

stage('Archive the Artifacts'){

    steps{

      bat 'mvn clean install'
    }
    post{
        success{

            archiveArtifacts artifacts: '**target/*.war'
        }
    }

    }


stage('Test Cases'){

    steps{

      bat 'mvn test'

    }
}


stage('Deploy to tomcat server'){

    steps{

      deploy adapters: [tomcat9(credentialsId: 'tomcat9credentials', path: '', url: 'http://localhost:8080/')], contextPath: 'SRINFOTECH', war: '**/*.war'

    }
}

}
}


Onlinebookstore::
=============

 pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'master', url: 'https://github.com/srinfotech7358/onlinebookstore.git'
            }
        }
        
          stage('Build') {
            steps {
               bat 'mvn clean install'
            }
        }
         stage('Generate Artifacts') {
            steps {
               archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }

          stage('Deploy to Tomcat Server') {
            steps {
               deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'Tomcat', path: '', url: 'http://localhost:8080')], contextPath: 'SR INFOTECH SOLUTIONS PVT LIMITED', war: 'target/*.war'
            }
        }
    }
}



10/07/2025::
==============


Introduction to SonarQube::
================================

SonarQube is an open-source platform developed by SonarSource that is used for continuous inspection of code quality. It helps developers and development teams identify bugs, code smells, vulnerabilities, and duplication in their codebases across multiple programming languages.

Key Features of SonarQube
Static Code Analysis
SonarQube analyzes source code without executing it, detecting issues like:

Bugs

Vulnerabilities

Code smells (bad design or coding practices)

Duplications

Technical debt


Sonarqube Integrate With Jenkins::
==================================

<img width="1852" height="758" alt="image" src="https://github.com/user-attachments/assets/cfe5963b-e3af-42e4-bdf4-a5825c65f72c" />

Sonarqube installed link::

https://gist.github.com/dmancloud/0abf6ad0cb16e1bce2e907f457c8fce9

default U/P ---admin/admin

default port number:: 9000

Server URL: URL to your SonarQube instance (e.g., http://localhost:9000). and default port is 9000

To integrate SonarQube with Jenkins, you need to ensure that Jenkins can communicate with your SonarQube server to perform static code analysis during your CI/CD pipeline. This will allow you to analyze your code quality and get reports from SonarQube as part of your build process.

Here's how you can integrate SonarQube with Jenkins:please follow below steps

1. Install the SonarQube Plugin in Jenkins
Before you start, ensure that you have the SonarQube Scanner Plugin installed in Jenkins:

Go to Jenkins Dashboard.
Click on Manage Jenkins → Plugins.
Go to the Available tab, and search for SonarQube Scanner.
Install it and restart Jenkins.

2. Configure SonarQube in Jenkins
Next, you need to configure SonarQube on Jenkins so it can communicate with your SonarQube server.



11/07/2025::
=============

Steps:
=====
Go to Jenkins Dashboard.
Click on Manage Jenkins → Configure System.
Scroll down to the SonarQube servers section and click Add SonarQube.

Fill in the following details:
=======================
Name::: Give your SonarQube instance a name (SonarQubeServer).
Server URL: URL to your SonarQube instance (e.g., http://localhost:9000). and default port is 9000
Server Authentication Token: You can generate a token in SonarQube by navigating to My Account → Security → Generate Tokens. Paste this token into Jenkins.
Click Save.

3. Configure the SonarQube Scanner in JenkinsSteps:
 ===============================================
In the Configure System page, scroll to the SonarQube Scanner section.
Click Add SonarQube Scanner and select SonarQube Scanner for Jenkins.

If you want to use a custom installation, specify the path to the SonarQube Scanner binary.
Click Save.

 Configure SonarQube Project::
 ========================
Go to your SonarQube server (e.g., http://localhost:9000).
Create a project or use an existing one.
Obtain the Project Key from the SonarQube project and update the pipeline script as shown in the sonar.projectKey parameter.

Go to Projects and click Local project

![image](https://github.com/user-attachments/assets/0b177021-0fc2-4ba4-a987-fee4a3420717)

Click Next

![image](https://github.com/user-attachments/assets/2cccbec2-463b-47ab-9379-f02244272f3a)

Selected Use the global setting

![image](https://github.com/user-attachments/assets/702766f0-01a9-4919-bbda-acb3a8996dcd)

Click Create Project

![image](https://github.com/user-attachments/assets/a614a64f-7171-43c3-b19e-787e13ee0c16)

Now Spring-petclinic Project created in Sonarqube

![image](https://github.com/user-attachments/assets/0f79347c-8bde-4fa3-8eaa-3ca91a27422d)

Click Locally

![image](https://github.com/user-attachments/assets/d6e4fa35-299c-4768-b291-c669d9b52995)

![image](https://github.com/user-attachments/assets/ba49dbeb-8f7f-4fb4-ab7d-8c4d3644a133)

Click Generate for Token

Analyze "spring-petclinic12": sqp_0eb364758c5186bea4077eff841ddb99ba89a3ab


![image](https://github.com/user-attachments/assets/7e46dded-06da-467a-8838-62e9f0337a7a)

Click Continue

![image](https://github.com/user-attachments/assets/590c723c-0df3-48df-bf7d-77575e63614a)

![image](https://github.com/user-attachments/assets/ace61156-d25b-4d00-b248-d5bd0b1de835)

Selected Maven and copy below script from sonarqube and it will help to integrate Sonarqube with jenkins pipeline

![image](https://github.com/user-attachments/assets/1da2fbb2-5118-45e5-85ec-c7767a44529b)


mvn clean verify sonar:sonar \
  -Dsonar.projectKey=spring-petclinic12 \
  -Dsonar.projectName='spring-petclinic12' \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.token=sqp_0eb364758c5186bea4077eff841ddb99ba89a3ab



 IntegrateSonarqubeWithJenkins::
  ==================================

  Go To jenkins and create new job IntegrateSonarqubeWithJenkins

  ![image](https://github.com/user-attachments/assets/dc7d3f1e-5852-4288-bf00-5537b6a4935c)

Please use below script to run the pipeline job

pipeline
{
    agent any

    tools{

        maven 'maven'
    }

stages{
stage('Git checkout'){

    steps{

        git branch: 'main', url: 'https://github.com/parasa7358/Petclinic.git'

    }
}

stage('clean and install'){

    steps{

      bat 'mvn clean install'

    }
}

stage('Package'){

    steps{

      bat 'mvn package'

    }
}

stage('Archive the Artifacts'){

    steps{

      bat 'mvn clean install'
    }
    post{
        success{

            archiveArtifacts artifacts: '**target/*.war'
        }
    }

    }


stage('Test Cases'){

    steps{

      bat 'mvn test'

    }
}

stage('Sonarqube Analysis'){

    steps{

      bat 'mvn clean package'

    bat '''mvn sonar:sonar \
  -Dsonar.projectKey=spring-petclinic \
  -Dsonar.projectName='spring-petclinic' \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.token=sqp_8d74d659dbf3d3bf2924a0d24104f5ddba914fac'''

    }
}


stage('Deploy to tomcat server'){

    steps{

      deploy adapters: [tomcat9(credentialsId: 'tomcat9credentials', path: '', url: 'http://localhost:8080/')], contextPath: 'Ifocus Solutions Pvt Ltd', war: '**/*.war'

    }
}

}
}



 

1. please start Jenkins on your machine & make sure Jenkins server is UP & Running state
2. please start Tomcat on your machine & make sure Tomcat server is UP & Running state
3. please start Sonarqube on your machine & make sure Sonarqube server is UP & Running state

once above steps done then we can execute below script

Working Scripts CI/CD::
===========================

pipeline{

    tools{

        maven 'Maven'
    }
agent any

stages{

    stage('Clone'){

        steps{

            git branch: 'main', url: 'https://github.com/srinfotech7358/Petclinic.git'
        }
    }

     stage('Build') {
            steps {
               bat 'mvn clean install'
            }
        }

         stage('Test Cases') {
            steps {
               bat 'mvn test'
            }
        }

         stage('Archive the Artifacts') {
            steps {
               archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }
 stage('Sonarqube Analysis') {
            steps {
               
               bat 'mvn package'
              bat '''mvn sonar:sonar \
             -Dsonar.projectKey=spring-petclinic \
             -Dsonar.projectName='spring-petclinic' \
            -Dsonar.host.url=http://localhost:9000 \
            -Dsonar.token=sqp_96cf5222ab632b69c14baa5590210a7125185d5a'''
            }
        }


 stage('Deploy Application into Tomcat Server') {
            steps {
               deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'NewTomcat', path: '', url: 'http://localhost:8080/')], contextPath: 'Test', war: 'target/*.war'
            }
        }

}

}


Once sonarqube scanner done, please verify the sonarqube dashboard for reports & results

![image](https://github.com/user-attachments/assets/acc53857-78ca-4e07-becc-6aba969c61b4)

Go to Administration

![image](https://github.com/user-attachments/assets/e94cc57e-d8fe-4d4a-8110-6a0afa2164af)


Click Projects & Select Background Tasks


![image](https://github.com/user-attachments/assets/53d35e0d-abe2-462e-a608-4736b3cd06c4)

You can able to see all scanned projects status

![image](https://github.com/user-attachments/assets/7075a240-88a1-4c2b-b68d-c963e8f666aa)

Click on any Project, see the PASSED the quality gates

![image](https://github.com/user-attachments/assets/0d329366-3a10-4131-b5a4-e2fb7063647d)

Click on Overall Code option

![image](https://github.com/user-attachments/assets/8435ef6f-8152-42fc-85c4-ab3940473379)

![image](https://github.com/user-attachments/assets/3b454b9a-6c88-435f-b543-962f710b3f86)

see the results

![image](https://github.com/user-attachments/assets/adb4c7f2-70d5-4a85-903a-2d64e0ef5cbb)

here Code coverage is 

Coverage
82.7%

![image](https://github.com/user-attachments/assets/f5954fe3-2c85-4283-a736-0bc58308687d)

NOTE:: Coverage is greater than or equal to 80.0%, this should be maintained minimum % every project

NOTE:::Duplicated Lines (%) is less than or equal to 3.0%



Create My own Quality Gates::
=======================

Go to Dashboard click on Quality Gates

![image](https://github.com/user-attachments/assets/b7e1b1c1-e25e-4bf4-acb2-7d3f386df80c)

at left side we can see create & just click on it

![image](https://github.com/user-attachments/assets/b203f151-0ab2-4de3-84f8-a262f462a9c5)


Provide the Name & Click Create


![image](https://github.com/user-attachments/assets/a008a297-54ef-49b3-b5bf-a7df05d19c96)


Your own quality gates are created

![image](https://github.com/user-attachments/assets/f46d3c2a-dfa7-408b-a30d-5d1688de1891)

this is your own quality gates

![image](https://github.com/user-attachments/assets/dab980c2-3767-4d6b-867a-03b423593323)

nditions on New Code
Metric
Operator
Value
Issues
is greater than
0
Security Hotspots Reviewed
is less than
100%
Coverage
is less than
80.0%


Duplicated Lines (%)
is greater than


select your project

![image](https://github.com/user-attachments/assets/3f0aed8a-ebd7-4a27-8e13-4b7bbac978e1)

apply the Grant permissions to a user or a group

![image](https://github.com/user-attachments/assets/a098832f-e4eb-476d-9cbf-e9bbd0a356c5)


Apply all the permissions & click Add

![image](https://github.com/user-attachments/assets/77ce722c-f751-4a9f-844f-edeb677ccb01)

![image](https://github.com/user-attachments/assets/48485193-39d4-4e32-a7cb-c943d0d00ed6)

![image](https://github.com/user-attachments/assets/0b988e9d-df3a-4118-98b8-f4b0cd6e3262)


Create my own Quality Profile::
================================

go to Quality Profiles


![image](https://github.com/user-attachments/assets/9f3c55e8-566a-4f48-8dff-1e473ab0aee0)

select Language

![image](https://github.com/user-attachments/assets/44cc17f2-03f4-4ea0-83ff-8d97a36e1f2b)

total java Rules 527

![image](https://github.com/user-attachments/assets/40ff10ed-e1cf-4ccf-bd80-f9ff509a6ae4)


at right saide top click create

![image](https://github.com/user-attachments/assets/e786de8b-915f-466c-904f-7453eab9efab)

provide the Language & Name and click Create

![image](https://github.com/user-attachments/assets/1a2aaba8-1855-4f13-859e-3cc0b5f0367f)


your own profile

![image](https://github.com/user-attachments/assets/12c55b42-aa02-46c9-a31d-60b46d682e7e)

click Active More rules

![image](https://github.com/user-attachments/assets/d9f3dde5-92cd-466f-9d68-b4bbaae336d5)

Bulk Change

![image](https://github.com/user-attachments/assets/8e927220-c993-4b8f-8ca7-6d9884aa41c4)

Activate In Spring-pipeline project

![image](https://github.com/user-attachments/assets/55e0b2e6-7c53-4b98-b2ce-87f75f935246)

Sure Apply

![image](https://github.com/user-attachments/assets/637731b5-bcbe-4798-b87b-ca808f39f2c1)

Succcessfully Applied my own quality profile rules

Activate In Quality Profile (683 rules)

![image](https://github.com/user-attachments/assets/b530b33a-c75f-470e-9118-e0d49bcbfb96)

Now we are successfully onboarded spring-petclininc project to Sonarqube server

![image](https://github.com/user-attachments/assets/1d8bbf77-c70d-479a-8057-ff62984f23f7)

![image](https://github.com/user-attachments/assets/0c1ea5e5-fd03-46b3-aa51-0f283095ffa8)

![image](https://github.com/user-attachments/assets/45b7263c-0e82-45ff-b06f-915a2af9b464)


Running the Pipeline Once the pipeline is configured, Jenkins will execute the SonarQube analysis during the build process. After the build completes, you can view the analysis results in your SonarQube dashboard.



Code coverage Code smells Bugs Vulnerabilities Duplications These reports will be available in the SonarQube dashboard for your project.



12/07/2025::
=============


Jfrog Artifactory Overview::
========================

JFrog Artifactory is a universal artifact repository manager that serves as a central hub for storing, managing, and distributing software artifacts, binaries, packages, and other assets throughout the software development lifecycle, improving automation, and ensuring release integrity.



<img width="1787" height="767" alt="image" src="https://github.com/user-attachments/assets/8d5b9a86-4be3-499e-bb05-1abd92be89db" />



Artifact Repository Management:

Allows for storing binaries and artifacts (e.g., libraries, packages, Docker images) in a centralized location.
Supports all major package types (e.g., Maven, Gradle, npm, NuGet, RubyGems, etc.).
Version Control:

Helps in managing versions of your artifacts and ensures the correct version is used during builds and deployments.
Integration with CI/CD:

Integrates seamlessly with CI/CD tools like Jenkins, Bamboo, GitLab CI, and others.
Enables automated publishing of artifacts as part of your continuous integration pipeline.
Access Control & Security:

Provides fine-grained access control and permissions for users and groups.
Supports user authentication, security, and audit trails to ensure compliance and secure artifact management.
Replication:

Allows you to replicate artifacts across multiple Artifactory instances, ensuring high availability and disaster recovery capabilities.
Remote Repositories:

Artifactory can proxy remote repositories, allowing you to cache and fetch external dependencies without re-downloading them each time.
Promotion & Release Management:

You can "promote" artifacts from one repository to another (e.g., from a development repository to a production repository), allowing for better control over releases.
Multi-Platform Support:

Artifactory supports multiple programming languages and platforms, making it a universal solution for managing software dependencies and releases.

AWS (Amazon Web Services)::
========================

Create AWS Free tier Account::
====================================
Please go throw the recorded video session and follow the steps to create the free tier AWS account.Let me know if anyone facing any issues.

Amazon Web Services (AWS) is a comprehensive and widely adopted cloud platform offered by Amazon. It provides a broad set of services to help organizations and individuals build and scale applications, manage data, and process workloads in the cloud. AWS is designed to provide flexible, scalable, and cost-effective solutions for computing, storage, networking, machine learning, and much more.



13/07/2025::
================

Integrate Jfrog with Jenkins::
=================================

<img width="1812" height="776" alt="image" src="https://github.com/user-attachments/assets/c2fa0230-9687-4a58-8d75-f25673299a2b" />

First Step:: 
https://jfrog.com/download-jfrog-platform/  ---download url

![image](https://github.com/user-attachments/assets/6ef7f0ee-d89e-4c84-8764-17bcde0c18b3)

previous versions link

https://jfrog.com/download-legacy/?product=artifactory&version=7.104.12

All zip version and search 6.12.1 OSS version

https://releases.jfrog.io/artifactory/bintray-artifactory/

jdk compatibility version with jfrog is::
=============================================
 
JDK 12.1.0
 
https://www.oracle.com/in/java/technologies/javase/jdk12-archive-downloads.html
 
artifactory-oss-6.12.1
 
All zip version and search 6.12.1 OSS version
 
https://releases.jfrog.io/artifactory/bintray-artifactory/


Jfrog Script::
===============

stage ('Artifactory Server'){
            steps {
               rtServer (
                 id: "Artifactory",
                 url: 'http://localhost:8081/artifactory',
                 username: 'admin',
                  password: 'password',
                  bypassProxy: true,
                   timeout: 300
                        )
            }
        }
        stage('Upload'){
            steps{
                rtUpload (
                 serverId:"Artifactory" ,
                  spec: '''{
                   "files": [
                      {
                      "pattern": "*.war",
                      "target": "ifocus-solutions-pvt-ltd"
                      }
                            ]
                           }''',
                        )
            }
        }
        stage ('Publish build info') {
            steps {
                rtPublishBuildInfo (
                    serverId: "Artifactory"
                )
            }
        }


installed plugin for artifactory (Jfrog)::
 =====================================


![image](https://github.com/user-attachments/assets/542a6be0-9059-4935-9658-81ce27634337)

After installed Artifactory plugin 

Go to Manage Jenkins--> System configuration find JFROG

 ![image](https://github.com/user-attachments/assets/5ddbd986-aaee-478b-8a03-e117f53a7b3a)

Click JFrog Platform Instances

![image](https://github.com/user-attachments/assets/c176ad14-5982-4ea3-b960-468d00f851c7)

For user name and password


Default Jfrog U/P----admin/password

![image](https://github.com/user-attachments/assets/83204f3d-bf7b-4bd5-b616-61eaf03ae216)


![image](https://github.com/user-attachments/assets/2af4f08d-5778-4517-8b90-43037eb6ecce)


![image](https://github.com/user-attachments/assets/c104f1c1-6cd0-4911-8eef-b9243a2dd41f)


I need to setup target in Jfrog

srinfotech-batch2

click Local repository

![image](https://github.com/user-attachments/assets/accda4b3-8ff1-412b-9dfb-c790ff8d9757)


Select maven

![image](https://github.com/user-attachments/assets/a711233f-8298-4fb9-84f7-3acd19d4e73c)

Repository key  :::: srinfotech-batch2

![image](https://github.com/user-attachments/assets/97c49959-7963-475d-8efb-693952d973ea)

Click save and finish

![image](https://github.com/user-attachments/assets/a17b2e49-1e1a-408a-ad16-64cb6bd734b4)


Go to artifacts and check repository is created with name -srinfotech-batch2

![image](https://github.com/user-attachments/assets/af618d7f-ba98-4b2f-8bd2-86fb7928bdae)


CI/CD all tools ans stages script:: create new job in jenkins and execute below script 
=====================================


pipeline{
agent any
 
tools{
 
    maven 'Maven'
}
 
stages{
    stage('Clone The Project'){
        steps{
            git branch: 'main', url: 'https://github.com/srinfotechbatch2/Petclinic.git'
        }
    }
    stage('Build'){
        steps{
             bat 'mvn clean install'
        }
    }
     stage('Test'){
        steps{
             bat 'mvn test'
        }
    }
     stage('Generated the test reports'){
        steps{
             junit 'target/surefire-reports/*.xml'
        }
    }
     stage('published the Artifacts'){
        steps{
            archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
        }
    }
 
    stage('SonarQube Analysis'){
        steps{
        bat 'mvn package'
      bat '''mvn sonar:sonar \
  -Dsonar.projectKey=spring-petclinic \
  -Dsonar.projectName='spring-petclinic' \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.token=sqp_b4f05b06814df65b8d3f1a467f3ed604e2dadb03'''
        }
    }
 
stage ('Artifactory Server'){

            steps {
            
               rtServer (
               
                 id: "Artifactory",
                 
                 url: 'http://localhost:8081/artifactory',
                 
                 username: 'admin',
                 
                  password: 'password',
                  
                  bypassProxy: true,
                  
                   timeout: 300
                   
                        )
            }
            
        }
        stage('Upload'){
        
            steps{
            
                rtUpload (
                
                 serverId:"Artifactory" ,
                 
                  spec: '''{
                  
                   "files": [
                   
                      {
                      
                      "pattern": "*.war",
                      
                      "target": "srinfotech-batch2"
                      
                      }
                      
                            ]
                            
                           }''',
                           
                        )
            }
            
        }
        stage ('Publish build info') {
        
            steps {
            
                rtPublishBuildInfo (
                
                    serverId: "Artifactory"
                )
                
            }
            
        }
 
 
    
    stage('Deploy to Tomcat Server'){
    
        steps{
        
            deploy adapters: [tomcat9(alternativeDeploymentContext: '', credentialsId: 'tomcatcredential', path: '', url: 'http://localhost:8080')], contextPath: 'SRInfotechSpringpetclinicJfrog', war: 'target/*.war'
        }

        
    }
    
}

}

JfrogIntegratedWithJenkinsPOLLSCM::
================================



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dcf472a6-5afd-441d-82fd-f3f31a9a1aeb" />




21/07/2025::
==============


AWS (Amazon Web Services)::
====================

Amazon Web Services (AWS) is a comprehensive and widely adopted cloud platform offered by Amazon. It provides a broad set of services to help organizations and individuals build and scale applications, manage data, and process workloads in the cloud. AWS is designed to provide flexible, scalable, and cost-effective solutions for computing, storage, networking, machine learning, and much more.

AWS ---Amazon web services

compute services::
Amazon EC2 (Elastic Compute Cloud): Provides scalable virtual servers to run applications.
AWS Lambda: Lets you run code without provisioning or managing servers. It automatically scales based on usage.

Storage services::
Amazon S3 (Simple Storage Service): Object storage for storing and retrieving large amounts of data.
Amazon EBS (Elastic Block Store): Persistent block-level storage for EC2 instances.

Database::
Amazon RDS (Relational Database Service): Managed relational database service supporting multiple database engines (e.g., MySQL, PostgreSQL, MariaDB, etc.).
Amazon DynamoDB: A managed NoSQL database service.
Amazon Aurora: A high-performance relational database engine compatible with MySQL and PostgreSQL.

Network services::
Amazon VPC (Virtual Private Cloud): Lets you create isolated networks within AWS for secure connections.

Security ::

AWS IAM (Identity and Access Management): Controls user access and permissions for AWS resources.
AWS KMS (Key Management Service): Managed service for creating and controlling encryption keys.
Security groups ---inbound, outbould roles


Containers & kuberneties::
ECS  ---elastic containers servcies
EKS  ----estastic kuberneties services
AKS  ---Azure kuberneties services

Cloud watch --Metrics Monitoring

CloudWatch Metrics allows you to track the performance and utilization of AWS resources such as EC2 instances, RDS databases, Lambda functions, S3 buckets, and much more.
These metrics include CPU utilization, disk activity, network traffic, and others. You can create custom metrics for your applications or services as well.

cloud trail ---Security Monitoring:

Use CloudTrail logs to detect unauthorized access or activity in your AWS environment. You can track changes in security settings, unauthorized API calls, or unexpected configuration changes.

Developer Tools::
AWS CodeCommit: Source control service for managing your code repositories.
AWS CodeDeploy: Automates code deployments to EC2 instances and Lambda.
AWS CodePipeline: Continuous integration and continuous delivery (CI/CD) service for automating the release pipeline.

AWS EC2 ::
===========
Amazon Elastic Compute Cloud (Amazon EC2) is one of the core services provided by Amazon Web Services (AWS)

Wide Variety of Instance Types:

EC2 instances are grouped into families based on the type of workload they are optimized for. Some common instance families include:
General Purpose: e.g., t3, m5 instances (balanced CPU, memory, and networking).
Compute Optimized: e.g., c5 instances (great for high-performance computing tasks).
Memory Optimized: e.g., r5, x1e instances (designed for high-memory workloads like databases).


Master & Node communication Via SSH keys::
============================================

<img width="1209" height="752" alt="image" src="https://github.com/user-attachments/assets/33663714-93dc-442d-901e-4ff85083fbd5" />


create EC2 Ubuntu Linux Machine in AWS::
==================================

Go to AWS ans Search EC2

![image](https://github.com/user-attachments/assets/32cf433a-97b3-444f-9231-1c4aa1da6f79)

Click EC2

![image](https://github.com/user-attachments/assets/f54992d2-7d2b-4a1c-8395-ba5aee7d5899)

Go to instances at left side bar

![image](https://github.com/user-attachments/assets/fcaee5fc-c31a-40cd-a7da-0255afef4373)

Click Launch Instances, EC2  ---> Instances  -----> Launch an instance

![image](https://github.com/user-attachments/assets/9b6128c5-cf0e-48ee-bc11-93852cc3e166)

Select Ubuntu

![image](https://github.com/user-attachments/assets/f610aae5-e7a9-43f6-af7e-e16b6ce9becb)

Select Amazon Machine Image (AMI)

![image](https://github.com/user-attachments/assets/2e5e91a6-cd80-445b-9932-b9d760475be7)


select Instance type,t2 medium

![image](https://github.com/user-attachments/assets/47d6a619-cbe2-41d4-b2ca-40ae44988efb)


Create Create new key pair and provide key pair name

![image](https://github.com/user-attachments/assets/1526a72d-ba98-45be-8998-2d67788c73ef)

click create pair

![image](https://github.com/user-attachments/assets/66a6f77c-36b3-49d3-87a5-abe0358a3c3b)

click launch instance

![image](https://github.com/user-attachments/assets/dca82f59-824d-4cf2-9bf2-ffe81948993c)

instance will be created

![image](https://github.com/user-attachments/assets/ed110a9c-d118-4a08-b678-a3cf945ef5c7)



![image](https://github.com/user-attachments/assets/38ccd3b2-71ce-4102-a047-db937ab13080)




22/07/2025::
==============

Master & Node communication Via SSH keys::
================================

i have to create 2 EC2 ubuntu machines in AWS
1. Jenkinsmaster
2. Node

<img width="1584" height="786" alt="image" src="https://github.com/user-attachments/assets/f37ad5f7-824d-4c42-a6af-625e90262341" />



we have already .pem file dowloaded in you local machin

right click from .pem and click Open git bash here option
Now Go to AWS Ubuntu machine which is already created in AWS insatnces and select master machine

![image](https://github.com/user-attachments/assets/ae110666-3e1d-4a48-bfb4-ecb3790187f8)

Click Connect

![image](https://github.com/user-attachments/assets/4130c330-b01d-4a7c-b820-7b836db556b9)

Click SSH Client

![image](https://github.com/user-attachments/assets/fb0dfc0d-abbe-427c-a79b-a10df2f2410c)

Copy URL

>ssh -i "Newkeysmasternode.pem" ubuntu@ec2-18-237-178-192.us-west-2.compute.amazonaws.com

![image](https://github.com/user-attachments/assets/a0bf53d1-3b1a-42a0-8c40-8cb39f85cd09)

Now past that url in Gitbash

![image](https://github.com/user-attachments/assets/e52355e5-73b3-4d7b-9e04-3ce8cd72ffe5)

switch to root user below command run
>Sudo -i

![image](https://github.com/user-attachments/assets/98086ebc-bbd6-4757-ac12-923a2a6eb896)

update the all packages ,please run below command

>sudo apt-get update

![image](https://github.com/user-attachments/assets/3b291e76-4a2a-4d5a-bbd2-58231282e4b7)

Install JDK & Maven:;
============

JDK link

https://bluevps.com/blog/how-to-install-java-on-ubuntu

MAven link

https://phoenixnap.com/kb/install-maven-on-ubuntu



>sudo apt-get install maven
>java -version
>mvn -v

Set java home environment 

>sudo vi /etc/environment
JAVA_HOME=”/usr/lib/jvm/java-8-openjdk-amd64/jre”
MAVEN_HOME=”/usr/share/maven”

Reload your system environment
>source /etc/environment

Veriy the variables was set correctly
>echo $JAVA_HOME
>echo $MAVEN_HOME

Insatll Jenkins on master machine::
========================================

https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-22-04

https://phoenixnap.com/kb/install-jenkins-ubuntu


AWS any machines default password authentication is disabled , 
we need to enabled in any linux machines
>sudo vi /etc/ssh/sshd_config
>sudo service sshd restart
In EC2 – by default password based authentication is disabled so we need to enabled

>sudo vi /etc/ssh/sshd_config
passwordauthentication :yes

![image](https://github.com/user-attachments/assets/99decb00-3ef0-4528-8e58-0d69bf14ce36)

In ubuntu machine default user is not sudo user,
>visudo
Jenkins ALL=(ALL:ALL) NOPASSWD:ALL
>su Jenkins
Switching to new user

![image](https://github.com/user-attachments/assets/86bc74b0-e31f-44aa-bcab-875ed9a3a016)

![image](https://github.com/user-attachments/assets/98b96a48-2ee3-466c-b917-26c1919b15f6)

Once installed Jenkins successfully
>we need to enabled the Inbounds and outbounds rules in AWS security groups

Inbounds rules

![image](https://github.com/user-attachments/assets/b7075d75-dd60-42d4-a282-7be861252685)

Copy public IP address and go to browser
Access Jenkins using Public IP address
http://35.86.160.156:8080/

bydefault Jenkins runs on port 8080
Jenkins home path/var/lib/Jenkins
How to change the port number in Jenkins::
https://stackoverflow.com/questions/28340877/how-to-change-port-number-for-jenkins-installation-in-ubuntu-12-04
>sudo nano /etc/default/jenkins


Now Go to Node Machine::
==============
Please insatll JDK & Maven in node machine and setup environemnt varibles

>sudo apt-get install maven

>java -version

>mvn -v

Set java home environment 

>sudo vi /etc/environment

JAVA_HOME=”/usr/lib/jvm/java-8-openjdk-amd64/jre”

MAVEN_HOME=”/usr/share/maven”

Reload your system environment

>source /etc/environment

Veriy the variables was set correctly

>echo $JAVA_HOME

>echo $MAVEN_HOME

comminicate master & node via SSH keys

>ssh-keygen

after generated copy the public & Private keys to node machine

option-1 to copy keys from master to node
>ssh-copy-id user@ipaddressofnodemachine

>ssh-copy-id node@172.31.44.169

2nd option --copy keys manually from master to node

3rd options --i have created authorized_keys  file in node machine and copy public key from master to node

Master Node Configuration::

>got to manage Jenkins

>manage Nodes

>click new node

Remote root directory

/home/node

![image](https://github.com/user-attachments/assets/774c7270-0607-4332-8679-ebad4a459979)

![image](https://github.com/user-attachments/assets/55da9a7b-3178-47cf-be6d-72b452a59b2d)

Launch methods via ssh

![image](https://github.com/user-attachments/assets/aa7e51ac-278f-473c-9512-bfb35422fea8)


Add credentials

![image](https://github.com/user-attachments/assets/2a3ae243-9a58-4666-bacd-317298d68f33)

>Host Key Verification Strategy
![image](https://github.com/user-attachments/assets/a926aed1-85d6-42e1-804f-da5df9792eed)

Add credentials ::
====================

option-1::

this time please use credentials option SSH key with private key from node machine



Session NOTE::
===============


Master & Node Communicatiion Via SSH keys::
===========================================
>sudo -i
>sudo apt update
>java --version
>mvn -v

environment setup::

Maven home: /usr/share/maven

>sudo apt install maven

Java Home::  /usr/lib/jvm/java-17-openjdk-amd64

>sudo apt install openjdk-17-jdk

>sudo vi /etc/environment

1.press i from your keyboard
2.press the esc from your keyboard
3. shift+:
4. wq
5. press Enter

>echo $JAVA_HOME
/usr/lib/jvm/java-17-openjdk-amd64

>echo $MAVEN_HOME
/usr/share/maven

>ssh-keygen -t ed25519

>su <username>
>su jenkins

>visudo
		
# Allow members of group sudo to execute any command
		
jenkins ALL=(ALL:ALL) NOPASSWD:ALL

ctrl+X
yes
enter

in aws passwordauthenticatuion is disabled , you need to enabled the passwordauthentication

>sudo vi /etc/ssh/sshd_config

PasswordAuthentication yes

NODE Machine::

1.sudo adduser node
2.user should provide the sudo permissions
>visudo

# Allow members of group sudo to execute any command

node ALL=(ALL:ALL) NOPASSWD:ALL

3.passwordauthentication is enabled

>sudo vi /etc/ssh/sshd_config
>cd ~

>ssh node@172.31.37.219



23/07/2025::
===============


<img width="1252" height="740" alt="image" src="https://github.com/user-attachments/assets/71f149ea-4a13-4bed-9560-bd3da0586e9e" />



Master Node Configuration::
>got to manage Jenkins
>manage Nodes
>click new node
Remote root directory

![image](https://github.com/user-attachments/assets/190f9e24-2842-4462-9773-6c98c7980d77)

![image](https://github.com/user-attachments/assets/10dcf0c4-7088-4071-a6e0-8f4729603029)
 
 

Launch methods via ssh

 ![image](https://github.com/user-attachments/assets/f25a3610-8d32-43ca-bde3-644426d37cb1)


Add credentials ::

option-1::

this time please use credentials option SSH key with private key from node machine

option::2 please use credentials with Username & password and let's try if you copy properly ,agent machine will conenct Successfully

 ![image](https://github.com/user-attachments/assets/d54e7393-a5b9-4194-8f50-c206b02c39d1)

 ![image](https://github.com/user-attachments/assets/2113f8d7-18d1-4e66-84ec-267c05fde9b5)

>Host Key Verification Strategy

 ![image](https://github.com/user-attachments/assets/58a7b48d-eab5-45a7-9661-1a72578ceda5)


Agent successfully connected

![image](https://github.com/user-attachments/assets/823523dc-fe3e-432c-b3d8-9c645483d30a)

 

Execute Jenkins job using slave 
Create one test slave job in Jenkins

>select Restrict where this project can be run

![image](https://github.com/user-attachments/assets/d6c206ac-06a1-4564-9351-7b35e4f4c521)


>select Label Expression

![image](https://github.com/user-attachments/assets/85b8897c-f6ec-4bd2-8bb9-3821251c20da)

please create 2 job in jenkins master and setup 1 job in Node machine and 2nd job master machine, just trigger Build Now 

Please observe below screenshot 2 job running different machines 

![image](https://github.com/user-attachments/assets/94005ac8-cb37-4c97-ba0e-14adf7c71566)

advantage of master & Node Integartion

![image](https://github.com/user-attachments/assets/5551bbab-46b7-49ae-b6c2-093299d2ecb2)

![image](https://github.com/user-attachments/assets/ac59dbc9-c012-44a0-ae98-0fbcc2d4e5d8)

<img width="1252" height="740" alt="image" src="https://github.com/user-attachments/assets/71f149ea-4a13-4bed-9560-bd3da0586e9e" />



24/07/2025::
==============


<img width="1252" height="740" alt="image" src="https://github.com/user-attachments/assets/7a62f53f-846f-45bb-8f32-008d1819238c" />


<img width="1561" height="767" alt="image" src="https://github.com/user-attachments/assets/fcfc76ac-8e62-4c18-b894-959e513d721d" />

Session NOTE:::
===================

Master & Node Communicatiion Via SSH keys::
===========================================
>sudo -i
>sudo apt update
>java --version
>mvn -v

environment setup::

Maven home: /usr/share/maven

>sudo apt install maven

Java Home::  /usr/lib/jvm/java-17-openjdk-amd64

>sudo apt install openjdk-17-jdk

>sudo vi /etc/environment

1.press i from your keyboard
2.press the esc from your keyboard
3. shift+:
4. wq
5. press Enter

>echo $JAVA_HOME
/usr/lib/jvm/java-17-openjdk-amd64

>echo $MAVEN_HOME
/usr/share/maven

>ssh-keygen -t ed25519

>su <username>
>su jenkins

>visudo
		
# Allow members of group sudo to execute any command
		
jenkins ALL=(ALL:ALL) NOPASSWD:ALL

ctrl+X
yes
enter

in aws passwordauthenticatuion is disabled , you need to enabled the passwordauthentication

>sudo vi /etc/ssh/sshd_config

PasswordAuthentication yes

NODE Machine::

1.sudo adduser node
2.user should provide the sudo permissions
>visudo

# Allow members of group sudo to execute any command

node ALL=(ALL:ALL) NOPASSWD:ALL

3.passwordauthentication is enabled

>sudo vi /etc/ssh/sshd_config
>cd ~

>ssh node@172.31.37.219


ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIOayYEJSyLHLOX25WbnoZgtL006XdmN6T5N0dlUnp7kI root@ip-172-31-44-252


--2 machines

1.master

a.java & mavne need install

b.setup environmemnt variables

c.install jenkins in master machine

d.provide the sudo permission to the jenkins user

e. passwordauthentication should be enabled

f. ssh-keygen -t ed25519 --> need to generate the keys in master

g. copy the public/private keys to Node machine

NOTE:: if authorized_keys file is there or not , if not there 

please be create both the machine

2.Node

a.java & mavne need install

b.setup environmemnt variables

c. need to create use as node-->adduser node

c.provide the sudo permission to the node user

visudo 

node ALL-(AAL:ALL) NOPASSWD:ALL

e. passwordauthentication should be enabled

if keys are copied correctly commenucation will be happend 



25/07/2025::
==============

Ansible:: Configuration Mamagement Tool(CM)::
==============================================

Ansible is an open-source automation tool used for configuration management, application deployment, task automation, and multi-node orchestration. It helps system administrators and DevOps professionals automate IT processes to improve efficiency, reduce errors, and simplify complex workflows.

<img width="1736" height="753" alt="image" src="https://github.com/user-attachments/assets/f0e37cb7-8866-4d28-8995-257266f7c337" />


Key Features of Ansible:
================
Agentless: Ansible doesn't require any agents to be installed on the target machines. It uses SSH (or WinRM for Windows systems) to communicate with remote nodes.

Declarative Syntax: Ansible uses YAML (Yet Another Markup Language) to define the tasks, which makes it easy to read and write.

Idempotent: Ansible ensures that running the same playbook multiple times has the same effect, meaning it won’t reapply configurations if they’ve already been applied correctly.

Modular: Ansible has a large number of pre-built modules that can be used to manage various systems, applications, and services.

Playbooks: These are YAML files that describe the automation tasks you want to run. Playbooks are the heart of Ansible automation and define the "what" and "how" of your automation tasks.

Inventory Management: Ansible can manage an inventory of systems, which is used to organize and target different sets of machines.

Basic Components:
==================
Inventory: A list of hosts (machines) that Ansible will manage.

Playbook: A YAML file that defines the tasks and roles to be applied to the inventory.

Roles: A way to group related tasks and files together in a reusable manner.

Modules: Pre-built commands that Ansible can run on target systems to accomplish specific tasks (e.g., file management, system configuration, etc.).

3 linux ubuntu machines
AWS_Ubuntu 24
1)	AWS free tier

a)ACS   ----Ansible control server

b)Node1

c)Node2


all these 3 machine ping to each other and see beow screenshots all 3 machines pings each other

![image](https://github.com/user-attachments/assets/08def171-c690-4c4c-8f93-17bdf9734c73)

Ansible Control Server(ACS):: steps
============================

<img width="292" height="244" alt="image" src="https://github.com/user-attachments/assets/4121fe3b-97b2-43bd-ac04-afa213b14d36" />


Ansible Install LInk

https://www.cherryservers.com/blog/install-ansible-ubuntu-24-04


NOTE1 & NODE2 Setup::steps
=========================


<img width="286" height="372" alt="image" src="https://github.com/user-attachments/assets/284d66db-b34b-4df0-bee4-3abc2ed651b8" />

we can search in google ansible playbook
https://docs.ansible.com/ansible/latest/user_guide/playbooks.html

https://docs.ansible.com/ansible/latest/user_guide/playbooks_intro.html#basics

Python Install link::

https://docs.vultr.com/how-to-install-python-and-pip-on-ubuntu-24-04


Steps::
======
ubuntu@ip-172-31-28-207:~$ sudo -i
root@ip-172-31-28-207:~# su ansible
ansible@ip-172-31-28-207:/root$ cd ~
ansible@ip-172-31-28-207:~$ cd /etc/ansible/
ansible@ip-172-31-28-207:/etc/ansible$ ansible -m ping all
[WARNING]: Platform linux on host localhost is using the discovered Python interpreter at /usr/bin/python3.12, but future installation of
another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
localhost | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}
[WARNING]: Platform linux on host ansiblenode2@172.31.30.200 is using the discovered Python interpreter at /usr/bin/python3.12, but future
installation of another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
ansiblenode2@172.31.30.200 | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}
[WARNING]: Platform linux on host ansiblenode1@172.31.20.135 is using the discovered Python interpreter at /usr/bin/python3.12, but future
installation of another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
ansiblenode1@172.31.20.135 | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}
ansible@ip-172-31-28-207:/etc/ansible$




28/07/2025::
=================

Ansible Playbooks Introduction::
==========================

Ansible playbooks are the heart of automation with Ansible. They are simple YAML (Yet Another Markup Language) files that define automation tasks in a structured, human-readable format. Playbooks allow you to automate configurations, deployments, and orchestration tasks in a clear and organized way.

1.what is playbook  

a.playbook is a text file

b.playbooks is set up of tasks

c.playbook is written in YAML or YML

d.each task is module

e.playbook is defined values key-values pairs

f.playbook is tell to the ansible , please execute the tasks

g.any configuration management tools maintained a state and each module have state


3 linux ubuntu machines::
==========================

AWS_Ubuntu 24
1)	AWS free tier 

a)ACS   ----Ansible control server

b)Node1

c)Node2



SSHKeys::
========= 

ssh-keys re generated in ACS--Ansible control Server

>ssh-keygen -t ed25519

above command is private & public keys are generated 

>copy public keys from ACS to Node1 & NOde2 inside the Authorized_keys files

NOTE::: Please verify the all the machines ,if Authorized_keys file is present OR not . if not please create the Authorized_keys all the machines manually

create file::
=========
>touch  Authorized_keys

Inventory::
============

add the all the node machines to hosts which is Ansible installed home directory 

>ubuntu@ip-172-31-6-13:~$ sudo -i

root@ip-172-31-6-13:~# su ansible

ansible@ip-172-31-6-13:/root$ cd ~

ansible@ip-172-31-6-13:~$ cd /etc/ansible/

ansible@ip-172-31-6-13:/etc/ansible$ ls

ansible.cfg  hosts  roles

Ansible installed Home Directory::
======================
>/etc/ansible/


Verify Ping the Machines::
============================

ansible@ip-172-31-6-13:/etc/ansible$ ansible -m ping all
[WARNING]: Platform linux on host node2@172.31.0.185 is using the discovered Python interprete
/usr/bin/python3.12, but future installation of another Python interpreter could change the
meaning of that path. See https://docs.ansible.com/ansible-
core/2.18/reference_appendices/interpreter_discovery.html for more information.
node2@172.31.0.185 | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}
[WARNING]: Platform linux on host node1@172.31.11.24 is using the discovered Python interprete
/usr/bin/python3.12, but future installation of another Python interpreter could change the
meaning of that path. See https://docs.ansible.com/ansible-
core/2.18/reference_appendices/interpreter_discovery.html for more information.
node1@172.31.11.24 | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}
[WARNING]: Platform linux on host ansible@172.31.6.13 is using the discovered Python interpret
at /usr/bin/python3.12, but future installation of another Python interpreter could change the
meaning of that path. See https://docs.ansible.com/ansible-
core/2.18/reference_appendices/interpreter_discovery.html for more information.
ansible@172.31.6.13 | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3.12"
    },
    "changed": false,
    "ping": "pong"
}


all these 3 machine ping to each other and see beow screenshots all 3 machines pings each other


Key Concepts::
==============

Playbook: A playbook is a file that contains one or more "plays." Each play defines a set of tasks to be executed on a group of hosts. The playbook can be used for things like installing packages, managing users, configuring services, etc.

Task: A task is an individual unit of work. Tasks define specific actions, such as installing a package, starting a service, or copying a file. Tasks are executed sequentially, in the order in which they are written in the playbook.

Inventory: An inventory is a list of hosts that Ansible will manage. The inventory file defines which machines to target. An inventory can group hosts together (e.g., web servers, db servers) for easy management.

Modules: Ansible provides numerous modules that are responsible for performing specific tasks like managing packages, services, files, etc. Common modules include apt, yum, service, copy, and file.


Structure of a Basic Playbook:
===============================
A basic playbook has the following components:

YAML Header: The file begins with a --- to indicate it’s a YAML file.

 the hosts (target machines)
 become: yes   ----->Sudo user 

Tasks: Tasks define the actions to be executed on the target systems.

![image](https://github.com/user-attachments/assets/71982463-6b41-4481-af94-29c76690b0b6)

I want to see where the Ansible is installed on ACS
>cd /etc/ansible

NOTE::
==========
Playbook is written in YAML format
Inside the playbook tasks
Each task is a module
Playbook is a one of yaml file
Yaml file is a collection of key-value pairsset of all tasks
Playbook is tell to the ansible what are the tasks can be performed
Each task  one module
Module is a smallest item of ansible
Module can be used to individual or smallest task can be performed
Any configuration management tool should maintain ‘state’


hosts: all (apply all we can be mentioned in inventory )
become: yes  (become user as a sudo user)
tasks:

we can search in google ansible playbook
https://docs.ansible.com/ansible/latest/user_guide/playbooks.html
https://docs.ansible.com/ansible/latest/user_guide/playbooks_intro.html#basics


install git example playbook::
==============================

---
- hosts: all

  become: yes
  
  tasks:
  
  -  name: install git
    
     apt:
     
       name: git
     
       state: present
     
       update_cache: yes

     
note:::default state is present 
update_cache: yes tells Ansible to run the apt-get update command on the remote machine before performing any further package operations (like installing or upgrading packages).
become: yes  # Elevate privileges to execute tasks as root

java install playbook::
https://www.geeksforgeeks.org/how-to-install-java-using-ansible-playbook/




java and git install playbook::
---
- hosts: all
  
  become: yes
  
  tasks:
  
  -  name: install git
    
     apt:
     
       name: git
     
       state: present
     
       update_cache: yes

  -  name: Install Java
    
     apt:
     
       name: openjdk-17-jdk
     
       state: present

>sudo vi demo.yml

copy git playbook code to demo.yml

---
- hosts: all
  
  become: yes
  
  tasks:
  
  -  name: install git
    
     apt:
     
       name: git
     
       state: present
     
       update_cache: yes

     

Run the playbook::
===============
>ansible-planbook <playbookname>
>ansible-playbook demo.yml

![image](https://github.com/user-attachments/assets/9bc02cd9-6749-4a09-a7d3-218110fd00d1)

ansible@ip-172-31-28-207:/etc/ansible$ ansible-playbook demo.yml

![image](https://github.com/user-attachments/assets/7df9edfc-af27-4815-b340-482237dfc368)


PLAY [all] **************************************************************************************************************************************

TASK [Gathering Facts] **************************************************************************************************************************
[WARNING]: Platform linux on host localhost is using the discovered Python interpreter at /usr/bin/python3.12, but future installation of
another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
ok: [localhost]
[WARNING]: Platform linux on host ansiblenode2@172.31.30.200 is using the discovered Python interpreter at /usr/bin/python3.12, but future
installation of another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
ok: [ansiblenode2@172.31.30.200]
[WARNING]: Platform linux on host ansiblenode1@172.31.20.135 is using the discovered Python interpreter at /usr/bin/python3.12, but future
installation of another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.17/reference_appendices/interpreter_discovery.html for more information.
ok: [ansiblenode1@172.31.20.135]

TASK [install git] ******************************************************************************************************************************
ok: [localhost]
ok: [ansiblenode1@172.31.20.135]
ok: [ansiblenode2@172.31.30.200]

PLAY RECAP **************************************************************************************************************************************
ansiblenode1@172.31.20.135 : ok=2    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
ansiblenode2@172.31.30.200 : ok=2    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
localhost                  : ok=2    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

ansible@ip-172-31-28-207:/etc/ansible$


install git and jdk17 insatlled playbook::
======================================

---
- hosts: localhost
  
  become: yes
  
  tasks:
  
  -  name: install git
    
     apt:
     
       name: git
     
       state: present
     
       update_cache: yes
     
  -   name: Install Java jdk17 on ubuntu machine
 
      apt:
      
        name: openjdk-8-jdk
      
        state: absent
      
        update_cache: yes

Usefull Google links::
===========

https://docs.ansible.com/ansible/2.9/modules/list_of_all_modules.html
https://docs.ansible.com/ansible/2.9/modules/apt_module.html#parameters
https://www.geeksforgeeks.org/how-to-install-java-using-ansible-playbook/
https://www.yamllint.com/
https://www.geeksforgeeks.org/how-to-install-tomcat-using-ansible-playbook/




