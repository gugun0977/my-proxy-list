
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

> Scraper found **9496** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|389|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|389|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|389|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1132|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1200|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|6081|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|192.99.182.243|3128|United States|Newark|OVH Hosting|
|2|144.217.131.61|3148|Canada|Beauharnois|OVH Hosting|
|3|158.69.185.37|3129|Canada|Montreal|OVH SAS|
|4|144.217.119.85|3207|Canada|Beauharnois|OVH Hosting|
|5|191.186.106.34|8080|Brazil|São Paulo|Claro NXT Telecomunicacoes Ltda|
|6|202.86.138.18|8080|Macao|Macao|Companhia de Telecomunicacoes de Macau|
|7|64.226.110.184|45212|Germany|Frankfurt am Main|DigitalOcean, LLC|
|8|191.186.106.34|8080|Brazil|São Paulo|Claro NXT Telecomunicacoes Ltda|
|9|118.69.111.51|8080|Vietnam|Ho Chi Minh City|FPT Telecom Company|
|10|119.8.120.4|80|Hong Kong|Hong Kong|Huawei International Pte. LTD|
|11|69.64.46.32|3128|United States|St Louis|GoDaddy.com, LLC|
|12|202.86.138.18|8080|Macao|Macao|Companhia de Telecomunicacoes de Macau|
|13|186.121.235.66|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|14|20.44.206.138|80|Singapore|Singapore|Microsoft Corporation|
|15|122.211.138.2|53128|Japan|Otemae|SUGOKURA|
|16|103.224.195.41|3128|Taiwan|Neihu District|Taiwan Fixed Network|
|17|195.201.151.184|8080|Germany|Gunzenhausen|Hetzner Online GmbH|
|18|13.112.253.104|80|Japan|Tokyo|Amazon Technologies Inc|
|19|209.38.250.139|45212|Germany|Frankfurt am Main|DigitalOcean, LLC|
|20|41.76.145.136|8080|Mozambique|Maxixe|VM  S.A|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

