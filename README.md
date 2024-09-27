git checkout --orphan latest
git add -A
git commit -m newest
git branch -D master
git branch -m master
git push -f origin master