# create tool to verify Emails

## Description
Make simple [mail-tester](https://www.mail-tester.com/).

## Tech
You need to run SMTP server (MTA agent), that will accept incoming mails.
You need to run web server, which will register temporary email box, that will be attached to exact web session.
You need to parse email headers, to validate
- RDNS (reverse dns of sender ip matches sending domain)
- [SPF](https://ru.wikipedia.org/wiki/Sender_Policy_Framework)
- [DKIM](https://ru.wikipedia.org/wiki/DomainKeys_Identified_Mail)
- [DMARC](https://ru.wikipedia.org/wiki/DMARC)

## Gotchas
You need to run MTA, which is impossible to do on serverless env. It should be VPS or VDS.
