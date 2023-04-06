# YooKassa API PHP Client Library

[![Build Status](https://img.shields.io/travis/yoomoney/yookassa-sdk-php)](https://travis-ci.org/yoomoney/yookassa-sdk-php)
[![Latest Stable Version](https://img.shields.io/packagist/v/yoomoney/yookassa-sdk-php?label=stable)](https://packagist.org/packages/yoomoney/yookassa-sdk-php)
[![Total Downloads](https://img.shields.io/packagist/dt/yoomoney/yookassa-sdk-php)](https://packagist.org/packages/yoomoney/yookassa-sdk-php)
[![Monthly Downloads](https://img.shields.io/packagist/dm/yoomoney/yookassa-sdk-php)](https://packagist.org/packages/yoomoney/yookassa-sdk-php)
[![License](https://img.shields.io/packagist/l/yoomoney/yookassa-sdk-php)](https://packagist.org/packages/yoomoney/yookassa-sdk-php)

Russian | [English](README.en.md)

Клиент для работы с платежами по [API ЮKassa](https://yookassa.ru/developers/api)
Подходит тем, у кого способ подключения к ЮKassa называется API.

[Документация по данному SDK](docs/readme.md).

## Требования
PHP 5.3.2 (и выше) с расширением libcurl

## Установка
### В консоли с помощью Composer

1. Установите менеджер пакетов Composer.
2. В консоли выполните команду
```bash
composer require yoomoney/yookassa-sdk-php
```

### В файле composer.json своего проекта
1. Добавьте строку `"yoomoney/yookassa-sdk-php": "^2.1"` в список зависимостей вашего проекта в файле composer.json
```
...
    "require": {
        "php": ">=5.3.2",
        "yoomoney/yookassa-sdk-php": "^2.1"
...
```
2. Обновите зависимости проекта. В консоли перейдите в каталог, где лежит composer.json, и выполните команду:
```bash
composer update
```
3. В коде вашего проекта подключите автозагрузку файлов нашего клиента:
```php
require __DIR__ . '/vendor/autoload.php';
```

### Вручную

1. Скачайте [архив YooKassa API PHP Client Library](https://git.yoomoney.ru/rest/api/latest/projects/SDK/repos/yookassa-sdk-php/archive?format=zip), распакуйте его и скопируйте каталог lib в нужное место в вашем проекте.
2. В коде вашего проекта подключите автозагрузку файлов нашего клиента:
```php
require __DIR__ . '/lib/autoload.php'; 
```

## Начало работы

1. Импортируйте нужные классы
```php
use YooKassa\Client;
```
2. Создайте экземпляр объекта клиента, задайте идентификатор магазина и секретный ключ (их можно получить в личном кабинете ЮKassa). [Как выпустить секретный ключ](https://yookassa.ru/docs/support/merchant/payments/implement/keys)
```php
$client = new Client();
$client->setAuth('shopId', 'secretKey');
```
3. Вызовите нужный метод API. 
   
   [Подробнее в документации к API ЮKassa](https://yookassa.ru/developers/api#create_payment).
   
   [Подробнее в документации к SDK ЮKassa](docs/readme.md).

## Примеры использования SDK

#### [Настройки SDK API ЮKassa](docs/examples/01-configuration.md)
* [Установка дополнительных настроек для Curl](docs/examples/01-configuration.md#Установка-дополнительных-настроек-для-Curl)
* [Аутентификация](docs/examples/01-configuration.md#Аутентификация)
* [Статистические данные об используемом окружении](docs/examples/01-configuration.md#Статистические-данные-об-используемом-окружении)
* [Получение информации о магазине](docs/examples/01-configuration.md#Получение-информации-о-магазине)
* [Работа с Webhook](docs/examples/01-configuration.md#Работа-с-Webhook)
* [Входящие уведомления](docs/examples/01-configuration.md#Входящие-уведомления)

#### [Работа с платежами](docs/examples/02-payments.md)
* [Запрос на создание платежа](docs/examples/02-payments.md#Запрос-на-создание-платежа)
* [Запрос на создание платежа через билдер](docs/examples/02-payments.md#Запрос-на-создание-платежа-через-билдер)
* [Запрос на частичное подтверждение платежа](docs/examples/02-payments.md#Запрос-на-частичное-подтверждение-платежа)
* [Запрос на отмену незавершенного платежа](docs/examples/02-payments.md#Запрос-на-отмену-незавершенного-платежа)
* [Получить информацию о платеже](docs/examples/02-payments.md#Получить-информацию-о-платеже)
* [Получить список платежей с фильтрацией](docs/examples/02-payments.md#Получить-список-платежей-с-фильтрацией)

#### [Работа с возвратами](docs/examples/03-refunds.md)
* [Запрос на создание возврата](docs/examples/03-refunds.md#Запрос-на-создание-возврата)
* [Запрос на создание возврата через билдер](docs/examples/03-refunds.md#Запрос-на-создание-возврата-через-билдер)
* [Получить информацию о возврате](docs/examples/03-refunds.md#Получить-информацию-о-возврате)
* [Получить список возвратов с фильтрацией](docs/examples/03-refunds.md#Получить-список-возвратов-с-фильтрацией)

#### [Работа с чеками](docs/examples/04-receipts.md)
* [Запрос на создание чека](docs/examples/04-receipts.md#Запрос-на-создание-чека)
* [Запрос на создание чека через билдер](docs/examples/04-receipts.md#Запрос-на-создание-чека-через-билдер)
* [Получить информацию о чеке](docs/examples/04-receipts.md#Получить-информацию-о-чеке)
* [Получить список чеков с фильтрацией](docs/examples/04-receipts.md#Получить-список-чеков-с-фильтрацией)

#### [Работа с безопасными сделками](docs/examples/05-deals.md)
* [Запрос на создание сделки](docs/examples/05-deals.md#Запрос-на-создание-сделки)
* [Запрос на создание сделки через билдер](docs/examples/05-deals.md#Запрос-на-создание-сделки-через-билдер)
* [Запрос на создание платежа с привязкой к сделке](docs/examples/05-deals.md#Запрос-на-создание-платежа-с-привязкой-к-сделке)
* [Получить информацию о сделке](docs/examples/05-deals.md#Получить-информацию-о-сделке)
* [Получить список сделок с фильтрацией](docs/examples/05-deals.md#Получить-список-сделок-с-фильтрацией)

#### [Работа с выплатами](docs/examples/06-payouts.md)
* [Запрос на выплату продавцу](docs/examples/06-payouts.md#Запрос-на-выплату-продавцу)
* [Получить информацию о выплате](docs/examples/06-payouts.md#Получить-информацию-о-выплате)

#### [Работа с персональными данными](docs/examples/08-personal-data.md)
* [Создание персональных данных](docs/examples/08-personal-data.md#Создание-персональных-данных)
* [Получить информацию о персональных данных](docs/examples/08-personal-data.md#Получить-информацию-о-персональных-данных)

#### [Работа со списком участников СБП](docs/examples/09-sbp-banks.md)
* [Получить список участников СБП](docs/examples/09-sbp-banks.md#Получить-список-участников-СБП)
