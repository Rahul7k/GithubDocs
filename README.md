# GithubDocs

…or create a new repository on the command line
echo "# GithubDocs" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Rahul7k/GithubDocs.git
git push -u origin main


…or push an existing repository from the command line
git remote add origin https://github.com/Rahul7k/GithubDocs.git
git branch -M main
git push -u origin main

To Add Into Existing repository
open VS Code -> Go to Source control -> Commit using ✔ Sign -> Now run below commands in VS Code terminal
git remote add origin https://github.com/Rahul7k/Taazaa-Training.git
git branch -M main
git pull --rebase origin main
git push origin main
