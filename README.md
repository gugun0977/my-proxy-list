
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

> Scraper found **8581** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|288|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|288|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|288|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|86|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1029|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|757|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|5726|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|18.116.27.91|443|United States|Dublin|Amazon.com, Inc.|
|2|194.163.132.232|3128|Germany|Düsseldorf|Contabo GmbH|
|3|35.158.190.140|3128|Germany|Frankfurt am Main|Amazon Technologies Inc.|
|4|34.213.191.165|3128|United States|Portland|Amazon.com, Inc.|
|5|62.138.7.104|8646|France|Strasbourg|Host Europe Group|
|6|18.185.20.28|3128|Germany|Frankfurt am Main|Amazon Technologies Inc.|
|7|34.87.55.162|8080|Singapore|Singapore|Google LLC|
|8|186.121.235.222|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|9|18.116.27.91|443|United States|Dublin|Amazon.com, Inc.|
|10|34.213.191.165|3128|United States|Portland|Amazon.com, Inc.|
|11|20.44.206.138|80|Singapore|Singapore|Microsoft Corporation|
|12|64.225.4.63|9993|United States|Clifton|DigitalOcean, LLC|
|13|34.143.228.238|8080|Singapore|Singapore|Google LLC|
|14|165.232.169.44|8080|Singapore|Singapore|DigitalOcean, LLC|
|15|203.109.19.137|12241|South Korea|Mapo-gu|HAIonNet|
|16|18.143.215.49|80|Singapore|Singapore|Amazon Technologies Inc.|
|17|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|18|136.243.55.199|3128|Germany|Falkenstein|Hetzner Online GmbH|
|19|147.50.253.79|8080|Thailand|Huai Khwang|DC-CLOUDFOREST3|
|20|115.144.221.125|10761|South Korea|Nowon-gu|HAIonNet|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

