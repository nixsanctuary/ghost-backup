# ghost-backup
Easy systemd backup service using rclone and storj.io

## How to install
```
cp backup.service backup.timer /etc/systemd/system/
systemctl enable backup.timer
systemctl daemon-reload && systemctl daemon-reexec
```
