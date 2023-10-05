# ansible-role-zabbix-server

This ansible role helps to install Zabbix Server on different Linux distributions. According to the guidelines provided in [Zabbix](https://www.zabbix.com/download) official website, I developed an ansible role that automates the package and prerequisites installation required to run a brand new Zabbix Server.

## Example Playbook

It is recommended not to pass any variable to the role. instead, you can modify package versions in roles/{{ role_name }}/defaults/main.yml with respect to the information provided on [zabbix](https://www.zabbix.com/download) official website.

    - hosts: new-servers
      roles:
         - zabbix_server_apache_mysql
         - ...

## License

MIT

## Author Information

| Author | Masoud Maghsoudi                      |
| ------ | ------------------------------------- |
| Email  | <masoud_maghsopudi@yahoo.com>         |
| Github | <https://github.com/masoud-maghsoudi> |
