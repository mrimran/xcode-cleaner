# xcode-cleaner
The script cleans the huge extra space occupied by XCode's cache, simulator devices and archives. 
Please note that after this next time when you try to build via xcode, you should login again. 

**_Using this script I was able to reclaim around 60GB of space._**

## Important Notes
Please also note that after running this, all of your simulators, archives and caches would be deleted. 
So if you are running out of space due to mobile development, this is a must have script, which you can run every few months.

This solution is for Linux, Unix and Mac. I don't know if its going to work on Windows, but for windows the same technique can be used.

## Usage
```
chmod +x ./xcode-cleaner.sh
./xcode-cleaner.sh
```
