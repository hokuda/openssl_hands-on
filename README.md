# hands-on-openssl

## objective

Understand how to create your own CA and intermediate CA, sign a server/client certificate, and configure TLS on httpd/JBoss EAP 7.x with them so that you can create a testing environment on Fedora/RHEL.


## prerequisites

Need to install openssl and openssl-perl 1.1.0i or later

```
$ sudo dnf install openssl openssl-perl
```


## start the lab

* [make directories](#make-directories)
* [create CA](#create-ca)
* [create intermediate CA](#create-intermediate-ca)



### make directories

* make working directories

```
$ mkdir -p openssl/rootca
$ mkdir openssl/subca
```


### create CA

* cd openssl

```
$ cd openssl
```

* copy CA.pl

```
$ cp /usr/bin/CA.pl rootca.pl
```




### create intermediate CA





### hash を sha256 に


### RSA を ECDSA に
