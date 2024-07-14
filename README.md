# 🚀 Setup Script

Ez a `setup.sh` script frissíti a rendszert és telepít néhány hasznos alkalmazást és eszközt. A következő lépéseket tartalmazza:

1. 🛠️ Rendszer frissítése és frissítése.
2. 📦 Hasznos alkalmazások és eszközök telepítése:
    - git
    - curl
    - vim
    - zsh
    - htop
    - nvm
    - kitty
    - inkscape
    - vlc
    - obs-studio
3. 💬 Discord telepítése snap csomagkezelő segítségével.

## 💻 Használat

1. Győződj meg róla, hogy a script futtatható:
    ```bash
    chmod +x setup.sh
    ```

2. Futtasd a scriptet:
    ```bash
    ./setup.sh
    ```

## 📜 Tartalom

```bash
#!/bin/bash
sudo apt update && sudo apt upgrade -y
sudo apt install git curl vim zsh htop nvm kitty inkscape vlc obs-studio -y
sudo snap install discord
