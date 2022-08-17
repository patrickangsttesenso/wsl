# wsl

wsl isntallieren
```powershell
wsl --install
```

wsl updaten
```powershell
wsl --update
```

wsl Linux versionen anzeigen
```powershell
wsl --list --online
```

wsl Linux Version installieren
```powershell
wsl --install -d <DistroName>
```

  
https://www.hanselman.com/blog/how-to-run-linux-gui-apps-on-windows-10-with-wsl-and-wslg
  

## insall Intellij Idea Community

 install the required dependencies
```bash
sudo apt install vim apt-transport-https curl wget software-properties-common
```

add repository
```bash
sudo add-apt-repository ppa:mmk2410/intellij-idea -y
```

install IntelliJ Community Edition
```bash
sudo apt install intellij-idea-community -y
```