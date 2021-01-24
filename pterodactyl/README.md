## Pterodactyl installer:

### File download
``wget https://raw.githubusercontent.com/DoctorWhoFR/InstallScripts/main/pterodactyl/pannel.sh | sh pannel.sh``

### WebServer configuration
``wget https://raw.githubusercontent.com/DoctorWhoFR/InstallScripts/main/pterodactyl/pterodactyl.conf | mv pterodactyl.conf /etc/nginx/sites-available/pterodactyl.conf | sudo ln -s /etc/nginx/sites-available/pterodactyl.conf /etc/nginx/sites-enabled/pterodactyl.conf | systemctl restart nginx  ``

### wings:

``wget https://raw.githubusercontent.com/DoctorWhoFR/InstallScripts/main/pterodactyl/wings.sh | sh wings.sh``
