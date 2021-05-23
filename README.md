# gentoo-alpha repo overlay

Jake's Gentoo repo overlay for Alpha Linux features and bug fixes.

# Installation

Sync this repo to a location such as `/var/db/repos/gentoo-alpha`,
and then add this file to `/etc/portage/repos.conf/gentoo-alpha.conf`:

```
[gentoo-alpha]
location = /var/db/repos/gentoo-alpha
auto-sync = no
priority = 100
strict-misc-digests = false
sync-openpgp-key-refresh = false
```
