dir_tree
========

Prints directory and subdirectories as tree in shell.

### Install ###
```sh
mkdir -p ~/bin
svn export https://github.com/withaspark/dir_tree/trunk/dir_tree ~/bin/dir_tree
chmod +x ~/bin/dir_tree
```

### Usage ###
```sh
Usage:
		dir_tree
		dir_tree path/to/directory
```

### Example Output ###
```
withaspark:~$ dir_tree parent
/home/withaspark/parent
 .
 | -child1
 | -child2
 |  | -child21
 |  | -child22
 |  | -child23
 |  |  | -child231
 |  |  | -child232
 |  | -child24
 | -child3
```

### What Makes ```dir_tree``` Special ###
Nothing; ```tree -d``` is better. But when you aren't an administrator and can't install additional packages (like on a university server), you can put a script in your bin path. But I'd encourage you to name it something shorter or alias it; I use ```dt```, which doesn't collide with any packages on Debian.
