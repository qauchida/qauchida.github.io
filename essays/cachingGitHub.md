---
layout: essay
type: essay
title: Caching GitHub
# All dates must be YYYY-MM-DD format!
date: 2019-07-01
labels:
  - GitHub
  - Git
---
Recently, I messed up on our github (again).

I used this opportunity to learn about how to cache files that I don't want commited without modifying the .gitignore.

I came across [this medium article](https://medium.com/@dave_lunny/exclude-files-from-git-without-committing-changes-to-gitignore-986fa712e78d), which describes using the exclude file found in .git/info.
I found that this will work for new files not already commited but I needed to use 
```
git update-index --assume-unchanged file.name
```
[found from this SO article](https://stackoverflow.com/questions/1139762/ignore-files-that-have-already-been-committed-to-a-git-repository)
to prevent my changes to an existing file from being comitted. I needed this because I had to modify the settings.development.json which I accidentally commited (whoops). 



