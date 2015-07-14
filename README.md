# Ansible Roles

Ansible roles to sync your local folder and provision a server with PHP, Nginx, MariaDB and more.

    roles:
      - { role: base }
      - { role: php-fpm }
      - { role: nginx }
      - { role: composer }
      - { role: mysql }
      - { role: memcached }
      - { role: ufw }
      - { role: fail2ban }
      - { role: logwatch }
      - { role: swapfile }
      - { role: sync }
      - { role: cron }
      - { role: newrelic }
