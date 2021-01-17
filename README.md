# create_new_or_push_existing_repo_from_command_line
Quick guide to create a new create a new repository or or push an existing repository from the command line

### create a new repository on the command line

echo "# tester" >> README.md

git init

git add README.md

git status

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/<github_username>/<repo_name>.git

git push -u origin main


### push an existing local repository from the command line
git remote add origin https://github.com/<github_username>/<repo_name>.git

git add .

git status

git commit -m "comment"

git branch -M main

git push -u origin main


### push an existing local repository from the command line
