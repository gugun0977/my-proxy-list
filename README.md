
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

> Scraper found **9007** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|546|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|546|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|546|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1204|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|557|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|6163|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|185.161.70.117|20000|United States|Los Angeles|DediPath|
|2|34.87.55.162|8080|Singapore|Singapore|Google LLC|
|3|51.79.50.31|9300|Canada|Beauharnois|OVH SAS|
|4|114.30.19.201|8080|South Korea|Paju|DLIVE|
|5|41.186.44.106|3128|Rwanda|Kigali|MTN Rwandacell|
|6|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|7|112.217.162.5|3128|South Korea|Gyeyang-gu|LG DACOM Corporation|
|8|185.98.23.229|3128|France|Valence|ITMETRIX|
|9|68.183.53.101|9990|United States|Clifton|DigitalOcean, LLC|
|10|188.43.247.36|3128|Russia|Vladivostok|Joint Stock Company TransTeleCom|
|11|67.225.139.153|3128|United States|Lansing|Liquid Web, L.L.C|
|12|43.130.148.94|80|United States|Ashburn|Shenzhen Tencent Computer Systems Company Limited|
|13|190.92.208.146|7890|Singapore|Singapore|Huawei International Pte. LTD|
|14|78.11.96.22|8080|Poland|Gora Kalwaria|Netia SA|
|15|122.211.138.2|53128|Japan|Otemae|SUGOKURA|
|16|190.2.212.20|999|Colombia|Bogotá|TV AZTECA SUCURSAL COLOMBIA|
|17|185.161.70.117|20000|United States|Los Angeles|DediPath|
|18|188.166.6.227|3128|Netherlands|Amsterdam|DigitalOcean, LLC|
|19|172.105.105.73|3128|Canada|Toronto|Akamai Technologies|
|20|202.86.138.18|8080|Macao|Macao|Companhia de Telecomunicacoes de Macau|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

