# Ansible collection for FreeBSD

Collection of roles for setting up a FreeBSD server

## To do

### `nginx_proxy`:
- Cron job to regenerate certificates

## Limitations

### `nginx_proxy`:
- Copying `options-ssl-nginx.conf` from `certbot-nginx` feels flaky - source location might change in future versions.
- Mananging `nginx.conf` to include familiar `sites-enabled`, `sites-available` dirs seems like an overkill and may lead to stale config.
