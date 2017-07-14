find all .csv files in subfolders and delete all except those with 'raw' string inside
```
$ ls -1 | grep '.csv' | grep -v 'raw' | xargs rm -f
```

create a new git repo and set up remote directory
```
echo "# bash_commands" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/gunnarpope/bash_commands.git
Git push -u origin master
```
