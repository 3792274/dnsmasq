# 概要

docker-compose を使って dnsmasq を構築する.


# 手順

```
$ git clone https://github.com/robozushi10/qiita-dnsmasq.git
$ cd qiita-dnsmasq
$ vim PV/etc/dnsmasq.d/add_hosts
(IPとマシン名を定義する)
$ docker-compose up -d
```

# 参考にしたサイト

https://sites.google.com/site/hollyroyaltea/home/dns/dnsmasq
