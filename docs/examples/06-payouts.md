## Работа с выплатами

Выплата — это сумма денег, которую вы переводите физическому лицу или самозанятому. С помощью API вы можете создать выплату и получить о ней актуальную информацию.

Выплаты используются в следующих платежных решениях ЮKassa:

* Выплаты — вы как компания переводите деньги физическим лицам и самозанятым (например, выплачиваете кэшбек пользователям).
* Безопасная сделка — ваша платформа в рамках созданной сделки переводит оплату от одного физического лица другому.

SDK позволяет проводить выплаты, а также получать информацию о них.

Объект выплаты `PayoutResponse` содержит всю информацию о выплате, актуальную на текущий момент времени. Он формируется при создании выплаты и приходит в ответ на любой запрос, связанный с выплатами.

Набор возвращаемых параметров зависит от статуса объекта (значение параметра status) и того, какие параметры вы передали в запросе на создание выплаты.

* [Запрос на выплату продавцу](#Запрос-на-выплату-продавцу)
* [Получить информацию о выплате](#Получить-информацию-о-выплате)

---

### Запрос на выплату продавцу <a name="Запрос-на-выплату-продавцу"></a>

[Выплата продавцу в документации](https://yookassa.ru/developers/api?lang=php#create_payout)

Запрос позволяет перечислить продавцу оплату за выполненную услугу или проданный товар в рамках Безопасной сделки. 
Выплату можно сделать на банковскую карту или на кошелек ЮMoney.

В ответ на запрос придет объект выплаты - `PayoutResponse` в актуальном статусе.

```php
require_once 'vendor/autoload.php';

$client = new \YooKassa\Client();
$client->setAuth('xxxxxx', 'test_XXXXXXX');

$request = array(
    'amount' => array(
        'value' => '80.00',
        'currency' => 'RUB',
    ),
    'payout_destination_data' => array(
        'type' => PaymentMethodType::SBP,
        'bank_id' => '100000000111',
        'phone' => '79001002030',
    ),
    'description' => 'Выплата по заказу №37',
    'metadata' => array(
        'order_id' => '37',
    ),
    'payment_method_id' => '2a217a2d-000f-5000-9000-1bd6f124af9c',
    'self_employed' => array('id' => 'se-285c0ab7-0003-5000-9000-0e1166498fda'),
    'receipt_data' => array(
        'service_name' => 'Оказание услуг по доставке товара', 
        'amount' => array(
            'value' => '10.00', 
            'currency' => 'RUB',
        ),
    ),
    'personal_data' => array(
        array(
            'id' => 'pd-285c0ab7-0003-5000-9000-0e1166498fda',
        ),
    ),
);
$idempotenceKey = uniqid('', true);
try {
    $result = $client->createPayout($request, $idempotenceKey);
} catch (\Exception $e) {
    $result = $e;
}

var_dump($result);
```
[Подробнее о проведении выплат](https://yookassa.ru/developers/solutions-for-platforms/safe-deal/integration/payouts)

---

### Получить информацию о выплате <a name="Получить-информацию-о-выплате"></a>

[Информация о выплате в документации](https://yookassa.ru/developers/api?lang=php#get_payout)

Запрос позволяет получить информацию о текущем состоянии выплаты по ее уникальному идентификатору.

Данные для [аутентификации](https://yookassa.ru/developers/using-api/interaction-format#auth) запросов зависят от того, какое платежное решение вы используете — [обычные выплаты](https://yookassa.ru/developers/payouts/overview) или выплаты в рамках [Безопасной сделки](https://yookassa.ru/developers/solutions-for-platforms/safe-deal/basics).

В ответ на запрос придет объект выплаты - `PayoutResponse` в актуальном статусе.

```php
require_once 'vendor/autoload.php';

$client = new \YooKassa\Client();
$client->setAuth('xxxxxx', 'test_XXXXXXX');

$payoutId = 'po-285c0ab7-0003-5000-9000-0e1166498fda';
try {
    $response = $client->getPayoutInfo($payoutId);
} catch (\Exception $e) {
    $response = $e;
}

var_dump($response);
```
