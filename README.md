# Apache2 Webserver

![Docker Pulls](https://img.shields.io/docker/pulls/foobox/docker-apache.svg)
![Docker Stars](https://img.shields.io/docker/stars/foobox/docker-apache.svg)

[![](https://images.microbadger.com/badges/version/foobox/docker-apache:2.4-amd64.svg)](https://microbadger.com/images/foobox/docker-apache:2.4-amd64 "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/foobox/docker-apache:2.4-amd64.svg)](https://microbadger.com/images/foobox/docker-apache:2.4-amd64 "Get your own image badge on microbadger.com")

[![](https://images.microbadger.com/badges/version/foobox/docker-apache:2.4-arm32v6.svg)](https://microbadger.com/images/foobox/docker-apache:2.4-arm32v6 "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/foobox/docker-apache:2.4-arm32v6.svg)](https://microbadger.com/images/foobox/docker-apache:2.4-arm32v6 "Get your own image badge on microbadger.com")

## Modules

### Enabled modules

* alias
* authz_core
* deflate
* dir
* expires
* headers
* log_config
* mime
* mpm_event
* rewrite
* security
* unixd

## Environment Variables

### APACHE_SERVER_ADMIN

https://httpd.apache.org/docs/2.4/en/mod/core.html#serveradmin

### APACHE_SERVER_NAME

https://httpd.apache.org/docs/2.4/en/mod/core.html#servername

Default: 0.0.0.0:80

### APACHE_MODULE_ENABLE

    apache-module-enable cache cache_socache

Space separated list of modules to enable on startup.

### APACHE_MODULE_DISABLE

    apache-module-disable rewrite
    
Space separated list of modules to disable on startup.