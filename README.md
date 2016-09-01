# origin-detect

A utility to discover open webservers behind a CDN or WAF service.

Modules to include:
- Google dorking such as `site:<domain> inurl:origin`
- CDN X-headers
- DNS enumeration
- Sweep the ip ranges that the entity owns for 80/443 and alter the host header to try and find a hit
- SPF Records
- Debug/info pages (i.e. apache/nginx error page, phpinfo)
- Cookie data
- DNS history
- SSL certificates
- Crimeflare domains (http://www.crimeflare.com/cfs.html)
