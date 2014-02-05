
<!-- background: #2d2422 -->
<!-- color: #fff4e3 -->

# **Hacktorial 5 - Intro to Git**


* * *

<!-- background: #4cc24e -->
<!-- color: #fff4e3 -->

# **"Who even cares about Version Control Systems?"**


* * *

# Everybody's doing it


* * *

# Play well in groups


* * *

# Be a better hacker


* * *

# You're not smart enough to *not* use it


* * *

<!-- background: #451834 -->
<!-- color: #fff4e3 -->

# **"Well what's so great about version control?"**


* * *

# Ctrl + S


* * *

# Panic button


* * *

# Branch out


* * *

# Merge back


* * *

# Version numbers


* * *

# <3 GitHub


* * *

<!-- background: #00b98c -->
<!-- color: #fff4e3 -->

# **"Fine, show me how to use it."**


* * *

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

<!-- background: #9c9c9d -->
<!-- color: #fff4e3 -->

# **"That's it? Why can't I just share the folder with him via Dropbox?"**


* * *

<p align="center">
  <img src="http://i.imgur.com/jAodaB5.jpg" width="320" height="318">
</p>


* * *

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

<!-- background: #cc5f4a -->
<!-- color: #fff4e3 -->

## Branches on branches

<p align="center">
  <img src="http://erickryski.com/assets/img/git_branch_diagram.jpg">
</p>


* * *

<!-- background: #75b6d3 -->
<!-- color: #fff4e3 -->

# gitflow does all of that stuff for you


* * *

<!-- background: #f39b12 -->
<!-- color: #fff4e3 -->

# Thanks for coming!

## I'm on [Twitter (@zfogg)](https://twitter.com/zfogg) and [Facebook](https://www.facebook.com/zach.fogg)

