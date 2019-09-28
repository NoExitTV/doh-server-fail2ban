# doh-server-fail2ban
All necessary files for running fail2ban with m13253's high performance dns-over-https server

## Install instructions
Install fail2ban
Add the [doh-filter]-jail to /etc/fail2ban/jail.local
Add the doh-filter.conf file to /etc/fail2ban/filter.d/
restart fail2ban: sudo systemctl restart fail2ban
View the doh-filter-jail status with: sudo fail2ban-client status doh-filter
Enjoy!