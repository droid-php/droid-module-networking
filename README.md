# Droid Module: networking

Configures networking and DNS on Debian/Ubuntu based systems. For more
information on Droid, please see [droidphp.com](http://droidphp.com).

The steps involved are:-

1. Generate `/etc/network/interfaces` based on public/private ip information known to Droid.
2. Generate `/etc/resolv.conf` file based on `dnsservers` array.


## Assumptions

1. The platform is Debian-based.


## Limitations

## Information required by the module

1. A list of one or more users to create, as follows:-

```yml
mod_networking_dns_servers:
  - 8.8.8.8
  - 8.8.4.4
```
