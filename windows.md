# Windows

## Setting

### WSL & Terminal
* Install zsh & oh-my-zsh
```
sudo apt install zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
* Add zsh to startup
vi ~/.bashrc
```
exec zsh
source ~/.zshrc
```
* Install Microsoft Colortest to configure Powershell
https://github.com/Microsoft/console/releases


## Software

1. Spacesniffer: view the disk space usage in details
http://www.uderzo.it/main_products/space_sniffer/download.html

2. Snipaste: screenshot & annotation
https://www.microsoft.com/zh-cn/p/snipaste/9p1wxpkb68kx

3. Visual Studio Code: free code editor from Microsoft
https://code.visualstudio.com/

4. Wox: Alfred in Windows
http://www.getwox.com/

5. Fliqlo: cool screensave for Digital Clock
https://fliqlo.com

6. Just Manager: free Totalcommander
http://justmanager.ru/

7. Draw.io: free diogram software (Electron based for desktop and web based):
draw.io

8. Scoop: package manager in Windows (for non-GUI app management)
```
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```
