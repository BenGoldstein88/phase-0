# 1.1 Think About Time
Time management boils down to scheduling and mindfulness. Embracing a working balance, pre-planning breaks, starting with small steps, and creating/maintaining good habits are essential. Time boxing involves working on something for a specific amount of time (as opposed to, say, until it's done) and can be useful in cracking away at tougher challenges. Currently, I manage my time pretty poorly so this will be good training. Maintaining good habits and a positive mindset will help with the workload at DBC. My overall plan for Phase 0 management is to do something every day while employing some versions of these management skills.

# 1.2 The Command Line


A shell lets you navigate a computing space with minimal visual cues. Bash is a particular Unix shell. I'm having to re-remember, relearn, and just regular learn a lot of these commands, but the flow is coming back slowly. Commands that move and open directories are somewhat less useful in this world of click-and-drag technology, but many that let you change file contents/metadata directly are useful and efficient.





pwd - print working

ls - list

mv - move

cd - change directory

../ -

touch - update date

mkdir - make directory

less - show less

rmdir - remove directory

rm - remove

help - get help





#1.4 Forking and Cloning


Github makes it easy to create a new repository with the "create new repository" button.

Forking is as easy as clicking the "fork" button in the top right.

Cloning is possible through Github desktop, or through the command line with "git clone URL" where URL is the SSH url available in the "code" section of your github repo.



Sometimes there are file permission issues (i had some in the command line interface). Google is helpful, as is the DBC literature on version control.

How does tracking and adding changes make developers' lives easier?

Makes it easier to identify and isolate bugs, helps keep multiple collaboraters on a similar timeline, and keeps individual mistakes from sabotaging a workflow.

What is a commit?

Basically a "save point" in the program. It's a moment in time in development with relevant comments attached.

What are the best practices for commit messages?

Early, often, clear comments.

What does the HEAD^ argument mean?

Takes you to a previous commit.

What are the 3 stages of a git change and how do you move a file from one stage to the other?

Change, add, commit. Use the command line.

Write a handy cheatsheet of the commands you need to commit your changes.
git init, git clone URL
git status, git add FILE, git commit -m "Message"

What is a pull request and how do you create and merge one?

A pull is a request to merge a branch back into the master. You can create and merge a pull from git.

Why are pull requests preferred when working with teams?

So you don't just jam your code back into the master branch and cause problems for the other devs. Pulls show transparency and accountability.