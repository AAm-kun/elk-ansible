Install ansible in your pc.
- You can follow this [documentation](https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html)
- Disable host_key_checking to make your life easier(optional)
- Clone the git repo
  
  ```bash git clone https://github.com/AAm-kun/elk-ansible.git```
- Edit the /vars/main.yml
- Edit the /host/hosts.yml
- Make sure all the LXC/VM are reachable from the machine you are running ansbile script
- Run the ansible script
  
  ```bash $ ansible-playbook –i path/hosts/hosts.yml path/playbook/play.yml```
