# Regex - regular expression notes


## Notes

```bash
# go to root
cd /
```

- tail -> outputs the end of a file

use `grep -E` for regex search

```bash 
# always use single quote
grep -E 'root' passwd

# character class [] and quantifier + 
head passwd | grep -E '^[a-z]+'

# caret ^ outside of character class [] means start with
# caret ^inside of character class [] means negation
head passwd | grep -E '[^a-z]+'

```


### /etc

directory for system config files -> applies to all users in the system

ex: 
- `/etc/password` contains info about users
