### ssh-tunnel@.service

Copy to /etc/systemd/system.
Create a configuration file e.g. /etc/default/ssh-tunnel@foobar

```
REMOTE_HOST=foobar
REMOTE_PORT=22
REMOTE_USER=foo
LOCAL_PORT=20022
KEY_FILE=/home/bar/.ssh/id_rsa
```

Start the service: `systemctl start ssh-tunnel@foobar.service`
