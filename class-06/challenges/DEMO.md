# Challenge - Show Listening Ports

## Demo Code

Netcat is a command-line tool that can scan a single port or a port range. Netcat is invoked with `nc` command.

```bash
#!/bin/bash

# Script:                       
# Author:                       
# Date of latest revision:      
# Purpose:     

# Scan localhost for port 22
nc -z -v 127.0.0.1 22
```

To read a user input into a variable, try this:

```bash
#!/bin/bash

# Main
echo "Hello, what is your name?"
read name
echo "Nice to meet you" $name 
```
