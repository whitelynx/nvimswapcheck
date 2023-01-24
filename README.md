nvimswapcheck
=============

```
Usage: nvimswapcheck [OPTIONS]

Options:
 -h    Show this help message, and exit
 -m    Only match modified files
 -M    Only match unmodified files
 -r    Only match files owned by running instances of nvim
 -R    Only match files owned by dead instances of nvim
 -o    Only display filenames
 -O    Show detailed file information
```


Examples
--------

Removing swap files from dead instances of (n)vim that have no modifications:
```
rm -v $(nvimswapcheck -MRo)
```
