# Before running this role you must modify IP address in "setIp/files/00-installer-config.yaml"
ansible-playbook -i inventory.yml setIp.yml --limit 'machine' --tags "setIp"