# Lab5

## Commands Executed

### Display the Kernel Version on DB Servers

```shell
# Use Ansible to display the Kernel version on DB servers
ansible db -m shell -a "uname -r"


# Use Ansible to copy index.html to Web Servers
ansible web -m ansible.builtin.copy -a "src=index.html dest=/var/www/html/index.html"
