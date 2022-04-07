# SSL generator

## Description
Create tool for SSL generation, supporting both CSR and ACMEv2 LetsEncrypt DNS.

## Tech
In common there is 2 cases
- General case (create CSR, download CSR and Private Key)
- LetsEncrypt DNS challenge (wildcard support)

[What is CSR](https://www.globalsign.com/en/blog/what-is-a-certificate-signing-request-csr)
We should support one domain, multiple domains, wildcard certificates.

[DNS Challenge](https://letsencrypt.org/docs/challenge-types/#dns-01-challenge)

[Example of existing app](https://punchsalad.com/ssl-certificate-generator/)

[Explanation manual](https://punchsalad.com/ssl-certificate/install-lets-encrypt-godaddy/)

## Gotchas
Making tests for DNS challenge require modifying DNS by API, check CloudFlare (they have good api)
