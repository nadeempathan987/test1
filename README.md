$ sudo apt update
$ sudo apt install git
$ git --version
>> Initialise local git repository
$ mkdir gitdemo
$ cd gitdemo
$ git init 
$ nano file1
this is first line of code
$ git status
>> Put code to staging Area
$ git add file1
$ git status
>> Initialise Commit
$ git config user.name "Aasem Quazi"
$ git config user.email "aasem@databinaries.com"
$ git commit
>> Make changes
$ nano file1
this is second line of code
$ git status
2 | P a g e databinaries
$ git add file1
$ git status
$ git commit -m "added second line of code"
>> Check log
$ git log
----*** Connecting to remote repo ***----
$ ssh-keygen -t rsa -b 4096
$ cd .ssh
$ cat id_rsa.pub
(Copy content)
>> Add key in github account
$ cd
$ mkdir gitdemo2
$ cd gitdemo2
$ git clone git@github.com:aasemquazi/test1.git
$ cd test1
$ git status
$ nano pqr
first line of code
$ git status
$ git add pqr
$ git status
$ git commit -m "added"
$ git status
$ git push
>> Verify on Github.com# test1
