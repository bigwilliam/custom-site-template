# VVV site template for PHP apps
For when you just need a simple dev site, for PHP. Also sets up SSL if config has it turned on.

## Overview
This template will allow you to create a plain PHP dev environment using only `vvv-custom.yml`.

# Configuration

### The minimum required configuration:

```
my-site:
  repo: https://github.com/Varying-Vagrant-Vagrants/custom-vvv-php
  nginx_upstream: php72
  hosts:
    - my-site.test
```

### Recommended Utilities Config

```
# Utilities are system level items rather than sites, that install tools or packages
# the core utilities install tools such as phpmyadmin
utilities:
  core:
    - memcached-admin
    - opcache-status
    - phpmyadmin
    - webgrind
    - trusted-hosts
    - tls-ca
    - php56
    - php71
    - php72
```

| Setting    | Value       |
|------------|-------------|
| Domain     | my-site.test |
| Site Title | my-site.test |
| DB Name    | my-site     |

# Contributing

This repo was originally forked from https://github.com/Varying-Vagrant-Vagrants/custom-site-template and then modified for plain PHP sites. 

Feel free to contribute by submitting PR's or issues, or email me at hello@bigwilliam.com
