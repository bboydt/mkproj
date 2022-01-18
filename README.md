# mkproj
A project generation script for C projects.  

## Note

This was written for MacOS (all hail apple). I believe the only difference from linux is how sed works. To use this with linux, remove ".backup" from line 94 and delete line 95.

## Usage
```bash
# Creates ./Some/Path/YourProjectName
./mkproj.sh YourProjectName ./Some/Path/

# Creates ./YourProjectName
./mkproj.sh YourProjectName
```
