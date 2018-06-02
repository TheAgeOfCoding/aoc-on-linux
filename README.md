# Age of Conquerors on Linux
## Install HD
### Install Play On Linux
### Install Steam inside Play on Linux
### Bypass Launcher
Go to the game folder (right click and go "open applications directory" then navigate to /steamapps/common/age2HD/ ). 
Renamed the Launcher.exe to someting else. 
Then make a copy of the AoK HD.exe and name it Launcher.exe. 
## Install Voobly
First install [the compatibility patch](https://www.memberplus.net/) and then create an account on [voobly.com](https://www.voobly.com/) and install voobly.
### Make voobly links work in your browser
Install mimeo and xdg-utils-mimeo. Then open ~/.config/mimeo/associations.txt
and add

```
/usr/share/playonlinux/playonlinux --run \"voobly\" %u
  ^voobly://
```
now you can open voobly links right in your linux browser.
