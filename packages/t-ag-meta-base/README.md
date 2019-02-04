# t-ag-meta-base

Ein Metapaket, das Grundlegende Konfigurationen enthält

## Interne Pakete
* [`t-ag-auto-upgrade`](../t-ag-auto-upgrade/README.md)
* [`t-ag-motd-banner`](../t-ag-motd-banner/README.md)
* [`t-ag-sudo-pwfeedback`](../t-ag-sudo-pwfeedback/README.md)

## Externe Pakete

### avahi-daemon
Paketinfo:
* [Ubuntu 18.10 (Cosmic Cuttlefish)](https://packages.ubuntu.com/cosmic/avahi-daemon)
* [Debian Stretch](https://packages.debian.org/stretch/avahi-daemon)

Avahi stellt Multicast-DNS zur Verfügung. Dadurch kann ein Computer von anderen Computern, die es unterstützen,
durch <code>*hostname*.local.</code> erreicht werden.
Dies ist praktisch, wenn man die IP-Addresse des Computers nicht kennt und der DHCP-Server aus irgendeinem Grund nicht zuverlässig funktioniert.