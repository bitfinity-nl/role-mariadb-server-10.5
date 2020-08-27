# role-mariadb-server-10.5
MariaDB Server, with its continual open source innovation,
is a modern relational database that business can count on.


Example Playbook
----------------

    - hosts: mariadb
      become: true

      vars:
        # -- MariaDB server custom settings --
        mariadb_administrative_password : '{{ def_mariadb_pass }}'

      roles:
        - role-mariadb-server-10.5

License
-------

GPLv3

Author Information
------------------

E: info@bitfinity.nl

I: https://www.bitfinity.nl
