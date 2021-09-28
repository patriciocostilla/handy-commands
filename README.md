# handy-commands
Linux handy commands

Remove all `<folder>` folders in working tree: 

```
find . -name <folder> | xargs rm -R
```

View last log in date for all users

```
lastlog
```

Dump characters in file

```
hexdump -C <file>
```

Display the list of all the users logged in and out since the file /var/log/wtmp was created

```
last
```

List system information logs in wtmp (for example system down and reboot)

```
last -x 
```
