1. Create a fresh, Private repository
1. Clone the repository
1. Create new Arduino sketch
1. Add the .ino files
1. Ignore project files
 
 The easiest method is to copy the contents of this .gitignore file into your repository:
 
 https://github.com/WPIRoboticsEngineering/RBE2001_template/blob/master/.gitignore
 
 At the very least you need these lines: 

```
.metadata
core/
libraries/
sloeber.ino.cpp
bin/
tmp/
Release/
local.properties
.settings/
.project
.cproject
```


1. Commit .ino and .gitignore files
1. Add any new files created to index
1. Commit and push changes

