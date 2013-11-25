# Open SSH

## Creating .SSH Directory

Run the following commands

- mkdir ~/.ssh
- chmod 700 ~/.ssh
- touch ~/.ssh/authorized_keys
- chmod 600 ~/.ssh/authorized_keys

## Disable Username and Password Logins

- Edit ````/etc/ssh/sshd_config```` to set ````PasswordAuthentication```` and ````UsePAM```` to ````no````
- Restart the service ````ssh````

## References

1. http://www.howtoforge.com/ssh_key_based_logins_putty
