
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)
[![zevtyardt - proxy-list](https://img.shields.io/static/v1?label=zevtyardt&message=proxy-list&color=blue&logo=github)](https://github.com/zevtyardt/proxy-list "Go to GitHub repo")
[![stars - proxy-list](https://img.shields.io/github/stars/zevtyardt/proxy-list?style=social)](https://github.com/zevtyardt/proxy-list)
[![forks - proxy-list](https://img.shields.io/github/forks/zevtyardt/proxy-list?style=social)](https://github.com/zevtyardt/proxy-list)
[![Proxy Updater](https://github.com/zevtyardt/proxy-list/workflows/Proxy%20Updater/badge.svg)](https://github.com/zevtyardt/proxy-list/actions?query=workflow:"Proxy+Updater")
![GitHub repo size](https://img.shields.io/github/repo-size/zevtyardt/proxy-list)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/zevtyardt/proxy-list?logo=commits)](https://github.com/zevtyardt/proxy-list/commits/main)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.

> Scraper found **5207** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|300|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|300|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|300|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|773|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|709|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2642|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|185.238.72.222|53128|Poland|Lodz|IWACOM Sp. z o.o.|
|2|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|3|209.38.254.44|45212|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|91.236.120.4|3128|Russia|Bryansk|BitWeb LLC|
|5|51.81.24.36|3128|United States|New York|OVH US LLC|
|6|51.81.24.36|3128|United States|New York|OVH US LLC|
|7|209.38.250.139|45212|Germany|Frankfurt am Main|DigitalOcean, LLC|
|8|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|9|209.222.98.213|48747|United States|Piscataway|ReliableSite.Net LLC|
|10|158.69.53.98|9300|Canada|Montreal|OVH SAS|
|11|171.244.65.14|4002|Vietnam|Hanoi|Viettel Corporation|
|12|37.120.192.154|8080|Netherlands|Amsterdam|M247 Europe SRL|
|13|103.92.26.190|4002|Vietnam|Quan Phu Nhuan|TLSOFT|
|14|200.48.38.74|999|Peru|Pátapo|Telefonica del Peru S.A.A.|
|15|191.103.219.225|48612|Colombia|Montería|Edatel S.a. E.S.P|
|16|103.144.38.100|8080|Indonesia|Batam|BIG|
|17|45.238.220.1|8181|Argentina|Curuzu Cuatia|CA VI CU SRL|
|18|186.121.235.66|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|19|203.109.19.137|12241|South Korea|Mapo-gu|HAIonNet|
|20|103.145.160.4|8080|Indonesia|Bogor|PT Indonesia Comnets Plus|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

