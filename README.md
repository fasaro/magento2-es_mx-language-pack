## Paquete de idioma español (MX) para Magento 2

La plataforma Magento 2 aprueba múltiples idiomas en todo el mundo, por lo que se crea **Magento 2 Spanish es_MX Language Pack** para llevar a cabo el cambio de idioma a través del diccionario de traducción en línea en la tienda Magento 2. El diccionario de traducción en línea se desarrolló en base al proyecto comunitario en Crowdin, donde puede descargar más de 25,000 frases en español para reemplazar el idioma predeterminado.
El paquete de idioma español Magento 2 incluirá la lista de guías completas que son esenciales para la traducción perfecta. Por favor, siga el tema para terminar la interpretación en absoluto.

**Instalalar paquete en Español**:

```
composer require fasaro/magento2-es_mx-language-pack dev-master
php bin/magento setup:static-content:deploy es_MX
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```


**Actualizacón paquete en Español**:

```
composer update fasaro/magento2-es_mx-language-pack dev-master
php bin/magento setup:static-content:deploy es_MX
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```
How to active Spanish language pack

Now time to active the Spanish language pack for your Magento 2 store. From Magento 2 admin panel, navigate to Stores > Configuration > General > Locale Options {{Magento 2 Spanish language pack}}

## Magento 2 Spanish (MX) Language Pack

Magento 2 platform approves multiple languages around the world, so **Magento 2 Spanish es_MX Language Pack** is created to conduct the change of language via the in-line translation dictionary on Magento 2 store. The in-line translation dictionary is developed based on the community project at Crowdin where you can download over 25,000 phrases in Spanish to replace the default language.
			Magento 2 Spanish Language Package will involve the list of comprehensive guides which are essential for the perfect translation. Please keep tracking the topic to finish the interpretation at all.

Language Package Process

This is status of Spanish Language Pack, you can see how many percentage of this project has been done.

language pack

It is not fully translated? Feel free to contribute:

    On Crowdin: It takes time to approve your contribution by Magento team.
    On Github: It's faster, our team will approve it after you send pull request.

Find other language packs here
2. How to Install Spanish Language Pack

There are 3 different methods to install this language pack.
✓ Method #1. Composer method (Recommend)

Install the Spanish language pack via composer is never easier.

**Install Spanish pack**:

```
composer require fasaro/magento2-es_mx-language-pack dev-master
php bin/magento setup:static-content:deploy es_MX
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```


**Update  Spanish pack**:

```
composer update fasaro/magento2-es_mx-language-pack dev-master
php bin/magento setup:static-content:deploy es_MX
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```
How to active Spanish language pack

Now time to active the Spanish language pack for your Magento 2 store. From Magento 2 admin panel, navigate to Stores > Configuration > General > Locale Options {{Magento 2 Spanish language pack}}
