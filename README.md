Deployement Stage
----

Modify in Ubuntu Server: For Automating Script
--
it runs backend in background when instance starts (backend.service)

sudo nano /etc/systemd/system/backend.service

sudo nano /etc/systemd/system/auto-update.service

sudo nano /etc/systemd/system/apt-update-upgrade.service

Extra: enable socket configuration
--
sudo nano /etc/mysql/mysql.conf.d/mysqld.cnf
uncomment socket


