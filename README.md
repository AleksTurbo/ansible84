# Разворачиваем связку Vector+ClickHouse+lighthouse(NGINX) с применением roles

## HomeWork for NETOLOGY Course. 
### Chapt 8.4

Используем роли для ansible:

- name: ansible-clickhouse
  src: https://github.com/AlexeySetevoi/ansible-clickhouse.git

- name: vector_role
  src: https://github.com/AleksTurbo/vector-role.git

- name: lighthouse_role
  src: https://github.com/AleksTurbo/lighthouse-role.git
