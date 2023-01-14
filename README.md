# Some default Nginx configuration files

A small collection of reusable configs for use in Nginx site configs

## Installation

1. Clone into /etc/nginx/includes
2. Include in nginx configs e.g. `include 'includes/php.conf';`

## Notes

**basic_auth.conf** - Enables basic auth.

**cache.conf** - Set expiration of assets to MAX for caching

**kirby.conf** - Set up location handlers for kirby CMS.

**php.conf** - Basic php configuration, handles index, route to php and FastCGI.

