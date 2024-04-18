# Bash Scripting


### .bash_profile 
It runs as soon as you login. All the environment variables are enabled once you login.

### .bashrc
It runs as soon as you open a new terminal window.

### .bash_history 
Shows the history of commands you have typed so far. It can be modified to
1. Not show duplicate commands
2. Not show ignored commands (ignorespace)

### Variables
hamza="hamza sherazi"

echo "My name is $hamza"

### Arrays
```
#!/bin/bash

# simple script showing arrays in work

names=(hamza saad shaheer)

echo ${names[0]}        # this will output hamza
echo ${names[1]}        # this will output saad
echo ${names[2]}        # this will output shaheer


# you can find length of an array using the ${#array[@]} syntax

echo ${#names[@]}       # this will output 3
```



