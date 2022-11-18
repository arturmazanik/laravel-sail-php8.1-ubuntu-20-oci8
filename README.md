# New configuration with downgrade Ubuntu version to 20.04 and with OCI8
## Laravel sail with ubuntu 20
### Since ver 1.1 support oci8 (without special libs)

### Install from composer:
```
  composer require arturmazanik/Laravel-Sail-PHP8.1-Ubuntu-20-OCI8
```

### After installing add context in laravel.test:

```
  context: ./vendor/arturmazanik/Laravel-Sail-PHP8.1-Ubuntu-20-oci8/runtimes/8.1
```
