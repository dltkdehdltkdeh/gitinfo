## gitinfo

Introduction for Git and SVN by written Stone

```sql
/* My Life is ... */
SELECT T.MyAge, T.LifeInfo, T.*
  FROM BravoMyLife
 WHERE T.MyAge >= 20
 ORDER BY
       T.MyAge DESC
```

Git Function | Command | Remark
-------------|---------|--------------
Initialize   | git init |
Initialize   | git remote add origin ☆repository address☆ |
PULL         | git pull origin master |
PUSH         | git status |
PUSH         | git add . |
PUSH         | git commit -m "2019.07.19.Fri. 07:29 First file is created by Stone." |
PUSH         | git push origin +master |
