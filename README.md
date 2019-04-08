Spanish (español Colombia) language for magento 2
============================================================


## Installation ##

Use composer package manager

```bash
composer require saulmoralespa/magento2-es_co
```

Execute the commands

```bash
php bin/magento setup:static-content:deploy es_CO
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```