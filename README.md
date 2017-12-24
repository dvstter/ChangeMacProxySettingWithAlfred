# Change Proxy Setting on Mac

A very little alfred workflow that can change SOCKS proxy setting for ShadowsocksX-NG on Mac.

![](https://github.com/dvstter/Change-Mac-Proxy-Setting-With-Alfred/blob/master/normal.png)

![](https://github.com/dvstter/Change-Mac-Proxy-Setting-With-Alfred/blob/master/goo.png)

## Getting Started

These instructions will let you install an alfred workflow to make you easier change the proxy setting (network card is Wi-Fi) for Shadowsocks.

### Prerequisite

* System Requirement: maxOS
* [ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG)
* [Alfred](https://www.alfredapp.com) With Powerback Installed

### Installing

1. Change ShadowsocksX-NG's mode to **Manual Mode**, like these

![](https://github.com/dvstter/Change-Mac-Proxy-Setting-With-Alfred/blob/master/ss_settings.png)

2. Install the **ss.alfredworkflow**
3. Go to installing dir of ss.alfredwork from alfred workflow setting page and change the **SS_LISTEN_PORT** and **SS_LISTEN_HOST** in the `change_proxy_setting.py` like these
```
SS_LISTEN_HOST="localhost"
SS_LISTEN_PORT="1086"
```
4. Type **kex** in the alfred and see what happen

## Acknowledgments

* Any suggestion or problem please contact me.
* Email: p1usj4de_work@gmail.com
