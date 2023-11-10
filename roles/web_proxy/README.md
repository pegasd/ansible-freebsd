# web_proxy

Install nginx and certbot, manage vhosts to use `proxy_pass`

### Limitations
- Copying `options-ssl-nginx.conf` from `certbot-nginx` feels flaky - source location might change in future versions
- Mananging `nginx.conf` to include `nginx/vhosts` directory seems like an overkill and will likely lead to
  stale configuration
