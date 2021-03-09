Update your dynu DNS records. It supports IPv4 and IPv6.
Stepts:
* Clone the repository
git clone https://github.com/koko004/dynu-update-script && cd dynu-update-script && chmod 700 update.sh
* Edit the credentials.conf
* Edit the main.conf and replace the domain.
* run it via cron
   crontab -e 
   */5 * * * * ~/dynu-update-script/update.sh


