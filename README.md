# USAGE

```
NAME
    git-mergepoint - show merge commit of spefified commit

    With this, you can see what pull-request merged the spefified commit.

SYNOPSIS
      $ git mergepoint [-v] <commit>

OPTIONS
      --verbose, -v      show merge commit in detail
      --help,    -h      show this message
      --man,     -m      full documentaion
```

# INSTALL

Clone this repository, and Set $PATH.

```
$ git clone https://github.com/kuwa0224/git-mergepoint
$ export PATH=`pwd`/git-mergepoint:$PATH
```

# Todo

- In big repository, too slow...
