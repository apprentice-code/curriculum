# How to Setup Git

These steps assume that you are working on macOS or Linux. Also you should have a [github](http://www.github.com) account prior to completing these instructions.

## Steps for MacOS:
1. Complete the following steps in a terminal to install git:
    - `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
    - `brew install git`
    - `git config --global user.name "John Doe"` Replace "John Doe" with your name
    - `git config --global user.email johndoe@example.com` replace johndoe@example.com with your email address, this should match github credentials
1. Create a  ssh "finger-print" for your laptop
    - `ssh-keygen -t rsa`
    - `pbcopy < ~/.ssh/id_rsa.pub` This will copy your fingerprint to the copy paste button of your laptop. Do not share this!
1. Paste into github settings.
    - go to https://github.com/settings/keys
    - click "New SSH Key"
    - Create a title
    - paste your "finger-print" into the "key" field

## Steps for Windows:
1. Download git [here](https://git-scm.com/download/win)
1. Complete the instructions and open a git bash terminal
    - search for git where you house your applications, and you should be able to filter through by typing "git bash"
1. Complete the following steps in a git bash terminal to configure git:
    - `git config --global user.name "John Doe"` Replace "John Doe" with your name
    - `git config --global user.email johndoe@example.com` replace johndoe@example.com with your email address, this should match github credentials
1. Create a  ssh "finger-print" for your laptop
    - `ssh-keygen -t rsa`
    - `pbcopy < ~/.ssh/id_rsa.pub` This will copy your fingerprint to the copy paste button of your laptop. Do not share this!
1. Paste into github settings.
    - go to https://github.com/settings/keys
    - click "New SSH Key"
    - Create a title
    - paste your "finger-print" into the "key" field

## Resources
- https://www.youtube.com/watch?v=SUv6z3EZ6E0
