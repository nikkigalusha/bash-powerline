# bash-powerline

Powerline for Bash in pure Bash script.

![bash-powerline](https://raw.github.com/bcmarinacci/bash-powerline/master/tomorrow-night-eighties.png)

## Features

* Git branch: display current git branch name, or short SHA1 hash when the head is detached
* Git branch: display "+" symbol when current branch is changed but uncommited
* Git branch: display "⇡" symbol and the difference in the number of commits when the current branch is ahead of remote
* Git branch: display "⇣" symbol and the difference in the number of commits when the current branch is behind of remote
* Fast execution (no noticable delay)
* No need for patched fonts

## Installation

Download the Bash script.
```bash
$ curl https://raw.githubusercontent.com/bcmarinacci/bash-powerline/master/bash-powerline.sh > ~/.bash-powerline.sh
```

Then source it in your `.bash_profile` (or `.bashrc`).
```bash
$ echo source ~/.bash-powerline.sh >> ~/.bash_profile
```

The theme used in the screenshot is [Tomorrow Night Eighties](https://github.com/chriskempson/tomorrow-theme/tree/master/OS%20X%20Terminal).

This command line prompt is based on the phenomenal [bash-powerline](http://learn.makerpass.com/groups/mks-52/courses/reactorcore/course.syllabus?s=3&p=5) by [riobard](https://github.com/riobard).
