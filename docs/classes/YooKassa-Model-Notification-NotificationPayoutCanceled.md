# [YooKassa API SDK](../home.md)

# Class: \YooKassa\Model\Notification\NotificationPayoutCanceled
### Namespace: [\YooKassa\Model\Notification](../namespaces/yookassa-model-notification.md)
---
**Summary:**

Класс объекта, присылаемого API при изменении статуса выплаты на "canceled"


---
### Examples
03-notification.php 3 Пример скрипта обработки уведомления

```php

```

---
### Constants
* No constants found

---
### Properties
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [$event](../classes/YooKassa-Model-Notification-AbstractNotification.md#property_event) |  | Тип события |
| public | [$object](../classes/YooKassa-Model-Notification-NotificationPayoutCanceled.md#property_object) |  | Объект с информацией о выплате |
| public | [$type](../classes/YooKassa-Model-Notification-AbstractNotification.md#property_type) |  | Тип уведомления в виде строки |

---
### Methods
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [__construct()](../classes/YooKassa-Model-Notification-NotificationPayoutCanceled.md#method___construct) |  | Конструктор объекта нотификации |
| public | [__get()](../classes/YooKassa-Common-AbstractObject.md#method___get) |  | Возвращает значение свойства |
| public | [__isset()](../classes/YooKassa-Common-AbstractObject.md#method___isset) |  | Проверяет наличие свойства |
| public | [__set()](../classes/YooKassa-Common-AbstractObject.md#method___set) |  | Устанавливает значение свойства |
| public | [__unset()](../classes/YooKassa-Common-AbstractObject.md#method___unset) |  | Удаляет свойство |
| public | [fromArray()](../classes/YooKassa-Common-AbstractObject.md#method_fromArray) |  | Устанавливает значения свойств текущего объекта из массива |
| public | [getEvent()](../classes/YooKassa-Model-Notification-AbstractNotification.md#method_getEvent) |  | Возвращает тип события |
| public | [getObject()](../classes/YooKassa-Model-Notification-NotificationPayoutCanceled.md#method_getObject) |  | Возвращает объект с информацией о выплате, уведомление о которой хранится в текущем объекте |
| public | [getType()](../classes/YooKassa-Model-Notification-AbstractNotification.md#method_getType) |  | Возвращает тип уведомления |
| public | [jsonSerialize()](../classes/YooKassa-Common-AbstractObject.md#method_jsonSerialize) |  |  |
| public | [offsetExists()](../classes/YooKassa-Common-AbstractObject.md#method_offsetExists) |  |  |
| public | [offsetGet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetGet) |  |  |
| public | [offsetSet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetSet) |  |  |
| public | [offsetUnset()](../classes/YooKassa-Common-AbstractObject.md#method_offsetUnset) |  |  |
| public | [toArray()](../classes/YooKassa-Common-AbstractObject.md#method_toArray) |  | Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации Является алиасом метода AbstractObject::jsonSerialize() |
| protected | [getUnknownProperties()](../classes/YooKassa-Common-AbstractObject.md#method_getUnknownProperties) |  | Возвращает массив свойств которые не существуют, но были заданы у объекта |
| protected | [setEvent()](../classes/YooKassa-Model-Notification-AbstractNotification.md#method_setEvent) |  | Устанавливает тип события |
| protected | [setType()](../classes/YooKassa-Model-Notification-AbstractNotification.md#method_setType) |  | Устанавливает тип уведомления |

---
### Details
* File: [lib/Model/Notification/NotificationPayoutCanceled.php](../../lib/Model/Notification/NotificationPayoutCanceled.php)
* Package: YooKassa
* Class Hierarchy:  
  * [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)
  * [\YooKassa\Model\Notification\AbstractNotification](../classes/YooKassa-Model-Notification-AbstractNotification.md)
  * \YooKassa\Model\Notification\NotificationPayoutCanceled

---
## Properties
<a name="property_event"></a>
#### public $event : string
---
***Description***

Тип события

**Type:** <a href="string"><abbr title="string">string</abbr></a>

**Details:**
* Inherited From: [\YooKassa\Model\Notification\AbstractNotification](../classes/YooKassa-Model-Notification-AbstractNotification.md)


<a name="property_object"></a>
#### public $object : \YooKassa\Model\PayoutInterface
---
***Description***

Объект с информацией о выплате

**Type:** <a href="classes/YooKassa-Model-PayoutInterface.html"><abbr title="\YooKassa\Model\PayoutInterface">PayoutInterface</abbr></a>

**Details:**


<a name="property_type"></a>
#### public $type : string
---
***Description***

Тип уведомления в виде строки

**Type:** <a href="string"><abbr title="string">string</abbr></a>

**Details:**
* Inherited From: [\YooKassa\Model\Notification\AbstractNotification](../classes/YooKassa-Model-Notification-AbstractNotification.md)



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() : mixed

```php
public __construct(array $source) : mixed
```

**Summary**

Конструктор объекта нотификации

**Description**

Инициализирует текущий объект из ассоциативного массива, который просто путём JSON десериализации получен из
тела пришедшего запроса. При конструировании проверяется валидность типа передаваемого уведомления, если
передать уведомление не того типа, будет сгенерировано исключение типа {@link}

**Details:**
* Inherited From: [\YooKassa\Model\Notification\NotificationPayoutCanceled](../classes/YooKassa-Model-Notification-NotificationPayoutCanceled.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">array</code> | source  | Ассоциативный массив с информацией об уведомлении |

##### Throws:
| Type | Description |
| ---- | ----------- |
| \YooKassa\Common\Exceptions\InvalidPropertyValueException|\Exception | Генерируется если значение типа нотификации или события не равны "notification" и "payout.canceled" соответственно, что может говорить о том, что переданные в конструктор данные не являются уведомлением нужного типа. |

**Returns:** mixed - 


<a name="method___get" class="anchor"></a>
#### public __get() : mixed

```php
public __get(string $propertyName) : mixed
```

**Summary**

Возвращает значение свойства

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | propertyName  | Имя свойства |

**Returns:** mixed - Значение свойства


<a name="method___isset" class="anchor"></a>
#### public __isset() : bool

```php
public __isset(string $propertyName) : bool
```

**Summary**

Проверяет наличие свойства

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | propertyName  | Имя проверяемого свойства |

**Returns:** bool - True если свойство имеется, false если нет


<a name="method___set" class="anchor"></a>
#### public __set() : mixed

```php
public __set(string $propertyName, mixed $value) : mixed
```

**Summary**

Устанавливает значение свойства

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | propertyName  | Имя свойства |
| <code lang="php">mixed</code> | value  | Значение свойства |

**Returns:** mixed - 


<a name="method___unset" class="anchor"></a>
#### public __unset() : mixed

```php
public __unset(string $propertyName) : mixed
```

**Summary**

Удаляет свойство

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | propertyName  | Имя удаляемого свойства |

**Returns:** mixed - 


<a name="method_fromArray" class="anchor"></a>
#### public fromArray() : mixed

```php
public fromArray(array|\Traversable $sourceArray) : mixed
```

**Summary**

Устанавливает значения свойств текущего объекта из массива

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">array OR \Traversable</code> | sourceArray  | Ассоциативный массив с настройками |

**Returns:** mixed - 


<a name="method_getEvent" class="anchor"></a>
#### public getEvent() : string

```php
public getEvent() : string
```

**Summary**

Возвращает тип события

**Description**

Тип события - одна из констант, указанных в перечислении {@link}.

**Details:**
* Inherited From: [\YooKassa\Model\Notification\AbstractNotification](../classes/YooKassa-Model-Notification-AbstractNotification.md)

**Returns:** string - Тип события


<a name="method_getObject" class="anchor"></a>
#### public getObject() : \YooKassa\Model\PayoutInterface

```php
public getObject() : \YooKassa\Model\PayoutInterface
```

**Summary**

Возвращает объект с информацией о выплате, уведомление о которой хранится в текущем объекте

**Description**

Так как нотификация может быть сгенерирована и поставлена в очередь на отправку гораздо раньше, чем она будет
получена на сайте, то опираться на статус пришедшей выплаты не стоит, лучше запросить текущую информацию о
выплате у API.

**Details:**
* Inherited From: [\YooKassa\Model\Notification\NotificationPayoutCanceled](../classes/YooKassa-Model-Notification-NotificationPayoutCanceled.md)

**Returns:** \YooKassa\Model\PayoutInterface - Объект с информацией о выплате


<a name="method_getType" class="anchor"></a>
#### public getType() : string

```php
public getType() : string
```

**Summary**

Возвращает тип уведомления

**Description**

Тип уведомления - одна из констант, указанных в перечислении {@link}.

**Details:**
* Inherited From: [\YooKassa\Model\Notification\AbstractNotification](../classes/YooKassa-Model-Notification-AbstractNotification.md)

**Returns:** string - Тип уведомления в виде строки


<a name="method_jsonSerialize" class="anchor"></a>
#### public jsonSerialize() : mixed

```php
public jsonSerialize() : mixed
```

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

**Returns:** mixed - 


<a name="method_offsetExists" class="anchor"></a>
#### public offsetExists() : mixed

```php
public offsetExists(mixed $offset) : mixed
```

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">mixed</code> | offset  |  |

**Returns:** mixed - 


<a name="method_offsetGet" class="anchor"></a>
#### public offsetGet() : mixed

```php
public offsetGet(mixed $offset) : mixed
```

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">mixed</code> | offset  |  |

**Returns:** mixed - 


<a name="method_offsetSet" class="anchor"></a>
#### public offsetSet() : mixed

```php
public offsetSet(mixed $offset, mixed $value) : mixed
```

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">mixed</code> | offset  |  |
| <code lang="php">mixed</code> | value  |  |

**Returns:** mixed - 


<a name="method_offsetUnset" class="anchor"></a>
#### public offsetUnset() : mixed

```php
public offsetUnset(mixed $offset) : mixed
```

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">mixed</code> | offset  |  |

**Returns:** mixed - 


<a name="method_toArray" class="anchor"></a>
#### public toArray() : array

```php
public toArray() : array
```

**Summary**

Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации
Является алиасом метода AbstractObject::jsonSerialize()

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

**Returns:** array - Ассоциативный массив со свойствами текущего объекта


<a name="method_getUnknownProperties" class="anchor"></a>
#### protected getUnknownProperties() : array

```php
protected getUnknownProperties() : array
```

**Summary**

Возвращает массив свойств которые не существуют, но были заданы у объекта

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

**Returns:** array - Ассоциативный массив с не существующими у текущего объекта свойствами


<a name="method_setEvent" class="anchor"></a>
#### protected setEvent() : mixed

```php
protected setEvent(string $value) : mixed
```

**Summary**

Устанавливает тип события

**Details:**
* Inherited From: [\YooKassa\Model\Notification\AbstractNotification](../classes/YooKassa-Model-Notification-AbstractNotification.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | value  | Тип события |

##### Throws:
| Type | Description |
| ---- | ----------- |
| \YooKassa\Common\Exceptions\EmptyPropertyValueException | Выбрасывается если в качестве значения было передано пустое значение |
| \YooKassa\Common\Exceptions\InvalidPropertyValueException | Выбрасывается если переданное значение не найдено в перечислении типов событий |
| \YooKassa\Common\Exceptions\InvalidPropertyValueTypeException | Выбрасывается если переданное значение не является строкой |

**Returns:** mixed - 


<a name="method_setType" class="anchor"></a>
#### protected setType() : mixed

```php
protected setType(string $value) : mixed
```

**Summary**

Устанавливает тип уведомления

**Details:**
* Inherited From: [\YooKassa\Model\Notification\AbstractNotification](../classes/YooKassa-Model-Notification-AbstractNotification.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | value  | Тип уведомления |

##### Throws:
| Type | Description |
| ---- | ----------- |
| \YooKassa\Common\Exceptions\EmptyPropertyValueException | Выбрасывается если в качестве значения было передано пустое значение |
| \YooKassa\Common\Exceptions\InvalidPropertyValueException | Выбрасывается если переданное значение не найдено в перечислении типов нотификаций |
| \YooKassa\Common\Exceptions\InvalidPropertyValueTypeException | Выбрасывается если переданное значение не является строкой |

**Returns:** mixed - 



---

### Top Namespaces

* [\YooKassa](../namespaces/yookassa.md)

---

### Reports
* [Errors - 0](../reports/errors.md)
* [Markers - 1](../reports/markers.md)
* [Deprecated - 25](../reports/deprecated.md)

---

This document was automatically generated from source code comments on 2023-04-06 using [phpDocumentor](http://www.phpdoc.org/)

&copy; 2023 YooMoney