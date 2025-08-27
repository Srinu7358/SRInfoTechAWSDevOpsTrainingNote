
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


 we should provide this password in Jenkins Email configuration level


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




29/07/2025::
============

Executing ansible in 2 ways
1.	Adhoc command  yearly base
2.	Playbook (YAML/YML) format use for repetitive work

When we can use adhoc commands  ->I want restart servers yearly base 

if you can use system inventory, below is the command
>ansible-playbook <playbookname>
>ansible-playbook hello-world.yml

I don’t want to use system level inventory

Inventory::
==========
where hosts/ipaddress are stored

I want to create my own inventory

>Cd /etc/ansible

![image](https://github.com/user-attachments/assets/e03cd989-34e8-46f5-88d0-9af56f11b6d9)

![image](https://github.com/user-attachments/assets/7a4d1993-1c1e-4da6-94b0-eeb105cb0d36)

![image](https://github.com/user-attachments/assets/79f8fb33-19d1-47a9-b26e-aff30d75d408)

>cat /etc/ansible/hosts

Sudo vi hosts

Copy all hosts

![image](https://github.com/user-attachments/assets/bcda07ba-ab66-4b86-bf67-f7ad9c556230)

I want categories into Inventory groups::
===================================

In Ansible, inventory groups are used to organize and categorize hosts (machines or servers) into logical groups. This allows you to apply tasks to specific sets of servers, simplifying playbook management and execution. An inventory is a list of managed hosts and their associated metadata, and groups are one of the key components of that structure.

Here’s a detailed explanation of Ansible inventory groups

1. What Are Inventory Groups?
An inventory group in Ansible is a way to group hosts based on a shared characteristic. For example, you might have groups for different environments (e.g., dev, prod), different types of servers (e.g., web_servers, db_servers), or other logical categories that fit your needs.

static inventory groups defined in the standard INI or YAML format.

# Define groups of hosts:: >sudo vi hosts

[web_servers]
node1@172.31.11.24

[App_servers]

node2@172.31.0.185
ansible@172.31.6.13

[DB_servers]

node1@172.31.11.24
node2@172.31.0.185
ansible@172.31.6.13
 
i want to insatll 3 spfwares :: below playbook name -----> installsoftware.yml
==============================

---
- hosts: web_server
  
  become: yes
  
  tasks:
  
  -  name: install git
    
     apt:
     
       name: git
     
       state: present
     
       update_cache: yes

  -  name: install tree
    
     apt:
     
       name: tree
     
       state: present  

  -  name: install apache
  
     apt:
     
       name: apache2
     
       state: present

once above two files created run the below command

>ansible-playbook -i hosts installsoftware.yml
     
![image](https://github.com/user-attachments/assets/36d33a9a-b113-402c-80f7-1e9c404a245b)

>ansible -i hosts -m ping Webserver

Best practice is you need to create our own inventories

>sudo vi hosts

after ran the above yaml, please try to access all machines with IPaddresss

![image](https://github.com/user-attachments/assets/4a7778cd-6b97-4822-ad5e-11bbdde82231)

![image](https://github.com/user-attachments/assets/96a67d2a-993a-47ff-aa79-3dc8cd7aa06a)

![image](https://github.com/user-attachments/assets/01ee5e45-446e-42f2-a47f-c8b3e2fbe2f5)

Please enabled Inbound and Outbound rules::
=======================================

Inbound and outbound rules refer to the types of network traffic that are allowed or denied to and from a system, such as a server, virtual machine, or network device. These rules are typically defined in firewalls or security groups (such as in cloud environments like AWS, Azure, or Google Cloud). The primary goal is to control which data can enter or leave a network, ensuring security and proper access control.

Here’s a detailed explanation of inbound and outbound rules:

 Inbound Rules::
Inbound rules control traffic entering a system or network. These rules define which types of external traffic are allowed to reach a server, instance, or device.

Common Uses:
Allowing specific users or services to access the system.

Restricting access to the system from unauthorized users.

Opening ports for services like web servers (HTTP, HTTPS), SSH, database connections, etc

Allowing incoming traffic on port 80 (HTTP) so that users can access a web server.

Outbound Rules::
Outbound rules control traffic leaving a system or network. These rules define which traffic is allowed to exit a server or device and reach external destinations.

Common Uses:
Allowing a server to access external services like APIs, databases, or external servers.

Restricting unwanted traffic from the system to external destinations.

Controlling the flow of outgoing traffic to ensure compliance with security policies.

Allow HTTP/HTTPS: Allow outbound traffic on ports 80 (HTTP) and 443 (HTTPS) to any IP:



![image](https://github.com/user-attachments/assets/0e51f799-d746-45a5-94cb-f358ade65ba2)

![image](https://github.com/user-attachments/assets/8fa024b7-0999-40f7-94cb-3eaa018fbd41)

![image](https://github.com/user-attachments/assets/2ca3de47-8bea-4f5a-a35e-0238788cb7c7)




Install LAMP on ubuntu 24.04::
==================================

A LAMP stack stands for Linux, Apache, MySQL, and PHP, which is a popular open-source software stack used for web development. It provides everything you need to set up a dynamic website or web application.

Here’s a quick overview of each component:

Linux: The operating system (in this case, Ubuntu).

Apache: The web server that serves your website’s files.

MySQL: The database management system for storing and retrieving data.

PHP: The programming language used for dynamic web page generation.



Manual Steps::
====================

https://www.digitalocean.com/community/tutorials/how-to-install-lamp-stack-on-ubuntu

>sudo apt update

>sudo apt install apache2

>sudo apt install mysql-server

>sudo apt install php

>sudo apt install libapache2-mod-php

>sudo apt install php-mysql

>sudo systemctl restart apache2

>sudo apt install php-cli

>sudo nano /var/www/html/info.php

above steps are manually installed all required softwares in LAMP project but my requirement is to write a Playbook for those manuall steps

Playbook for LAMP::  phppackage.yml
=====================



---
- hosts: all

  become: yes

  tasks:
  
  -  name: install apache2

     apt:

     name: apache2

     state: present

     update_cache: yes

  -  name: install php

      apt:

      name: php

      state: present  

  -  name: install mysql-server

     apt:

      name: mysql-server

      state: present
     
  -  name: install libapache2-mod-php

     apt:

     name: libapache2-mod-php

     state: present
                   
  -  name: install  php-mysql

     apt:

     name: php-mysql

     state: present
     
  -  name: restart apache

     service:

     name: apache2

      enabled: true

     state: restarted

  -  name: install php-cli

     apt:

     name: php-cli

      state: present 

  -  name: copy module info.php

     copy:

     src: info.php

     dest: /var/www/html/info.php     


Copy Module::
=========

https://docs.ansible.com/ansible/latest/collections/ansible/builtin/copy_module.html

Service Module::
==================

https://docs.ansible.com/ansible/latest/collections/ansible/builtin/service_module.html

info.php ::
==========


hosts grouping:
================

![image](https://github.com/user-attachments/assets/2eb4e4d2-bda2-44fa-8e86-d4b5bd51ed9e)


[web_servers]
node1@172.31.11.24

[App_servers]

node2@172.31.0.185
ansible@172.31.6.13

[DB_servers]

node1@172.31.11.24
node2@172.31.0.185
ansible@172.31.6.13


Reference flow::
==============
ansible@ip-172-31-28-207:/etc/ansible/playbook$ ls
hosts  info.php  installsoftwares.yml  phppackage.yml
ansible@ip-172-31-28-207:/etc/ansible/playbook$ sudo vi phppackage.yml
ansible@ip-172-31-28-207:/etc/ansible/playbook$ sudo vi hosts
ansible@ip-172-31-28-207:/etc/ansible/playbook$ sudo vi phppackage.yml
ansible@ip-172-31-28-207:/etc/ansible/playbook$ ansible-playbook -i hosts phppackage.yml
ansible@ip-172-31-28-207:/etc/ansible/playbook$ sudo vi info.php
ansible@ip-172-31-28-207:/etc/ansible/playbook$ ansible-playbook -i hosts phppackage.yml

PLAY [Webservers] *********************************************************************************************

TASK [Gathering Facts] ****************************************************************************************
[WARNING]: Platform linux on host localhost is using the discovered Python interpreter at /usr/bin/python3.12,
but future installation of another Python interpreter could change the meaning of that path. See
https://docs.ansible.com/ansible-core/2.17/reference_appendices/interpreter_discovery.html for more
information.
ok: [localhost]
[WARNING]: Platform linux on host ansiblenode2@172.31.30.200 is using the discovered Python interpreter at
/usr/bin/python3.12, but future installation of another Python interpreter could change the meaning of that
path. See https://docs.ansible.com/ansible-core/2.17/reference_appendices/interpreter_discovery.html for more
information.
ok: [ansiblenode2@172.31.30.200]
[WARNING]: Platform linux on host ansiblenode1@172.31.20.135 is using the discovered Python interpreter at
/usr/bin/python3.12, but future installation of another Python interpreter could change the meaning of that
path. See https://docs.ansible.com/ansible-core/2.17/reference_appendices/interpreter_discovery.html for more
information.
ok: [ansiblenode1@172.31.20.135]

TASK [install apache2] ****************************************************************************************
ok: [ansiblenode2@172.31.30.200]
ok: [ansiblenode1@172.31.20.135]
ok: [localhost]

TASK [install php] ********************************************************************************************
ok: [ansiblenode1@172.31.20.135]
ok: [ansiblenode2@172.31.30.200]
ok: [localhost]

TASK [install mysql-server] ***********************************************************************************
ok: [ansiblenode1@172.31.20.135]
ok: [ansiblenode2@172.31.30.200]
ok: [localhost]

TASK [install libapache2-mod-php] *****************************************************************************
ok: [ansiblenode1@172.31.20.135]
ok: [ansiblenode2@172.31.30.200]
ok: [localhost]

TASK [install  php-mysql] *************************************************************************************
ok: [ansiblenode1@172.31.20.135]
ok: [ansiblenode2@172.31.30.200]
ok: [localhost]

TASK [restart apache] *****************************************************************************************
changed: [ansiblenode2@172.31.30.200]
changed: [localhost]
changed: [ansiblenode1@172.31.20.135]

TASK [install php-cli] ****************************************************************************************
ok: [ansiblenode1@172.31.20.135]
ok: [localhost]
ok: [ansiblenode2@172.31.30.200]

TASK [copy module info.php] ***********************************************************************************
changed: [localhost]
changed: [ansiblenode2@172.31.30.200]
changed: [ansiblenode1@172.31.20.135]

PLAY RECAP ****************************************************************************************************
ansiblenode1@172.31.20.135 : ok=9    changed=2    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
ansiblenode2@172.31.30.200 : ok=9    changed=2    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
localhost                  : ok=9    changed=2    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0



Please execute above steps we will see the php insatlled on all 3 machines

![image](https://github.com/user-attachments/assets/d49aa2d0-69ad-4c40-8408-2ccf3edbf838)

![image](https://github.com/user-attachments/assets/74b9e6dd-8fb1-452f-85f1-faffd48d7dae)

![image](https://github.com/user-attachments/assets/6d58255a-e6ea-44b7-a4e2-39f8598358b3)


info.php::
===========

<html>
  <head>
    <title>your_domain website</title>
  </head>
  <body>
    <h1>Hello World!</h1>

    <p>This is the landing page of <strong>your_domain</strong>.</p>
  </body>
  <body>
    <h1>Hello World!</h1>

    <p>This is the landing page of <strong>your_domain</strong>.</p>
  </body>
</html>




30/07/2025::
===============

loop::

In Ansible, loops are used to repeat tasks over a list of items, making automation more efficient and reducing redundancy in playbooks. You can loop through arrays, dictionaries, and other types of data in Ansible to execute tasks multiple times.

There are several ways to use loops in Ansible, and here are the most common methods:

1. Using loop keyword
The loop keyword is the most common way to iterate over a list of items. Here's an example of how to use it:

https://spacelift.io/blog/ansible-loops

https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_loops.html

https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_loops.html


Examples::
==========

---
- hosts: Webservers

  become: yes

  tasks:

    - name: Install all packages
   
      apt:
    
	name: "{{ item }}"

        state: latest

     loop:
        -  apache2
        -  php
        -  php-mysql
        -  libapache2-mod-php
        -  php-cli
    -  name: restart apache

        service:

       name: apache2

        enabled: true

       state: restarted

    -  name: copy module info.php

       copy:

       src: info.php

       dest: /var/www/html/info.php  



Setup module in ansible::
============================


https://docs.ansible.com/ansible/latest/collections/ansible/builtin/setup_module.html
Setup module is used to collect the facts
Facts information gather from nodes called facts
>ansible -I hosts -m setup Webserver

Using filter command

>ansible -i hosts -m setup -a "filter=*os*" Webserver

ansible_os_family": "Debian"

Ansible when statements

https://docs.ansible.com/ansible/latest/user_guide/playbooks_conditionals.html#the-when-statement


ansible_os_family": "Debian"

When condition is always used bottom of the script and using scrips we can able to run a playbook on a different platforms 

1.Debian
2.Redhat
---
- hosts: Webserver

  become: yes

  tasks:
  - name: install apache

    apt:
      name: apache2

    state: present

    update_cache: yes

    when: ansible_os_family == "Debian"  
  - name: install apache

    yum:

    name: httpd

     state: present

    when: ansible_os_family == "Redhat"




In Ansible, variables are used to store values that can be referenced and used throughout your playbooks, roles, and tasks. This allows for dynamic, reusable, and flexible automation. Here’s a basic breakdown of how Ansible variables work and the different ways you can define and use them:


define variables in 3 places
1.	Inventory level  lowest priority
2.	Playbook level 
3.	Command line level –highest level priority


Inventory variables: These are defined in the inventory file (or dynamic inventory) for specific hosts or groups.

[webservers]
ansiblenode1@172.31.20.135  package_name=git
ansiblenode2@172.31.30.200 package_name=apache2
localhost 

[webservers:vars]
ansiblenode2@172.31.30.200 
localhost 

package_name=httpd

Playbook variables: You can define variables directly within your playbooks using the vars section.

---
- hosts: Webservers

  become: yes

  vars:

  pacakge_name: git

  tasks:
    
    - name: Install all packages

      apt:

      name: "{{ pacakge_name }}"

      state: present

      Command-line variables: You can pass variables to your playbooks at runtime using the -e or --extra-vars option.
      

      >ansible-playbook -i hosts -e "package_name=apache2" variables2.yml



Ansible resolves variable values based on a specific precedence order. The order from highest to lowest precedence is:
====================================================================================================================

Extra-vars (-e on the command line): Command-line variables take the highest precedence.

Playbook variables: Variables defined within the playbook.

Inventory variables: Variables set in the inventory.

Debug & vars & register in Ansible module::
==========================================

https://docs.ansible.com/ansible/latest/collections/ansible/builtin/debug_module.html

---
- name: Echo message on localhost

  hosts: localhost

   connection: local

   gather_facts: no

   vars:

   message: "Hello from Ansible playbook on localhost!"

  tasks:
    
    - name: Echo message and connection type

      ansible.builtin.shell: "echo '{{ message }}' ; echo 'Connection type: {{ ansible_connection }}'"

      register: echo_output

    
    - name: Display output

      debug:

      msg: "{{ echo_output.stdout_lines }}"


>ansible-playbook -i hosts -vvv variable.yaml  --------> verbose logs purpose ,please run this command


![image](https://github.com/user-attachments/assets/7d18a6e5-a53b-436b-bf26-dbe1db0e89af)





01/08/2025::
==============

Ansible Roles::
===================


![image](https://github.com/user-attachments/assets/99525357-1651-471a-b737-df79823dc24f)


Ansible roles are a way of organizing playbooks and tasks in a modular, reusable, and maintainable structure. They allow you to break down complex playbooks into smaller, focused units of functionality that can be easily shared and reused across different projects. Here's a more detailed look at Ansible roles:

https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_reuse_roles.html

1.Written ansible in a reusable fashion
2.How do I use someone else’s work
3.Ansible galaxy is a place where we can find reusable roles

https://galaxy.ansible.com/

4.Which we can use in your script



install roles

 > Ansible-galaxy install <rolename>

 >ansible-galaxy install my_role

create my own role::

> ansible-galaxy init <rolename>

>ansible-galaxy init my_role



Structure of Ansible Roles::
===================

my_role/
├── defaults/
│   └── main.yml            # Default variables
├── files/
│   └── somefile            # Files to be copied to the target
├── handlers/
│   └── main.yml            # Handlers (usually for service restarts)
├── meta/
│   └── main.yml            # Metadata about the role
├── tasks/
│   └── main.yml            # The main tasks (this file includes other task files if needed)
├── templates/
│   └── config.j2           # Jinja2 templates for dynamic file creation
├── tests/
│   └── test.yml            # Test playbooks to verify the role works
├── vars/
│   └── main.yml            # Custom variables


Using Roles in Playbooks
Once you've defined a role, you can use it in your playbook like this:

---
- name: Example Playbook using roles
  hosts: all
  become: yes
  roles:
    - my_role

Benefits of Using Roles
Reusability: Roles can be reused across different playbooks and projects.

Modularity: Roles allow you to organize your playbook into smaller, manageable parts.

Clarity: Each role focuses on a specific task or function, making your playbooks more understandable.

Example Role: Installing Tomcat

https://galaxy.ansible.com/ui/standalone/roles/robertdebock/tomcat/install/


Create my own role

> Ansible-galaxy init rolename

![image](https://github.com/user-attachments/assets/af275783-63b6-40ab-a319-645db283a40f)

![image](https://github.com/user-attachments/assets/34cfe34b-b8bc-4026-9014-0c07c952c3af)

Install tomcat

If you're looking to install or use an Ansible role for Tomcat from Ansible Galaxy, you can search for available roles and collections related to Tomcat. Here's how you can find and use a role related to Tomcat from Galaxy.
1.	Search for a Tomcat Role

https://galaxy.ansible.com/

To search for a role related to Tomcat on Ansible Galaxy, you can use the following command:
bash
Copy
ansible-galaxy search tomcat
This will return a list of roles related to Tomcat that you can install and use.
2. Install a Tomcat Role
Once you’ve found a suitable role for Tomcat, you can install it using the ansible-galaxy install command.
For example, if you find a role called geerlingguy.tomcat, you can install it by running:
bash
Copy
> ansible-galaxy install geerlingguy.tomcat
This will download and install the role into your ~/.ansible/roles/ directory (or the path defined in your ansible.cfg file).
3. Use the Installed Tomcat Role in Your Playbook
After installing the role, you can use it in your playbook. Here’s an example of a simple playbook that installs and configures Tomcat:
yaml
Copy

Deploywar.yml::
=============

---
- hosts: localhost
  become: yes
  roles:
  - robertdebock.java
  - robertdebock.tomcat
 
  > ansible-playbook -i hosts Deploywar.yml
  

![image](https://github.com/user-attachments/assets/306fd1fc-8c51-40f7-81b6-41a44e6ee915)

  
This will use the geerlingguy.tomcat role to set up Tomcat on your webservers hosts.

https://galaxy.ansible.com/robertdebock/tomcat

![image](https://github.com/user-attachments/assets/29cfc5e4-b8e6-494b-a462-d8a11699df12)

Deploywar.yml

![image](https://github.com/user-attachments/assets/d7f4d510-bee2-4d32-ad56-7906a8574e93)

![image](https://github.com/user-attachments/assets/adad9ea6-ed52-457e-a9eb-adb2d19ad026)

![image](https://github.com/user-attachments/assets/a4c880aa-f378-4085-9122-3ef93a25e09a)


By default  tomcat run port 8080
http://18.236.181.244:8080/
http://34.216.173.44:8080/manager/html

![image](https://github.com/user-attachments/assets/fa5faaeb-ec9e-43f2-9184-7bf46f1433c4)


Most of the work is done 
Where is my war file



04/08/2025::
================


Deploy Onlinebook store war to tomcat server using roles::
==============================================================

>If war file is available in local machine use copy module
>if war file is available other machine(internet) use get_url module
Tomcat by default install

>/opt/tomcat

![image](https://github.com/user-attachments/assets/45a19e09-7641-4dec-b730-d2b01a3ea63b)

![image](https://github.com/user-attachments/assets/721d2e75-0368-4d87-bdf1-d54331ef8afb)

---
- hosts: Webservers
  become: yes
  roles:
  - robertdebock.java
  - robertdebock.tomcat
  tasks:
  - name: copy war
    get_url:
      url: https://srinfotech.s3.us-west-2.amazonaws.com/jobs/AnsibleIntegartedWith+Jenkins/5/onlinebookstore.war
      dest: /opt/tomcat/webapps/onlinebookstore.war


![image](https://github.com/user-attachments/assets/d43d4d4a-ee8d-4dd8-af09-b71dfdf2da6f)

Create S3 Bucket in AWS account::
===============================

Go to AWS account and search S3 bucket 

S3=SSS=simple storage services

![image](https://github.com/user-attachments/assets/8c1b5637-9392-414d-ab0b-21bf9d882609)

Select S3

![image](https://github.com/user-attachments/assets/c62a298f-185d-43ec-9d62-8b874e7627ec)

Click Create bucket

![image](https://github.com/user-attachments/assets/097eedf8-8e2f-48f5-876f-2c3debfccda8)

Bucket name provide

![image](https://github.com/user-attachments/assets/669f5b5a-d4e4-43ee-add1-e6be36171ec4)

Object Ownership  ---- ACLs enabled selected


Unchecked Block all public access


![image](https://github.com/user-attachments/assets/61cac919-cbbd-4b39-9121-d1ed20e33bcd)

Ackened 

![image](https://github.com/user-attachments/assets/9edcd3b0-c71a-4e78-8132-0469a192cd82)

Click crete bucket

![image](https://github.com/user-attachments/assets/c0b39afe-325c-4d82-9ea6-2204896c1f55)

S3 bucket is created in AWS

![image](https://github.com/user-attachments/assets/702e2185-29cd-43d2-9176-ad9788907bc8)

S3 bucket Created successfully


![image](https://github.com/user-attachments/assets/3c2855d7-ae2c-4f18-8ce7-3b766211b811)

Click Bucket

![image](https://github.com/user-attachments/assets/3000b5bc-8691-40cc-b5ee-e378fe813bf6)


Click Upload 


![image](https://github.com/user-attachments/assets/71efca18-9c4a-4bad-97ff-6e6baf6b559c)

Click Add Files


![image](https://github.com/user-attachments/assets/e74175f3-ca04-47bb-977b-9f9df1cf7139)

Select Onlinebookstore.war file

![image](https://github.com/user-attachments/assets/89cac099-5c85-4a29-91e9-8868f2e2f020)

Select check box to upload the onlinebookstore.war file

![image](https://github.com/user-attachments/assets/30c81ce3-4605-45e9-90bd-b719dac4d875)

Click Upload

![image](https://github.com/user-attachments/assets/85a5204d-b660-4d0c-8983-fc24b05427e4)

Upload Succeeded

![image](https://github.com/user-attachments/assets/11d79c2d-c353-404c-be41-130608b34dcb)

Copy URL

![image](https://github.com/user-attachments/assets/147864ff-fc89-4ae1-b104-b383cccba33b)

![image](https://github.com/user-attachments/assets/37ad0996-d054-4a3b-aa57-c0480254c1c1)

Copy url to below script:: onlinebookstore.yml
===================

---
- hosts: localhost
  become: yes
  roles:
  - robertdebock.java
  - robertdebock.tomcat
  tasks:
  - name: copy war
    get_url:
      url: https://srinfotech.s3.us-west-2.amazonaws.com/jobs/AnsibleIntegartedWith+Jenkins/5/onlinebookstore.war
      dest: /opt/tomcat/webapps/onlinebookstore.war

![image](https://github.com/user-attachments/assets/402272bc-6604-4840-a406-c1cc8e95dcc6)

run the playbook

>ansible-playbook -i hosts onlinebookstore.yml

![image](https://github.com/user-attachments/assets/4ed55d65-f16e-4314-8dba-c3a34c3ee5c2)

Success

![image](https://github.com/user-attachments/assets/592b947e-d422-4430-9729-98724403ce0d)

Verify deployment in Tomcat server

![image](https://github.com/user-attachments/assets/c50103d8-21ba-484e-8562-34a1b5b2c0d0)

http://54.218.133.244:8080/onlinebookstore/

![image](https://github.com/user-attachments/assets/e79ac48a-f76e-42ff-b5a5-28094402c20a)



05/08/2025::
============


Integrated Ansible & Tomcat & S3 With Jenkins::
===============================================





S3 bucket creation and integrate S3 with Jenkins::
=====================================================

Go to AWS account and search S3 bucket 

S3=SSS=simple storage services


![image](https://github.com/user-attachments/assets/24bc6c86-9063-4d41-9f91-165cdb6238dc)

 

Select S3

![image](https://github.com/user-attachments/assets/91b082dc-65f2-46be-8800-997cd38e117b)

 

Click Create bucket

 ![image](https://github.com/user-attachments/assets/147baac9-7372-4b3e-9586-77687b9722c6)


AWS region  --virgenia

![image](https://github.com/user-attachments/assets/fd820852-8d1b-49eb-b8a4-9b33c18e70b7)


Bucket name provide


 

Object Ownership  ---- ACLs enabled selected


 ![image](https://github.com/user-attachments/assets/d1928ba2-8b6e-4df9-b68d-d94cc15326b8)


Unchecked Block all public access


 ![image](https://github.com/user-attachments/assets/813ea825-a67f-4b77-af97-338992d19d6e)


Ackened 

 ![image](https://github.com/user-attachments/assets/7b2a5776-e82e-4e4a-921f-1fb75aa02edc)


Click crete bucket



![image](https://github.com/user-attachments/assets/acfc10ae-76e4-4bb0-bb3e-caaa4c4f429d)

 

S3 bucket is created in AWS


![image](https://github.com/user-attachments/assets/23c158bb-207d-4a00-8b20-eed9881438e9)

 

First installed Jenkins in AWS ubuntu machine

Installed S3 publisher plugin

Found S3 profile at system configuration


![image](https://github.com/user-attachments/assets/cff577be-a2db-4ee0-b5f3-bfda98ae7384)

 

Second step::
Create IAM role in AWS account

 IAM----> Indentity Access Management

![image](https://github.com/user-attachments/assets/4cbba43f-c06d-43b6-8a27-3dc5c76e4ec2)


![image](https://github.com/user-attachments/assets/56b9485f-2538-4558-9963-a0253328a2f8)

 

Click Users

![image](https://github.com/user-attachments/assets/5178b83a-f01a-43c5-901b-82aa693ff52d)

 

Click create user


 ![image](https://github.com/user-attachments/assets/f9c443d3-4172-475c-92fd-d55f8bac2363)


Provide the user name


![image](https://github.com/user-attachments/assets/03fa6ef0-f565-47eb-a288-e9db884cb3dd)

 
![image](https://github.com/user-attachments/assets/63632b00-66bf-494e-8d25-dfd4b7a8fe46)

 
Click next
 
![image](https://github.com/user-attachments/assets/5ccb8d94-9dd7-4823-b336-64e1f40185e0)

![image](https://github.com/user-attachments/assets/0ebcab66-285f-4498-97b9-eac4c1f1d116)
 

![image](https://github.com/user-attachments/assets/61351716-26ce-4f59-abcc-95423a19bb83)

 
 
select S3 policies


 ![image](https://github.com/user-attachments/assets/4108108b-fd6b-4b41-98af-f75c846ade4d)



User created successfully


![image](https://github.com/user-attachments/assets/9c932e66-b49a-4c79-9acd-e475ce79e89e)

 
User name::

SRInfotech

Console password::

wv9PC8%3


![image](https://github.com/user-attachments/assets/7e60afc9-f167-458d-bbd1-dbee13f0668a)

  


Create access & secret keys:;

Open new user test


 ![image](https://github.com/user-attachments/assets/0c2db911-ee73-49fa-8521-65b54ec681b9)


Click create access key

 ![image](https://github.com/user-attachments/assets/6a165b7e-fbcd-4c02-bae8-7b0d725a45c1)



Select Application running on an AWS compute service


![image](https://github.com/user-attachments/assets/ef231f9a-1511-430f-a4f9-d5555e903d84)

 

Click next


 ![image](https://github.com/user-attachments/assets/b17aa07c-f4e6-4657-a0c8-a8144a2bee0c)


Access keys created


![image](https://github.com/user-attachments/assets/4a5d2768-8666-4c15-96b1-fe050ee523f3)

 
 ![image](https://github.com/user-attachments/assets/07429f2c-a808-4fc6-9908-296c3513ed42)



Integaretd S3 with Jenkins


![image](https://github.com/user-attachments/assets/e665dc0a-43b6-41dd-8ce7-90bc7cdd1e0a)

 

Provided access and secret key

Click test connection


![image](https://github.com/user-attachments/assets/9290abf9-a675-4a0a-ab68-9c46678b83e2)

 

Check passed


 ![image](https://github.com/user-attachments/assets/56db73d5-9d8d-4f6b-9df9-4c76e746de5f)


Bucket region us-east-1

 

 ![image](https://github.com/user-attachments/assets/5179600c-c962-4000-92c9-f78e34ccd596)

 

 

Destination bucket:: should be give AWS bucket name

 
![image](https://github.com/user-attachments/assets/8273aff6-f175-41fa-a0c2-7c0ba697f74d)

 
![image](https://github.com/user-attachments/assets/9d35ced8-7e52-4ef3-973d-9fbfdb354f24)


 ![image](https://github.com/user-attachments/assets/6f78f94c-c349-4c21-ab45-bb14f5c44400)

![image](https://github.com/user-attachments/assets/04ef0eef-31ff-4cb4-a152-74b97dbc3b37)


![image](https://github.com/user-attachments/assets/560d116a-206a-4688-9711-620198f6cfad)


![image](https://github.com/user-attachments/assets/2d1d7dd4-f351-4752-928f-28377c2d9ad8)


![image](https://github.com/user-attachments/assets/6819247b-1cf8-4265-b04b-e79adf3d4051)

![image](https://github.com/user-attachments/assets/db23a9d6-5725-41d8-9083-55173325b240)


 ![image](https://github.com/user-attachments/assets/77a787c6-07bb-4c22-93fc-07939f1eb36c)

![image](https://github.com/user-attachments/assets/2cfade4f-e8c7-4254-bbcf-e103d84c13c2)



![image](https://github.com/user-attachments/assets/5eaccb62-252d-4a3e-9d53-4768cf153b69)
Should be enabled Manage artifacts options
 



 06/08/2025::
 ============

 Docker Introductions::
=================

Docker is an opensource & Applicatuions level virtualization technology and it's called containirazition.

Docker is an open-source platform that automates the deployment, scaling, and management of applications in lightweight, portable containers. Containers are isolated environments that package an application and all its dependencies (such as libraries, binaries, and configurations) to ensure it runs uniformly across different computing environments.

![image](https://github.com/user-attachments/assets/c3b1350c-eb6b-44f1-94b1-0c05b65c3653)

Docker is a platform and that make it easier to create, deploy, and run applications using containers. Containers are lightweight, standalone, and executable units that include everything needed to run a piece of software, including the code, runtime, libraries, and system tools.

container ::
==============
1.container is an insolation area of executuions of your applications
 OR
 instance of images are called containers
2.Containers are created from “images”
3. Containers are the core of Docker. They are lightweight, portable, and isolated environments where applications run.
  Docker is run your software packages /Applications  in containers called containarizations.

4. if you build a docker container for your application called containerization
5. containers have it’s own boundaries  

who will create containers?
Ans --docker images are created the containers

 Docker Images:
 ===============

 docker image is a package with all dependencies and the necessary 
information to create the container and docker image derived from multiple base images.

An image is a snapshot of a container, a blueprint that defines what the container will contain and how it will behave when run. It consists of an application and its dependencies. Docker images are built using a Dockerfile

Docker Registry::
====================

A Docker Registry is a system for storing and distributing Docker images. It is a centralized location where Docker images can be uploaded (pushed), stored, and downloaded (pulled) by users and applications. Docker images are the building blocks of containers, and registries provide a way to manage, version, and share these images across different environments.

Default registry :: https://hub.docker.com/

Physical & Virtual & Hypervisors/VMwares::
=============================================

1.tomcat & nodejs containers have it’s own process tree,own files systems,own network interfaces own storage,ram…etc
2.when you want to give application to your team/testers  docker is the best choice and when you want give system to your team/ testers VMwares are best choice.
3.application level virtulization docker is the best choice and OS level virtulization VMwares are best choice
4.individually scale the your application very easy in docker

![image](https://github.com/user-attachments/assets/c3b1350c-eb6b-44f1-94b1-0c05b65c3653)


Example:: For festival season In your organization leave management application multiple employees are applied leaves at the same time in that scenario docker is very easy to scale the one more application but physically it’s very difficult so docker is the best choice


![image](https://github.com/user-attachments/assets/c3b1350c-eb6b-44f1-94b1-0c05b65c3653)




07/08/2025::
=================


Install Docker in Ubuntu machine::
=====================================

Please follow below link steps to install the docker in ubuntu and please read all the content in that link

https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-22-04

once installed docker please verify below commands::

>docker --version

root@ip-172-31-20-86:~# docker --version
Docker version 28.0.4, build b8034c0

root@ip-172-31-20-86:~# docker info
Client: Docker Engine - Community
 Version:    28.0.4
 Context:    default
 Debug Mode: false
 Plugins:
  buildx: Docker Buildx (Docker Inc.)
    Version:  v0.22.0
    Path:     /usr/libexec/docker/cli-plugins/docker-buildx
  compose: Docker Compose (Docker Inc.)
    Version:  v2.34.0
    Path:     /usr/libexec/docker/cli-plugins/docker-compose

Server:
 Containers: 0
  Running: 0
  Paused: 0
  Stopped: 0
 Images: 0
 Server Version: 28.0.4
 Storage Driver: overlay2
  Backing Filesystem: extfs
  Supports d_type: true
  Using metacopy: false
  Native Overlay Diff: true
  userxattr: false
 Logging Driver: json-file
 Cgroup Driver: systemd
 Cgroup Version: 2
 Plugins:
  Volume: local
  Network: bridge host ipvlan macvlan null overlay
  Log: awslogs fluentd gcplogs gelf journald json-file local splunk syslog
 Swarm: inactive
 Runtimes: io.containerd.runc.v2 runc
 Default Runtime: runc
 Init Binary: docker-init
 containerd version: 05044ec0a9a75232cad458027ca83437aae3f4da
 runc version: v1.2.5-0-g59923ef
 init version: de40ad0
 Security Options:
  apparmor
  seccomp
   Profile: builtin
  cgroupns
 Kernel Version: 6.8.0-1024-aws
 Operating System: Ubuntu 24.04.2 LTS
 OSType: linux
 Architecture: x86_64
 CPUs: 2
 Total Memory: 3.82GiB
 Name: ip-172-31-20-86
 ID: 201c6f4b-75d3-4326-adf5-00b9a82a8d4d
 Docker Root Dir: /var/lib/docker
 Debug Mode: false
 Experimental: false
 Insecure Registries:
  ::1/128
  127.0.0.0/8
 Live Restore Enabled: false

if above page is came without any erros, it means docker is installed in your machine


Docker High Level Client -Server Architecture::
==================================


<img width="1700" height="665" alt="image" src="https://github.com/user-attachments/assets/0c95b9d4-34ac-4795-aa30-addb1952b6a3" />



Docker's high-level architecture revolves around several components that work together to provide containerization and isolation for applications


Docker Client (CLI)::
=================

The Docker Client is the primary interface for interacting with Docker. It can be a command-line interface (CLI), like the docker command, or a graphical interface (GUI) in some tools.

It allows users to interact with Docker's features, such as building containers, running containers, and managing containers and images.

It sends requests to the Docker Daemon to execute commands.

Docker Daemon (Dockerd)::
====================

The Docker Daemon (also known as dockerd) is the core component of Docker. It runs in the background on the host system.

The daemon is responsible for managing Docker containers, images, networks, and volumes. It listens for Docker API requests and handles container lifecycle operations such as starting, stopping, and building containers.

The Docker Daemon can communicate with multiple Docker clients, allowing for distributed management of containers.

Flow:
============
1.The Docker Client sends a command to the Docker Daemon.

2.The Docker Daemon interacts with containers, images, and storage volumes.

3.The Docker Daemon can pull images from a Docker Registry.

4.The Docker Daemon runs containers based on the images and handles networking and storage.

Docker commands::
====================

 >docker pull <imagename>

 >docker pull hello-world

 >docker images   ----used to display the all images

 > docker image ls ----used to display the all images
 
 >docker run ---used to build the images and create the container

Create the Jenkins container::
=================================

>docker run -d -p 8080:8080 jenkins/jenkins:jdk21


http://35.155.150.89:8080/


![image](https://github.com/user-attachments/assets/30576b75-b3ee-47e1-97f0-f535c46ff015)


>docker ps

above command is used to verify the how many containers are running




08/08/2025::
================

Create the Nginx web based application container::
=======================================================

>docker run -d -p 80:80 nginx:latest

http://35.155.150.89/

![image](https://github.com/user-attachments/assets/003a7ca7-5a81-4ea6-8b60-3c1dd0b7a74d)


>docker ps

above command is used to verify the how many containers are running, you can seee nginx container is running state



detached mode::
=================

Docker detached mode refers to running a container in the background

>docker run -d <image_name>

example::
> docker run -d nginx

Where:

-d is the flag for detached mode.

<image_name> is the name of the Docker image you want to run.

> docker run -d nginx

This command will:

Run the nginx container in detached mode.

Start the container in the background.

To view the containers running in detached mode, you can use the docker ps command:
======================================

>docker ps

Stopping a Container::
=================

>docker stop <containerID>

Start a Container::
=================

>docker start <containerID>

To run a command inside a running container:
======================

>docker exec -it <container_id_or_name> <command>
>docker exec -it 5336d949f33b /bin/bash

>root@5336d949f33b:/# hostname
5336d949f33b
>root@5336d949f33b:/# hostname -i
172.17.0.3


![image](https://github.com/user-attachments/assets/c7114894-3fcd-46b0-b393-6f296d23b845)

NOTE:::
=========

>docker exec -it 5178eb58223a /bin/bash
Use this command inside the container

>ctrl pq
Outside the containers

Lab practice::
===============

take one nginx web server

>docker pull nginx

root@ip-172-31-20-86:~# docker pull nginx
Using default tag: latest
latest: Pulling from library/nginx
6e909acdb790: Pull complete
5eaa34f5b9c2: Pull complete
417c4bccf534: Pull complete
e7e0ca015e55: Pull complete
373fe654e984: Pull complete
97f5c0f51d43: Pull complete
c22eb46e871a: Pull complete
Digest: sha256:124b44bfc9ccd1f3cedf4b592d4d1e8bddb78b51ec2ed5056c52d3692baebc19
Status: Downloaded newer image for nginx:latest
docker.io/library/nginx:latest

>docker images

root@ip-172-31-20-86:~# docker images
REPOSITORY        TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins   latest    be95e0848c42   7 days ago     466MB
nginx             latest    53a18edff809   7 weeks ago    192MB

>docker run -d -p 80:80 nginx

root@ip-172-31-20-86:~# docker run -d -p 80:80 nginx
3d1a52d091b05878e079b89002aa57b460c5263a585a8add0ecc671608d1f999

>docker ps

root@ip-172-31-20-86:~# docker ps
CONTAINER ID   IMAGE     COMMAND                  CREATED         STATUS         PORTS                                 NAMES
3d1a52d091b0   nginx     "/docker-entrypoint.…"   3 seconds ago   Up 3 seconds   0.0.0.0:80->80/tcp, [::]:80->80/tcp   thirsty_shaw

>docker exec -it 3d1a52d091b0

root@ip-172-31-20-86:~# docker exec -it 3d1a52d091b0  /bin/bash
docker: 'docker exec' requires at least 2 arguments

root@ip-172-31-20-86:~# docker exec -it 3d1a52d091b0 /bin/bash
root@3d1a52d091b0:/# hostname
3d1a52d091b0
root@3d1a52d091b0:/# hostname -i
172.17.0.3

root@5336d949f33b:/# ls
bin  boot  dev  docker-entrypoint.d  docker-entrypoint.sh  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
root@5336d949f33b:/# cd opt/
root@5336d949f33b:/opt# ls
root@5336d949f33b:/opt# cd ..
root@5336d949f33b:/# ls
bin  boot  dev  docker-entrypoint.d  docker-entrypoint.sh  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
root@5336d949f33b:/# cd usr/
root@5336d949f33b:/usr# ls
bin  games  include  lib  lib64  libexec  local  sbin  share  src
root@5336d949f33b:/usr# cd lib
root@5336d949f33b:/usr/lib# ls
apt  dpkg  init  locale  lsb  mime  nginx  os-release  sasl2  ssl  systemd  terminfo  tmpfiles.d  udev  x86_64-linux-gnu
root@5336d949f33b:/usr/lib#
root@5336d949f33b:/usr/lib# docker images
bash: docker: command not found
root@5336d949f33b:/usr/lib# docker imagesexit
bash: docker: command not found
root@5336d949f33b:/usr/lib# read escape sequence
root@ip-172-31-20-86:~# docker images
REPOSITORY        TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins   latest    be95e0848c42   7 days ago     466MB
nginx             latest    53a18edff809   7 weeks ago    192MB
ubuntu            latest    a04dc4851cbc   2 months ago   78.1MB
hello-world       latest    74cc54e27dc4   2 months ago   10.1kB
root@ip-172-31-20-86:~# docekr runRead from remote host ec2-34-204-17-141.compute-1.amazonaws.com: Connection reset by peer
Connection to ec2-34-204-17-141.compute-1.amazonaws.com closed.
client_loop: send disconnect: Connection reset by peer

we can see below nginx web page and nginx is running on containers

![image](https://github.com/user-attachments/assets/878995bc-58b1-4f20-982e-2d60f105891d)



Lab Practice::
====================


root@ip-172-31-39-182:~# docker images
REPOSITORY        TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins   jdk21     52e1941f479f   21 hours ago   471MB
root@ip-172-31-39-182:~# docker run -d -p 8080:8080 -p 5000:5000 jenkins/jenkins:jdk21
aca7ec14bfc5f057f73dc4cf294e920a63712bbd5f838b5205e5e00faa542318
root@ip-172-31-39-182:~# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED         STATUS         PORTS                                                                                                 NAMES
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   7 seconds ago   Up 6 seconds   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp   festive_tharp
root@ip-172-31-39-182:~# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                 NAMES
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   43 seconds ago   Up 43 seconds   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp   festive_tharp
root@ip-172-31-39-182:~# java --version
Command 'java' not found, but can be installed with:
apt install default-jre              # version 2:1.17-75, or
apt install openjdk-17-jre-headless  # version 17.0.14+7-1~24.04
apt install openjdk-21-jre-headless  # version 21.0.6+7-1~24.04.1
apt install openjdk-19-jre-headless  # version 19.0.2+7-4
apt install openjdk-20-jre-headless  # version 20.0.2+9-1
apt install openjdk-22-jre-headless  # version 22~22ea-1
apt install openjdk-11-jre-headless  # version 11.0.26+4-1ubuntu1~24.04
apt install openjdk-8-jre-headless   # version 8u442-b06~us1-0ubuntu1~24.04
root@ip-172-31-39-182:~# docker exec -it aca7ec14bfc5 /bin/bash
jenkins@aca7ec14bfc5:/$ java --version
openjdk 21.0.7 2025-04-15 LTS
OpenJDK Runtime Environment Temurin-21.0.7+6 (build 21.0.7+6-LTS)
OpenJDK 64-Bit Server VM Temurin-21.0.7+6 (build 21.0.7+6-LTS, mixed mode)
jenkins@aca7ec14bfc5:/$ sudo apt update
bash: sudo: command not found
jenkins@aca7ec14bfc5:/$ hostname
aca7ec14bfc5
jenkins@aca7ec14bfc5:/$ java --version
openjdk 21.0.7 2025-04-15 LTS
OpenJDK Runtime Environment Temurin-21.0.7+6 (build 21.0.7+6-LTS)
OpenJDK 64-Bit Server VM Temurin-21.0.7+6 (build 21.0.7+6-LTS, mixed mode)
jenkins@aca7ec14bfc5:/$ cd /var/lib/
jenkins@aca7ec14bfc5:/var/lib$ ls
apt  dpkg  git  misc  pam  shells.state  systemd
jenkins@aca7ec14bfc5:/var/lib$ exit
exit
root@ip-172-31-39-182:~# cd /var/lib/
root@ip-172-31-39-182:/var/lib# ls
PackageKit  command-not-found  grub           os-prober     shim-signed              ucf
amazon      containerd         hibinit-agent  pam           snapd                    udisks2
app-info    dbus               ieee-data      plymouth      sudo                     unattended-upgrades
apport      dhcpcd             landscape      polkit-1      swcatalog                update-manager
apt         docker             libuuid        private       systemd                  update-notifier
boltd       dpkg               logrotate      python        tpm                      usb_modeswitch
chrony      fwupd              man-db         sgml-base     ubuntu-advantage         vim
cloud       git                misc           shells.state  ubuntu-release-upgrader  xml-core
root@ip-172-31-39-182:/var/lib# cd ..
root@ip-172-31-39-182:/var# cd ..
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED         STATUS         PORTS                                                                                                 NAMES
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   7 minutes ago   Up 7 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp   festive_tharp
root@ip-172-31-39-182:/# docker exec -it aca7ec14bfc5 /bin/bash
jenkins@aca7ec14bfc5:/$ cd /var/jenkins_home/secret
bash: cd: /var/jenkins_home/secret: No such file or directory
jenkins@aca7ec14bfc5:/$ ls
bin  boot  dev  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
jenkins@aca7ec14bfc5:/$ cd secrets
bash: cd: secrets: No such file or directory
jenkins@aca7ec14bfc5:/$ cd ..
jenkins@aca7ec14bfc5:/$ ls
bin  boot  dev  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
jenkins@aca7ec14bfc5:/$ pwd
/
jenkins@aca7ec14bfc5:/$ cd /var/jenkins_home/
jenkins@aca7ec14bfc5:~$ ls
config.xml                     jenkins.telemetry.Correlator.xml  plugins                   secrets      users
copy_reference_file.log        jobs                              secret.key                updates      war
hudson.model.UpdateCenter.xml  nodeMonitors.xml                  secret.key.not-so-secret  userContent
jenkins@aca7ec14bfc5:~$ cd secrets
jenkins@aca7ec14bfc5:~/secrets$ ls
initialAdminPassword  jenkins.model.Jenkins.crumbSalt  master.key
jenkins@aca7ec14bfc5:~/secrets$ cat initialAdminPassword
3268b754fc93442e9ea3cf22c40fcc8e
jenkins@aca7ec14bfc5:~/secrets$ read escape sequence
root@ip-172-31-39-182:/# docker run -d -p 8080:8080 -p 5000:5000 jenkins/jenkins:jdk21
1b6159a409c358d5a2db6ecc34b13cf29e8f1d94ca249722a47424d02a8d6bc1
docker: Error response from daemon: failed to set up container networking: driver failed programming external connectivity on endpoint unruffled_pare (f76e7f84de1872354f3caf9f2c4d2ee9bf83c468178a614d407f1c5d35df00f3): Bind for 0.0.0.0:5000 failed: port is already allocated

Run 'docker run --help' for more information
root@ip-172-31-39-182:/# docker run -d -p 8081:8081 -p 5001:5001 jenkins/jenkins:jdk21
601ef30a9a97b2ef1ab13a6956d603edbc23cd2d2717cb4d2db41f4b88e148ae
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   8 seconds ago    Up 8 seconds    0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   12 minutes ago   Up 12 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS              PORTS                                                                                                           NAMES
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   2 minutes ago    Up About a minute   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   14 minutes ago   Up 14 minutes       0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   3 minutes ago    Up 3 minutes    0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   16 minutes ago   Up 16 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker exec -it 601ef30a9a97 /bin/bash
jenkins@601ef30a9a97:/$ java --version
openjdk 21.0.7 2025-04-15 LTS
OpenJDK Runtime Environment Temurin-21.0.7+6 (build 21.0.7+6-LTS)
OpenJDK 64-Bit Server VM Temurin-21.0.7+6 (build 21.0.7+6-LTS, mixed mode)
jenkins@601ef30a9a97:/$ cd /var/jenkins_home/
jenkins@601ef30a9a97:~$ ls
config.xml                     jenkins.telemetry.Correlator.xml  plugins                   secrets      users
copy_reference_file.log        jobs                              secret.key                updates      war
hudson.model.UpdateCenter.xml  nodeMonitors.xml                  secret.key.not-so-secret  userContent
jenkins@601ef30a9a97:~$
jenkins@601ef30a9a97:~$ exit
exit
root@ip-172-31-39-182:/# docker run -d -p 8585:8585 jenkins/jenkins:jdk21
bc684af40e16b2c7eb91de87e952ec7a1ae0bab608bc9d0e17bad723ce853d69
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   7 seconds ago    Up 7 seconds    8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   7 minutes ago    Up 7 minutes    0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   19 minutes ago   Up 19 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker run -d -p 80:80 jenkins/jenkins:jdk21
a800fb0e6d7cd81cefdb33b1ded7019c478fbd8ebd232498c99316a092b92660
root@ip-172-31-39-182:/# docker psdock
docker: unknown command: docker psdock

Run 'docker --help' for more information
root@ip-172-31-39-182:/#
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED              STATUS              PORTS                                                                                                           NAMES
a800fb0e6d7c   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   About a minute ago   Up About a minute   8080/tcp, 0.0.0.0:80->80/tcp, [::]:80->80/tcp, 50000/tcp                                                        romantic_lewin
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   2 minutes ago        Up 2 minutes        8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   9 minutes ago        Up 9 minutes        0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   22 minutes ago       Up 22 minutes       0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker pull srinfotech
Using default tag: latest
Error response from daemon: pull access denied for srinfotech, repository does not exist or may require 'docker login': denied: requested access to the resource is denied
root@ip-172-31-39-182:/# docker pull nginx
Using default tag: latest
latest: Pulling from library/nginx
dad67da3f26b: Pull complete
4eb3a9835b30: Pull complete
021db26e13de: Pull complete
397cc88dcd41: Pull complete
5f4a88bd8474: Pull complete
66467f827546: Pull complete
f05e87039331: Pull complete
Digest: sha256:dc53c8f25a10f9109190ed5b59bda2d707a3bde0e45857ce9e1efaa32ff9cbc1
Status: Downloaded newer image for nginx:latest
docker.io/library/nginx:latest
root@ip-172-31-39-182:/# docker images
REPOSITORY        TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins   jdk21     52e1941f479f   21 hours ago   471MB
nginx             latest    9a9a9fd723f1   2 days ago     192MB
root@ip-172-31-39-182:/# docker run -d -p 80:80 nginx:latest
78f28d3d450fa094d496e22de149de21141ffd1e884772251922121a7b40422d
docker: Error response from daemon: failed to set up container networking: driver failed programming external connectivity on endpoint interesting_mclaren (f76b2b0d8ace4755840ce6f55c5da9f57bfed6e0f29dd8a41991b31217fc3f6a): Bind for 0.0.0.0:80 failed: port is already allocated

Run 'docker run --help' for more information
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
a800fb0e6d7c   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   10 minutes ago   Up 10 minutes   8080/tcp, 0.0.0.0:80->80/tcp, [::]:80->80/tcp, 50000/tcp                                                        romantic_lewin
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   11 minutes ago   Up 11 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   18 minutes ago   Up 18 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   31 minutes ago   Up 31 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker stop a800fb0e6d7c
a800fb0e6d7c
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   12 minutes ago   Up 12 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   19 minutes ago   Up 19 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   31 minutes ago   Up 31 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker run -d -p 80:80 nginx:latest
585b90814ed4871098000ddaf38376502a490bc2f38bfe625d47a3ddd7f0c85f
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
585b90814ed4   nginx:latest            "/docker-entrypoint.…"   9 seconds ago    Up 9 seconds    0.0.0.0:80->80/tcp, [::]:80->80/tcp                                                                             festive_euler
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   12 minutes ago   Up 12 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   19 minutes ago   Up 19 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   32 minutes ago   Up 32 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker images
REPOSITORY        TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins   jdk21     52e1941f479f   21 hours ago   471MB
nginx             latest    9a9a9fd723f1   2 days ago     192MB
root@ip-172-31-39-182:/# docker image tag nginx srinfotech7358/SrInfotechnginx:latest
Error parsing reference: "srinfotech7358/SrInfotechnginx:latest" is not a valid repository/tag: invalid reference format: repository name (srinfotech7358/SrInfotechnginx) must be lowercase
root@ip-172-31-39-182:/# docker image tag nginx srinfotech7358/srinfotechnginx:latest
root@ip-172-31-39-182:/# docker images
REPOSITORY                       TAG       IMAGE ID       CREATED        SIZE
jenkins/jenkins                  jdk21     52e1941f479f   21 hours ago   471MB
nginx                            latest    9a9a9fd723f1   2 days ago     192MB
srinfotech7358/srinfotechnginx   latest    9a9a9fd723f1   2 days ago     192MB
root@ip-172-31-39-182:/# docker login -u srinfotech7358

i Info → A Personal Access Token (PAT) can be used instead.
         To create a PAT, visit https://app.docker.com/settings


Password:

WARNING! Your credentials are stored unencrypted in '/root/.docker/config.json'.
Configure a credential helper to remove this warning. See
https://docs.docker.com/go/credential-store/

Login Succeeded
root@ip-172-31-39-182:/# docker push srinfotech7358/srinfotechnginx
Using default tag: latest
The push refers to repository [docker.io/srinfotech7358/srinfotechnginx]
cd38dca3d982: Mounted from library/nginx
d35594dd7e6d: Mounted from library/nginx
126eaee18409: Mounted from library/nginx
6380429cac56: Mounted from library/nginx
13fcb2d303e8: Mounted from library/nginx
151f9feea563: Mounted from library/nginx
7fb72a7d1a8e: Mounted from library/nginx
latest: digest: sha256:3004321c732af3becb9dc247f5e8926faba9186aa67960e15767996abcec588b size: 1778
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
585b90814ed4   nginx:latest            "/docker-entrypoint.…"   10 minutes ago   Up 10 minutes   0.0.0.0:80->80/tcp, [::]:80->80/tcp                                                                             festive_euler
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   22 minutes ago   Up 22 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   29 minutes ago   Up 29 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   42 minutes ago   Up 42 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker stop 585b90814ed4
585b90814ed4
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   23 minutes ago   Up 23 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   30 minutes ago   Up 30 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   42 minutes ago   Up 42 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker run -d -p 80:80 srinfotech7358/srinfotechnginx:latest
9f5173c50d14631bd31c8270f79a45db441e8c66db5b730dbb7197de65594c20
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
9f5173c50d14   srinfotech7358/srinfotechnginx:latest   "/docker-entrypoint.…"   9 seconds ago    Up 8 seconds    0.0.0.0:80->80/tcp, [::]:80->80/tcp                                                                             vibrant_dewdney
bc684af40e16   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   24 minutes ago   Up 24 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   31 minutes ago   Up 31 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   43 minutes ago   Up 43 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker stop 9f5173c50d14
9f5173c50d14
root@ip-172-31-39-182:/# docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                                                                                           NAMES
bc684af40e16   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   25 minutes ago   Up 25 minutes   8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   32 minutes ago   Up 32 minutes   0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
aca7ec14bfc5   jenkins/jenkins:jdk21   "/usr/bin/tini -- /u…"   44 minutes ago   Up 44 minutes   0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker ps -a
CONTAINER ID   IMAGE                                   COMMAND                  CREATED              STATUS                        PORTS                                                                                                           NAMES
9f5173c50d14   srinfotech7358/srinfotechnginx:latest   "/docker-entrypoint.…"   About a minute ago   Exited (137) 27 seconds ago                                                                                                                   vibrant_dewdney
585b90814ed4   nginx:latest                            "/docker-entrypoint.…"   12 minutes ago       Exited (0) 2 minutes ago                                                                                                                      festive_euler
78f28d3d450f   nginx:latest                            "/docker-entrypoint.…"   13 minutes ago       Created                                                                                                                                       interesting_mclaren
a800fb0e6d7c   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   23 minutes ago       Exited (143) 13 minutes ago                                                                                                                   romantic_lewin
bc684af40e16   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   25 minutes ago       Up 25 minutes                 8080/tcp, 50000/tcp, 0.0.0.0:8585->8585/tcp, [::]:8585->8585/tcp                                                romantic_buck
601ef30a9a97   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   32 minutes ago       Up 32 minutes                 0.0.0.0:5001->5001/tcp, [::]:5001->5001/tcp, 8080/tcp, 0.0.0.0:8081->8081/tcp, [::]:8081->8081/tcp, 50000/tcp   frosty_pare
1b6159a409c3   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   33 minutes ago       Created                                                                                                                                       unruffled_pare
aca7ec14bfc5   jenkins/jenkins:jdk21                   "/usr/bin/tini -- /u…"   44 minutes ago       Up 44 minutes                 0.0.0.0:5000->5000/tcp, [::]:5000->5000/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 50000/tcp             festive_tharp
root@ip-172-31-39-182:/# docker start 9f5173c50d14
9f5173c50d14
root@ip-172-31-39-182:/# Read from remote host ec2-35-155-150-89.us-west-2.compute.amazonaws.com: Connection reset by peer
Connection to ec2-35-155-150-89.us-west-2.compute.amazonaws.com closed.
client_loop: send disconnect: Connection reset by peer


Usefull commands:
===============

>docker --version

>docker info

>docker pull <imagename>

>docker pull ubuntu =docker pull ubuntu:latest

>docker images

>docker run -d ubuntu

>docker ps -aq

>docker rmi <imagenname>

>docker run -d -p 8080:8080 -p 5000:5000 jenkins/jenkins:jdk21

>docker exec -it aca7ec14bfc5 /bin/bash     --->inside the container comamnd

>docker run -d -p 8080:8080 -p 5000:5000 jenkins/jenkins:jdk21

>ctrl+pq or exit

>docker image tag nginx srinfotech7358/srinfotechnginx:latest


Class Note::
=============

Docker Introduction::

--docker is a open source contaniraztion platform
--application level virtulazition platform docker is best choice 
--lightweight platform
--

container:: insolated area of running your application

images:: image is package with all the dependencies and the necessary information to 
create the contaienrs

if you build a docker containers for your application called containarization

who created the containers?

images are created by containarization

Docker registry::

storage area of images called docker registry

default registry---docker hub

>docker images

>docker pull <imagename>:tagname
>docker pull jenkins/jenkins:jdk21
>docker run -d -p 8080:8080 jenkins/jenkins:jdk21
>docker exec -it 1cd47478b564 /bin/bash     ----> this cpommand is used to go inside the contaienr

>docker run -d -p 9090:9090 jenkins/jenkins:jdk21

>docker stop <containerID>
>docker stop 6cd503941b8a
>docker rmi <imagename>
>docker rmi hello-world -f
>docker run -d -p 80:80 nginx:latest

>docker login -u srinfotechbatch2

>docker image tag <imagename> <userofdockerhub/imagenametagname:imagetagname>

>docker image tag jenkins/jenkins srinfotechbatch2/srinfotechjenkins:latest
>docker tag nginx srinfotechbatch2/nginxapp:latest
>docker push srinfotechbatch2/nginxapp
>docker run -d -p 80:80 srinfotechbatch2/nginxapp:latest




11/08/2025::
==================

Dockerfile Introduction::
=================

A Dockerfile is a script containing a series of instructions on how to build a Docker image. It defines the environment and application setup, including dependencies, configurations, and the necessary steps to get your application running in a container.

dockerfile is a text file, and it have set up of all instructiuons

https://docs.docker.com/get-started/docker-concepts/building-images/writing-a-dockerfile/


Dockerfile::dockerfile is text file, and it have set up of all instructiuons

FROM nginx or ubuntu or 

LABEL "AUthor =nagaraju@gamil.com"

RUN apt update && apt-get install jenkins -y

COPY . .  ----src destnations

ADD  . . -----src destinatuion

CMD ["echo",".jar"]

ENTRYPOINT ["echo", "war"]

EXPOSE 8080,8085

ENV APP_HOME ="Ifocus SOlutions pvt ltd"

WORKDIR $APP_HOME /app

VOLUME 

Key Components of a Dockerfile:
==========================

FROM: Specifies the base image for the Docker image you're creating.

FROM ubuntu:20.04

RUN: Executes commands inside the container, often used to install dependencies.

RUN apt-get update && apt-get install -y python3

COPY or ADD: Copies files from your local machine into the container.

COPY . /app

WORKDIR: Sets the working directory for any subsequent commands in the Dockerfile.


WORKDIR /app

CMD: Specifies the command to run when a container is started from the image.

CMD ["python3", "app.py"]

EXPOSE: Defines the network ports the container will listen on at runtime.

EXPOSE 8080

ENV: Sets environment variables inside the container.
ENV APP_ENV=production
CMD & ENTRPOINT can be executed starting of the container

CMD & ENTRYPOINT Different::
===========================
--use CMD you can change the value but ENTRYPOINT not possible to change the value at the starting of the container
--CMD you can change the argument value 
--ENTRYPOINT can’t change the argument value

CMD ["echo",".jar"]
ENTRYPOINT ["echo", "war"]

CMD/ENTRYPOINT ====should have something which runs till your app is alive

Note::
=======
life time of your container -->time which your cmd/entrypont is alive

Example Dockerfile:::
==========
Here’s a simple Dockerfile example that builds a Python web app:

# Use an official Python runtime as the base image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container
COPY . /app

# Install the required dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose the port the app runs on
EXPOSE 5000

# Define the command to run the application
CMD ["python", "app.py"]

Building and Running a Docker Image:
Once you’ve written your Dockerfile, you can build and run it using Docker commands:

Build the Docker image:

>docker build -t my-python-app .

Run the container:
>docker run -d -p 8080:8080 my-python-app

A **Dockerfile** is a script containing a series of instructions on how to build a Docker image. It defines the environment and application setup, including dependencies, configurations, and the necessary steps to get your application running in a container. Essentially, it's the blueprint for creating Docker images.

### Key Components of a Dockerfile:
1. **FROM**: Specifies the base image for the Docker image you're creating.
   ```dockerfile
   FROM ubuntu:20.04
   ```

2. **RUN**: Executes commands inside the container, often used to install dependencies.
   ```dockerfile
   RUN apt-get update && apt-get install -y python3
   ```

3. **COPY** or **ADD**: Copies files from your local machine into the container.
   ```dockerfile
   COPY . /app
   ```

4. **WORKDIR**: Sets the working directory for any subsequent commands in the Dockerfile.
   ```dockerfile
   WORKDIR /app
   ```

5. **CMD**: Specifies the command to run when a container is started from the image.
   ```dockerfile
   CMD ["python3", "app.py"]
   ```

6. **EXPOSE**: Defines the network ports the container will listen on at runtime.
   ```dockerfile
   EXPOSE 8080
   ```

7. **ENV**: Sets environment variables inside the container.
   ```dockerfile
   ENV APP_ENV=production
   ```

### Example Dockerfile
Here’s a simple Dockerfile example that builds a Python web app:

```dockerfile
# Use an official Python runtime as the base image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container
COPY . /app

# Install the required dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose the port the app runs on
EXPOSE 5000

# Define the command to run the application
CMD ["python", "app.py"]
```

### Building and Running a Docker Image:
Once you’ve written your Dockerfile, you can build and run it using Docker commands:

1. **Build the Docker image**:
   ```bash
   docker build -t my-python-app .
   ```

2. **Run the container**:
   ```bash
   docker run -p 5000:5000 my-python-app
   ```

The Dockerfile streamlines the process of creating consistent and reproducible environments, making it easier to deploy applications across different systems.


Please try Below Example on Docker file:
============================================

https://docs.docker.com/get-started/workshop/02_our_app/


Spring Micro Services Aplication::
=======================

https://github.com/srinfotech7358/spring-ms.git

LAB Practice::
==============

root@ip-172-31-32-42:~# git clone https://github.com/srinfotech7358/spring-ms.git
Cloning into 'spring-ms'...
remote: Enumerating objects: 242, done.
remote: Counting objects: 100% (145/145), done.
remote: Compressing objects: 100% (78/78), done.
remote: Total 242 (delta 47), reused 103 (delta 31), pack-reused 97 (from 1)
Receiving objects: 100% (242/242), 29.16 MiB | 3.85 MiB/s, done.
Resolving deltas: 100% (76/76), done.
root@ip-172-31-32-42:~# ls
getting-started-app  snap  spring-ms
root@ip-172-31-32-42:~# cd spring-ms/
root@ip-172-31-32-42:~/spring-ms# ls
Dockerfile  azure-pipeline.yml  azure-pipelines.yml  deploy.yaml  pom.xml  src
root@ip-172-31-32-42:~/spring-ms# sudo vi Dockerfile
root@ip-172-31-32-42:~/spring-ms# docker build -t srinfotech .
[+] Building 43.6s (12/12) FINISHED                                    docker:default
 => [internal] load build definition from Dockerfile                             0.0s
 => => transferring dockerfile: 256B                                             0.0s
 => WARN: FromAsCasing: 'as' and 'FROM' keywords' casing do not match (line 1)   0.0s
 => [internal] load metadata for registry.access.redhat.com/ubi8/openjdk-11:lat  0.9s
 => [internal] load metadata for docker.io/library/maven:3.6.3-jdk-11            1.0s
 => [auth] library/maven:pull token for registry-1.docker.io                     0.0s
 => [internal] load .dockerignore                                                0.0s
 => => transferring context: 2B                                                  0.0s
 => [internal] load build context                                                0.3s
 => => transferring context: 30.64MB                                             0.3s
 => [stage-1 1/2] FROM registry.access.redhat.com/ubi8/openjdk-11:latest@sha25  25.4s
 => => resolve registry.access.redhat.com/ubi8/openjdk-11:latest@sha256:28b35ee  0.0s
 => => sha256:28b35eea470174a39befd8eb9250a3276b79a4f6e7dac7872 1.47kB / 1.47kB  0.0s
 => => sha256:8be99c30a4e5b021129310847bddca64a93fb38b0c8dfeac482b4 596B / 596B  0.0s
 => => sha256:0c46377f1021ce6db9f2457907fe43fd1001b2ecc1ae2ac 30.70kB / 30.70kB  0.0s
 => => sha256:e0348fdb2685077d22116d294a90a253709aba78815882a 39.49MB / 39.49MB  2.6s
 => => sha256:50d776090f4e8d167cbe918c0da58f7b67533ab58d59 113.69MB / 113.69MB  18.7s
 => => extracting sha256:e0348fdb2685077d22116d294a90a253709aba78815882a57fcc53  2.7s
 => => extracting sha256:50d776090f4e8d167cbe918c0da58f7b67533ab58d59ffa6acb6f2  6.4s
 => [stage1 1/3] FROM docker.io/library/maven:3.6.3-jdk-11@sha256:1d29ccf46ef2  16.5s
 => => resolve docker.io/library/maven:3.6.3-jdk-11@sha256:1d29ccf46ef2a5e64f7d  0.0s
 => => sha256:1801d353e27e68d60355b371ddfd2ed8d06204bc3266f1746 2.42kB / 2.42kB  0.0s
 => => sha256:004f1eed87df3f75f5e2a1a649fa7edd7f713d1300532fd 50.43MB / 50.43MB  1.0s
 => => sha256:1d29ccf46ef2a5e64f7de3d79a63f9bcffb4dc56be0ae3daed5ca 549B / 549B  0.0s
 => => sha256:e23b595c92ada5c9f20a27d547ed980a445f644eb1cbde7cf 8.93kB / 8.93kB  0.0s
 => => extracting sha256:004f1eed87df3f75f5e2a1a649fa7edd7f713d1300532fd0909bb3  3.6s
 => => sha256:5d6f1e8117dbb1c6a57603cb4f321a861a08105a81bcc6b01 7.83MB / 7.83MB  1.4s
 => => sha256:48c2faf66abec3dce9f54d6722ff592fce6dd4fb58a0d0b 10.00MB / 10.00MB  1.7s
 => => sha256:234b70d0479d7f16d7ee8d04e4ffdacc57d7d14313faf59 51.84MB / 51.84MB  3.1s
 => => sha256:d7eb6c022a4e6128219b32a8e07c8c22c89624ff440ebac15 5.29MB / 5.29MB  2.8s
 => => sha256:6c215442f70bd949a6f2e8092549943905e2d4f9c87a4f532d774 213B / 213B  3.1s
 => => sha256:cf5eb43522f68d7e2347e19ad70dadcf1594d25b792ede046 9.58MB / 9.58MB  3.7s
 => => sha256:355e8215390faee903502a9fddfc65cd823f1606f0533 202.81MB / 202.81MB  6.8s
 => => sha256:4fee0489a65b64056f81358639bfe85fd87776630830fd02ce8c1 855B / 855B  4.1s
 => => sha256:413646e6fa5d7bcd9722d3e400fc080a77deb505baed79afa5fed 363B / 363B  4.3s
 => => extracting sha256:5d6f1e8117dbb1c6a57603cb4f321a861a08105a81bcc6b01b0ec2  0.6s
 => => extracting sha256:48c2faf66abec3dce9f54d6722ff592fce6dd4fb58a0d0b7228293  0.3s
 => => extracting sha256:234b70d0479d7f16d7ee8d04e4ffdacc57d7d14313faf59d332f18  2.9s
 => => extracting sha256:d7eb6c022a4e6128219b32a8e07c8c22c89624ff440ebac1506121  0.2s
 => => extracting sha256:6c215442f70bd949a6f2e8092549943905e2d4f9c87a4f532d7740  0.0s
 => => extracting sha256:355e8215390faee903502a9fddfc65cd823f1606f053376ba2575a  3.0s
 => => extracting sha256:cf5eb43522f68d7e2347e19ad70dadcf1594d25b792ede0464c293  0.2s
 => => extracting sha256:4fee0489a65b64056f81358639bfe85fd87776630830fd02ce8c15  0.0s
 => => extracting sha256:413646e6fa5d7bcd9722d3e400fc080a77deb505baed79afa5feda  0.0s
 => [stage1 2/3] COPY . .                                                        1.2s
 => [stage1 3/3] RUN mvn clean package                                          24.0s
 => [stage-1 2/2] COPY --from=stage1 target/*.jar app.jar                        0.1s
 => exporting to image                                                           0.1s
 => => exporting layers                                                          0.1s
 => => writing image sha256:a1aa2587a6a74ca2d5e113d039a0c5198d12f54919056285ec3  0.0s
 => => naming to docker.io/library/srinfotech                                    0.0s

 1 warning found (use docker --debug to expand):
 - FromAsCasing: 'as' and 'FROM' keywords' casing do not match (line 1)
root@ip-172-31-32-42:~/spring-ms# docker images
REPOSITORY   TAG       IMAGE ID       CREATED          SIZE
srinfotech   latest    a1aa2587a6a7   17 seconds ago   410MB
test         latest    944581c42756   7 minutes ago    166MB
root@ip-172-31-32-42:~/spring-ms# docker run -d -p 8080:8080 srinfotech:latest
eb3d6d70bc9e049db0255b30f406b9559f7b03d1e82862d59205f363e1b8087e
root@ip-172-31-32-42:~/spring-ms# docker ps
CONTAINER ID   IMAGE               COMMAND               CREATED         STATUS         PORTS                                                             NAMES
eb3d6d70bc9e   srinfotech:latest   "java -jar app.jar"   6 seconds ago   Up 5 seconds   8443/tcp, 0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp, 8778/tcp   fervent_bassi
root@ip-172-31-32-42:~/spring-ms# Read from remote host ec2-34-222-12-103.us-west-2.compute.amazonaws.com: Connection reset by peer
Connection to ec2-34-222-12-103.us-west-2.compute.amazonaws.com closed.
client_loop: send disconnect: Connection reset by peer



Application up & running::
=============================

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/baaf82db-c008-400e-9f18-83732e2ece37" />




12/08/2025::
==================

Network Types in Docker:
============================

•	bridge: Default network for containers on the same host.

•	host: The container shares the host’s networking stack.

•	overlay: Used for multi-host networking (requires Docker Swarm).

•	none: No network connectivity is assigned to the container.

•	>bridge network is used for single node communication

•	>overlay network is used for multi node communication

•	---Kubernetes/swarm are used to communicate 2 containers in docker that’s like orchestration
macvlan network:: may be used to give containers across different hosts unique, routable IP addresses in a larger network
IPVLAN:Containers share the host’s MAC address but have individual IP addresses.

create my own network ::
=========================
> docker network create my_custom_network

![image](https://github.com/user-attachments/assets/43dbaed8-eb30-45ad-8df3-6cd9f1a3d063)

Created my own network - my_custom_network
![image](https://github.com/user-attachments/assets/a2136223-4a9a-48bc-b884-3e64a57268d5)

Run Containers on the Custom Network::
=================
>docker run -d --name container1 --network my_custom_network nginx

![image](https://github.com/user-attachments/assets/0f65c683-0ef5-4415-9413-41a46735a633)

>docker run -d --name container2 --network my_custom_network redis


![image](https://github.com/user-attachments/assets/0a4811c8-24cf-400a-93f9-e72196d504a5)

In this example:
•	container1 will run an Nginx container.

•	container2 will run a Redis container.

Both containers are connected to the my_custom_network.

Inspect the Network::
=================
To view detailed information about a network (like connected containers and settings), use the docker network inspect command:
>docker ps

>docker network ls

> docker network inspect my_custom_network

![image](https://github.com/user-attachments/assets/367d1d82-51e3-43fa-88c0-5a8414c73688)

Connect a Container to a Network:
==================
> docker network connect my_custom_network container_name
Disconnect a Container from a Network:

> docker network disconnect my_custom_network container_name
Remove a Docker Network::

>docker network rm my_custom_network
Note that the network must be unused by any containers before it can be removed.

A common use case for Docker networks is to isolate different applications or microservices, ensuring that containers in one application cannot easily communicate with containers in another. This helps you maintain security and control over how containers interact with each other.

USE CASE::
======================

--default network bridge can only ping throw ip address not container name

--our own network bridge(mybridge) able to ping both ip address and container name that’s advantage of network create.


---Kubernetes/swarm are used to communicate 2 containers in docker that’s like orchestration

--if you create your own bridge network the advantage is you can able to resolved the any issues using container name not only ipaddress but by default using you can able to resolved the issues by ipaddress.

>bridge network is used for single node communication

>overlay network is used for multi node communication




14/08/2025::
================


Docker Swarm::
===================

Docker and Docker Swarm are both tools used to manage containers, but they serve different purposes and have different features. 


![image](https://github.com/user-attachments/assets/a7dc1fa3-6551-44cf-b954-7e411141b87e)


Docker::
===========

Docker is a platform that allows you to create, deploy, and run applications inside containers. Containers are lightweight, portable, and ensure that the application works the same regardless of where it's deployed, making Docker a powerful tool for developing, testing, and deploying applications.


Key Features of Docker:
=======================
•	Containerization: Docker encapsulates applications and their dependencies into containers, ensuring consistency across environments (e.g., development, staging, production).
•	Images and Containers: Docker uses images to define the environment for an application. Containers are instances of those images.

•	Docker Hub: Docker Hub is a cloud-based registry where you can find pre-built images or upload your own.

•	Portability: Docker containers can run on any system with Docker installed, from your laptop to a cloud server.

•	Isolation: Containers are isolated from the host system, so they don’t interfere with other processes or systems.

Common Docker Commands:
===================
•	Build an Image: docker build -t my-image .

•	Run a Container: docker run -d --name my-container my-image

•	List Containers: docker ps

•	Stop a Container: docker stop my-container

•	Remove a Container: docker rm my-container

•	List Images: docker images

Docker Swarm::
==================

Docker Swarm is a clustering and orchestration tool for Docker containers. It allows you to deploy and manage multiple containers across multiple Docker hosts (machines), forming a swarm. This means that you can treat a collection of Docker hosts as a single virtual host and manage them as one.
Docker Swarm makes it easier to scale, deploy, and maintain containerized applications in production environments. It provides high availability, fault tolerance, and easy scaling of applications across multiple machines.


Docker SWARM Overview::
=====================
- this is Docker Inc's Container Orchestration Platform

- it only supports managing Docker containerized application workloads

- it is pretty easy to install and learn

- can be installed on a laptop with pretty basic configuation as well as it is very light weight

- good for POC or learning purpose

- not production grade


Key Concepts in Docker Swarm:
===============================
•	Node: A machine (physical or virtual) running Docker that is part of the Swarm cluster. There are two types of nodes:

o	Manager Node: Manages the cluster and orchestrates services.

o	Worker Node: Runs the actual containers based on instructions from manager nodes.

•	Service: A service is a description of the tasks (containers) you want to run. When you define a service, Docker Swarm ensures that the desired number of replicas of that service are running at all times.

•	Task: A task is a running container in the context of a service. Each task runs a container that is part of a service.

Docker vs Docker Swarm::
============================
•	Docker is used to build and run containers on a single machine, whereas Docker Swarm extends Docker to manage containers across a cluster of machines.

•	Docker Swarm provides orchestration features such as load balancing, scaling, and high availability, which are not available in basic Docker.

•	Docker Swarm is built into Docker, making it easier to set up and use compared to other container orchestration systems like Kubernetes.


I have created 3 ubuntu machines::
================================

1.Manager Node

2.Worker Node1

3. Worker Node2

![image](https://github.com/user-attachments/assets/1c3827ee-7df0-4063-b36e-51345ef08afd)


![image](https://github.com/user-attachments/assets/8d70d3eb-1df0-46a0-bbae-fa9474112b8f)

>docker swarm init runs on master

>docker swarm join runs on node

> docker swarm join --token SWMTKN-1-33cj3h7mhtq98iy5aifyy9s1cdqnzh4jgl3rdgdez0vbfx8fnc-bu27q63wt2i7qfgkh0r07o85o 172.31.24.64:2377

![image](https://github.com/user-attachments/assets/c3434137-924b-4ea7-9a3f-24f188d3d19a)

![image](https://github.com/user-attachments/assets/015201ed-aea1-461f-90bc-08c1d78fae7b)

![image](https://github.com/user-attachments/assets/06424e51-1f9b-46e3-89af-80062ccb2f26)

>once initialize the swarm it will automatically created overlay network

![image](https://github.com/user-attachments/assets/d19378c2-01c9-4698-ad1d-c8af6aff1a55)


create our own overlay network ::
==========================

>docker network create –d overlay sr-overlay

![image](https://github.com/user-attachments/assets/84319ff3-e569-40c5-bdf6-69634bf65484)

> docker network create -d overlay sr-overlay

>docker node ls

![image](https://github.com/user-attachments/assets/3fb48730-74d2-4e65-ac80-dce537b2438a)

![image](https://github.com/user-attachments/assets/c545c853-157b-484f-8b7b-e3c81236d142)

create service under the overlay network::
========================

> docker service create -d --name my-own-SRservice --replicas 3 -p 80:80 nginx:latest

>docker service ls

>docker node ls

--docker always maintain --replicas 3 means 3 containers by default if for example 1 container die docker automatically create container automatically this is main use of services with docker

docker swarm:: multi containarization for your applications

Docker Swarm is a built-in container orchestration tool that allows you to manage a cluster of Docker hosts as a single entity




15/08/2025::
================


In any cloud we have docker /container services lke

1.AWS --->ECS ----elastic conatienr services
2.Azure---->ACS  ----Azure contaienr services
3.Kuberneties---->EKS  ---Elsatic kuberneties services


Docker Flow

<img width="678" height="690" alt="image" src="https://github.com/user-attachments/assets/04860bd6-00d0-4272-8a2e-640a7a0acc58" />


Docker compose::
=====================

Docker Compose is a tool for defining and running multi-container Docker applications. With a docker-compose.yml file, you can configure your application’s services, networks, and volumes, and then start them all with a single command.
Below, I'll explain how to create a docker-compose.yml file and walk you through an example that demonstrates its use.
version: "3"  # Specify the version of Docker Compose

services:
  <service_name>:  # Define your services (containers)
    image: <image_name>  # The Docker image to use (can be local or from Docker Hub)
    build: <path_to_dockerfile>  # Path to the Dockerfile if you need to build the image
    container_name: <container_name>  # Optionally define a container name
    ports:  # Map container ports to host ports
      - "<host_port>:<container_port>"
    volumes:  # Mount volumes (directories or files)
      - <host_directory>:<container_directory>
    environment:  # Set environment variables
      - <key>=<value>
    depends_on:  # Define dependencies between services
      - <another_service>
    networks:  # Specify networks to connect to
      - <network_name>

networks:
  <network_name>:  # Define custom networks
    driver: bridge  # Optional: can be "bridge", "host", or "none"

volumes:
  <volume_name>:  # Define named volumes for persistent data

Explanation of the docker-compose.yml Example:
1.	Version: Specifies the version of the Docker Compose file format to use. In this case, 3.8.
2.	Services:
o	web: This is the service for your Node.js application.
	image: Specifies the base image to use (node:18-alpine).
	working_dir: Sets the working directory inside the container.
	volumes: Mounts the current directory (.) to /app inside the container so your application code is accessible to the container.
	ports: Maps port 3000 on the host to port 3000 inside the container.
	environment: Sets environment variables like NODE_ENV and the database connection information (DB_HOST=db).
	depends_on: Ensures the db service is started before the web service.
o	db: This is the service for your MySQL database.
	image: Specifies the MySQL version to use (mysql:8.0).
	environment: Sets environment variables such as the MySQL root password, database name, and user credentials.
	volumes: Mounts a named volume (db-data) to persist MySQL data between container restarts.
	ports: Exposes port 3306 for MySQL to allow communication between containers or with the host.
3.	Volumes: Defines a named volume (db-data) to persist the database data outside of the container.


docker-compose.yml::
=====================

version: '3.8'

services:
  web:
    image: node:18-alpine  # Use the official Node.js image
    container_name: node-app
    working_dir: /app
    volumes:
      - .:/app  # Mount the current directory to /app in the container
    ports:
      - "3000:3000"  # Expose port 3000 on the host and map it to port 3000 in the container
    environment:
      - NODE_ENV=development
      - DB_HOST=db  # Reference the db service as the hostname
    depends_on:
      - db  # Ensure the db service starts first

  db:
    image: mysql:8.0  # Use the official MySQL image
    container_name: mysql-db
    environment:
      MYSQL_ROOT_PASSWORD: rootpassword
      MYSQL_DATABASE: mydb
      MYSQL_USER: user
      MYSQL_PASSWORD: password
    volumes:
      - db-data:/var/lib/mysql  # Mount a volume for persistent data
    ports:
      - "3306:3306"  # Expose port 3306 for MySQL

volumes:
  db-data:  # Define a volume for MySQL data persistence

> docker compose up -d

>docker exec -it bbeebd8d5ca2 /bin/bash

> mysql -u root -p

> SHOW DATABASES;

CREATE DATABASE SRINFOTECH;
USE SRINFOTECH;

CREATE TABLE SRINFOTECHTABLE ( id INT NOT NULL, name VARCHAR(250) NOT NULL, cource VARCHAR(100) NOT NULL, city VARCHAR(200) NOT NULL, PRIMARY KEY(id) );

INSERT INTO SRINFOTECHTABLE VALUES ( 1, "veeresh", "AWSDEVOPS","Hyderabad" );

INSERT INTO SRINFOTECHTABLE VALUES ( 2, "laxmikanth", "AWSDEVOPSTraining","Bangalour" );

INSERT INTO SRINFOTECHTABLE VALUES ( 1, "Rawali", "AWSDEVOPSFullStack","Chennai" );

SELECT * FROM SRINFOTECHTABLE;


Use Cases for Docker Compose:
•	Multi-container applications: Perfect for web applications that rely on more than one service (e.g., database, caching, backend).
•	Development environments: Provides a consistent environment that can be easily replicated across different machines.
•	Testing and CI/CD: Can be used to quickly spin up environments for testing or continuous integration/deployment pipelines



Docker Compose Quickstart::
============================

please try to practice below example for docker compose 

https://docs.docker.com/compose/gettingstarted/


![image](https://github.com/user-attachments/assets/8683a557-4a34-42a1-93ee-ca1cbf78fdfa)


Example2 Dockerfile::
===================

https://github.com/srinfotech7358/spring-ms.git

Please clone this project in ubuntu machines

root@ip-172-31-20-86:~# git clone https://github.com/srinfotech7358/spring-ms.git

![image](https://github.com/user-attachments/assets/188db6f2-c5b5-419d-8824-0b9b9c6728ee)

root@ip-172-31-20-86:~# cd spring-ms/
root@ip-172-31-20-86:~/spring-ms# ls
Dockerfile  azure-pipeline.yml  azure-pipelines.yml  deploy.yaml  pom.xml  src
root@ip-172-31-20-86:~/spring-ms#

Build Image::
============
root@ip-172-31-20-86:~/spring-ms# docker image build -t springmyapp .
[+] Building 0.4s (12/12) FINISHED                                                                                      docker:default
 => [internal] load build definition from Dockerfile                                                                              0.0s
 => => transferring dockerfile: 256B                                                                                              0.0s
 => WARN: FromAsCasing: 'as' and 'FROM' keywords' casing do not match (line 1)                                                    0.0s
 => [internal] load metadata for registry.access.redhat.com/ubi8/openjdk-11:latest                                                0.3s
 => [internal] load metadata for docker.io/library/maven:3.6.3-jdk-11                                                             0.1s
 => [auth] library/maven:pull token for registry-1.docker.io                                                                      0.0s
 => [internal] load .dockerignore                                                                                                 0.0s
 => => transferring context: 2B                                                                                                   0.0s
 => [internal] load build context                                                                                                 0.0s
 => => transferring context: 2.76kB                                                                                               0.0s
 => [stage-1 1/2] FROM registry.access.redhat.com/ubi8/openjdk-11:latest@sha256:28b35eea470174a39befd8eb9250a3276b79a4f6e7dac787  0.0s
 => [stage1 1/3] FROM docker.io/library/maven:3.6.3-jdk-11@sha256:1d29ccf46ef2a5e64f7de3d79a63f9bcffb4dc56be0ae3daed5ca5542b38aa  0.0s
 => CACHED [stage1 2/3] COPY . .                                                                                                  0.0s
 => CACHED [stage1 3/3] RUN mvn clean package                                                                                     0.0s
 => CACHED [stage-1 2/2] COPY --from=stage1 target/*.jar app.jar                                                                  0.0s
 => exporting to image                                                                                                            0.0s
 => => exporting layers                                                                                                           0.0s
 => => writing image sha256:bdbbb4bbe700af425032e6a27d6909e2906677fbffce9b833d596e3f37082479                                      0.0s
 => => naming to docker.io/library/springmyapp                                                                                    0.0s

 1 warning found (use docker --debug to expand):
 - FromAsCasing: 'as' and 'FROM' keywords' casing do not match (line 1)
root@ip-172-31-20-86:~/spring-ms#

![image](https://github.com/user-attachments/assets/44c6ba1e-7322-436d-af30-4606cb484283)

create container::
===============

root@ip-172-31-20-86:~/spring-ms# docker images
REPOSITORY                  TAG       IMAGE ID       CREATED        SIZE
spring                      latest    bdbbb4bbe700   9 hours ago    410MB
springmyapp                 latest    bdbbb4bbe700   9 hours ago    410MB
srinu7358/spring-03042025   latest    bdbbb4bbe700   9 hours ago    410MB
allinstructions             latest    c2993e54968d   9 hours ago    1.17GB
<none>                      <none>    805cbec82269   9 hours ago    1.17GB
testmyownimage              latest    621f509fde33   10 hours ago   1.1GB
ifocus                      latest    381bfb89fb02   10 hours ago   1.1GB
srinu7358/ifocus-myapp      latest    381bfb89fb02   10 hours ago   1.1GB
root@ip-172-31-20-86:~/spring-ms# docker run -d -p 8081:8081 springmyapp:latest
17ac78f05de4abdca3d46972e63f29c897a011d732ca3e76e7c1ef2158af10b1
root@ip-172-31-20-86:~/spring-ms#

![image](https://github.com/user-attachments/assets/d0132046-021c-46b7-9259-75382dc155fb)

![image](https://github.com/user-attachments/assets/b9064110-355c-4619-adf5-fb9fac875b6f)

Image formate::
============

<registoryname>/repositoryname:<imagetag>
Docker.io            username/reponame  ::latest

[docker.io/srinu7358/ifocus-myapp] :latest  ---->image formate

docker.io -----registry name  ----docekr hub

srinu7358 ----repository username

ifocus-myapp ---image name

>docker container run –d –p 8080:8080 springmyapp:1.0
-d --> detached mode
-p  -->mappimg a port
8080: host port
8080: container port
springmyapp:: image name
1.0:: tag name

Expected 
http://54.162.108.91:8080/


![image](https://github.com/user-attachments/assets/3f90a7ca-b7a7-4d5d-ac7a-0d8a24346518)


Usefull commands::
====================

>docker compose up

sudo apt-get install docker-compose-plugin
>docker image tag srinfotechmyapp srinfotech7358/myapp:latest

>docker.io/library/hello-world:latest

docker.io--->registry name
library  -->username-->docker hub username--

Image formate is

registry name/repositoryusername/imagename:tagname

docker -io/srinfotech7358/myapp:latest










18/08/2025::
===============


Docker SWARM Overview::
=============================

1.this is Docker Inc's Container Orchestration Platform
2.it only supports managing Docker containerized application workloads
3.it is pretty easy to install and learn
4.can be installed on a laptop with pretty basic configuation as well as it is very light weight
5.good for POC or learning purpose
6.not production grade

Kubernetes Overview::
========================


Kubernetes (often abbreviated as K8s) is an open-source container orchestration platform designed to automate the deployment, scaling, and management of containerized applications. Originally developed by Google.


<img width="1678" height="747" alt="image" src="https://github.com/user-attachments/assets/40054a14-9fef-40db-a43d-e8e7cc419ece" />



free and opensource container orchestration platform developed by Google along with many open source contributors

it is production grade

free for personal and commercial use

as it is opensource, we won't get support from Google

only supports command line interface (CLI)

doesn't support web console

Kubernetes does provide some basic Dashboard but it is considered a security vulnerability, hence no one uses the Kubernetes Dashboard

Rancher is opensource webconsole for Google Kubernetes

supports inbuilt monitoring features

it can check the health of our application, when it finds your application is not responding, it can repair it or replace it with another good healthy instance of your application
it supports inbuilt load-balancing
Master ---Management --(Orchestration) Node machine (minion) --workers (containers)

POD ---the smallest unit, mainatained one or more containers

YAML --key-value paires

1.Container Orchestration: Kubernetes helps you manage multiple containers, ensuring that they run efficiently and reliably across many servers.

2.Scaling: Kubernetes can automatically scale your applications up or down based on demand, making it easier to handle varying workloads.

3.Load Balancing: It can distribute network traffic to different containers, ensuring that applications remain responsive even under heavy loads.

4.Self-Healing: If a container crashes or stops working, Kubernetes can automatically restart or replace it, ensuring the application stays available.

5.Automated Deployment and Rollback: Kubernetes can automate the process of deploying new versions of an application, and if something goes wrong, it can roll back to a previous version.

6.Storage Management: Kubernetes can automatically mount the storage resources you need for your applications, making it easier to manage persistent data.

In short, Kubernetes is designed to make it easier to manage applications at scale in a way that is highly automated, reliable, and efficient. It’s widely used in DevOps platform

Cluster:: collection of nodes with a single responsibility

All the nodes in that cluster do same process, same type of work can will do collection of nodes in cluster

Cluster::
a cluster might refer to a set of virtual machines or containers working together for a specific application or service.


Kubernetes Cluster Components:
===================================

1.Master Node (Control Plane): 
=====================================

The Master Node is the brain of the Kubernetes cluster. It manages the cluster and makes decisions about scheduling, scaling, and maintaining the health of the application. The control plane consists of several key components:

1.API Server::
The API server exposes the Kubernetes API, which is used to interact with the cluster.

2.Scheduler::
The scheduler assigns work (pods) to available worker nodes.

3.Controller Manager: :
Ensures that the desired state of the system is maintained, such as ensuring that the correct number of pods are running.

4.etcd:
A distributed key-value store used to store all cluster data, including the state of the system (like deployed pods, config maps, and secrets).

Worker Nodes:
===========================

o The Worker Nodes are responsible for running the actual application workloads. These nodes host the pods, which are the smallest deployable units in Kubernetes. A worker node typically runs:

1.Kubelet: An agent that ensures the containers in the pods are running and healthy.

2.Kube Proxy: A network proxy that maintains network rules for pod communication.

3.Container Runtime: The software responsible for running containers (e.g., Docker, containerd).

4.Pods::

A pod is the smallest unit of execution in Kubernetes and can contain one or more containers that share resources such as networking and storage. Pods are always deployed in a Kubernetes cluster and are managed by the control plane.



19/08/2025::
===========


Services:
===============
A service in Kubernetes is a way to expose an application running in a pod to other pods or external users. It ensures that network communication between pods is reliable, even as pods are dynamically created or destroyed.

1.Pod is a smallest component in kubernetes 

2.In docker smallest component --  > container

3.in kuberneties we will create pods and inside the pods containers are running.

4.one pod speak with other pod using id address(kube-proxy)

5.every pod has ip address


<img width="1426" height="702" alt="image" src="https://github.com/user-attachments/assets/ff401123-20f7-43f8-b171-56e53ce1253d" />



Above picture directly using pods without using services and if ipaddress no longer available our application is not worked. pods communication throw ip address right so it has a problem to resolved the this problem services is come to the picture.



With Services::
==================

<img width="1526" height="748" alt="image" src="https://github.com/user-attachments/assets/7221fec6-3fc2-456c-8a30-6fbb708acefd" />


Services –logical entity and maintain ip address


Basically kubernetes is used for maintain containers


Kubeadm::
============
bootstraps a cluster. It’s designed to be a simple way for new users to build clusters (more detail on this is in a later chapter).

Kubectl::
===========
is a tool for interacting with your existing cluster.

Kubelet: 
============
An agent that ensures the containers in the pods are running and check healthy.


How to Install Kubernetes Cluster on Ubuntu 22.04::
=====================================================

Please follow the below link steps to configured the Kubernetes Master and Workers 

https://www.linuxtechi.com/install-kubernetes-on-ubuntu-22-04/


Docker Install link::
=======================

Make sure we should install the Docker in all the machines 

https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-22-04

root@k8smaster:~# docker --version

Docker version 28.3.2, build 578ccf6




22/08/2025::
==============

How to Install Kubernetes Cluster on Ubuntu 22.04::
=====================================================

Please follow the below link steps to configured the Kubernetes Master and Workers 

https://www.linuxtechi.com/install-kubernetes-on-ubuntu-22-04/


>kubectl get nodes


root@k8smaster:~# kubectl get nodes
NAME         STATUS   ROLES           AGE   VERSION
k8smaster    Ready    control-plane   12h   v1.28.15
k8sworker1   Ready    <none>          12h   v1.28.15
k8sworker2   Ready    <none>          12h   v1.28.15


Verify the status of pods in kube-system namespace,

>kubectl get pods -n kube-system

root@k8smaster:~# kubectl get pods -n kube-system
NAME                                       READY   STATUS    RESTARTS   AGE
calico-kube-controllers-658d97c59c-92qgs   1/1     Running   0          12h

calico-node-2j6mh                          1/1     Running   0          12h

calico-node-6w8zt                          1/1     Running   0          12h

calico-node-bccc9                          1/1     Running   0          12h

coredns-5dd5756b68-2vpmt                   1/1     Running   0          12h

coredns-5dd5756b68-s68cn                   1/1     Running   0          12h

etcd-k8smaster                             1/1     Running   5          12h

kube-apiserver-k8smaster                   1/1     Running   5          12h

kube-controller-manager-k8smaster          1/1     Running   5          12h

kube-proxy-4dfkl                           1/1     Running   0          12h

kube-proxy-wglb9                           1/1     Running   0          12h

kube-proxy-wl677                           1/1     Running   0          12h

kube-scheduler-k8smaste


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2ef60ee9-a0b1-47cb-a7a7-65714d07459a" />


Clone the Project (docker-Java-kubernetes-project) :::
====================================================

https://github.com/ifocus7358/docker-Java-kubernetes-project.git

>git clone https://github.com/ifocus7358/docker-Java-kubernetes-project.git

root@ip-172-31-36-154:~# git clone https://github.com/ifocus7358/docker-Java-kubernetes-project.git

Cloning into 'docker-Java-kubernetes-project'...

remote: Enumerating objects: 156, done.

remote: Counting objects: 100% (42/42), done.

remote: Compressing objects: 100% (32/32), done.

remote: Total 156 (delta 27), reused 10 (delta 10), pack-reused 114 (from 1)

Receiving objects: 100% (156/156), 27.40 KiB | 9.13 MiB/s, done.

Resolving deltas: 100% (35/35), done.



Build the image::
============

root@ip-172-31-36-154:~# ls

docker-Java-kubernetes-project 

root@ip-172-31-36-154:~# cd docker-Java-kubernetes-project/

root@ip-172-31-36-154:~/docker-Java-kubernetes-project# ls

README.md  kubernetes  productcatalogue  shopfront  stockmanager
root@ip-172-31-36-154:~/docker-Java-kubernetes-project# cd kubernetes/

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# ls

productcatalogue-service.yaml  shopfront-service.yaml  stockmanager-service.yaml
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# cd ..

root@ip-172-31-36-154:~/docker-Java-kubernetes-project# ls

README.md  kubernetes  productcatalogue  shopfront  stockmanager

root@ip-172-31-36-154:~/docker-Java-kubernetes-project# cd shopfront/

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# ls

Dockerfile  pom.xml  src
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront#

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker image build -t shopfront .


installed maven::
===============

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# mvn -v

Apache Maven 3.8.7

So need to build the source code first it will generate target folder

>mvn clean install

[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  5.598 s
[INFO] Finished at: 2025-04-08T05:52:09Z
[INFO] ------------------------------------------------------------------------



root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# ls

Dockerfile  pom.xml  src  target
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# cd  target/

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront/target# ls

classes  generated-sources  maven-archiver  maven-status  shopfront-0.0.1-SNAPSHOT.jar  shopfront-0.0.1-SNAPSHOT.jar.original
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront/target# ls

classes  generated-sources  maven-archiver  maven-status  shopfront-0.0.1-SNAPSHOT.jar  shopfront-0.0.1-SNAPSHOT.jar.original
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront/target# cd ..
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker build -t shopfront .

[+] Building 8.8s (7/7) FINISHED                                                                                        docker:default
 => [internal] load build definition from Dockerfile                                                                              0.0s
 => => transferring dockerfile: 198B                                                                                              0.0s
 => [internal] load metadata for docker.io/library/openjdk:8-jre                                                                  0.1s
 => [internal] load .dockerignore                                                                                                 0.0s
 => => transferring context: 2B                                                                                                   0.0s
 => [internal] load build context                                                                                                 0.5s
 => => transferring context: 46.10MB                                                                                              0.5s
 => [1/2] FROM docker.io/library/openjdk:8-jre@sha256:667a15e7bc533a90fb39ddb7e5bed63162ac3c13a97e6c698bf4f139f51b7d33            6.1s
 => => resolve docker.io/library/openjdk:8-jre@sha256:667a15e7bc533a90fb39ddb7e5bed63162ac3c13a97e6c698bf4f139f51b7d33            0.0s
 => => sha256:2068746827ec1b043b571e4788693eab7e9b2a95301176512791f8c317a2816a 10.88MB / 10.88MB                                  0.3s
 => => sha256:a6a74c7b774e00fd2ec5664e257d344f1b7e69e2a618b1c0678f69719863c5ad 1.58kB / 1.58kB                                    0.0s
 => => sha256:0c14a0e20aa3a19448f6227265c6642571112e9cd9a69b5e7a323df46d1aa835 7.43kB / 7.43kB                                    0.0s
 => => sha256:d9d4b9b6e964657da49910b495173d6c4f0d9bc47b3b44273cf82fd32723d165 5.16MB / 5.16MB                                    0.2s
 => => sha256:667a15e7bc533a90fb39ddb7e5bed63162ac3c13a97e6c698bf4f139f51b7d33 1.04kB / 1.04kB                                    0.0s
 => => sha256:001c52e26ad57e3b25b439ee0052f6692e5c0f2d5d982a00a8819ace5e521452 55.00MB / 55.00MB                                  1.3s
 => => sha256:8510da692cda60e4746c14dd90905695eade5888e2ad640706a2be9dc42a0224 5.66MB / 5.66MB                                    0.5s
 => => sha256:c34215579d03c1311f4e8cd3525bc03dbbb53d79d8b58e63cce8cdd355356347 211B / 211B                                        0.4s
 => => sha256:73d77b4774a96dfa09076212d5170e977d153ceab60c1ec4312a8f436b91371c 41.42MB / 41.42MB                                  1.2s
 => => extracting sha256:001c52e26ad57e3b25b439ee0052f6692e5c0f2d5d982a00a8819ace5e521452                                         2.7s
 => => extracting sha256:d9d4b9b6e964657da49910b495173d6c4f0d9bc47b3b44273cf82fd32723d165                                         0.2s
 => => extracting sha256:2068746827ec1b043b571e4788693eab7e9b2a95301176512791f8c317a2816a                                         0.3s
 => => extracting sha256:8510da692cda60e4746c14dd90905695eade5888e2ad640706a2be9dc42a0224                                         0.2s
 => => extracting sha256:c34215579d03c1311f4e8cd3525bc03dbbb53d79d8b58e63cce8cdd355356347                                         0.0s
 => => extracting sha256:73d77b4774a96dfa09076212d5170e977d153ceab60c1ec4312a8f436b91371c                                         1.0s
 => [2/2] ADD target/shopfront-0.0.1-SNAPSHOT.jar app.jar                                                                         2.1s
 => exporting to image                                                                                                            0.3s
 => => exporting layers                                                                                                           0.3s
 => => writing image sha256:3ccf19de392942c193c580caabe914257071f0c0b1cb8c8b371d369d5e0630fd                                      0.0s
 => => naming to docker.io/library/shopfront                                                                                      0.0s
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker images

REPOSITORY                    TAG       IMAGE ID       CREATED          SIZE
shopfront                     latest    3ccf19de3929   14 seconds ago   320MB
gcr.io/k8s-minikube/kicbase   v0.0.46   e72c4cbe9b29   2 months ago     1.31GB
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker run -d -p 80:80 shopfront

836d8e23016935ac3cd74067bbdb4998dba147ce425d17edafced967b1884233
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker ps

CONTAINER ID   IMAGE                                 COMMAND                  CREATED          STATUS          PORTS                                                                                                                                  NAMES
836d8e230169   shopfront                             "java -Djava.securit…"   6 seconds ago    Up 5 seconds    0.0.0.0:80->80/tcp, [::]:80->80/tcp, 8010/tcp                                                                                          epic_leavitt
ad8f297fbeca   gcr.io/k8s-minikube/kicbase:v0.0.46   "/usr/local/bin/entr…"   27 minutes ago   Up 27 minutes   127.0.0.1:32768->22/tcp, 127.0.0.1:32769->2376/tcp, 127.0.0.1:32770->5000/tcp, 127.0.0.1:32771->8443/tcp, 127.0.0.1:32772->32443/tcp   minikube
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront#

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker images

REPOSITORY                    TAG       IMAGE ID       CREATED         SIZE
shopfront                     latest    3ccf19de3929   3 minutes ago   320MB
gcr.io/k8s-minikube/kicbase   v0.0.46   e72c4cbe9b29   2 months ago    1.31GB
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker ps

CONTAINER ID   IMAGE                                 COMMAND                  CREATED              STATUS              PORTS                                                                                                                                  NAMES
836d8e230169   shopfront                             "java -Djava.securit…"   About a minute ago   Up About a minute   0.0.0.0:80->80/tcp, [::]:80->80/tcp, 8010/tcp                                                                                          epic_leavitt
ad8f297fbeca   gcr.io/k8s-minikube/kicbase:v0.0.46   "/usr/local/bin/entr…"   28 minutes ago       Up 28 minutes       127.0.0.1:32768->22/tcp, 127.0.0.1:32769->2376/tcp, 127.0.0.1:32770->5000/tcp, 127.0.0.1:32771->8443/tcp, 127.0.0.1:32772->32443/tcp   minikube
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker rm 836d8e230169
Error response from daemon: cannot remove container "/epic_leavitt": container is running: stop the container before removing or force remove
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker rm -f 836d8e230169

836d8e230169
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker ps

CONTAINER ID   IMAGE                                 COMMAND                  CREATED          STATUS          PORTS                                                                                                                                  NAMES
ad8f297fbeca   gcr.io/k8s-minikube/kicbase:v0.0.46   "/usr/local/bin/entr…"   29 minutes ago   Up 29 minutes   127.0.0.1:32768->22/tcp, 127.0.0.1:32769->2376/tcp, 127.0.0.1:32770->5000/tcp, 127.0.0.1:32771->8443/tcp, 127.0.0.1:32772->32443/tcp   minikube
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker images

REPOSITORY                    TAG       IMAGE ID       CREATED         SIZE
shopfront                     latest    3ccf19de3929   4 minutes ago   320MB
gcr.io/k8s-minikube/kicbase   v0.0.46   e72c4cbe9b29   2 months ago    1.31GB
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker image tag shopfront srinu7358/shopfront-myapp

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker images

REPOSITORY                    TAG       IMAGE ID       CREATED         SIZE
shopfront                     latest    3ccf19de3929   6 minutes ago   320MB
srinu7358/shopfront-myapp     latest    3ccf19de3929   6 minutes ago   320MB
gcr.io/k8s-minikube/kicbase   v0.0.46   e72c4cbe9b29   2 months ago    1.31GB
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker login -u srinu7358

i Info → A Personal Access Token (PAT) can be used instead.
         To create a PAT, visit https://app.docker.com/settings


Password:

WARNING! Your credentials are stored unencrypted in '/root/.docker/config.json'.
Configure a credential helper to remove this warning. See
https://docs.docker.com/go/credential-store/

Login Succeeded
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker push srinnfotech7358/shopfrontnewapp

Using default tag: latest
The push refers to repository [docker.io/srinu7358/shopfront-myapp]
c54136e18c64: Pushed
1aaddf64804f: Mounted from library/openjdk
990c5138f5d1: Mounted from library/openjdk
5c384ea5f752: Mounted from library/openjdk
293d5db30c9f: Mounted from library/openjdk
03127cdb479b: Mounted from library/openjdk
9c742cd6c7a5: Mounted from library/openjdk
latest: digest: sha256:e027803e479a98c9d1fdcc6d983a6b778b62c2a91dee9bcccfffcb921848b42e size: 1794
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker pull srinu7358/shopfront-myapp:latest

latest: Pulling from srinu7358/shopfront-myapp
Digest: sha256:e027803e479a98c9d1fdcc6d983a6b778b62c2a91dee9bcccfffcb921848b42e
Status: Image is up to date for srinu7358/shopfront-myapp:latest
docker.io/srinu7358/shopfront-myapp:latest
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# docker images

REPOSITORY                    TAG       IMAGE ID       CREATED          SIZE
shopfront                     latest    3ccf19de3929   12 minutes ago   320MB
srinnfotech7358/shopfrontnewapp     latest    3ccf19de3929   12 minutes ago   320MB
gcr.io/k8s-minikube/kicbase   v0.0.46   e72c4cbe9b29   2 months ago     1.31GB
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/shopfront# cd ..

root@ip-172-31-36-154:~/docker-Java-kubernetes-project# ls

README.md  kubernetes  productcatalogue  shopfront  stockmanager
root@ip-172-31-36-154:~/docker-Java-kubernetes-project# Read from remote host ec2-54-174-108-84.compute-1.amazonaws.com: Connection reset by peer
Connection to ec2-54-174-108-84.compute-1.amazonaws.com closed.
client_loop: send disconnect: Connection reset by peer


pushed image to docker hub::
----------------------

![image](https://github.com/user-attachments/assets/4223faf9-b478-4d75-8f4e-7c7017d52e7b)


Please build the stockmanager project and it will generated target/ after build success

[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  5.152 s
[INFO] Finished at: 2025-04-10T04:54:00Z
[INFO] ------------------------------------------------------------------------
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/stockmanager# ls
Dockerfile  build  pom.xml  src  target
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/stockmanager# cd target/
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/stockmanager/target# ls
classes  generated-sources  maven-archiver  maven-status  stockmanager-0.0.1-SNAPSHOT.jar  stockmanager-0.0.1-SNAPSHOT.jar.original


Build the Image::
=================

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/stockmanager# docker image build -t stockmanager .


[+] Building 1.1s (8/8) FINISHED                                                                                        docker:default
 => [internal] load build definition from Dockerfile                                                                              0.0s
 => => transferring dockerfile: 201B                                                                                              0.0s
 => [internal] load metadata for docker.io/library/openjdk:8-jre                                                                  0.1s
 => [auth] library/openjdk:pull token for registry-1.docker.io                                                                    0.0s
 => [internal] load .dockerignore                                                                                                 0.0s
 => => transferring context: 2B                                                                                                   0.0s
 => [internal] load build context                                                                                                 0.4s
 => => transferring context: 43.32MB                                                                                              0.4s
 => CACHED [1/2] FROM docker.io/library/openjdk:8-jre@sha256:667a15e7bc533a90fb39ddb7e5bed63162ac3c13a97e6c698bf4f139f51b7d33     0.0s
 => [2/2] ADD target/stockmanager-0.0.1-SNAPSHOT.jar app.jar                                                                      0.2s
 => exporting to image                                                                                                            0.3s
 => => exporting layers                                                                                                           0.3s
 => => writing image sha256:3de0cce0b9d4173e0ab799d4a59b986a841c5e08244b25d0887f1d0a9d496662                                      0.0s
 => => naming to docker.io/library/stockmanager 

Verify the docker images::
=================
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/stockmanager# docker images

REPOSITORY                    TAG       IMAGE ID       CREATED          SIZE
stockmanager                  latest    3de0cce0b9d4   10 seconds ago   317MB
shopfront                     latest    3ccf19de3929   47 hours ago     320MB
srinu7358/shopfront-myapp     latest    3ccf19de3929   47 hours ago     320MB
gcr.io/k8s-minikube/kicbase   v0.0.46   e72c4cbe9b29   2 months ago     1.31GB


 Tag the Image:;
==============

 root@ip-172-31-36-154:~/docker-Java-kubernetes-project/stockmanager# docker image tag stockmanager srinu7358/stockmanager-myapp
 
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/stockmanager# docker images

REPOSITORY                     TAG       IMAGE ID       CREATED              SIZE
stockmanager                   latest    3de0cce0b9d4   About a minute ago   317MB
srinu7358/stockmanager-myapp   latest    3de0cce0b9d4   About a minute ago   317MB
shopfront                      latest    3ccf19de3929   47 hours ago         320MB
srinu7358/shopfront-myapp      latest    3ccf19de3929   47 hours ago         320MB
gcr.io/k8s-minikube/kicbase    v0.0.46   e72c4cbe9b29   2 months ago         1.31GB


Login to DockerHub::
-------------------

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/stockmanager# docker login -u srinu7358


i Info → A Personal Access Token (PAT) can be used instead.
         To create a PAT, visit https://app.docker.com/settings


Password:
Login Succeeded

Pushed image to docker hub::
============================

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/stockmanager# docker push srinu7358/stockmanager-myapp

Using default tag: latest
The push refers to repository [docker.io/srinu7358/stockmanager-myapp]
03b73450f8a0: Pushed
1aaddf64804f: Mounted from srinu7358/shopfront-myapp
990c5138f5d1: Mounted from srinu7358/shopfront-myapp
5c384ea5f752: Mounted from srinu7358/shopfront-myapp
293d5db30c9f: Mounted from srinu7358/shopfront-myapp
03127cdb479b: Mounted from srinu7358/shopfront-myapp
9c742cd6c7a5: Mounted from srinu7358/shopfront-myapp
latest: digest: sha256:1104a4cb9737fc33cae8cfb60b7b0093942da0c201322e4e001ddb9fb417f23b size: 1794

build the productcatalogue micro service::
================================

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/productcatalogue# ls

Dockerfile  pom.xml  product-catalogue.yml  src

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/productcatalogue# cd src/

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/productcatalogue/src# ls
main
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/productcatalogue/src# cd ..

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/productcatalogue# mvn clean install

[INFO] Scanning for projects...

[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  9.130 s
[INFO] Finished at: 2025-04-10T04:58:34Z
[INFO] ------------------------------------------------------------------------
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/productcatalogue# ls
Dockerfile  pom.xml  product-catalogue.yml  src  target


build the docker image::
=========================

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/productcatalogue# docker image build -t productcatalogue .


[+] Building 0.6s (8/8) FINISHED                                                                                        docker:default
 => [internal] load build definition from Dockerfile                                                                              0.0s
 => => transferring dockerfile: 273B                                                                                              0.0s
 => [internal] load metadata for docker.io/library/openjdk:8-jre                                                                  0.1s
 => [internal] load .dockerignore                                                                                                 0.0s
 => => transferring context: 2B                                                                                                   0.0s
 => CACHED [1/3] FROM docker.io/library/openjdk:8-jre@sha256:667a15e7bc533a90fb39ddb7e5bed63162ac3c13a97e6c698bf4f139f51b7d33     0.0s
 => [internal] load build context                                                                                                 0.2s
 => => transferring context: 17.63MB                                                                                              0.2s
 => [2/3] ADD target/productcatalogue-0.0.1-SNAPSHOT.jar app.jar                                                                  0.1s
 => [3/3] ADD product-catalogue.yml app-config.yml                                                                                0.0s
 => exporting to image                                                                                                            0.1s
 => => exporting layers                                                                                                           0.1s
 => => writing image sha256:6c0847459aa3acde4375bfed34e3f04d029bf02a6ceedff1503657d3fc4e75e4                                      0.0s
 => => naming to docker.io/library/productcatalogue 

 verify the images::
 ==================

 root@ip-172-31-36-154:~/docker-Java-kubernetes-project/productcatalogue# docker images
 
REPOSITORY                     TAG       IMAGE ID       CREATED         SIZE
productcatalogue               latest    6c0847459aa3   9 seconds ago   291MB
stockmanager                   latest    3de0cce0b9d4   4 minutes ago   317MB
srinu7358/stockmanager-myapp   latest    3de0cce0b9d4   4 minutes ago   317MB
shopfront                      latest    3ccf19de3929   47 hours ago    320MB
srinu7358/shopfront-myapp      latest    3ccf19de3929   47 hours ago    320MB
gcr.io/k8s-minikube/kicbase    v0.0.46   e72c4cbe9b29   2 months ago    1.31GB

Tag the image:::
=====
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/productcatalogue# docker image tag productcatalogue 

srinu7358/productcatalogue-myapp

verify the tag image::
=====================

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/productcatalogue# docker images

REPOSITORY                         TAG       IMAGE ID       CREATED              SIZE
productcatalogue                   latest    6c0847459aa3   About a minute ago   291MB
srinu7358/productcatalogue-myapp   latest    6c0847459aa3   About a minute ago   291MB
stockmanager                       latest    3de0cce0b9d4   5 minutes ago        317MB
srinu7358/stockmanager-myapp       latest    3de0cce0b9d4   5 minutes ago        317MB
srinu7358/shopfront-myapp          latest    3ccf19de3929   47 hours ago         320MB
shopfront                          latest    3ccf19de3929   47 hours ago         320MB
gcr.io/k8s-minikube/kicbase        v0.0.46   e72c4cbe9b29   2 months ago         1.31GB


pushed the image to docker hub::
======================

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/productcatalogue# docker push srinu7358/productcatalogue-myapp

Using default tag: latest
The push refers to repository [docker.io/srinu7358/productcatalogue-myapp]
c445b4f83c8c: Pushed
24772609f9a3: Pushed
1aaddf64804f: Mounted from srinu7358/stockmanager-myapp
990c5138f5d1: Mounted from srinu7358/stockmanager-myapp
5c384ea5f752: Mounted from srinu7358/stockmanager-myapp
293d5db30c9f: Mounted from srinu7358/stockmanager-myapp
03127cdb479b: Mounted from srinu7358/stockmanager-myapp
9c742cd6c7a5: Mounted from srinu7358/stockmanager-myapp
latest: digest: sha256:5254cff2f0ce313265acee48dc8a8bd7a502ff0a6f08e3bb0dfa3ec7738676c8 size: 2001


all 3 projects images are pushed to docker hub::
===============================================

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4dbca3bb-f1a0-40e6-b140-6e9846f30c96" />



25/08/2025::
==============


edit the yaml file

root@ip-172-31-36-154:~/docker-Java-kubernetes-project# ls

README.md  kubernetes  productcatalogue  shopfront  stockmanager

root@ip-172-31-36-154:~/docker-Java-kubernetes-project# cd kubernetes/

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# ls

productcatalogue-service.yaml  shopfront-service.yaml  stockmanager-service.yaml

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# sudo vi shopfront-service.yaml

in yaml file please use your docker hub image------->srinu7358/shopfront-myapp

verify the pods,deployments,services::
=========================

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get pods

No resources found in default namespace.
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get deploy

No resources found in default namespace.
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get service

NAME         TYPE        CLUSTER-IP       EXTERNAL-IP   PORT(S)        AGE
kubernetes   ClusterIP   10.96.0.1        <none>        443/TCP        47h

apply the yaml file::
========

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl apply -f shopfront-service.yaml

service/shopfront created
deployment.apps/shopfront created
 above command is used to created pods,deployments,servcies

 root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get po
 
NAME                         READY   STATUS    RESTARTS   AGE
shopfront-69467555f6-nzsxw   1/1     Running   0          22s

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get deploy

NAME           READY   UP-TO-DATE   AVAILABLE   AGE
shopfront      1/1     1            1           7m2s

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get service

NAME           TYPE        CLUSTER-IP      EXTERNAL-IP   PORT(S)          AGE
kubernetes     ClusterIP   10.96.0.1       <none>        443/TCP          2d
shopfront      NodePort    10.109.12.218   <none>        8010:32451/TCP   7m14s

we need to do other 2 micro services as well

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# sudo vi productcatalogue-service.yaml

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl apply -f productcatalogue-service.yaml

service/productcatalogue created
deployment.apps/productcatalogue created
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get po

NAME                               READY   STATUS         RESTARTS     AGE
productcatalogue-968c9cbf8-dl5zx   0/1     ErrImagePull   0            15s
shopfront-69467555f6-nzsxw         1/1     Running        0            9m4s
stockmanager-6c4454c6cb-2hhfd      1/1     Running        3 (2s ago)   2m43s
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get deploy

NAME               READY   UP-TO-DATE   AVAILABLE   AGE
productcatalogue   0/1     1            0           42s
shopfront          1/1     1            1           9m31s
stockmanager       1/1     1            1           3m10s
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get svc

NAME               TYPE        CLUSTER-IP       EXTERNAL-IP   PORT(S)          AGE
kubernetes         ClusterIP   10.96.0.1        <none>        443/TCP          2d
productcatalogue   NodePort    10.105.165.177   <none>        8020:32215/TCP   56s
shopfront          NodePort    10.109.12.218    <none>        8010:32451/TCP   9m45s
stockmanager       NodePort    10.96.92.240     <none>        8030:31767/TCP   3m24s
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get deploy

NAME               READY   UP-TO-DATE   AVAILABLE   AGE
productcatalogue   0/1     1            0           71s
shopfront          1/1     1            1           10m
stockmanager       1/1     1            1           3m39s
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get po

NAME                               READY   STATUS             RESTARTS      AGE
productcatalogue-968c9cbf8-dl5zx   0/1     ImagePullBackOff   0             77s
shopfront-69467555f6-nzsxw         1/1     Running            0             10m
stockmanager-6c4454c6cb-2hhfd      1/1     Running            4 (14s ago)   3m45s

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get po

NAME                               READY   STATUS             RESTARTS      AGE
productcatalogue-968c9cbf8-dl5zx   0/1     ImagePullBackOff   0             2m8s
shopfront-69467555f6-nzsxw         1/1     Running            0             10m
stockmanager-6c4454c6cb-2hhfd      1/1     Running            5 (15s ago)   4m36s
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# sudo vi productcatalogue-service.yaml

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl apply -f productcatalogue-service.yaml

service/productcatalogue unchanged
deployment.apps/productcatalogue configured
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get po

NAME                                READY   STATUS             RESTARTS      AGE
productcatalogue-86c9dd7b7b-bzj29   1/1     Running            0             16s
shopfront-69467555f6-nzsxw          1/1     Running            0             14m
stockmanager-6c4454c6cb-2hhfd       0/1     CrashLoopBackOff   6 (44s ago)   8m25s
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get po

NAME                                READY   STATUS             RESTARTS      AGE
productcatalogue-86c9dd7b7b-bzj29   1/1     Running            0             28s
shopfront-69467555f6-nzsxw          1/1     Running            0             14m
stockmanager-6c4454c6cb-2hhfd       0/1     CrashLoopBackOff   6 (56s ago)   8m37s
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl apply -f stockmanager-service.yaml

service/stockmanager unchanged
deployment.apps/stockmanager configured
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get po

NAME                                READY   STATUS             RESTARTS      AGE
productcatalogue-86c9dd7b7b-bzj29   1/1     Running            0             47s
shopfront-69467555f6-nzsxw          1/1     Running            0             15m
stockmanager-6c4454c6cb-2hhfd       0/1     CrashLoopBackOff   6 (75s ago)   8m56s


if any pod is CrashLoopBackOff , please delete or update new image

delete the pod::
==================

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get po

NAME                                READY   STATUS             RESTARTS      AGE
productcatalogue-86c9dd7b7b-bzj29   1/1     Running            0             47s
shopfront-69467555f6-nzsxw          1/1     Running            0             15m
stockmanager-6c4454c6cb-2hhfd       0/1     CrashLoopBackOff   6 (75s ago)   8m56s
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl delete po stockmanager-6c4454c6cb-2hhfd

verify the after deleted::
====================

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get po

NAME                                READY   STATUS    RESTARTS   AGE
productcatalogue-86c9dd7b7b-bzj29   1/1     Running   0          91s
shopfront-69467555f6-nzsxw          1/1     Running   0          16m
stockmanager-6c4454c6cb-8wkxv       1/1     Running   0          5s

all 3 micro service projects ,running pods,deploy,services::
===========================================================

root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get po

NAME                                READY   STATUS    RESTARTS      AGE
productcatalogue-86c9dd7b7b-bzj29   1/1     Running   0             2m54s
shopfront-69467555f6-wwfbv          1/1     Running   0             5s
stockmanager-6c4454c6cb-8wkxv       1/1     Running   1 (28s ago)   88s
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get deploy

NAME               READY   UP-TO-DATE   AVAILABLE   AGE
productcatalogue   1/1     1            1           10m
shopfront          1/1     1            1           19m
stockmanager       1/1     1            1           12m
root@ip-172-31-36-154:~/docker-Java-kubernetes-project/kubernetes# kubectl get svc

NAME               TYPE        CLUSTER-IP       EXTERNAL-IP   PORT(S)          AGE
kubernetes         ClusterIP   10.96.0.1        <none>        443/TCP          2d
productcatalogue   NodePort    10.105.165.177   <none>        8020:32215/TCP   10m
shopfront          NodePort    10.109.12.218    <none>        8010:32451/TCP   19m
stockmanager       NodePort    10.96.92.240     <none>        8030:31767/TCP   13m


>kubectl describe svc shopfront

use above command to ge the details of service 

in kubernetes we have multiple key components or objects::
======================

 YAML::

apiversion  --v1 or v2 --standadard syntax
 kind  ----deployment/service
 metadata  ----we can define name of the service
   name: shopfront
 labels ---->laben are very important in kubernetes and match with pod and matcgh with service

 spec
   type: clusterIP/NodePort

   ClusterIP::
   ==============

   ClusterIP is the default service type in Kubernetes. It creates a virtual IP (VIP) inside the cluster that other internal components (pods/services) can access — but it's not accessible from outside the cluster.

   apiVersion: v1
kind: Service
metadata:
  name: backend-service
spec:
  type: ClusterIP  # This is the default, so it can be omitted
  selector:
    app: my-backend
  ports:
    - protocol: TCP
      port: 80           # Port exposed by the service
      targetPort: 8080   # Port the container is listening on


 NodePort:
 =====
   NodePort is a type of Kubernetes Service that exposes your app outside the cluster, by opening a specific port on each worker node's IP address.

   apiVersion: v1
kind: Service
metadata:
  name: my-nodeport-service
spec:
  type: NodePort
  selector:
    app: my-app
  ports:
    - port: 80          # Service port (used internally by ClusterIP)
      targetPort: 8080  # Port on the pod
      nodePort: 30080   # Optional: if not set, Kubernetes picks one


root@k8smaster:~# kubectl get svc

NAME               TYPE        CLUSTER-IP       EXTERNAL-IP   PORT(S)          AGE

kubernetes         ClusterIP   10.96.0.1        <none>        443/TCP          2d11h

nginx-app          NodePort    10.102.214.44    <none>        80:31129/TCP     2d10h

productcatalogue   NodePort    10.101.216.239   <none>        8020:32208/TCP   2d10h

shopfront          NodePort    10.102.253.116   <none>        8010:31499/TCP   2d10h

stockmanager       NodePort    10.96.66.251     <none>        8030:32579/TCP   2d10h

root@k8smaster:~# kubectl get deploy

NAME               READY   UP-TO-DATE   AVAILABLE   AGE

nginx-app          2/2     2            2           2d11h

productcatalogue   1/1     1            1           2d10h

shopfront          1/1     1            1           2d10h

stockmanager       1/6     6            1           2d10h

root@k8smaster:~# kubectl get pods

NAME                                READY   STATUS             RESTARTS          AGE

nginx-app-5777b5f95-fcx8r           1/1     Running            0                 2d11h

nginx-app-5777b5f95-v5ghx           1/1     Running            0                 2d11h

productcatalogue-869f894bc7-66f86   1/1     Running            0                 2d10h

shopfront-66555cc947-hkg9v          1/1     Running            0                 2d10h

stockmanager-7657c6dfc5-4rntl       0/1     CrashLoopBackOff   995 (4m31s ago)   2d10h

stockmanager-7657c6dfc5-4skjh       0/1     CrashLoopBackOff   1016 (112s ago)   2d10h

stockmanager-7657c6dfc5-657z6       0/1     CrashLoopBackOff   997 (2m11s ago)   2d10h

stockmanager-7657c6dfc5-7nrdc       0/1     CrashLoopBackOff   995 (3m11s ago)   2d10h

stockmanager-7657c6dfc5-f46vf       1/1     Running            996 (5m41s ago)   2d10h

stockmanager-7657c6dfc5-qznfs       0/1     CrashLoopBackOff   999 (118s ago)    2d10h


root@k8smaster:~# kubectl get svc

NAME               TYPE        CLUSTER-IP       EXTERNAL-IP   PORT(S)          AGE

kubernetes         ClusterIP   10.96.0.1        <none>        443/TCP          2d11h

nginx-app          NodePort    10.102.214.44    <none>        80:31129/TCP     2d11h

productcatalogue   NodePort    10.101.216.239   <none>        8020:32208/TCP   2d10h

shopfront          NodePort    10.102.253.116   <none>        8010:31499/TCP   2d10h

stockmanager       NodePort    10.96.66.251     <none>        8030:32579/TCP   2d10h

PORTS for all 3 micro services::
=================================
shopfront                  8010:31499/TCP 

productcatalogue           8020:32208/TCP    

stockmanager               8030:32579/TCP 

Navigate to browser url shopfront with port

http://35.94.221.231:31499/

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5e7be549-ebd1-4bd5-b7e2-615f329b5a62" />

Navigate to browser url productcatalogue with port

http://35.94.221.231:32208/products

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a5dadfab-9d61-4cc4-9306-f49f910bb03b" />

Navigate to browser url stockmanager with port

http://35.94.221.231:32579/stocks

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b313bbf1-b052-4595-9426-4b1a33b8156f" />


<img width="1625" height="644" alt="image" src="https://github.com/user-attachments/assets/754f87cc-0356-4ac7-917e-597a29c1fc8c" />



25/08/2025::
===============


OpenShift Orchestration::
=============================

OpenShift Orchestration::
======================


OpenShift is an open-source container application platform built around Docker containers and Kubernetes. It's designed to help developers and IT organizations to develop, deploy, and manage applications in a highly automated environment. OpenShift offers a range of tools to make the development process more streamlined, such as CI/CD (Continuous Integration/Continuous Delivery) pipelines, a user-friendly web console, monitoring, and logging features.
Here are some key features and components of OpenShift:
1.	Kubernetes-based orchestration: OpenShift is built on top of Kubernetes, providing advanced container orchestration, scaling, and management.
2.	Developer Tools: OpenShift offers tools that make it easier for developers to deploy applications, like a simple web-based interface, CLI (Command Line Interface), and built-in support for various programming languages.
3.	Integrated CI/CD Pipelines: OpenShift integrates with Jenkins and other tools to automate the process of building, testing, and deploying applications.
4.	Security: OpenShift has several security features, including integrated authentication, network policies, and role-based access control (RBAC).
5.	Multi-cloud & Hybrid Cloud: It supports hybrid cloud environments, so applications can run across multiple infrastructures—on-premises, in the cloud, or a combination.
6.	Automated Scaling: OpenShift can automatically scale applications up or down based on resource usage.
7.	Registry and Image Management: It includes a built-in container registry to manage Docker images and store them for your applications

Red Hat Openshift Overview::
============================

- Red Hat Openshift is developed on top of Opeensource OKD ( which in turn is developed on top of opensource Kubernetes )
- supports command line interface and webconsole(GUI)
- supports Role based access control (RBAC), hence multiple users can be created with different level of access to Openshift cluster
- supports many additional features on top of all the Kubernetes features
  1. User Management
  2. Pre-integrated monitoring tools ( Prometheus & Grafana Dashboards )
  3. Out of the box - Private Container Registry
  4. Routes - a new feature only available in Openshift which is developed on top of Kubernetes Ingress
  5. Using the Kubernetes operators, the Red Hat Openshift team has many additional features on top of Kubernetes
- Openshift version upto 3 - supported many different container runtime/engines including Docker
- Openshift version 4 and above - only supports Podman Container Engine and CRI-O Container Runtime
- Due to security vulnerabilities issues in Docker, 

Using Free RedHat Developer Sandox on cloud - Openshift::
=============================

https://console.redhat.com/openshift/sandbox

we need to register free Red Hat account for  OpenShift

![image](https://github.com/user-attachments/assets/d78d4def-c589-446d-934b-3109d979b3be)

![image](https://github.com/user-attachments/assets/c4900081-a748-4f8b-b1fa-625fcccb3b5c)

Enter Redhat Login Name

![image](https://github.com/user-attachments/assets/785803bd-4d2b-480f-9d1e-9249a3d28cad)

Enter the Password

![image](https://github.com/user-attachments/assets/234e53d4-da04-4781-92d6-f44baed46307)

![image](https://github.com/user-attachments/assets/16f49b20-0632-46c7-920e-e87cd7894ce1)

click create account

![image](https://github.com/user-attachments/assets/1478f402-bb54-4166-8351-c77cb04e4303)

you will get the Email verification, please check the email

![image](https://github.com/user-attachments/assets/a0b0a9cf-d103-4fae-92d7-a70f62f8d391)

![image](https://github.com/user-attachments/assets/7182b022-e9a6-442a-96eb-a19bfd0e5401)

click the link which is you got

![image](https://github.com/user-attachments/assets/4dd9989d-3c90-4ac3-a510-ab26b2f3cf42)

Red Hat Developer Sandbox

![image](https://github.com/user-attachments/assets/42a31572-f423-4512-bfbd-5a3684b52508)

![image](https://github.com/user-attachments/assets/bfb647b7-747a-4338-b640-209587fa699f)

![image](https://github.com/user-attachments/assets/4d7d539a-9a07-4df4-9ecb-ceee0797d482)

Select Openshift Launch

![image](https://github.com/user-attachments/assets/19773259-41b0-47ae-8f76-e2386d520d1b)


click DevSandBox

![image](https://github.com/user-attachments/assets/f0218c41-9bdf-4c8b-9684-9f2c54574d63)

select Role is Developer

![image](https://github.com/user-attachments/assets/5d6e2c8f-c1d5-4ee1-a399-74ef2e03fd00)

click all selected permissions

![image](https://github.com/user-attachments/assets/17d83152-51fe-49b8-8a31-ba66884efaf1)

![image](https://github.com/user-attachments/assets/f4e855fd-a34a-4668-941b-fb4baf3c28bb)

![image](https://github.com/user-attachments/assets/2ce3c97d-de12-4e69-b2b4-6e51100d421a)

Get started

![image](https://github.com/user-attachments/assets/ac637db7-c2cc-4b8f-8841-809131f72732)

Openshift is ready and go to Developer -->Helm---->Helm charts---->search Jenkins ---Installed Jenkins Helm Charts


![image](https://github.com/user-attachments/assets/b91564a1-27d1-473c-b8b3-ce67403694fc)

Login command line::

OC ----> Openshift Client

click Copy login command at top right corner

![image](https://github.com/user-attachments/assets/4e1735af-4114-4d8d-8c01-526127c36ceb)

![image](https://github.com/user-attachments/assets/6f4cfb80-19ca-4a3b-b4be-405c6e69f812)

copy Login in with this Token

![image](https://github.com/user-attachments/assets/11a7edbb-f3aa-4e79-8457-90dedfb0af06)

![image](https://github.com/user-attachments/assets/3d18ae45-f2d6-43ca-b8e5-95d5b2d23a64)

Getting oc command is not found

So we need to download the oc from google

1 download oc.exe https://developers.redhat.com/openshift/command-line-tools
2 navigate to environment variables -> system variables -> new
3 add here: /path/to/the/oc.exe

https://docs.redhat.com/en/documentation/openshift_container_platform/4.8/html/cli_tools/openshift-cli-oc#cli-installing-cli_cli-developer-commands

https://access.redhat.com/downloads/content/290/ver=4.18/rhel---9/4.18.7/x86_64/product-software

OC download LInk::
=====================

OC
is a client tool used to create and manage Openshift resources in OpenShift
it makes REST call to API Server

https://access.redhat.com/downloads/content/290/ver=4.18/rhel---9/4.18.8/x86_64/product-software

Download Windows client

![image](https://github.com/user-attachments/assets/14d36459-8cf3-4ba1-8cb5-361f34730aa0)

Download the oc for window and extracted all the files

![image](https://github.com/user-attachments/assets/85d30663-3fc1-4a7a-878a-3f316b74ce7c)

Open from command line

![image](https://github.com/user-attachments/assets/999801e8-1078-474c-9ab1-27e4bb3e8a21)


![image](https://github.com/user-attachments/assets/3122d471-9a89-467c-b986-d9229f95db9f)

Switch project
>oc project <projectname>
>oc project srinu942-dev

![image](https://github.com/user-attachments/assets/31f81eac-41a4-403b-8de3-3edf5089e4f0)

OpenShift resources
•	Deployment (K8s resource)
•	ReplicaSet (K8s resource)
•	Pod (K8s resource)
•	Job (K8s resource)
•	DaemonSet (K8s resource)
•	StatefulSet (K8s resource)
•	Build ( OpenShift resource - Custom Resource added by OpenShift )
•	ImageStream ( OpenShift resource - Custom Resource added by OpenShift )
•	DeploymentConfig ( OpenShift resource - Custom Resource added by OpenShift )

Deployment command looks like this
>oc create deployment nginx --image=bitnami/nginx:latest --replicas=3

![image](https://github.com/user-attachments/assets/dbc5a3bd-aa15-4346-b753-9621d8dd3e81)

Deployment::
=================
This is a JSON/YAML definition which is stored in etcd database
The deployment is managed by Deployment Controller
when we applications, they are deployed as Deployment with Kubernetes/OpenShift
Deployment Controller creates ReplicaSet, which is then managed by ReplicaSet Controller
Deployment has one or more ReplicaSet(s)

ReplicaSet::
=============
This is a JSON/YAML definition which is stored in etcd database
The ReplicaSet is managed by ReplicaSet Controller
ReplicaSet capture details like
How many Pod instances are desired?
ReplicaSet Controller reads the ReplicaSet definition and learns the desired Pod instance count
ReplicaSet Controller creates so many Pod definition as indicated in the ReplicaSet
ReplicaSet Controller ensures the desired Pod count matches with the actual Pod count, whenever a Pod crashes, it is the responsibility of ReplicaSet Controller to ensure the desired and actual Pods are equal
ReplicaSet has one or more Pods

Pod::
====
is a collection of one or more Containers
IP address is assigned on the Pod level not on the Container level
If two containers are in the same Pod, there will be sharing IP Address of the Pod
within container, application are deployment ( tomcat,mysql, nginx these are applications )
recommended best practice,only one application should be there in a Pod
Pods are scheduled by Scheduler onto some Node
every Pod has a Network Stack and Network Interface Card (NIC)

Kubelet::
===========
is a daemon service that interacts with the Container Runtime on the current node/server where kubelet is running
kubelet downloads the required container image and creates the Pod containers
kubelet frequently reports the status of Pod container status to the API server
kubelet also monitors the health of POds running on the node and ensures they are healthy
kubelet will there on every node ( master and worker nodes )

kube-proxy::
=============
is a Pod that runs one instance per node (both master and worker nodes)
provides load-balancing a group of similar Pods
Sample Demo Project fro Openshift

Kubectl::
========
is a client tool used to create and manage deployments and services in Kubernetes
it also works in OpenShift
it make REST call to API Server

OC::
===
is a client tool used to create and manage Openshift resources in OpenShift
it makes REST call to API Server

https://github.com/wicksy/openshift-demo-app/tree/master
https://github.com/wicksy/openshift-demo-app

Login command line::

OC ----> Openshift Client

click Copy login command at top right corner

![image](https://github.com/user-attachments/assets/4e1735af-4114-4d8d-8c01-526127c36ceb)

![image](https://github.com/user-attachments/assets/6f4cfb80-19ca-4a3b-b4be-405c6e69f812)

copy Login in with this Token

![image](https://github.com/user-attachments/assets/11a7edbb-f3aa-4e79-8457-90dedfb0af06)

![image](https://github.com/user-attachments/assets/3d18ae45-f2d6-43ca-b8e5-95d5b2d23a64)

Getting oc command is not found

So we need to download the oc from google

1 download oc.exe https://developers.redhat.com/openshift/command-line-tools
2 navigate to environment variables -> system variables -> new
3 add here: /path/to/the/oc.exe

https://docs.redhat.com/en/documentation/openshift_container_platform/4.8/html/cli_tools/openshift-cli-oc#cli-installing-cli_cli-developer-commands

https://access.redhat.com/downloads/content/290/ver=4.18/rhel---9/4.18.7/x86_64/product-software

OC download LInk::
=====================

OC
is a client tool used to create and manage Openshift resources in OpenShift
it makes REST call to API Server

https://access.redhat.com/downloads/content/290/ver=4.18/rhel---9/4.18.8/x86_64/product-software

Download Windows client

![image](https://github.com/user-attachments/assets/14d36459-8cf3-4ba1-8cb5-361f34730aa0)

Download the oc for window and extracted all the files

![image](https://github.com/user-attachments/assets/85d30663-3fc1-4a7a-878a-3f316b74ce7c)


OC (Openshift Client) Environment Path Setup::
=================================================

Go to Environment Variable

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/49b284e4-d6f4-4174-882b-eba40f7278a7" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/785ec522-2004-4b35-a508-ae66bb170e3a" />

Set the User Variables::
===========================

C:\Openshift\oc\


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c5c9a09a-bd7a-445e-ac0a-5ae719ee5b7b" />

Set the System Variables and Path::
===================================

C:\Openshift\oc\

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fb77f2ad-5bd6-4e30-9e1f-88c40f65d4a5" />

click OK ----> OK----> OK

Go to command prompt

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/49ebb7c8-f469-4046-9c44-2030129aa615" />

verify the OC

>oc


verify the oc verison

>oc version


C:\Users\HP>oc version

Client Version: 4.19.3

Kustomize Version: v5.5.0

Server Version: 4.18.16

Kubernetes Version: v1.31.8


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/48fd2ee7-1510-416d-8124-ec3ac161fec5" />


Clone the Project from Openshift Command line(cli)::
========================================================

>git clone https://github.com/srinfotech7358/docker-Java-kubernetes-project.git


C:\Users\HP>git clone https://github.com/srinfotech7358/docker-Java-kubernetes-project.git

Cloning into 'docker-Java-kubernetes-project'...

remote: Enumerating objects: 173, done.

remote: Counting objects: 100% (58/58), done.

remote: Compressing objects: 100% (47/47), done.

Rremote: Total 173 (delta 33), reused 10 (delta 10), pack-reused 115 (from 1)

Receiving objects: 100% (173/173), 31.47 KiB | 4.00 KiB/s, done.

Resolving deltas: 100% (41/41), done.


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2eb89ce1-14e2-4cff-92de-2aa757f9a2cd" />

>cd docker-Java-kubernetes-project

>cd kubernetes

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fb1c3b1f-4da1-4cff-9f5a-4f72e0aae4ce" />

>oc projects

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/250aba7f-14e3-46b7-8f1c-032da5197b11" />

switch the project

>oc project <projectname OR Namespace>

>oc project srinfotech7358-dev

C:\Users\HP\docker-Java-kubernetes-project\kubernetes>oc project srinfotech7358-dev

Already on project "srinfotech7358-dev" on server "https://api.rm1.0a51.p1.openshiftapps.com:6443".

C:\Users\HP\docker-Java-kubernetes-project\kubernetes>


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/198007de-0f67-4ba8-9d33-33ae5386f1d7" />


create the openshift deployment::
====================================

Syntax::
========

>kubectl apply -f <playbook/yaml/yml>

>oc apply -f shopfront-service.yaml

>oc apply -f productcatalogue-service.yaml

>oc apply -f stockmanager-service.yaml

all 3 Micro services Deployemnts is created

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6ec769fc-fed2-4601-92fd-7ac0a0ad7f13" />


expose Openshift Services::
============================

Syntax::
===============

>oc expose service <servicename>

>oc expose deployment <deploymentName>

>oc get svc OR services

C:\Users\HP\docker-Java-kubernetes-project\kubernetes>oc get svc
NAME                          TYPE           CLUSTER-IP       EXTERNAL-IP                                                  PORT(S)                                              AGE
example                       ClusterIP      172.30.120.21    <none>                                                       80/TCP                                               7d6h
jenkins                       ClusterIP      172.30.2.244     <none>                                                       80/TCP                                               7d7h
jenkins-jnlp                  ClusterIP      172.30.35.46     <none>                                                       50000/TCP                                            7d7h
modelmesh-serving             ClusterIP      None             <none>                                                       8033/TCP,8008/TCP,8443/TCP,2112/TCP                  7d7h
my-app-service                ClusterIP      172.30.167.153   <none>                                                       8080/TCP                                             9h
nginx                         ClusterIP      172.30.43.7      <none>                                                       8080/TCP                                             7h30m
petclinic-00001               ClusterIP      172.30.121.230   <none>                                                       80/TCP,443/TCP                                       7h41m
petclinic-00001-private       ClusterIP      172.30.127.53    <none>                                                       80/TCP,443/TCP,9090/TCP,9091/TCP,8022/TCP,8012/TCP   7h41m
productcatalogue              NodePort       172.30.36.130    <none>                                                       8020:30170/TCP                                       8h
shopfront                     NodePort       172.30.246.166   <none>                                                       8010:31109/TCP                                       8h
sonarqube                     ClusterIP      172.30.197.221   <none>                                                       9000/TCP                                             7h13m
spring-ms-git                 ExternalName   <none>           kourier-internal.knative-serving-ingress.svc.cluster.local   80/TCP                                               7d6h
spring-ms-git-00001           ClusterIP      172.30.134.127   <none>                                                       80/TCP,443/TCP                                       7d6h
spring-ms-git-00001-private   ClusterIP      172.30.131.234   <none>                                                       80/TCP,443/TCP,9090/TCP,9091/TCP,8022/TCP,8012/TCP   7d6h
stockmanager                  NodePort       172.30.158.37    <none>                                                       8030:31782/TCP                                       7h53m


>oc expose service shopfront

>oc expose service productcatalogue

>oc expose service stockmanager

all 3 micro services are up & running in Openshift cluster

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/494b1042-e10b-424a-a50b-0b632e021a9e" />


Shopfront::
=============

http://shopfront-srinfotech7358-dev.apps.rm1.0a51.p1.openshiftapps.com/

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b73a85c7-d73e-4f25-bd98-364afab07df5" />


productcatalogue::
====================

http://shopfront-srinfotech7358-dev.apps.rm1.0a51.p1.openshiftapps.com/products

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a105b423-c20b-4823-8ae4-eb8ca69944a5" />


stockmanager::
===================

http://stockmanager-srinfotech7358-dev.apps.rm1.0a51.p1.openshiftapps.com/stocks

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/393c4678-fd19-49ed-8def-bc08b7190529" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5f4eed44-9f10-4549-84bb-6506d65911fa" />


Deploy Nginx Application To Openshift Platform::CLI
=====================================================

>oc create deployment nginx --image=bitnami/nginx:latest

>oc expose deployment nginx --port=8080 --target-port=8080 --name=nginx


http://route-unfortunate-smelt-srinfotech7358-dev.apps.rm1.0a51.p1.openshiftapps.com/


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7b164789-3b24-4212-8d53-989011144a96" />


26/08/2025::
============

Splunk::
============

Splunk is a powerful platform for searching, monitoring, and analyzing machine-generated big data via a web-style interface. It’s widely used for:

1.Log aggregation

2.Monitoring and observability

3.Security (SIEM/SOAR)

4.Dashboards and alerting

Splunk Integrate With Jenkins::
===========================

Jenkins install link

https://www.cherryservers.com/blog/install-jenkins-ubuntu

Splunk install link

https://www.splunk.com/en_us/download/splunk-enterprise.html

Create Account

![image](https://github.com/user-attachments/assets/4275dc32-37e7-41a4-8634-89bff7f6ce38)

Click Create your account


Verify the email

![image](https://github.com/user-attachments/assets/65095d9c-4f93-4d44-9f0c-50d11c752093)

![image](https://github.com/user-attachments/assets/9479e5ef-2f2f-481a-9ff2-796971238eb7)

Copy Wget URL

wget -O splunk-9.4.1-e3bdab203ac8-linux-amd64.deb https://download.splunk.com/products/splunk/releases/9.4.1/linux/splunk-9.4.1-e3bdab203ac8-linux-amd64.deb

![image](https://github.com/user-attachments/assets/91dcd374-23b5-4951-ba91-2031f3df5e7a)

Create one AWS Ubuntu Machine and past the Wget url and enter

![image](https://github.com/user-attachments/assets/da0d2f58-6893-41a3-87dc-9cfde5abdb54)

![image](https://github.com/user-attachments/assets/6ca6e5cc-e93e-4fc2-ad07-321d2b546b6d)

Download successfully using that wget url

![image](https://github.com/user-attachments/assets/9ab0f410-654b-41bf-aeaf-0ddd9cb8f9bf)

Go to splunk tutorial
https://docs.splunk.com/Documentation/Splunk/9.4.1/SearchTutorial/WelcometotheSearchTutorial

go to below link

https://docs.splunk.com/Documentation

click Splunk enterprise
![image](https://github.com/user-attachments/assets/e29a16ac-e8c0-4001-b9e7-0a38083a143c)

Search tutorial
![image](https://github.com/user-attachments/assets/a4c67579-d4a8-433f-b5f8-b7e8c03a6440)

Part 1: Getting started

•	Install Splunk Enterprise

![image](https://github.com/user-attachments/assets/8cd7631b-f021-4e17-8c17-c745719cd89e)

Install the Splunk Enterprise DEB package
![image](https://github.com/user-attachments/assets/9d25b1f5-610b-424c-a382-ada36c84def9)

dpkg -i splunk_package_name.deb.

>sudo dpkg -i

![image](https://github.com/user-attachments/assets/eab015f9-658c-40a4-a0a9-f3d4a5fe9c2e)

Run below command in ubuntu

>sudo dpkg -i splunk-9.4.1-e3bdab203ac8-linux-amd64.deb

![image](https://github.com/user-attachments/assets/b927efe6-7bf2-47f1-bc5c-08362cd95812)


![image](https://github.com/user-attachments/assets/a071e14d-4dda-415c-8bdb-ed610ce66b56)

To start the splunk please run below command

>sudo /opt/splunk/bin/splunk enable boot-start


![image](https://github.com/user-attachments/assets/322f83e9-90a3-4e9e-b4d4-09e08d19ff7f)


Click enter

![image](https://github.com/user-attachments/assets/b932045c-f586-439d-9c13-f2afd9035922)


![image](https://github.com/user-attachments/assets/790d67c5-cc65-4a8a-a2ed-1f52f878cfea)


![image](https://github.com/user-attachments/assets/d65bda8a-2255-4231-9d9b-e2914798a31f)


Username:: 

![image](https://github.com/user-attachments/assets/a1a5f381-3ded-4291-b779-561b2373e4e1)


Password:

![image](https://github.com/user-attachments/assets/a95d259e-b0b6-4299-98e4-c690b057bbf5)


![image](https://github.com/user-attachments/assets/2ffcc310-04f3-4e41-b09d-63087230510d)


For enabled boost start right for that we need to run below command

>sudo ufw allow openSSH

![image](https://github.com/user-attachments/assets/857857f0-9262-4d83-af93-53097331bfcd)


![image](https://github.com/user-attachments/assets/cc881e9c-94c1-454f-a8cc-4a375778c1e8)


openSSH means open por 22

enabled port for splunk

>sudo ufw allow 8000


![image](https://github.com/user-attachments/assets/0112d03f-4f19-43cc-b27a-0b5d5248fa4c)


Check the splunk status
>sudo ufw status

Inactive, so we need to enabled


![image](https://github.com/user-attachments/assets/ab0950ca-af19-439f-bf79-401d208c175d)


Enabled splunk

>sudo ufw enable


![image](https://github.com/user-attachments/assets/4740cb2b-3ff0-4f2f-a1c9-af5e2bd8af6b)


![image](https://github.com/user-attachments/assets/f8ef0cda-91bb-499f-be3b-257c106657f2)


Now see openSSH port -22 allowed
8000 port enabled allowed 

Now we need to start splunk
>sudo /opt/splunk/bin/splunk start


![image](https://github.com/user-attachments/assets/d0593020-69ba-4212-9046-ff69e665593f)


![image](https://github.com/user-attachments/assets/37cf9f5e-85b2-442b-9e28-3dcac692605e)


Enter user/pwd
Srinu/Srinu@7358
