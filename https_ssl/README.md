# HTTPS SSL

| File | Description |
|---|---|
| `0-world_wide_web` | Bash script that shows the record type and destination of the www, lb-01, web-01 and web-02 subdomains (or of one given subdomain) |
| `1-haproxy_ssl_termination` | HAProxy config terminating SSL on port 443 for www.builtbykoffi.tech |
| `2-redirect_http_to_https` | HAProxy config that also redirects all HTTP traffic to HTTPS with a 301 |
