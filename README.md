# ansible-phpMyAdmin
phpMyAdmin for administering databases via a graphical user interface. 

Cento 5,6,7
eg of execution: ansible-playbook main.yml -t "install-phpMyAdmin" --extra-vars '{"phpMyadmin_host":"localhost","phpMyAdmin_allow_ip":82.0.62.108}' -k -i "162.13.41.37," -c paramiko

Ubuntu 16,18
eg of execution: ansible-playbook main.yml -t "install-phpMyAdmin" --extra-vars '{"phpMyadmin_host":"localhost"}' -k -i "162.13.41.37," -c paramiko

Predefined Variables in group_vars


