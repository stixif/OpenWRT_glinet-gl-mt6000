#openwrt-builder Automated builds OpenWRT repository using GitHub Actions<br>

OpenWrt is pulled daily and if last commit is less than a day old a new build is triggered.<br>
Manual build can also be triggered.<br>
Build artifacts are stored as releases.<br>


activate WED<br>
modify "/etc/modules.conf" with
options mt7915e wed_enable=Y
