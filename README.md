# magento2-helloworld-extension
===============================

Hello World Magento2 extension

Module was made for educational purposes only. 

Install
=======

1. Go to Magento2 root folder

2. Enter following commands to install module:

    ```bash
    composer config repositories.helloworld git https://github.com/magevishwas/magento2-helloworld-extension.git
    composer require magevishwas/magento2-helloworld-extension:dev-master
    ```
   Wait while dependencies are updated.

3. Enter following commands to enable module:

    ```bash
    php bin/magento module:enable Vishwas_Hello --clear-static-content
    php bin/magento setup:upgrade
    ```
4. Enable and configure Extension in Magento Admin.


