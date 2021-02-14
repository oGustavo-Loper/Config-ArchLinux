![Logo do Arch Linux](https://upload.wikimedia.org/wikipedia/commons/thumb/7/74/Arch_Linux_logo.svg/1280px-Arch_Linux_logo.svg.png "Logo do Arch-Linux")


# Configuração do Arch Linux, mais download de aplicativos para quem tiver duvidas.

## Download GIT

[git_scm](https://git-scm.com/)

```sh
sudo pacman -S git
```

### Testando GIT

#### git --version

## Download YAY.

[wiki.arch-linux](https://aur.archlinux.org/packages/yay/)

## Instalação

```sh
sudo pacman -S base-devel
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```
### Testando YAY

#### yay --version
