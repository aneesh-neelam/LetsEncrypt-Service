# LetsEncrypt-Service

Renewing and backing up Let's Encrypt SSL certificates


##### Prerequisites

* `/usr/bin/letsencrypt` binary is present (Installation instructions for Ubuntu Xenial [here](https://certbot.eff.org/#ubuntuxenial-apache)). 
* Let's Encrypt SSL is setup already. 


##### Installation

* Extract the files to the respective directories. 
* `# systemctl start letsencrypt.timer`
* `# systemctl enable letsencrypt.timer`

##### TODO

* Backup script to Dropbox
* Add systemd timer and service for backup script (Dependency on letsencrypt.service, or using same timer)

