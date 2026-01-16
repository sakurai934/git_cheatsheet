# git_cheatsheet

## GitHubで.gitignoreを先に作った場合

git init
git branch -M main
git remote add origin <URL>
git pull --rebase origin main
git add .
git commit -m "initial commit"
git push -u origin main
