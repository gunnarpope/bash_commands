find all .csv files in subfolders and delete all except those with 'raw' string inside
$ ls -1 | grep '.csv' | grep -v 'raw' | xargs rm -f
