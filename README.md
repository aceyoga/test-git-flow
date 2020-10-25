# README develop

```
git clone git@github.com:rms46/test-git-flow.git develop
cd develop
git pull;git push;
git flow init -d
git push --set-upstream origin develop
echo "#####    #####     This is branch develop..." | tee develop.md
git pull; git add -A; git commit -m "develop"; git push;

git flow feature start user1
git checkout feature/user1
git push --set-upstream origin feature/user1
git pull;git push;
git checkout develop 

git flow feature start user2
git checkout feature/user2
git push --set-upstream origin feature/user2
git pull;git push;
git checkout develop 

git flow feature start user3
git checkout feature/user3
git push --set-upstream origin feature/user3
git pull;git push;
git checkout develop 

git pull;git push;
git checkout develop 
git branch
```

