chmod +x cf-v4-ddns.sh


./cf-v4-ddns.sh


(crontab -l 2>/dev/null; echo "*/2 * * * * /root/cf-v4-ddns.sh -f true >/dev/null 2>&1") | crontab -
