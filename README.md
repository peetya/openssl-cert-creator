# openssl-cert-creator

- create a root authority cert

`./create_root_cert_and_key.sh`

- create a wildcard cert for mysite.com

`./create_certificate_for_domain.sh mysite.com`

- or create a cert for www.mysite.com, no wildcards

`./create_certificate_for_domain.sh www.mysite.com www.mysite.com`
