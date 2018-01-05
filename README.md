# Mysql Ansible Role

Install Mysql Role for Debian/Ubuntu Linux Servers

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (/vars/main.yml) :

    mysql_packages
    mysql_root_password

## Dependencies

None

## Example Playbook

    - hosts: servers
      become: yes
      roles:
        - ansible.mysql.role

## License

MIT

## Author Information

This role was created in 2018 by Moula Anis, System and Network Administrator.
