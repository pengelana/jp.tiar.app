# jp.tiar.app

Public DNS Server in Japan.

## Features
- [x] No Censorship
- [x] DNS 0x20
- [x] DNSSEC Validation
- [x] No EDNS Client Subnet (ECS)
- [x] No logs
- [x] Free

## Table of Contents

* [Features](#features)
* [DNS](#features)
* [DNSCrypt](#dnscrypt)
* [DoH (DNS-over-HTTPS)](#doh-dns-over-https)
* [DoT (DNS-over-TLS)](#dot-dns-over-tls)

## DNS

### IPv4

 `172.104.93.80 port 53 or port 5003`

### IPv6

 `[2400:8902::f03c:91ff:feda:c514] port 53 or port 5003`

## DNSCrypt

### IPv4:

`sdns://AQcAAAAAAAAAEjE3Mi4xMDQuOTMuODA6MTQ0MyAyuHY-8b9lNqHeahPAzW9IoXnjiLaZpTeNbVs8TN9UUxsyLmRuc2NyeXB0LWNlcnQuanAudGlhci5hcHA`

### IPv6:

`sdns://AQcAAAAAAAAAJVsyNDAwOjg5MDI6OmYwM2M6OTFmZjpmZWRhOmM1MTRdOjE0NDMgMrh2PvG_ZTah3moTwM1vSKF544i2maU3jW1bPEzfVFMbMi5kbnNjcnlwdC1jZXJ0LmpwLnRpYXIuYXBw`

## DoH (DNS-over-HTTPS)

`https://jp.tiarap.org/dns-query`

`https://jp.tiar.app/dns-query`

### IPv4 (jp.tiarap.org)

`sdns://AgcAAAAAAAAAAAANanAudGlhcmFwLm9yZwovZG5zLXF1ZXJ5`

### IPv4 (jp.tiar.app)

`sdns://AgcAAAAAAAAADTE3Mi4xMDQuOTMuODCgMob_ZaZfrzIIXuoTiMNzi6fjeHPJBszjxKKLTMKliYigRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984gzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYLanAudGlhci5hcHAKL2Rucy1xdWVyeQ`

### IPv6 (jp.tiarap.org)

`sdns://AgcAAAAAAAAAG1syNjA2OjQ3MDA6MzAzNjo6NjgxYjo5NmFhXQANanAudGlhcmFwLm9yZwovZG5zLXF1ZXJ5`

### IPv6 (jp.tiar.app)

`sdns://AQcAAAAAAAAAJVsyNDAwOjg5MDI6OmYwM2M6OTFmZjpmZWRhOmM1MTRdOjE0NDMgMrh2PvG_ZTah3moTwM1vSKF544i2maU3jW1bPEzfVFMbMi5kbnNjcnlwdC1jZXJ0LmpwLnRpYXIuYXBw`

## DoT (DNS-over-TLS)

`jp.tiar.app port 853`

### IPv4

`172.104.93.80 port 853`

### IPv6

`[2400:8902::f03c:91ff:feda:c514] port 853`
