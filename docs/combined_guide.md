# Welcome to  ∂'Alembert !

We're thrilled to have you join us. This guide is designed to help you get settled in, find the resources you need, and connect with our community.

## Key People & Contacts

*   **Director:** [Pierre-Yves Lagrée](mailto:)
*   **Your Administrative Contact (by team - for ongoing support):**
    *   Olivier Labbey (FCIH)
    *   Catherine Dejancourt (MISES)
    *   Sandrine Bandeira (LAM)
    *   Evelyne Mignon & Célia Sakho (CEPT & MPIA)
    *   *Find them on the 5th floor, corridor 44-54.*
*   **General Administrative Contact:** [Simona Otarasanu](mailto:simona.otarasanu@upmc.fr), corridor 44-54, office 510
*   **[IT Department / Technical Team](mailto:info@dalembert.upmc.fr):** 55-65, room 507/508
*   **[PhD Delegates](mailto:rep-doc@dalembert.upmc.fr):**
    {% for representative in representatives %}
    - [{{representative.name}}](mailto:{{representative.email}}), room {{representative.room}}
    {% endfor %}

## Essential ressources

*   **This PhD Welcome Guide:** You're reading it!
*   **Lab Main Website & Organization Chart:** [www.dalembert.upmc.fr](http://www.dalembert.upmc.fr)
*   **Lab Internal Wiki:** [wiki.dalembert.upmc.fr](http://wiki.dalembert.upmc.fr) (Printer IPs, remote access, etc.)
*   **PhD Student WhatsApp Group:** Ask a current PhD student or your supervisor to add you!# Before you arrive

Remember to fill out [the inscription form](http://inscription.dalembert.upmc.fr/) at least **two weeks before** your arrival. This form helps automatically trigger:

*   Office allocation
*   Access key request
*   LDAP account creation (if you requested an "account on calculation room" – this is needed for lab intranet access).

**Ask your supervisor (N+1) for details needed to complete the form.**# Upon Arrival
During the first few days, you must:

1.  **Sign Your Contract:** Your first official step with your employer.
2.  **Sign your Installation Report** (Procès Verbal d'Installation)
3.  **Register at the Doctoral School (ED SMAER):**
    *   Most PhDs at d'Alembert are part of [ED SMAER](ed391.upmc.fr) (École Doctorale Sciences Mécaniques, Acoustique, Électronique et Robotique de Paris).
    *   Directors: Djimédo Kondo and Faiz Ben Amar.
    *   Secretary: Charlotte Vallin (corridor 45-46, room 205).
4.  **Register at Sorbonne Université:**
    *   After doctoral school registration, register at the university.
    *   Fees: ~380€ (registration) + ~90€ (CVEC).
    *   This provides your student card.# Accounts

You will primarily have two types of accounts:

1. **Lab-managed accounts**: Managed by the IT team at your research lab.
2. **University-managed accounts**: Managed by Sorbonne University.

## D'Alembert lab accounts

### Webmail account
Login of the form `jane.doe@dalembert.upmc.fr`. Allows you to connect to the [lab webmail](https://webmail.dalembert.upmc.fr). Ask the IT team to get one.

!!! note
    You will also receive an email alias in the format `jane.doe@sorbonne-universite.fr`. This isn't a separate email account - it's simply an alias (forwarder) to your lab email. Any messages sent to this address will be automatically forwarded to your primary lab email address.

    If you do not receive this alias automatically, contact Simona.

### Intranet account
Login of the form `jdoe`. Useful to access some intern ressources of the lab (office booking).

## Sorbonne University accounts

You should automatically be assigned an account ID and password upon signing your contract with the university. Check that it works on the [Annuaire UPMC webpage](https://www.annuaire.upmc.fr/).

Each time you want to access a Sorbonne University service, you will need to use this account.

!!! note
    If, like most PhD students at the lab, Sorbonne University is both your employer and your university, you will get two accounts :
    1. A student account, the login being your student ID
    2. An employee account, the login being a username

    Most of the time, the second one is all you need. Every service is accessible via an employee account. The reciprocal is not true# Email account

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
    Outgoing mail requires Sorbonne credentials - messages won't send if you use lab credentials# Internet

## Wired
Only lab computers can connect to the lab network. If you have a new lab computer:

- Find your computer and/or internet hub mac address.
- Send a [mail to the IT department](mailto:info@dalembert.upmc.fr) or go and see them: corridor 55/65, 5th floor, office 507. Ask if your device can be enabled on the lab network.

!!! warning
    Only Linux or Mac OS systems are allowed for wired connections at Jussieu.

## Wireless
Connect to `eduroam` with your Sorbonne University credentials. See [this page](https://cat.eduroam.org) or [this one](https://www.geteduroam.org/download/) for setup.

!!! info
    Some services like Spotify don't work on this network. You can bypass that by using a VPN.# Contacts

- **Access/badge issues**: [Olivier Labbey](mailto:labbey@dalembert.upmc.fr)
- **Office/space issues** (doors, electrical problems): [Olivier Labbey](mailto:labbey@dalembert.upmc.fr) and [Arnaud Antkowiak](mailto:arnaud.antkowiak@upmc.fr)
- **Thesis administrative questions** (equipment purchase, interns): Your manager
- **Thesis-related questions/issues** (supervision, relations with other PhD students): Your [representatives](mailto:rep-doc@dalembert.upmc.fr):
    {% for representative in representatives %}
    - [{{representative.name}}](mailto:{{representative.email}})
    {% endfor %}
- **IT Team** (list) : [IT Team](mailto:info@dalembert.upmc.fr)
- **For any doubts**: [Simona Otarasanu](mailto:simona.otarasanu@sorbonne-universite.fr)# Administrators

Like a lighthouse in the night, your administrator is there to help when you're lost. At ∂'Alembert, there are four who divide the teams:

- [Olivier Labbey](mailto:labbey@dalembert.upmc.fr) - FCIH team
- [Anitha Coridon](mailto:anitha.coridon@sorbonne-universite.fr) - LAM team
- [Catherine Dejancourt](mailto:dejancourt@dalembert.upmc.fr) - MISES team
- [Catherine Dejancourt](mailto:dejancourt@dalembert.upmc.fr) - CEPT and MPIA teams# Room booking

Connect to the lab [room booking service](http://www.dalembert.upmc.fr/grr/week_all.php) with your d'Alembert intranet credentials.# SSH

Create a public/private SSH key pair on your personal computer. Email IT (`info@dalembert.upmc.fr`) with your **public** SSH key, requesting access to lab machines via `vauban.dalembert.upmc.fr` and `chagall.dalembert.upmc.fr`.# Printers

Follow instructions on the [Lab Wiki - Imprimantes](http://wiki.dalembert.upmc.fr/pmwiki/pmwiki.php?n=Dalembert.Imprimantes) for setup.# Webservices

A curated list of webservices.

## D'Alembert services
Managed by the IT team. Use your lab credentials to connect or create a new account when needed.

- :material-cloud: [Nextcloud](https://nextcloud.dalembert.upmc.fr) : cloud collaboration platform
- :material-webcam: [Jitsi](https://meeting.dalembert.upmc.fr) : video conferencing platform
- :material-forum: [Mattermost](https://mm.dalembert.upmc.fr) : team messaging platform
- :material-code-braces: [Gitea](https://git.dalembert.upmc.fr) : Git service platform
- :material-calendar: [GRR](http://www.dalembert.upmc.fr/grr/week_all.php) : office booking platform

## Sorbonne University services
Managed by Sorbonne University. You can check the status of those services [here](https://meteo.fsi.hosted.lip6.fr/status/default).

- [Nextcloud](https://dropsu.sorbonne-universite.fr/) : cloud collaboration platform
- [AmongSU](https://amongsu.sorbonne-universite.fr/) : Element (Discord-like) messaging platform
- [VPN](https://vpn.sorbonne-universite.fr/) : a VPN hosted by SU
- [Jitsi](https://jitsi2.dsi.sorbonne-universite.fr) : video conferencing platform
- [BigBlueButton](https://webinaire.sorbonne-universite.fr) : video conferencing platform
- [Gitlab](https://gitlabsu.sorbonne-universite.fr) : Git service platform

## RENATER services
Services managed by other structures (CNRS), but accessible via your Sorbonne University credentials.

- [Rendez-vous](https://rendez-vous.renater.fr/home/) : video conferencing platform
- [FileSender](https://filesender.renater.fr/) : large file transfer
- [Evento](https://evento.renater.fr/) : events planner
- [PLMLatex](https://plmlatex.math.cnrs.fr) : CNRS-hosted overleaf
- [Mattermost](https://mattermost.math.cnrs.fr/) : team messaging platform
- [CodiMD](https://codimd.math.cnrs.fr/) : real-time collaboration Markdown editor# Transports

## Navigo (public transport)

Sorbonne will reimburse part of your Navigo pass. See [this page](https://intranet.sorbonne-universite.fr/fr/ressources-humaines/remuneration-1/prise-en-charge-frais-de-transport/prise-en-charge-partielle-frais-de-transport.html) for details.

## Eco-mobility (bike, e-scooter, ...)

To encourage the use of more sustainable transportation methods, staff members who choose alternative and eco-friendly modes of transport for their home-to-work commute may be eligible for an annual subsidy of up to €300. See [this page](https://intranet.sorbonne-universite.fr/fr/ressources-humaines/remuneration-1/prise-en-charge-frais-de-transport/forfait-mobilites-durables-2.html) for details.# Crous (University restaurant)

Only available if you have a Sorbonne University or CNRS work contract. Once you have an Annuaire UPMC account:

- Grab a copy of your work contract and your ID card / passport.
- Go to the Crous building. Find the help desk (to your right as you enter).
- (optional) Install the [Izly app](https://www.izly.fr/) on your smartphone and link your account.

!!! info
    **Saint-Cyr Canteen:** Ask Anne Marchal for a badge for the INRA canteen.