# DDOS_DEFENCE
- It is a simple DDOS defence stratage, it can detect how many TCP connection via a same source IP address and ban it

# User Guide
- 1. chmod 777 ddos_defence.sj
- 2. Run the script every 1 minutes with the command: crontab -e
- 3. Copy this line to the conf: */1 * * * * /root/bin/ddos_defence.sh

# TIPS
- /root/bin/ddos_defence.sh is not the same as yours.
