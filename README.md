#  Home work 2

<div align = "center">
<img src="/screens/hw02.png" width="100%">  
<br>
</div>

<p align="center">
<img src="https://img.shields.io/badge/PHP-7.3-orange.svg" alt="PHP-7.3"/>
<img src="https://img.shields.io/badge/Symfony-4.2.8-blue.svg">
<img src="https://img.shields.io/badge/licence-MIT-lightgray.svg" alt="Licence MIT"/>
</p>

## Информация для проверяющего
* выбран фреймворк `Symfony 4`
* "настройка" для задания №1 хранится в файле [myConfig.yaml](/config/packages/myConfig.yaml) и он привязан к Container в файле [services.yaml](/config/services.yaml) в секции `bind:`
* Скрипт сборки проекта должен запускаться примерно так:
    ```
  php phing.phar -f ./build/production/build.xml -Dapp.destination.path=/Users/eugem/Developer/PHP/php-3HW02.prod -Dapp.domain=test.com -Ddb_driver=mysql -Ddb_user=eug -Ddb_password=123 -Ddb_host=php-3HW02.mac -Ddb_port=8889 -Ddb_name=php3hw02
  ```
  параметры `-Dapp.destination.path` и `-Dapp.domain` должны быть обязательно указаны
* применена дополнительная настройка web-сервера nginx:
 <img src="/screens/nginx.png" width="50%">

## Main functionality
* PSR-standards
* Composer


## Credits
* thanks to **Albert Stepantsev** and to his [awesome school](https://pr-of-it.ru/courses/php-3.html)

## License

This project is licensed under the MIT License.
