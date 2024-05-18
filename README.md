# by telegram @ecintt




### 1 ) archlinux : SCRIPTS 

```
pacman -Sy git 
```
```
git clone https://github.com/ecint/archinst.git
```
```
cd archinstall && chmod +x archinstall && ./archinstall
```



### 2 ) Install Hyprland scripts

```
git clone --depth 1 https://github.com/prasanthrangan/hyprdots ~/HyDE
```
```
cd ~/HyDE/Scripts
```
```
./install.sh 
```



### 3 ) Install Nvidia drivers
```
nvidia nvidia-utils lib32-nvidia-utils nvidia-settings
```


### 4 ) Installing fonts

```
sudo pacman -Syu extra/ttf-nerd-fonts-symbols
```
```
sudo pacman -Syu --needed noto-fonts noto-fonts-cjk noto-fonts-emoji ttf-dejavu ttf-liberation
```

### 5) Removes noise from the microphone

```
yay -S noisetorch-git
```
