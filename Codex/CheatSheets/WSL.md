**In order to install WSL2 (Windows Subsistem for Linux 2, now it's personal) it is necessary to have at least Windows 10**

# Installation

There are two ways to install WSL:
```
1 > Go the the Microsoft Store and search the desired Linux distriburion (Ubuntu recommended), that's ALL!

2 > Via commands:
  a > Open PowerShell
  b > Type:
    wsl --install -d <DistributionName>                   //Or simply wsl --install (installs Ubuntu by default)
```
### **Restart Computer and open the Linux distribution installed**

---------------------------------------------------------------------

# Usage
```
1 > Once you open WSL:
  a > Create a user, name and password (don't overcomplicate your password, you'll be typing it A LOT). Now you can start!
```
```
2 > Most common commands (Debain/Ubuntu based distros):
  a > sudo apt update                                     //Updates your package list
  b > sudo apt upgrade                                    //Upgrades all available packages, basically updates your computer
//Run the two above every now and then to ensure everything is up to date, for security and productivity, also run them as soon as you install Linux!
  c > sudo apt install [package name]                     //Change [package name] with the name of the package you desire to install
  d > sudo apt remove [package name]                      //Removes a package
  e > cd [directory]                                      //Moves to specified directory/folder (e.g. Downloads, Desktop...)
  f > ls                                                  //Lists the directories and files inside the current directory
  g > rm -r [directory/file name]                         //Removes the desired directory 
  h > cp [directory/file source name] [destination]       //Copies a package or file from an origin to a destination directory
  i > mv [source] [destination]                           //Moves a file/directory into a destination directory. Also used to change the name of files or directories
```
```
3 > Most common commands (Arch Linux based distros):
//If this is your first Linux distro go back before it's too late xD
  a > sudo pacman -Syu                                    //Equivalent of "sudo apt update" and "sudo apt upgrade" in  a single command 
  b > sudo pacman -S [package name]                       //Install a package
  c > sudo pacman -Rns [package name]                     //Remove a package along with all dependencies
  d > The rest should be the same/quite similar to Ubuntu/Debian distros
```
---------------------------------------------------------------------

# Comments
```
Hybris > If you're here I guess you want to program every now and then. I strongly suggest installing NeoVim. For more information check the NeoVim CheatSheet!

Hybris > If you need more information about some package/command type: [command] --help , virtually all of them support this functionality.
```


