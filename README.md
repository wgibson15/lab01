# Introduction
Assigned: 2016-01-11
Due: 2016-01-18

This is the Lab 1 assignment for ECE 1120 - C Programming for ECE.

# Objectives

The goals of this lab are to introduce you to the Cloud9 development
environment, and the GitHub software hosting repository and use these
tools to build and run a simple C program.

# Steps

## Create a free GitHub account
GitHub is Web-based source code repository service. That is, it lets
users easily store and share source code - the ingredients that are
used to build software.

To create an account, visit https://github.com. Use the same username
that's associated with your GW email account. For example, if your
GW email is randomstudent@gwu.edu, use the username "randomstudent".

## Create a free Cloud9 account
Cloud9 is a web-based integrated development environment and Linux
workspace. This lets you have your very own Linux system that you can
use to edit, build, run, and test your software.

Once you have a GitHub account created, you can use that same account
to sign up for a Cloud9 account. First, visit https://c9.io then click
on the icon that lets you sign in with GitHub. Once you have logged in
with your account, create a *PRIVATE* workspace called "work".

## Use git to clone the Lab 1 assignment.

From the cloud9 command-line, use the git source code control tool to
make a copy of the starter source code for this assignment.

```
randomstudent@work:~/workspace $ git clone https://github.com/gw-ece1120-s2016/lab01
```

You should see some output similar to this:
```
Cloning into 'lab01'...
remote: Counting objects: 4, done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 4 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), done.
Checking connectivity... done.
```

## Build the starter program for the lab 1 assignment

Go into the cloned lab01 directory (i.e. folder):

```
cd lab01
```

Build your first program from the source code by running "make":

```
randomstudent@work:~/workspace $ make
```

You should see some output similar to this:
```
cc -Wall    hello.c   -o hello
```

Finally run your first C program:
```
randomstudent@work:~/workspace $ ./hello
Hello world!
```

## Edit the lab 1 assignment.
From the Cloud9 workspace menu on the left, navigate to hello.c source
file. First, modify the comment to have your own name. Next, figure
out how to add another print statement to your program so that it
prints your name when it runs, for example:

```
Hello world!
written by Random A. Student

```

