# Frequently Bought Together GraphQl

## How to install
Run the following command in Magento 2 root folder:

```
composer require mageplaza/module-frequently-bought-together-graphql
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

## How to use

To start working with **Frequently Bought Together GraphQl** in Magento, you need to:

- Use Magento 2.3.x. Return your site to developer mode
- Install chrome extension (currently does not support other browsers)
- Set GraphQL endpoint as `http://<magento2-3-server>/graphql` in url box, click **Set endpoint**. (e.g. http://develop.mageplaza.com/graphql/ce232/graphql)

The module currently supports queries to retrieve a list of Frequently Bought Together products under certain conditional fields related to the product.

- For example: List of Frequently Bought Together products of products with SKU is 24-MB04

![](https://i.imgur.com/0V0cwtV.png)
