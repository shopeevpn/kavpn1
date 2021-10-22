# kavpn 

```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl wget tcpdump dsniff grepcidr dnsutils -y && wget https://raw.githubusercontent.com/shopeevpn/kavpn1/main/setup.sh && chmod +x setup.sh && "/root/setup.sh"
```
