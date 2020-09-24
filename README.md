1. Install Ansible:

```
sudo dnf update
sudo dnf install python3-devel
# Can't install Ansible with dnf due to https://github.com/ansible/ansible-runner/issues/54#issuecomment-516400702
pip3 install --user ansible
pip3 install --user psutil 
```

2. Install Anisble [community.general collection](https://docs.ansible.com/ansible/latest/collections/community/general/dconf_module.html#dconf-module)

```
~/.local/bin/ansible-galaxy collection install community.general
```

3. Run playbook

```
~/.local/bin/ansible-playbook -K setup.yml
```

4. Install Oh My Zsh

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

5. Install space-vim

```
bash <(curl -fsSL https://raw.githubusercontent.com/liuchengxu/space-vim/master/install.sh)
```

6. Configure Caplock as Ctrl: https://unix.stackexchange.com/a/253497
