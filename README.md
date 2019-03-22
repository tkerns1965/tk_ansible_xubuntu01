# tk_ansible_xubuntu01

For use on bare Xubuntu 18.04.2 Desktop

1. sudo apt-add-repository -y ppa:ansible/ansible
2. sudo apt install -y ansible git python-pexpect
3. git clone https://github.com/tkerns1965/tk_ansible_xubuntu01.git
4. cd tk_ansible_xubuntu01/
5. cp roles/xubuntu01/vars/private.yml.sample roles/xubuntu01/vars/private.yml
6. nano roles/xubuntu01/vars/private.yml
7. ansible-playbook -K xubuntu01.yml
