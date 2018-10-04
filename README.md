# VVV site template for PHP apps
For when you just need a simple dev site, PHP. WordPress has been removed for this one.

## Overview
This template will allow you to create a plain PHP dev environment using only `vvv-custom.yml`.

The supported environments are:
- A single site
- A subdomain multisite
- A subdirectory multisite

# Configuration

### The minimum required configuration:

```
my-site:
  repo: https://github.com/Varying-Vagrant-Vagrants/custom-vvv-php
  hosts:
    - my-site.test
```
| Setting    | Value       |
|------------|-------------|
| Domain     | my-site.test |
| Site Title | my-site.test |
| DB Name    | my-site     |
