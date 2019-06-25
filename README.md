# HidePriceM2
Extension bug fixes for Hide Price M2 by magentobyte


### Bug Fixes: 
* Added config file to Auto Enable Plugin

### New Features:
* Remove button if text is blank
* Multistore enable/disable
* Added Configurable product conditions
* Added Cart layout


## Installing
* Backup magento files and the store database.

* Log into your hosting space via a FTP client.

* Unzip extension package and upload it into Magento root directory.

* Run setup

> Enter the following at the command line

```
php bin/magneto setup:upgrade
```


## Configuration

Go to Stores > Configuration > KDC > Hide Price.



## FAQS

Q: Messy page, no style. What should I do?

A: it because of static content is not generated to pub/ folder. Let’s run command to deploy it.

> Enter the following at the command line

```
php bin/magento setup:static-content:deploy
```

## Authors

* **Kita Cranfill** - *Bug Fixes & Added Features* - [GitHub](https://github.com/kita86)
* **magentobyte** - *Origional Code* - [Magento Marketplace](https://marketplace.magento.com/estdevs-hideprice.html)

