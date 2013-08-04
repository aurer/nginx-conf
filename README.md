# Some default Nginx configuration files
 
A small collection of reusable configs for use in Nginx site configs

## Installation

1. Clone into /etc/ningx/configs.
2. Make sure to reference the 'configs' path when including e.g. `include configs/php.conf;` 

## Notes

**cache.conf** - Set expiration of assets to MAX for caching

**favicon.conf** - Remove favicon from the access and not_found logs.

**php.conf** - Basic php configuration, handles index, route to php and FastCGI.

**basic_auth.conf** - Enables basic auth.