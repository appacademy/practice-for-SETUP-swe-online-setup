# Update Phase 1 Installations

Now that you have WSL installed, it's time to check the software that you
installed during the Learning Challenges. You need to make sure that you can
access this software through WSL.

## Google Chrome

Check that Google Chrome is installed and working properly by finding it in
Windows Explorer, and double-click to open it.

## Visual Studio Code
Check that Visual Studio Code is installed and working properly by finding it
in Windows Explorer, and double-click to open it.

If either Google Chrome or Visual Studio Code are not installed or you cannot
access them, install them using the instructions in __Phase 1: Learning
Challenges Setup__. If you run into trouble, talk to an instructor for support.

## Git

Now that WSL 2 is set up and you are using an Ubuntu distribution, you already
have git within linux!

_If you are using a different distribution you may need to manually install
git._

Check that Git is configured properly and working through WSL by typing the
following commands into the Ubuntu terminal. You should see your real name and
real email address returned.

```shell
git config --global user.name    # your name returned
git config --global user.email   # your email address returned
```

If you do not see the correct output, configure Git within WSL using the following commands:

- Type `git config --global user.name "Your Name"`, replacing "Your Name" with your real name.
- Then type `git config --global user.email your@email.com`, replacing "your@email.com" with your real email.

Congratulations! You've confirmed that you have Google Chrome, Visual Studio
Code, and Git installed on your machine, and that you can access them through
WSL.