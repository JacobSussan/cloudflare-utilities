# Cloudflare DNS

1) Edit file to add your email, auth_key, etc
2) Add the following to your crontab (will run every 5 minutes)

``` */5 * * * * /path/to/ddns_update_dns_to_current_ip.sh ```
