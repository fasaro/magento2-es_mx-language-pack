## Paquete de idioma español (MX) para Magento 2

La plataforma Magento 2 aprueba múltiples idiomas en todo el mundo, por lo que se crea **Magento 2 Spanish es_MX Language Pack** para llevar a cabo el cambio de idioma a través del diccionario de traducción en línea en la tienda Magento 2. El diccionario de traducción en línea se desarrolló en base al proyecto comunitario en Crowdin, donde puede descargar más de 25,000 frases en español para reemplazar el idioma predeterminado.
El paquete de idioma español Magento 2 incluirá la lista de guías completas que son esenciales para la traducción perfecta. Por favor, siga el tema para terminar la interpretación en absoluto.

**Proceso del paquete de idiomas**

Este es el estado del paquete de idioma español, puede ver cuántos porcentajes de este proyecto se han realizado.

paquete de idioma

¿No está completamente traducido? Siéntase libre de contribuir:

     En Crowdin: lleva tiempo aprobar su contribución del equipo de Magento.
     En Github: es más rápido, nuestro equipo lo aprobará después de que envíe la solicitud de extracción.

**Compatibilidad**
Magento CE 2.1.x, 2.2.x, 2.3.x

Instalar el paquete de idioma español a través del compositor (recomendable)

**Instalalar paquete en Español**:

```
php bin/magento maintenance:enable
composer require fasaro/magento2-es_mx-language-pack dev-master
php bin/magento setup:static-content:deploy es_MX
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
php bin/magento maintenance:disable

```

**Actualizacón paquete en Español**:

```
php bin/magento maintenance:enable
composer update fasaro/magento2-es_mx-language-pack dev-master
php bin/magento setup:static-content:deploy es_MX
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
php bin/magento maintenance:disable

```
**Como activar el paquete en Español**

Como activar el paquete de idioma español para su tienda Magento 2. Desde el panel de administración de Magento 2 
  →   Stores > Configuration > General > Locale Options > Locale > Español (Mexico)



## Magento 2 Spanish (MX) Language Pack

Magento 2 platform approves multiple languages around the world, so **Magento 2 Spanish es_MX Language Pack** is created to conduct the change of language via the in-line translation dictionary on Magento 2 store. The in-line translation dictionary is developed based on the community project at Crowdin where you can download over 25,000 phrases in Spanish to replace the default language.
			Magento 2 Spanish Language Package will involve the list of comprehensive guides which are essential for the perfect translation. Please keep tracking the topic to finish the interpretation at all.

**Language Package Process**

This is status of Spanish Language Pack, you can see how many percentage of this project has been done.

language pack

It is not fully translated? Feel free to contribute:

    On Crowdin: It takes time to approve your contribution by Magento team.
    On Github: It's faster, our team will approve it after you send pull request.

**Compatibility**
Magento CE 2.1.x, 2.2.x, 2.3.x

Install the Spanish language pack via composer (recommended)

**Install Spanish pack**:

```
php bin/magento maintenance:enable
composer require fasaro/magento2-es_mx-language-pack dev-master
php bin/magento setup:static-content:deploy es_MX
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
php bin/magento maintenance:disable

```


**Update  Spanish pack**:

```
php bin/magento maintenance:enable
composer update fasaro/magento2-es_mx-language-pack dev-master
php bin/magento setup:static-content:deploy es_MX
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
php bin/magento maintenance:disable

```
**How to Activate Spanish Language Pack**

Now time to active the Spanish language pack for your Magento 2 store. From Magento 2 admin panel, navigate to 
  →   Stores > Configuration > General > Locale Options > Locale > Español (Mexico)
