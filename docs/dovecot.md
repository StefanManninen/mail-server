### Generate a Dovecot password

Interactive (recommended):

```bash
doveadm pw -s SHA512-CRYPT

```

or doveadm pw -s SHA512-CRYPT -p yourpassword

### Generate dh.pem

This will take awhile

```bash
openssl dhparam -out /etc/dovecot/dh.pem 4096
```
