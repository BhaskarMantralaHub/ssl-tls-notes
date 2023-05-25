****************************************************
# ssl-tls-notes

https://www.youtube.com/watch?v=j9QmMEWmcfo


### Secure Sockets Layer (SSL)

### Transport Layer Security (TLS)

* HTTPS (Secured HTTP Protocol) uses TLS (Encrypted connection) between client and server

### Public Key Infrastructure (PKI)

****************************************************
# CA (Certificate Authority)

### PEM certificate - Privacy Enhanced Mail

* Base 64 ASCII format
* Holds
    > Public Key Information

    > Private Key Information

    > Root certificate

    > Format:

    ```certificate
    BEGIN CERTIFICATE
    //CODE
    END CERTIFICATE
    ```

### PFX / P12 / PKCS12 certificate - Personal Exchange Format

* Microsoft Apps

* PKCS12 - Public Key Cryptography Standard

* Holds
    > Public Key Information

    > Private Key Information

    > Password Protected


### P7B / P7C / P7S / PKCS7 certificate - Public Key Cryptography Standard Version 7

* Java Apps

* Holds
    > Public Key Information only   
### DER - Distinguished Encoding Rules 

* Binary Files format

### CER / CERT / CRT - Canonical Encoding Rules

* Holds
    > Public Key Information

    > Private Key Information