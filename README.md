This is a template module for Magento 2 if you need to change configuration programmatically (modify the core_config_data table).
To update the configuration later just bump the module version and change the UpgradeData.php class - check branch module-update-script for that.

After the module is in place run the setup scripts first and then clean cache:
php bin/magento setup:upgrade
php bin/magento cache:clean

