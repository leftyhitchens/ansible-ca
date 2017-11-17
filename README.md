# About

Creates the files and directories necessary for the server to operate as a Certificate Authority

## Defaults

There are two default variables in this role: 

```
default_days: 3650 # specifies the number of days certs signed by this ca will be valid for

config_path: /etc/consul.d/ssl  # specifies the path will the CA config files will live 
```