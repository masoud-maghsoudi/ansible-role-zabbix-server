# ansible-role-zabbix-server

This ansible role helps to install Zabbix Server on different Linux distributions. based on helps and guideline provided in [Zabbix](https://www.zabbix.com/download) official website, I developed an ansible role which automates the package and prequisities installation required to run a brand new Zabbix Server.

## Example Playbook

It is recommended not to pass any variable to role, instead you can modify package versions in roles/{{ role_name }}/defaults/main.yml with respesct to [zabbix](https://www.zabbix.com/download) official website.

    - hosts: new-servers
      roles:
         - zabbix_server_apache_mysql
         - ...

## License

MIT

## Author Information

| Author | Masoud Maghsoudi                      |
| ------ | ------------------------------------- |
| Email  | masoud_maghsopudi@yahoo.com           |
| Github | <https://github.com/masoud-maghsoudi> |
