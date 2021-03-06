# BulkGiftAccount Module

**Author**: Warby Parker (Igor Finchuk & Gershon Herczeg)

**Version**: 0.1.2

## Description

This module is built upon the existing gift-card functionality available in [Magento Enterprise Edition](http://www.magentocommerce.com/product/enterprise-edition). 

BulkGift adds a custom admin panel to the Gift Cards admin page for users to add gift cards in bulk.

![Yo dawg, I herd u liked gift cards](http://i.imgur.com/w9Zidqr.png)
## Dependencies 

- [modman](https://github.com/colinmollenhour/modman) for module installation.

## Installation

    $ cd /var/www                                         
    $ modman init                                         
    $ modman clone git@github.com:WarbyParker/Warby_BulkGiftAccount.git

## Configuration

*Optional*: if you're concerned about performance, you can adjust the bulk creation limit:

- System > Configuration > Sales
- In the **Gift Cards** section, go to the **Gift Card Account General Settings** subsection.
- Update the Bulk Create Limit

![Set yourself before you wreck yourself](http://i.imgur.com/EbJ9A4V.png)

## Licensing/Legal

[MIT](http://opensource.org/licenses/MIT)
