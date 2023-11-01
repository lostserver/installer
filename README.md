# Free Auto Script Installer SSH, VMESS, VLESS, TROJAN, SS
Support SlowDNS & UDP Custom

# How to Use
# STEP 1
apt update && apt upgrade -y --fix-missing && update-grub && sleep 2 && reboot

# STEP 2
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget -O setup 'https://github.com/lostserver/installer/raw/master/setup.sh' && chmod +x setup && screen -S setup ./setup
