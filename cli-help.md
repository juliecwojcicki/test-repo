# helpfile

## setting up the directory 
$git clone https://github.com/juliecwojcicki/test-repo

## testing

```
$ git show-ref
1f829f354abf8706dc34952f145318378946325e refs/heads/master
1f829f354abf8706dc34952f145318378946325e refs/remotes/origin/HEAD
1f829f354abf8706dc34952f145318378946325e refs/remotes/origin/master
```


## more help on
<https://stackoverflow.com/questions/4855561/difference-between-git-remote-add-and-git-clone?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa>

# history (installation of packages)

a <- available.packages()
head(rownames(a),3)
install.packages(c("slidify", "ggplot2","devtools"))
source("http://bioconductor.org/biocLite.R")
biocLite()
biocLite(c("GenomicFeatures","AnnotationDbi"))

Install rtools, then reboot RStudio before installing devtools
install.packgaes(devtools)

# to load packages

library(ggplot2)

# git push/pull instructions
$ cd git-repos/test-repo/
$ git pull
$ git add .
$ git commit -m "comments"
$ git push