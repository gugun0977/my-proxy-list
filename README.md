
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

> Scraper found **8020** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|376|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|376|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|376|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1149|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|428|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|5360|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|142.4.123.41|80|United States|San Jose|PEG TECH INC|
|2|34.133.176.86|3128|United States|Council Bluffs|Google LLC|
|3|142.4.123.41|80|United States|San Jose|PEG TECH INC|
|4|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|5|34.133.176.86|3128|United States|Council Bluffs|Google LLC|
|6|178.62.254.6|3128|Netherlands|Amsterdam|DigitalOcean, LLC|
|7|194.233.81.116|14344|Singapore|Singapore|Contabo Asia Private Limited|
|8|186.97.102.70|999|Colombia|Medellín|Colombia Móvil|
|9|47.242.3.214|8081|Hong Kong|Hong Kong|Alibaba.com LLC|
|10|186.121.235.222|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|11|136.243.55.199|3128|Germany|Falkenstein|Hetzner Online GmbH|
|12|190.97.240.10|1994|Venezuela|Vigia|Viginet C.A|
|13|200.63.104.44|999|Ecuador|Quito|Eliana Vanessa Morocho Oña|
|14|186.201.63.83|3128|Brazil|São Paulo|Vivo|
|15|191.97.14.26|999|Colombia|Bogotá|TV AZTECA SUCURSAL COLOMBIA|
|16|50.236.203.15|8080|United States|Peru|Comcast Cable Communications, LLC|
|17|202.86.138.18|8080|Macao|Macao|Companhia de Telecomunicacoes de Macau|
|18|115.110.230.18|3128|India|Mumbai|Tata Communications Limited|
|19|190.82.110.102|80|Chile|Santiago|Telefonica Empresas|
|20|110.34.3.229|3128|Nepal|Bharatpur|SUBISU C7|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

