
# doh-server-fail2ban

All necessary files for running fail2ban with m13253's high performance dns-over-https server that can be found [here](https://github.com/m13253/dns-over-https)

  

## Install instructions

1. Install fail2ban  

2. Add the [doh-filter]-jail to /etc/fail2ban/jail.local  

3. Add the doh-filter.conf file to /etc/fail2ban/filter.d/  

4. restart fail2ban: sudo systemctl restart fail2ban  

5. View the doh-filter-jail status with: sudo fail2ban-client status doh-filter  

Enjoy!  