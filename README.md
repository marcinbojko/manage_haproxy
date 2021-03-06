# manage_haproxy

## Table of Contents

1. [Description](#description)
1. [Usage - Configuration options and additional functionality](#usage)
1. [Known Issues](#known-issues)
1. [Author](#author)

## Description

Aggregator/wrapper for `puppetlabs-haproxy` [https://forge.puppet.com/puppetlabs/haproxy](https://forge.puppet.com/puppetlabs/haproxy)

## Changelog

### Version 0.5.0 2021-05-02

* converted to pdk 2.1.0
* added constrains for max version being puppet 5 (for now)

### Version 0.4.0 2019-10-28

* converted to pdk 1.14
* added `haproxy::resolver`

### Version 0.3.1 2018-10-21

* fixed wrong date in README.md
* gitignore working now

### Version 0.3.0 2018-10-21

* converted to PDK version 1.7.1
* added files for Travis CI
* converted to puppet 5 syntax

### Version 0.2.0 2017-01-08

* added all public classes from `puppetlabs-haproxy`

### Version 0.1.0 Initial

## Parameters

### `listen`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxylisten](https://forge.puppet.com/puppetlabs/haproxy#define-haproxylisten)

### `frontend`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxyfrontend](https://forge.puppet.com/puppetlabs/haproxy#define-haproxyfrontend)

### `backend`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxybackend](https://forge.puppet.com/puppetlabs/haproxy#define-haproxybackend)

### `balancermember`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxybalancermember](https://forge.puppet.com/puppetlabs/haproxy#define-haproxybalancermember)

### `userlist`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxyuserlist](https://forge.puppet.com/puppetlabs/haproxy#define-haproxyuserlist)

### `peers`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxypeers](https://forge.puppet.com/puppetlabs/haproxy#define-haproxypeers)

### `peer`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxypeer](https://forge.puppet.com/puppetlabs/haproxy#define-haproxypeer)

### `mailers`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxymailers](https://forge.puppet.com/puppetlabs/haproxy#define-haproxymailers)

### `mailer`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxymailer](https://forge.puppet.com/puppetlabs/haproxy#define-haproxymailer)

### `instance`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxyinstance](https://forge.puppet.com/puppetlabs/haproxy#define-haproxyinstance)

### `instance_service`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxyinstance_service](https://forge.puppet.com/puppetlabs/haproxy#define-haproxyinstance_service)

### `mapfile`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxymapfile](https://forge.puppet.com/puppetlabs/haproxy#define-haproxymapfile)

### `defaults`

#### [https://forge.puppet.com/puppetlabs/haproxy#define-haproxydefaults](https://forge.puppet.com/puppetlabs/haproxy#define-haproxydefaults)

### `resolver`

#### [https://forge.puppet.com/puppetlabs/haproxy#set-up-a-resolver](https://forge.puppet.com/puppetlabs/haproxy#set-up-a-resolver)

## Usage

```yaml
listen:
frontend:
backend:
balancermember:
userlist:
peers:
peer:
mailers:
mailer:
instance:
instance_service:
mapfile:
defaults:
resolver:
```

## Known Issues

Remember to set `net.ipv4.ip_nonlocal_bind=1`

## Author

Marcin Bojko (marcin@bojko.com.pl)

[https://marcinbojko.wordpress.com/](https://bojko.dev/)
