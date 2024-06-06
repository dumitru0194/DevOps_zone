# Task adduser
ansible-playbook -i inventory.yml adduser.yml --limit 'machine' --tags "adduser" -e "user_name='TheUser'" -e "user_pass='ThePassword'"
