#openwrt-builder Automated builds OpenWRT repository using GitHub Actions

OpenWrt is pulled daily and if last commit is less than a day old a new build is triggered.
Manual build can also be triggered.
Build artifacts are stored as releases.


activate WED
modify "/etc/modules.conf" with
options mt7915e wed_enable=Y
