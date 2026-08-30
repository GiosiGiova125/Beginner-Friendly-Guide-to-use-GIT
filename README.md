# How to use **GIT**. Beginner friendly guide 💿

Git is a useful **software** related to Github. With Git you can simply update the code saved in your pc, directly on your your **repo**.

---

### How to install GIT ⬇️

Firstly you need to install git on your computer. There are a few way to do this, depending on your OS or package manager (GNU/Linux).

1. **Windows**: To install GIT on Windows download the **.exe** file on the official GIT website (https://git-scm.com/install/windows). After downloading the file simply duble click the installer and follow the guide.
2. **Linux**: To install GIT on Linux you'll need a package manager. Every distro have one, so I'll report here **the most common** terminal commands to install GIT. **REMEMBER!** IF THE DISTRO OR PM THAT YOU'RE USING ISN'T IN THIS GUIDE SIMPLY LOOK AT THE OFFICIAL GIT GUIDE THAT I'LL REPORT HERE: (https://git-scm.com/install/linux)
    - **Fedora based distro**: sudo dnf install git
    - **Ubuntu**: apt-get install git
    - **Arch**: pacman -S git
    - **openSuse**: zypper install git
3. **MacOS**: The easiest way to install GIT in your mac is to install via terminal **Homebrew**, then paste this command into the terminal. 
brew install git

---

### How to setup git for the first time 🖊️

The first thing to do after installing GIT into your sistem is to **setup your personal data** via the terminal. To do that simply paste this commands with your information.
```
git config --global user.name "YOUR NAME HERE"
git config --global user.email YOUR GITHUB E MAIL HERE
```
If you want to **check your setting** even after putting them in you can simply use this command:
```
git config --list
```
You installed git and configured it!

---

### How to use it
Here is a step by step guide on how to to use git into a GitHub repo.

1. In your browser search github and create a new repo, choose a name and check "add a README file"
2. After creating the repo copy his link.
3. Open the terminal and move into the position where your project will be, using the command cd (ex cd ~/my folder). After that use the command: git clone HERE-THE-LINK-OF-YOUR-REPO to clone all the things inside of your repo into your pc
4. Work into that folder
5. When you finished your daily work simply use this 3 commands into the path of the folder
```
git add .
git commit -m "write what you've done"
git push
```
git add . says to git to select all the files in the folder, git commit -m "write what you've done" says what you updated and git push send all to your repo.

---

I did this guide to help beginners that want to start programming and using github. I seed other guides online and they are pretty complicated so, i choosed to do a simpler one.
**If you fond this useful please feel free to star the repo🌟**

