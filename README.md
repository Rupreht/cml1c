# Плагин cml1c
Плагин для обмена данными по протоколу [CommerceML](http://v8.1c.ru/edi/edi_stnd/90/) с приложением Shop-Script (Webasyst)

This is Fork from [cml1c](https://www.webasyst.ru/store/plugin/shop/cml1c/) (Webasyst) 2.0.2.41764 от 4 сентября 2015

## Requirements
  * PHP Framework [Webasyst](https://github.com/webasyst/webasyst-framework)
  * Webasyst Application [Shop-Script](http://www.shop-script.ru/platform/)

## Install

${WEB_ROOT} - корневая директория для Web сервера (Например: /home/user/public_html/)

    cd ${WEB_ROOT}wa-apps/shop/plugins/
    git clone git://github.com/Rupreht/cml1c.git
    (edit) ${WEB_ROOT}wa-config/apps/shop/plugins.php add 'cml1c' => true,

## Update

    cd ${WEB_ROOT}wa-apps/shop/plugins/cml1c/
    git pull


> Если разработчики из Webasyst поддерживать не будут, придется переименовать.

Код распространяется без изменения лицензии.

[Свободная лицензия LGPL](http://www.gnu.org/licenses/lgpl.html)
