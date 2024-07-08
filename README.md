# Mage2 Module WdevAmar ProductImageInvoice     ``wdevamar/module-productimageinvoice``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)

## Main Functionalities
Show the product image on invoice pdf.
Developed By Amarjeet Prajapati (wdevamar@gmail.com)

## Installation
\* In production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/WdevAmar`
 - Enable the module by running `php bin/magento module:enable WdevAmar_ProductImageInvoice`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Install the module composer by running `composer require wdevamar/module-productimageinvoice`
 - enable the module by running `php bin/magento module:enable WdevAmar_ProductImageInvoice`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

