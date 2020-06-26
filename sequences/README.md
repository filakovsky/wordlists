# Sequences - cheatsheet

the meaning of following characters
```
> PowerShell prompt
$ Bash prompt
# Comment
```

### Output filtering
```
# by rules
> TODO
$ TODO
```


### Numbers
```
# 1 2 3 4 5 6 7 8 9 10
> 1..10
$ seq 1 10
$ echo {1..10} # inline version

# 01 02 03 04 05 06 07 08 09 10
> 1..10 | % tostring 00
$ seq -w 1 10
```

### Ascii characters
```
> TODO
$ echo -e \\x{21..79} | tr " " "\n
```

### Phone numbers
```
# in +420602xxxxxx format
> TODO
$ echo +420602{000000..999999} | tr " " "\n

# in +420-602-xxx-xxx format
> TODO
$ echo 420-602-{000..999}-{000..999} | tr " " "\n
```
