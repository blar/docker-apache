# Apache2 Webserver

https://images.microbadger.com/badges/image/foobox/apache.svg

# Modules

* alias
* authz_core
* dir
* mpm_event
* rewrite
* unixd

## Environment Variables

### APACHE2_SERVER_ADMIN

https://httpd.apache.org/docs/2.4/en/mod/core.html#serveradmin

### APACHE2_SERVER_NAME

https://httpd.apache.org/docs/2.4/en/mod/core.html#servername

Default: 0.0.0.0:80

### APACHE2_MODULE_ENABLE

    apache-module-enable cache cache_socache

Space separared list of modules to enable on startup.

### APACHE2_MODULE_DISABLE

    apache-module-disable rewrite