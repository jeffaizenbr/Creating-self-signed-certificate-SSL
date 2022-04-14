# Creating-self-signed-certificate-SSL


## Generate

```bash
openssl req -x509 -sha256 -newkey rsa:2048 -keyout certificate.key -out certificate.crt -days 7500 -nodes
```

## verify expiration date

```bash
openssl x509 -enddate -noout -in
```
