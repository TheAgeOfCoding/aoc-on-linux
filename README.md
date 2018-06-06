# Age of Conquerors on Linux
## Install HD
- Install Play On Linux
- Install Steam inside Play on Linux
    - Install MS core fonts
    - Add parameters to steam icon `-no-cef-sandbox -no-dwrite`
- Deaktivate the Steam overlay for better performance
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
now you can open voobly links right by clicking the link in your linux browser.

#### Firefox
Go to about:config and right-click. Then click on New->Boolean->network.protocol-handler.expose.voobly -> Value -> false
Upon the next click on a voobly link firefox will ask you to choose a program to open voobly links. Choose xdg-open.
