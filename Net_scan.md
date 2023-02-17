# Dział poświęcony bezpieczeństwu w sieci lokalnej
[![.github/workflows/ci.yaml](https://github.com/pages-themes/hacker/actions/workflows/ci.yaml/badge.svg)](https://github.com/pages-themes/hacker/actions/workflows/ci.yaml) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-hacker.svg)]( https://github.com/bartdurak/char)

*Kali Linux  [idealny system do pracy w LAN](https://www.kali.org), or even [use it today](#usage).*

<img height="400" src="/1a/assets/images/nethunter-pro-5.jpg" width="200"/>

1. [ netscan ] ## Podstawwy namierzania hostów windows 
* 1 Wyobraź sobie że **musisz uzyskać dostęp do zasobów windows**, pracujesz na linux.
nasze pierwsze szukanie hostów w sieci, które udostępniają zasoby sieciowe.

a) skanujemy prorty sieć za pomocą **nmap**
```javascript
nmap -Pn 192.168.0.0/24
nbtscan 192.168.0.0/24
```
Użyłem tutaj dwóch narzędzi `nmap `i `nbtscan`

2. przykład wykrywania windowsa w sieci **ważne naszej sieci**

```javascript
192.168.0.94     GUMI             <server>  <unknown>        8c-89-a5-0d-45-fe
 nbtscan -v -s 192.168.0.0/24
```
3. Drugie polecenie zwrówci nam bardziej dokładne informacje **nmbscan -h** 191.168.0.208
````javascript
nmbscan -h 191.168.0.208
nmbscan version 1.2.6 - fedora - Sat Feb 11 12:29:48 AM CET 2023
domain -
server LAPTOP-S17-14
ip-address 192.168.0.208
mac-address 74:2B:62:F5:82:91
smb-mac-address 74:2B:62:F5:82:91
arp-mac-address 74:2B:62:F5:82:91
````