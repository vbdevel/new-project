The project name is new-project.

Preparing dirrctory for project:
mkdir new-project
cd new-project

Creating public project new-project on github, and then linking it with local directory:
git init
git remote add origin git@github.com:vbdevel/new-project.git

Creating README.md:
vim README.md

Preparing init commit:
git add README.md
git commit -m 'init'

Creating branch "development":
git checkout -b development

Adding instructions to README.md:
vim README.md

Commiting changes to development branch:
git add README.md
git commit -m "added instructions to README.md"

Merging branch "development" to branch "main" and checking status:
Note: to merge feature branch to main branch there should be created PR on github and then it will be merged, (after review).

git checkout main
git merge development
git status
git commit

Pushing to github:
git push -u origin main
