# bind-ds-temporary
Bind Synology DSM 7 Download Station temporary folder somewhere to access it with File Station

# Installation
Just edit bind-ds-temporary.service with folder you want (/volume1/pri/temporary in my case), copy it to /etc/systemd/system/ and enable/start service with command `systemctl enable bind-ds-temporary.service` and `systemctl start bind-ds-temporary.service`
