Wordpress ansible playbook
--------------------------

1. Install ansible
2. Edit `hosts.ini`
3. Set mysql password and wordpress keys and salts in `install-wp.yml` file in vars section.
4. Run ``ansible-playbook -i hosts.ini install-wp.yml``