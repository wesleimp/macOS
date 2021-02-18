# macOS

How I setup a new mac

## Install brew
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Install deps
Install Homebre
```sh
git clone https://github.com/wesleimp/macOS.git
cd macOS
brew bundle
```

## Install dotfiles
```sh
git clone https://github.com/wesleimp/.dotfiles.git ~/.dotfiles
cd ~/.dotfiles
./install.sh
```

## Setup SSH

Create a new SSH key or copy the previous one into `~/.ssh`. That should be it.

Also fix perms:

```sh
chmod 0600 ~/.ssh/id_rsa
```

## Reboot
```sh
sudo reboot
```
