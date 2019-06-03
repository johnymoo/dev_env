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

### Auto Dark Mode (for Windows 10 >= 1809)

https://github.com/Armin2208/Windows-Auto-Night-Mode/releases

## Software

1. Spacesniffer: view the disk space usage in details

http://www.uderzo.it/main_products/space_sniffer/download.html

2. Snipaste: screenshot & annotation

https://www.microsoft.com/zh-cn/p/snipaste/9p1wxpkb68kx

3. Visual Studio Code: free code editor from Microsoft

https://code.visualstudio.com/

4. Wox: Alfred in Windows

http://www.getwox.com/
tips: https://sspai.com/post/33460
* Wox 也可以记住复制过的内容并可随时调用，只需要安装 ClipBoard History 插件即可实现，触发关键词「cb」，安装命令：
```
wpm install Clipboard History
```

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

9. Xmeters: free monitoring toolkit

https://entropy6.com/xmeters/download/

10. SumatraPDF: free pdf viewer (also support epub, mobi and etc.)

https://www.sumatrapdfreader.org/download-free-pdf-viewer.html

11. WinSize: windows management

https://github.com/dmscode/WinSize/releases/tag/v3.0.3
