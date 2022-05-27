nginx-role
=========

Роль для Ansible 2.10 и новее для установки web-сервера Nginx на CentOS 7. 

Requirements
------------

Роль работает только на дистрибутивах CentOS 7.

Role Variables
--------------

nginx_version - версия устанавливаемого nginx

Dependencies
------------

Иные зависимости не требуются. 

Example Playbook
----------------

Пример использования:

---
- name: Install nginx
  hosts: lighthouse
  roles:
    - nginx-role

License
-------

MIT

Author Information
------------------

[Git](https://github.com/zMaAlz/nginx-role)
