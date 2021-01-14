# wordpress-with-postgresql-and-nginx
1. Edit roles/defaults/main.yaml
2. Optional edit config in role/templates
3. Run ansible-playbook playbook/wordpress.yaml

If you have postgresql, run ansible with tags
ansible-playbook playbook/wordpress.yaml --tags "create_db,create_user,grant"
