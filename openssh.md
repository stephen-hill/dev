# Open SSH

## Disable Username and Password Logins

- Edit ````/etc/ssh/sshd_config```` to set ````PasswordAuthentication```` and ````UsePAM```` to ````no````
- Restart the service ````ssh````
