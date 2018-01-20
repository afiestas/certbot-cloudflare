# Usage

### cloudflare.ini
> dns_cloudflare_email=<cloudflare_email>
> dns_cloudflare_api_key=<cloudflare_api_key>

```bash
certbot certonly --dns-cloudflare \
--dns-cloudflare-credentials /etc/cloudflare.ini \
-m foo@example.com --agree-tos \
--no-eff-email -d example.com
```