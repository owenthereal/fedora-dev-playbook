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
