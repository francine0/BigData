Created 5/1/2014 

Three ways to commit git changes

1)  Call git add in some form for every file that you want to commit.  call git commit at end.
> git add file1
> git commit -m "Name"

2) You are on a working tree.  Pass -a parameter.  Commits most current version of working tree to repository
> git commit -m "Name" -a

3) specify file or files after all options
> git commit -m "Name" file1