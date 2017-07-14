## Find all .csv files in subfolders and delete all except those with 'raw' string inside
```
$ ls -1 | grep '.csv' | grep -v 'raw' | xargs rm -f
```


## Create a new git repo and set up remote directory
```
echo "# bash_commands" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/gunnarpope/bash_commands.git
Git push -u origin master
```

## Change characters in batch of files

change u1710@eda.csv to u10@eda.csv
```
rename  -e 's/u17/u/'  *.csv
``` 
