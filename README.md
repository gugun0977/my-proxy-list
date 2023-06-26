
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

> Scraper found **9876** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|563|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|563|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|563|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1305|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1025|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|6463|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.213.91.45|80|Japan|Tokyo|Google LLC|
|2|66.70.225.202|8050|Brazil|Mairi|OVH Hosting|
|3|3.8.154.87|3128|United Kingdom|London|Amazon Technologies Inc.|
|4|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|5|37.120.192.154|8080|Netherlands|Amsterdam|M247 Europe SRL|
|6|158.160.56.149|8080|Russia|Moscow|Yandex.Cloud LLC|
|7|165.232.169.44|8080|Singapore|Singapore|DigitalOcean, LLC|
|8|203.150.113.57|8080|Thailand|Vadhana|Internet Thailand Company Ltd.|
|9|20.44.206.138|80|Singapore|Singapore|Microsoft Corporation|
|10|213.171.44.134|3128|Russia|Moscow|JSC Comcor|
|11|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|12|185.98.23.229|3128|France|Valence|ITMETRIX|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|178.234.31.40|3128|Russia|Lipetsk|Address point-to-point Lipetsk Regional Public Network BBN-3/1/1 General|
|15|119.8.10.18|7890|Mexico|Mexico City|Huawei International Pte. LTD|
|16|91.25.93.174|3128|Germany|Frankfurt am Main|Deutsche Telekom AG|
|17|186.121.235.222|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|18|173.176.14.246|3128|Canada|Vaudreuil-Dorion|Le Groupe Videotron Ltee|
|19|77.238.79.111|8080|Bulgaria|Sofia|FIBER1|
|20|86.100.71.126|8080|Lithuania|Klaipėda|Balticum TV network|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

