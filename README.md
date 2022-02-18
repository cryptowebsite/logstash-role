Kibana role
=========

Роль для установки logstash на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

А также для обновления и настройки стека ELK

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name    | Default | Description                                                         |
|------------------|----------|---------------------------------------------------------------------|
| logstash_version | "7.14.0" | Параметр, который определяет какой версии logstash будет установлен |

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: logstash-role }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
