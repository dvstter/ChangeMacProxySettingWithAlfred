# Change Proxy Setting on Mac

A very little alfred workflow that can change SOCKS proxy setting for ShadowsocksX-NG and Tor on Mac.

![](https://github.com/dvstter/Change-Mac-Proxy-Setting-With-Alfred/blob/master/normal.png)

## Getting Started

These instructions will let you install an alfred workflow to make you easier change the proxy setting (network card is Wi-Fi) for Shadowsocks or Tor.

### Prerequisite

* System Requirement: macOS
* [ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG)
* Tor
* [Alfred](https://www.alfredapp.com) With Powerback Installed

### Installing

1. Install the **ss.alfredworkflow**
2. Go to installing dir of ss.alfredwork from alfred workflow setting page and change all the listen hosts and ports in constant.py
```python
SS_LISTEN_HOST="localhost"
SS_LISTEN_PORT="1086"

TOR_LISTEN_HOST="localhost"
TOR_LISTEN_PORT="9050"
```
3. Type **kex** in the alfred and see what happen

## Acknowledgments

* Any suggestion or problem please contact me.
* Email: p1usj4de_work@gmail.com
