
# ubuntu setup

Setup for Ubuntu 20.04 LTS

```
sudo apt update
sudo apt install -y ansible
ansible-playbook main.yaml -e "username=$(id -un)" -e "hostname=$(uname -n)" -K
```

## Summary

system update
- [x] dist upgrade

system tools
- [x] neofetch

archiving tools
- [x] unzip
- [x] zip

developer tools
- [x] build-essential
- [x] curl
- [x] git
- [x] jq

ssh
- [x] ssh-keygen

terminal
- [x] zsh
- [x] zsh-antigen
- [x] change shell

dotfiles
- [ ] link dotfiles

tools
- [x] docker
- [x] kubectl
- [x] awscli
- [ ] terraform

languages
- [x] dotnet
- [ ] nodejs / npm / nvm

applications
- [x] google chrome
- [x] vscode
- [ ] unetbootin
- [ ] slack
- [ ] screenshot tool
- [ ] gif recorder tool