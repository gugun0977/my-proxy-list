
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

> Scraper found **8980** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|464|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|464|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|464|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1275|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|513|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|6109|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|43.130.151.199|80|United States|Ashburn|Shenzhen Tencent Computer Systems Company Limited|
|2|43.130.148.94|80|United States|Ashburn|Shenzhen Tencent Computer Systems Company Limited|
|3|209.126.2.124|3128|United States|St Louis|Nubes, LLC|
|4|217.61.247.50|3128|Sweden|Stockholm|Elastx AB|
|5|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|6|192.241.238.167|31028|United States|San Francisco|DigitalOcean, LLC|
|7|43.130.135.185|80|United States|Ashburn|Shenzhen Tencent Computer Systems Company Limited|
|8|209.126.2.124|3128|United States|St Louis|Nubes, LLC|
|9|43.130.135.185|80|United States|Ashburn|Shenzhen Tencent Computer Systems Company Limited|
|10|112.217.162.5|3128|South Korea|Gyeyang-gu|LG DACOM Corporation|
|11|35.213.91.45|80|Japan|Tokyo|Google LLC|
|12|186.121.235.222|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|13|192.241.238.167|31028|United States|San Francisco|DigitalOcean, LLC|
|14|117.251.103.186|8080|India|Hazratpur|BSNL Internet|
|15|34.87.55.162|8080|Singapore|Singapore|Google LLC|
|16|200.46.65.66|8080|Panama|Panama City|Cable Onda|
|17|140.238.245.116|8100|India|Mumbai|Oracle Corporation|
|18|47.74.226.8|5001|Singapore|Singapore|Alibaba Cloud (Singapore) Private Limited|
|19|20.44.206.138|80|Singapore|Singapore|Microsoft Corporation|
|20|170.80.58.102|5566|Brazil|Varzea da Palma|Gnet Telecom|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

