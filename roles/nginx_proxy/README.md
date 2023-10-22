# nginx_proxy

Install nginx and certbot, manage vhosts to use `proxy_pass`

### To do
- Cron job to regenerate certificates

### Limitations
- Copying `options-ssl-nginx.conf` from `certbot-nginx` feels flaky - source location might change in future versions
- Mananging `nginx.conf` to include familiar `sites-enabled`, `sites-available` dirs seems like an overkill and will likely lead to
  stale configuration
