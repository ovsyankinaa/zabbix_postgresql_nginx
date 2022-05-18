# zabbix_postgresql_nginx
zabbix+postgresql+nginx

1. To start a stack type the command "docker-compose -f zabbix_stack.yml up -d"
2. To stop a stack type the command "docker-compose -f zabbix_stack.yml down"
3. The "certs" directory contains ssl certificates.
4. The "sql_data/data" directory is used for store postresql databases.
5. The postgres_pass file contains password for access to PostgreSQL server(for postgres user by default).
6. After the stack is running, you can use the web frontend at https://localhost.
7. The default credential to access to Zabbix through web interface - user:Admin, password:zabbix
8. The port 10051 for active checks is exposed to host.
