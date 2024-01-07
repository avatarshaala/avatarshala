Hi,
AvatarShala aims to build a repository of AI/ML codes.

Steps to create and initialize the repository in GitHub.
[
-- First create a github account. 
-- Install a git CLI (gitbash) by searching git cli in google.
-- Open Command Prompt (in windows) and enter "git --version" to check if cli is installed correctly.
-- You can interact with git repository using Command Prompt or (gitlab) now.

First-Time Git Setup

check if global config exists

$ git config user.name
John Doe

Now that you have Git on your system, you’ll want to do a few things to customize your Git environment. You should have to do these things only once on any given computer; they’ll stick around between upgrades. You can also change them at any time by running through the commands again.

Git comes with a tool called git config that lets you get and set configuration variables that control all aspects of how Git looks and operates.

The first thing you should do when you install Git is to set your user name and email address. This is important because every Git commit uses this information, and it’s immutably baked into the commits you start creating:

$ git config --global user.name "John Doe"
$ git config --global user.email "johndoe@example.com"

Again, you need to do this only once if you pass the --global option, because then Git will always use that information for anything you do on that system. If you want to override this with a different name or email address for specific projects, you can run the command without the --global option when you’re in that project.

Many of the GUI tools will help you do this when you first run them.
]

1. Create a new repository (for example: avatarshala) in your github.
2. create a local directory (for eg: local_avatarshala) and change working directory  of gitbash (or Command Prompt) to local_avatarshala.
3. Create a README.md file in local_avatarshala.
4. git init
5. git status     #shows the untracked and tracked files
6. git add README.md
7. git status
8. git commit -m "first commit"
9. git status
10. git branch [shows master branch]
11. git branch -M main    #renames master branch to main branch
12. git remote add origin https://github.com/avatarshala/avatarshala.git #maps local repo to the remote repository
13. git remote -v  #shows origin mapped to remote
14. git push origin main


######################################################################
…or create a new repository on the command line
echo "#Some Message >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/avatarshala/avatarshala.git
git push -u origin main

-----------------
…or push an existing repository from the command line
git remote add origin https://github.com/avatarshala/QA_ChatBot.git
git branch -M main
git push -u origin main

##############################################################

<!---
- 👋 Hi, I’m @avatarshala
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
--->
<!---
avatarshala/avatarshala is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.

Profile Image is created by DALL-E 3, with Bing Search using following prompt:

"A smily nepali looking gender-neutral toddler holographic avatar creating another AI"
--->
