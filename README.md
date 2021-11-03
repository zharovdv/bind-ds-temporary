# bind-ds-temporary
Bind Synology DSM 7 Download Station temporary folder somewhere to access it with File Station

# Installation
Just edit bind-ds-temporary.service with folder use want (/volume1/pri/temporary in my case) and copy it to /etc/systemd/system/ and enable service with command `systemctl enable bind-ds-temporary.service`
