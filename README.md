### ssh-tunnel@.service

Create a configuration file e.g. /etc/default/secure-tunnel@foobar

```
TARGET=foobar
LOCAL_ADDR=0.0.0.0
LOCAL_PORT=20022
REMOTE_PORT=22
```

Start the service: `systemctl start ssh-tunnel@foobar.service`
