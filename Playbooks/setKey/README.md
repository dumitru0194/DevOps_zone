# To add public key to the server add key in "setKey/files" and add path to key in "defaults/main.yml" the run command form bellow
  ansible-playbook -i inventory.yml setKey.yml --limit 'machine' --tags "setKey"

# To disable password auth on server run next role tag:
ansible-playbook -i inventory.yml setKey.yml --limit 'machine' --tags "authPass, authPassDisable"

# To enable passwrod auth on server run this one:
ansible-playbook -i inventory.yml setKey.yml --limit 'machine' --tags "authPass, authPassEnable"