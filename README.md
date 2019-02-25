## Magento 2 Spanish Language Pack

Magento 2 platform approves multiple languages around the world, so **Magento 2 Spanish MX Language Pack** is created to conduct the change of language via the in-line translation dictionary on Magento 2 store. The in-line translation dictionary is developed based on the community project at Crowdin where you can download over 12,000 phrases in Spanish to replace the default language.
			Magento 2 Spanish Language Package will involve the list of comprehensive guides which are essential for the perfect translation. Please keep tracking the topic to finish the interpretation at all.

Read more [Magento 2 Spanish Language Pack](https://www.mageplaza.com/magento-2-spanish-language-pack.html)


## Overview

1. Language Package Process
2. Install MX Spanish Language Pack
3. How to active Spanish language pack
4. How to contribute
5. Supported Magento versions
6. Notes
7. Language package authors

## 1. Language Package Process

This is status of Spanish Language Pack, you can see how many percentage of this project has been done.

It is not fully translated? Feel free to contribute:
- [On Crowdin](https://crowdin.com/project/magento-2): It takes time to approve your contribution by Magento team.
- [On Github](https://github.com/Rioxygen/magento-2-spanish-mexican-language-pack/blob/master/HOW-TO-CONTRIBUTE.md): It's faster, our team will approve it after you send pull request.

**Install Spanish pack**:

```
composer require rioxygen/magento-2-spanish-mexican-language-pack:master
php bin/magento setup:static-content:deploy es_MX
php bin/magento cache:flush

```


**Update  Spanish pack**:

```
composer update rioxygen/magento-2-spanish-mexican-language-pack:master
php bin/magento setup:static-content:deploy es_MX
php bin/magento cache:flush

```

