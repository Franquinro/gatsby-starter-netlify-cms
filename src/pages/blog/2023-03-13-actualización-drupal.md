---
templateKey: blog-post
title: Actualización Drupal
tags:
  - Web
---
```shell
#Simular actualización:
composer update drupal/core "drupal/core-*" --with-all-dependencies --dry-run

#Actualización:
composer update drupal/core "drupal/core-*" --with-all-dependencies

#Restaurar .htaccess:
cp ~/.BACKUPS/archivos_config_dru/.htaccess  ~/drupalUp/web/
cp ~/.BACKUPS/archivos_test/.htaccess  ~/drupalTest/drupalUp/web/
```