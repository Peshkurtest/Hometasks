# HW Git.Local
Home work 02
## Valera Peshkur

```bash
 1487  git init 
 1488  touch first.txt
 1489  git add -a
 1490  git add --all
 1491  git status 
 1492  git commit -m "first into master"
 1493  date > second.txt
 1494  git add second.txt 
 1495  git commit -m "second into master"
 1496  git log --oneline 
 1497  git branch dev
 1498  git checkout dev
 1499  git branch 
 1500  vi first.txt 
 1501  git log
 1502  git status 
 1503  git add --all
 1504  git commit -m "first dev"
 1505  date >> second.txt 
 1506  git add --all
 1507  git commit -m "second dev"
 1508  git log --oneline 
 1509  git checkout -b features/do_one
 1510  mkdir features
 1511  git status 
 1512  touch ./features/some_file.txt
 1513  git status 
 1514  git add features/
 1515  git status 
 1516  git commit -m "commit folder whith file"
 1517  git checkout master 
 1518  git checkout -b hotfix/we_a-a-a
 1519  git log --oneline 
 1520  git branch --all
 1521  touch fix.txt
 1522  git add fix.txt 
 1523  git commit -m "hotfix"
 1524  git checkout master 
 1525  git branch 
 1526  git merge -v --stat features/do_one 
 1527  git rebase dev 
 1528  ll
 1529  git log --oneline 
 1530  git merge hotfix/we_a-a-a 
 1531  ll
 1532  git branch 
 1533  git checkout dev 
 1534  git merge -v hotfix/we_a-a-a 
 1535  git checkout features/do_one 
 1536  git rebase hotfix/we_a-a-a
```
