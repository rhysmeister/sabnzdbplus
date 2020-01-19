# sabnzdbplus
Ansible Playbook to setup SabNZDBPlus on Raspian

# Run Playbook

```
ansible-playbook -l all -i inventory.txt sabnzdbplus.yml
```

# TODO

* Setup install for unrar-nonfree

```
sudo apt-get source -b unrar-nonfree
sudo dpkg -i blah....deb
