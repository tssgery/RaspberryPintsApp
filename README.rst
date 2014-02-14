Raspberry Pints
=============================================

`Raspberry Pints`_ is a digital signage version of the common 
chalkboard-based taplist. Based on the kegerface/kegerface git.

This appliance includes all the standard features in `TurnKey LAMP`_,
and on top of that:

- Raspberry Pints configurations:

    - Installed from git source code to /var/RaspberryPints and 
      linked to /var/www

- `PHPMyAdmin`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- All secrets will be regenerated during installation / firstboot
  (security).
- Webmin modules for configuring Apache2, PHP, and MySQL.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL, phpMyAdmin: username **root**
-  RaspberryPints: username and password configured during setup 


.. _RaspberryPints: http://www.raspberrypints.com
.. _TurnKey LAMP: http://www.turnkeylinux.org/lamp
.. _PHPMyAdmin: http://www.phpmyadmin.net

