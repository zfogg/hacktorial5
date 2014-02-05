
<!-- background: #151515 -->
<!-- color: #f5f5f5 -->

# **Hacktorial 5 - Intro to Git**


* * *

<!-- background: #ac4142 -->

# **"Who even cares about Version Control Systems?"**


* * *

# Everybody's doing it


* * *

# Play well in groups


* * *

# Be a better hacker


* * *

# Because you take yourself seriously


* * *

# You're not smart enough to *not* use it


* * *

<!-- background: #202020 -->

# **"Well what's so great about version control?"**


* * *

<!-- background: #90a959 -->

# Git is a camera for your project


* * *

# and a panic button  for when you screw up


* * *

# It lets you branch out


* * *

# and merge back painlessly (lol SVN)


* * *

# Git gives you difference diagnostics


* * *

# A tag is like a new save file

* * *

# <3 GitHub


* * *

<!-- background: #303030 -->

# **"But the interface is scary and the docs don't make sense"**


* * *

<!-- background: #f4bf75 -->

# I know :(


* * *

# Aliases and text editor plugins help


* * *

<!-- background: #505050 -->

# **"Fine, show me how to use it"**


* * *

<!-- background: #6a9fb5 -->

# Okay


* * *

# First we need to tell Git to keep track of a project


* * *

    % pwd
    /home/zfogg/src/hacktorial5

    % git init


* * *

# Tell Git about a new file


* * *

    % touch index.coffee

    % git add index.coffee

    % git commit -m "Initial commit."


* * *

# . . . and stick it all on 'the cloud'


* * *

    % echo $USER
    zfogg

    % git remote add origin git@github.com/$USER/hacktorial5

    % git push -u origin master


* * *

# Now your buddy can help you hack


* * *

    % echo $USER
    someguy

    % git clone https://github.com/zfogg/hacktorial5


* * *

# Add him to the project on GitHub and start working together :)


* * *

<!-- background: #b0b0b0 -->
<!-- color: #151515 -->

# **"That's it? Why can't I just share the folder with him via Dropbox?"**


* * *

<p align="center">
  <img src="http://i.imgur.com/jAodaB5.jpg" width="320" height="318">
</p>


* * *

<!-- background: #aa579f -->
<!-- color: #f5f5f5 -->

# A few problems arise when you collaborate with someone


* * *

## What if there are **merge conflicts**?

Two people are working on a project.
Both are on the master branch, both are at the same commit.

One person changes a line in a file,
the other person deletes the same line in the same file.

One person stages, commits, and pushes their changes.
Of course this works just fine; a very standard task for Git.

Now, the second person tries to commit and push their changes.


* * *

### What will Git do?

### What *should* Git do?


* * *

# Git has tools to fix code collaboration issues


* * *

# but sometimes manual work is still required :(


* * *

# . . . and that's why we **always work on seperate branches**


* * *

# Working on separate branches reduces bugs when working with others


* * *

# You should never work on the master branch


* * *

<!-- background: #d0d0d0 -->
<!-- color: #151515 -->

## Branches on branches

<p align="center">
  <img src="https://www.atlassian.com/git/workflows/pageSections/00/contentFullWidth/0/tabs/02/pageSections/06/contentFullWidth/0/content_files/file0/document/git-workflow-release-cycle-2feature.png">
</p>


* * *

<!-- background: #8f5536 -->
<!-- color: #f5f5f5 -->

# gitflow does all of that stuff for you


* * *

# Feature, release, hotfix, support.


* * *

<!-- background: #e0e0e0 -->
<!-- color: #151515 -->

# **Got all that?**


* * *

<!-- background: #ac4142 -->
<!-- color: #f5f5f5 -->

# Thanks for coming!

## I'm on [Twitter (@zfogg)](https://twitter.com/zfogg) and [Facebook](https://www.facebook.com/zach.fogg)

