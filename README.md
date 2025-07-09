# Free proxy list

This repository provides lists of **working, tested, free (open), anonymizing proxies** for HTTP, HTTPS, SOCKS4, SOCKS5.

Updates every 30 minutes. Contains thousands of working proxies collected from various sources.

## Proxy lists

- [All working proxies](https://github.com/iplocate/free-proxy-list/blob/main/all-proxies.txt)
- [HTTP proxies](https://github.com/iplocate/free-proxy-list/blob/main/protocols/http.txt)
- [HTTPS proxies](https://github.com/iplocate/free-proxy-list/blob/main/protocols/https.txt)
- [SOCKS4 proxies](https://github.com/iplocate/free-proxy-list/blob/main/protocols/socks4.txt)
- [SOCKS5 proxies](https://github.com/iplocate/free-proxy-list/blob/main/protocols/socks5.txt)
- [🇺🇸 USA proxies](https://github.com/iplocate/free-proxy-list/blob/main/countries/US/proxies.txt)
- [🌏 Other proxies by country](https://github.com/iplocate/free-proxy-list/tree/main/countries/)

### Features

- 📝 Validated every 30 minutes
- 🫣 Anonymizing proxies - only contains proxies that **hide  your IP address**
- 📓 Sorted into **HTTP**, **HTTPS**, **SOCKS4**, & **SOCKS5**
- 🌎 Contains proxies from **dozens of countries**
- 🔐 Supports HTTPS connections
- 😊 No duplicates

## How to test a proxy?

You can check your proxy is working and hiding your IP address by making a call to [**api.iplocate.io/ip**](https://api.iplocate.io/ip)

This endpoint is free to use and has no rate limits.

### Examples

Test a SOCKS5 proxy:

```bash
curl http://api.iplocate.io/ip --socks5 159.203.61.169:1080
```

Test a SOCKS4 proxy:

```bash
curl http://api.iplocate.io/ip --socks4 192.95.33.162:24794
```

Test a HTTP or HTTPS proxy:

```bash
curl http://api.iplocate.io/ip -k --proxy http://203.19.38.114:1080
curl https://api.iplocate.io/ip -k --proxy https://3.29.67.17:4480
```

## How to detect proxies

Need to **detect proxies, VPNs, or hosting providers?**

[IPLocate.io](https://www.iplocate.io) is a fast and accurate IP geolocation and threat intelligence API, providing hourly-updated detection for:

- open/free proxies (this repo)
- closed (paid/private) proxy networks
- residential proxy networks
- hosting/datacenter providers
- Tor exit nodes
- VPNs

100% free to use up to 1,000 requests per day with a [free API key](https://iplocate.io/signup).

Browse our [docs](https://iplocate.io/docs) and see how easy it is to get started, or see what information we can provide for [your IP address](https://www.iplocate.io/what-is-my-ip).

### About IPLocate

<a href="https://www.iplocate.io"><img src="https://static.iplocate.io/custom/logo-square-rounded.png" alt="IPLocate.io" width="64"></a><br>

Since 2017, IPLocate has set out to provide the most reliable and accurate IP address data.

We process 50TB+ of data to produce our comprehensive IP geolocation, IP to company, proxy and VPN detection, hosting detection, ASN, and WHOIS data sets. Our API handles over 15 billion requests a month for tens of thousands of businesses and developers.

- [Get your current IP address (free forever, no rate limits)](https://api.iplocate.io/ip)
- Email: [support@iplocate.io](mailto:support@iplocate.io)
- Website: [iplocate.io](https://iplocate.io)
- Documentation: [iplocate.io/docs](https://iplocate.io/docs)
- Sign up for a free API Key: [iplocate.io/signup](https://iplocate.io/signup)
