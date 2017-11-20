# About

Creates the files and directories necessary for the server to operate as a Certificate Authority

## Defaults

There are two default variables in this role: 

```
default_days: 3650 # specifies the number of days certs signed by this ca will be valid for
ca_config_path: /etc/pki/ssl/CA  # specifies the path will the CA config files will live 
cert_config_path: /etc/pki/tls/certs # path to certificates
key_config_path: /etc/pki/tls/private # path to the server key
```