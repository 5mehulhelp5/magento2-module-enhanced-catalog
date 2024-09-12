# MagedIn_EnhancedCatalog Extension for Magento 2

This extension enhances the catalog feature in Magento 2.

[![Magento 2 Coding Standard](https://github.com/magedin/magento2-module-enhanced-catalog/actions/workflows/coding-standard.yml/badge.svg)](https://github.com/magedin/magento2-module-enhanced-catalog/actions/workflows/coding-standard.yml)

## Compatibility

- Magento 2.3
- Magento 2.4

## Features

### Control the Default Sorting on PLPs

It adds a new configuration field under `STORES > Settings > Configuration > CATALOG > Catalog > Storefront` called `Product Listing Default Sort Order`. This field controls the default order of the sorting in the product listing pages (PLP).

## Installation

```bash
> composer require magedin/module-enhanced-catalog
> php bin/magento module:enable MagedIn_EnhancedCatalog
> php bin/magento setup:upgrade
> php bin/magento setup:di:compile
```

<br>

<div style="text-align: center;">
    <a href="https://github.com/magedin/magento2-module-enhanced-catalog">
        <img src="https://raw.githubusercontent.com/magedin/assets/c0cd4f15cee6580c6c96848400cf089e91417529/images/logo/magedin_horizontal.svg?raw=true" width="200" alt="MagedIn Technology" title="MagedIn Technology"/>
    </a>
</div>
