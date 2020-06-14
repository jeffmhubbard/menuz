# menuz

```
# select menu from list
$ menuz

# call specific menu
$ menuz <menu>

# select and edit menu files
$ menuz -e
```

```
# menu file
NAME=" Example"
ITEMS=(
  [" Terminal"]="$TERMINAL"
  [" Editor"]="$TERMINAL -e $EDITOR"
  [" Browser"]="$BROWSER"
  [" Email"]="$TERMINAL -e neomutt"
  [" Chat"]="$TERMINAL -e irssi"
)
```
