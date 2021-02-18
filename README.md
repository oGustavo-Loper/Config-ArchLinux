![Logo do Arch Linux](https://upload.wikimedia.org/wikipedia/commons/thumb/7/74/Arch_Linux_logo.svg/1280px-Arch_Linux_logo.svg.png "Logo do Arch-Linux")


# Configuração do Arch Linux, E download de alguns aplicativos utilizados.

## Download GIT

[git_scm](https://git-scm.com/)

```sh
sudo pacman -S git
```

### Testando GIT

#### git --version

## Download YAY.

[wiki.arch-linux](https://aur.archlinux.org/packages/yay/)

```sh
sudo pacman -S base-devel
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```
### Testando YAY

#### yay --version

## Download AnyDesk

[AnyDesk](https://anydesk.com/pt/downloads/linux)

```sh
sudo pacman -S anydesk
### OU
yay -S anydesk
```

### Testando AnyDesk

#### anydesk --version

## Download node.js

[nodejs.org](https://nodejs.org)

```sh
sudo pacman -S nodejs npm
```

### Testando node.js

#### node --version


## Desabilitando o IPV6

#### No terminal digitar 

```sh
sudo vim /etc/default/grub
```

#### E na linha do:

```sh
GRUB_CMDLINE_LINUX_DEFAULT="loglevel=3"

Adicionar  ipv6.disable=1: Ficando

GRUB_CMDLINE_LINUX_DEFAULT="loglevel=3 ipv6.disable=1"

```