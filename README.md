# phpcc
Commandline PHP 5.6 to 7.2 compatibility checker. Reads all php files recursively and checks for possible compatibility and deprecation issues.

## Mind you! 
This is in no way a full test on all issues when upgrading a PHP project. This script is meant to be a good helper in identifying attention points. 

### Installation:

Put the file in `/usr/local/bin` and make executable (`chmod +x /usr/local/bin/phpcc`)

(and check the script before you execute. I just might format your drive!)

### Usage:
```
phpcc {directory}
```

### Options:
```
--exclude="{directory name}"
```
