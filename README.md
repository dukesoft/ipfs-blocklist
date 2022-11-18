# ipfs-blocklist
Automated blocking content on your Saturn / IPFS nodes

### What
This is a simple & short cronjob to automatically update the blocklist within your Saturn L1 node
(https://github.com/filecoin-saturn/L1-node)

### How
Just add the .cron file in your cronjob directory or add the line in your crontab. It has to run as
the root user if you're running Docker as root.

### Updates
This is a quick and dirty hack to quickly block some content from being served by your Saturn node. 
This is no where near complete, or quick, or fool-proof. We need to work out a better way of identifying,
marking and blocking content. 
