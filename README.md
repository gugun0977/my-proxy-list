
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

> Scraper found **10029** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|627|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|627|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|627|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1289|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1316|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|6341|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|66.135.14.166|443|United States|Piscataway|The Constant Company, LLC|
|2|43.153.117.113|8800|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|3|190.2.137.225|3128|Netherlands|Naaldwijk|WorldStream B.V.|
|4|178.234.31.40|3128|Russia|Lipetsk|Address point-to-point Lipetsk Regional Public Network BBN-3/1/1 General|
|5|66.135.14.166|443|United States|Piscataway|The Constant Company, LLC|
|6|43.153.117.113|8800|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|7|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|8|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|9|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|10|115.76.203.68|11080|Vietnam|Ho Chi Minh City|VIETELGPRS|
|11|27.79.56.134|11080|Vietnam|Buon Ma Thuot|Viettel Group|
|12|186.121.235.66|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|13|103.134.44.176|8080|India|Haridwar|Countrylink Communiction Pvt Ltd|
|14|154.79.248.44|32650|Kenya|Nairobi|Airtel KE Mobile & Fixed Internet|
|15|103.92.26.190|4002|Vietnam|Quận Phú Nhuận|TLSOFT|
|16|103.165.253.10|3125|Indonesia|Kabupaten Subang|PT Pelangi Communication Network|
|17|192.241.238.167|31028|United States|San Francisco|DigitalOcean, LLC|
|18|185.78.29.95|3128|Russia|St Petersburg|System servers virtual hosting BEGET.RU|
|19|119.110.65.218|3888|Indonesia|Ciputat|Maxindo|
|20|27.77.144.94|10002|Vietnam|Ho Chi Minh City|Newass2011xDSLHCMC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

