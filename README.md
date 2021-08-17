# Discord Webpage Status Webhook

Create home folder your status.sh file

Then give premission chmod u+x and then go edit crontab, to make sendig automatic.

Add crontab -e . My automatic is every 12 hours.
```
0 */12 * * * /root/aarmaa_status.sh
0 */12 * * * /root/siimleaks_status.sh
```
