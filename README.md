<p>This is a template module for Magento 2 if you need to change configuration programmatically (modify the core_config_data table).<br>
To update the configuration later just bump the module version and change the UpgradeData.php class - check branch module-update-script for that.
</p>
<p>After the module is in place run the setup scripts first and then clean cache:<br>
<pre><code>php bin/magento setup:upgrade
php bin/magento cache:clean</code></pre>
