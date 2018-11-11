Wordpress ansible playbook
--------------------------

1. Install ansible
2. Edit `hosts.ini`
3. Set project name, mysql password and wordpress keys/salts in `install-wp.yml` file in vars section.
4. Run ``ansible-playbook -i hosts.ini install-wp.yml``