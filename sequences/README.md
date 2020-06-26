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
> 1..9
$ seq 1 9
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
