# ansible

1. root@ubuntu:/home/sergey/netology/ansible/playbook# cat group_vars/all/examp.yml 
---
  some_fact: 'all default fact'

2. root@ubuntu:/home/sergey/netology/ansible/playbook# ansible-playbook site.yml -i inventory/test.yml

3. ansible-vault encrypt

4. ansible-vault decrypt

5. ansible-vault view

6. ansible-playbook site.yml -i inventory/prod.yml --ask-vault-pass

7. ansible_connection=winrm

8. ansible-doc -t connection ssh

9. - remote_user
