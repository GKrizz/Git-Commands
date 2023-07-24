# Git-Commands

echo "# Git-Commands" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/GKrizz/Git-Commands.git
git push -u origin main

*SETUP*
Configuring user information used across all local repositories

git config --global user.name “[firstname lastname]”
set a name that is identifiable for credit when review version history

git config --global user.email “[valid-email]”
set an email address that will be associated with each history marker

git config --global color.ui auto
set automatic command line coloring for Git for easy reviewing
