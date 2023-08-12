# lazy-server-setup

## ansible control node setup

```bash
pipx install --include-deps ansible
cd ~/.ansible/
ansible-config init --disabled > ansible.cfg
echo 'export ANSIBLE_CONFIG="$HOME/.ansible/"' >> ~/.zshrc
```

- [Ansible Configuration Settings — Ansible Documentation](https://docs.ansible.com/ansible/latest/reference_appendices/config.html)
- [Building an inventory — Ansible Documentation](https://docs.ansible.com/ansible/latest/getting_started/get_started_inventory.html#get-started-inventory)
- [Creating a playbook — Ansible Documentation](https://docs.ansible.com/ansible/latest/getting_started/get_started_playbook.html)

## links

- [The Reluctant Sysadmin's Guide to Securing a Linux Server](https://pboyd.io/posts/securing-a-linux-vm/)
- [pboyd/initscripts](https://github.com/pboyd/initscripts/tree/master)
- [Vim Commands Cheat Sheet {Downloadable PDF Included}](https://phoenixnap.com/kb/vim-commands-cheat-sheet)
- [Getting started with Ansible — Ansible Documentation](https://docs.ansible.com/ansible/latest/getting_started/index.html)

## links - 20230812

- [Getting started with Ansible — Ansible Documentation](https://docs.ansible.com/ansible/latest/getting_started/index.html)
- [How to Use Ansible to Install and Set Up Docker on Ubuntu 20.04 | DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-use-ansible-to-install-and-set-up-docker-on-ubuntu-20-04)
- [The Reluctant Sysadmin's Guide to Securing a Linux Server](https://pboyd.io/posts/securing-a-linux-vm/)
- [Vim Commands Cheat Sheet {Downloadable PDF Included}](https://phoenixnap.com/kb/vim-commands-cheat-sheet)
