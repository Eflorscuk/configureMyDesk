# Lista de coisas para serem instaladas

## VIM
```sudo apt install vim```

## Chrome =P

### Download:
```wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb```

### Install:
```sudo apt install ./google-chrome-stable_current_amd64.deb```

## Terminator
```sudo apt install terminator```

## Git

### Install
```sudo apt install git-all```

### Config
#### Name
```git config --global user.name "your name"```

#### Mail
```git config --global user.email your mail```

### Editor
```git config --global core.editor vim```

#### SSH config
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

## NVM
### Download
```wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash```

### Node install
```nvm install lts/fermium```

## Intellij
```sudo snap install intellij-idea-ultimate --classic```

## Spotify
```sudo snap install spotify```

## GIMP
```sudo snap install gimp```

## VLC
```sudo snap install vlc```

## Mini Diary
```sudo snap install mini-diary```

## Java
### Update
```sudo apt update```

### Install
```sudo apt install default-jdk```

### Install javac
```sudo apt install default-jdk```

### Managing and Setting Java and JAVA_HOME
https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-20-04

## Android Studio
### Download 
https://developer.android.com/studio?gclid=Cj0KCQjwz7uRBhDRARIsAFqjulmKQEkZTPS_AuSiz35Dtb0tCagTRpxsU5sK_IDh0_CarRA7_4LLvFEaAl3qEALw_wcB&gclsrc=aw.ds

### Unpack
```tar -xvf android-studio-2021.1.1.22-linux.tar.gz```

### Moving Android Studio to usr
```sudo mv ./android-studio /usr/local/```

## Nativescript
https://docs.nativescript.org/environment-setup.html#linux-android

### Install
```npm install -g nativescript```

## Docker / docker-compose

### Install
```sudo apt install docker-compose```

### User not root
```sudo usermod -aG docker $USER```

### Reboot
```systemctl reboot```


