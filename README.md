# AnonScript

Bash script that allow you to redirect all the traffics through Tor network for anonymization

# Features

1. -h, --help      show this help message and exit
2. -t, --tor       start transparent proxy through tor
3. -c, --clearnet  reset iptables and return to clearnet navigation
4. -m, --mac  change mac address on all interfaces
5. -l, --logs  remove some logs and bash history

## Install

As sudo go to /usr/share and clone the git repo:
```
cd /usr/share
git clone https://github.com/v4resk/AnonScript
```

## Usage

1. Start tor transparent proxy :
```
sudo ./AnonScript.sh --tor
```
