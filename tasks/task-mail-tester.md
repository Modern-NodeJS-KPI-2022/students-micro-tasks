# Mail tester app

## Description
App should implement online tester for different email services (SMTP, POP3, IMAP). 
We should provide UI for settings customization, also output should be well-structured.

## Tech
In common there is 3 protocols that we should support.
- POP3
- SMTP
- IMAP

On backand we should use NodeJS that will make outgoing connection based on user input. 
For example for POP3:
- host: pop.gmail.com
- port: 995
- SSL/TLS/No: SSL
- SMTP login: somemail@gmail.com
- SMTP pass: supersecretpassword

On front-end we should be aware that all user input should be reflected to URL.
It will allow user to copy link and share it with others.

## Gotchas
Handle errors. There could be lots of different errors.

Handle timeouts.

Test coverage - you need pop3/smtp/imap server available for running tests.
Docker will help you.

