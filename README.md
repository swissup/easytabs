# Easytabs

It's a metapackage for the [source code repository](https://github.com/swissup/module-easytabs).

#### Installation

```bash
cd <magento_root>
composer config repositories.swissup composer https://docs.swissuplabs.com/packages/
composer require swissup/easytabs --prefer-source
bin/magento module:enable Swissup_Core Swissup_Easytabs
bin/magento setup:upgrade
```
