# Dział poświęcony bezpieczeństwu w sieci lokalnej
[![.github/workflows/ci.yaml](https://github.com/pages-themes/hacker/actions/workflows/ci.yaml/badge.svg)](https://github.com/pages-themes/hacker/actions/workflows/ci.yaml) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-hacker.svg)]( https://github.com/bartdurak/char)

*Kali Linux  [idealny system do pracy w LAN](https://www.kali.org), or even [use it today](#usage).*

<img alt="Thumbnail of Hacker" height="200" src="../RubymineProjects/1a/batq_zdalne.png" width="200"/>

## Kilka podstawowych poleceń w linuxie
 nasze pierwsze szukanie hostów w sieci, które udostępniają zasoby sieciowe.
```javascript
nmap -Pn 192.168.0.0/24
nbtscan 192.168.0.0/24
```
Użyłem tutaj dwóch narzędzi `nmap `i `nbtscan`

1.  przykład wykrywania windowsa w sieci **ważna naszej sieci**

 ```   wynik z nbtscan
192.168.0.94     GUMI             <server>  <unknown>        8c-89-a5-0d-45-fe
 nbtscan -v -s 192.168.0.0/24
```

2. Optionally... CDN

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` once before the test script will work.
````