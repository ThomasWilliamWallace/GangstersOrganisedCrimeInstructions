# _Gangsters: Organised Crime_ Instructions
Complete instructions to run an ISO of the 1998 game _Gangsters: Organised Crime_ on a modern computer.

## Instructions for Windows 10:
1. Mount the gangsters ISO
2. Install by running SETUP.EXE (don't change any compatibility settings here)
3. Restart your computer, and make sure the Gangsters disc is still mounted
4. Copy the elishacloud [patch files](https://github.com/elishacloud/dxwrapper/wiki/Gangsters-Organized-Crime) into the gangsters.exe folder
5. Install the XPGangPatch from [Sold-out Games](http://www.sold-out.co.uk/soldout/support/gangsters.html)
6. Set the compatibility mode settings
```
'win XP service pack 3',
'Run in 640 x 480 screen resolution'
'Run as administrator'
```
7. Run the Gangsters.exe
8. Wait for screen to go black
9. Ctrl-alt-delete, then choose 'Cancel' from the resulting blue screen menu
10. Wait about 10 seconds, then the Gangsters game should start

## Instructions for Windows 7 and below:
1. Mount the gangsters ISO
2. Install by running SETUP.EXE (don't change any compatibility settings here)
3. Restart your computer, and make sure the Gangsters disc is still mounted
4. Install the XPGangPatch from [Sold-out Games](http://www.sold-out.co.uk/soldout/support/gangsters.html).
5. Set the compatibility mode settings
```
'win XP service pack 3',
'Run in 640 x 480 screen resolution'
'Run as administrator'
```
6. Create a text file in the gangsters.exe folder, name it gangsters.txt
7. Paste in this text:
```
taskkill /f /im explorer.exe
start /w Gangsters.exe
start explorer.exe
```
8. Save, and rename the file to gangsters.bat
9. Create a shortcut to the gangsters.bat, and move the shortcut to your desktop
10. Double click the shortcut to start gangsters.


## Frequent Problems

### "The application was unable to start correctly 0xc0000022" Error:
[Enable DirectPlay](https://www.youtube.com/watch?v=llI1vc1scbw). To do this:
Search for 'Turn windows features on or off' from the start menu
Under 'Legacy Components', enable 'DirectPlay'.

### Cannot initialize CD player error:
Install the XPGangPatch from [Sold-out Games](http://www.sold-out.co.uk/soldout/support/gangsters.html).

### Start Menu has no button text:
Copy the elishacloud [patch files](https://github.com/elishacloud/dxwrapper/wiki/Gangsters-Organized-Crime) into the gangsters.exe folder.

### CD Drive makes too much whirring noise:
Mount an ISO of the disk instead.

### The colours aren't right:
1. Create a text file in the gangsters.exe folder, name it gangsters.txt
2. Paste in this text:
```
taskkill /f /im explorer.exe
start /w Gangsters.exe
start explorer.exe
```
3. Save, and rename the file to gangsters.bat
4. Create a shortcut to the gangsters.bat, and move the shortcut to your desktop
5. Double click the bat file to start gangsters
