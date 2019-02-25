## Magento 2 Spanish Language Pack

Magento 2 platform approves multiple languages around the world, so **Magento 2 Spanish MX Language Pack** is created to conduct the change of language via the in-line translation dictionary on Magento 2 store. The in-line translation dictionary is developed based on the community project at Crowdin where you can download over 13,000 phrases in Spanish to replace the default language.
			Magento 2 Spanish Language Package will involve the list of comprehensive guides which are essential for the perfect translation. Please keep tracking the topic to finish the interpretation at all.


**Install Spanish pack**:

```
composer require fasaro/magento2-es_mx-language-pack dev-master
php bin/magento setup:static-content:deploy es_MX
php bin/magento cache:flush

```


**Update  Spanish pack**:

```
composer update fasaro/magento2-es_mx-language-pack dev-master
php bin/magento setup:static-content:deploy es_MX
php bin/magento cache:flush

```

