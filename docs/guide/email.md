# Email account

You can access your emails by

1. Using the [webmail]()
2. Using your preferred email client

To setup your email client, you will need to fill these informations.

IMAP server for incoming messages :
```yaml
imap server:    imap.dalembert.upmc.fr
encryption:     SSL/TLS
port:           993
login:          Your lab credentials (jane.doe@dalembert.upmc.fr without domain)
```

SMTPS server for outgoing messages :
```yaml
SMTPS server:   smtps.sorbonne-universite.fr
encryption:     SSL/TLS
port:           465
login:          Your Sorbonne University credentials
```

!!! warning "Important"
    Outgoing mail requires Sorbonne credentials - messages won't send if you use lab credentials