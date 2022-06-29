1. Install Ansible:

```
sudo dnf update && dnf install ansible python3-devel

pip3 install --user psutil
```

2. Install Anisble [community.general collection](https://docs.ansible.com/ansible/latest/collections/community/general/dconf_module.html#dconf-module)

```
ansible-galaxy collection install community.general
```

3. Run playbook

```
ansible-playbook -K main.yml
```

4. Configure CAPS as CTRL and Swap WIN & ALT: https://unix.stackexchange.com/a/253497

5. Install Topicons for Dropbox: https://extensions.gnome.org/extension/1031/topicons/
