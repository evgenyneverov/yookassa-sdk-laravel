# [YooKassa API SDK](../home.md)

# Class: \YooKassa\Model\Payout\PayoutDestinationSbp
### Namespace: [\YooKassa\Model\Payout](../namespaces/yookassa-model-payout.md)
---
**Summary:**

Класс, описывающий метод оплаты, при оплате через ЮMoney


---
### Constants
* No constants found

---
### Properties
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [$bank_id](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#property_bank_id) |  | Идентификатор выбранного участника СБП — банка или платежного сервиса, подключенного к сервису |
| public | [$bankId](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#property_bankId) |  | Идентификатор выбранного участника СБП — банка или платежного сервиса, подключенного к сервису |
| public | [$phone](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#property_phone) |  | Телефон, к которому привязан счет получателя выплаты в системе участника СБП |
| public | [$recipient_checked](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#property_recipient_checked) |  | Проверка получателя выплаты |
| public | [$recipientChecked](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#property_recipientChecked) |  | Проверка получателя выплаты |
| public | [$type](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#property_type) |  | Тип объекта |
| public | [$type](../classes/YooKassa-Model-Payout-AbstractPayoutDestination.md#property_type) |  | Тип метода оплаты |

---
### Methods
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [__construct()](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#method___construct) |  |  |
| public | [__get()](../classes/YooKassa-Common-AbstractObject.md#method___get) |  | Возвращает значение свойства |
| public | [__isset()](../classes/YooKassa-Common-AbstractObject.md#method___isset) |  | Проверяет наличие свойства |
| public | [__set()](../classes/YooKassa-Common-AbstractObject.md#method___set) |  | Устанавливает значение свойства |
| public | [__unset()](../classes/YooKassa-Common-AbstractObject.md#method___unset) |  | Удаляет свойство |
| public | [fromArray()](../classes/YooKassa-Common-AbstractObject.md#method_fromArray) |  | Устанавливает значения свойств текущего объекта из массива |
| public | [getBankId()](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#method_getBankId) |  | Возвращает идентификатор выбранного участника СБП. |
| public | [getPhone()](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#method_getPhone) |  | Возвращает телефон, к которому привязан счет получателя выплаты в системе участника СБП. |
| public | [getRecipientChecked()](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#method_getRecipientChecked) |  | Возвращает признак тестовой операции |
| public | [getType()](../classes/YooKassa-Model-Payout-AbstractPayoutDestination.md#method_getType) |  | Возвращает тип метода оплаты |
| public | [jsonSerialize()](../classes/YooKassa-Common-AbstractObject.md#method_jsonSerialize) |  |  |
| public | [offsetExists()](../classes/YooKassa-Common-AbstractObject.md#method_offsetExists) |  |  |
| public | [offsetGet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetGet) |  |  |
| public | [offsetSet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetSet) |  |  |
| public | [offsetUnset()](../classes/YooKassa-Common-AbstractObject.md#method_offsetUnset) |  |  |
| public | [setBankId()](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#method_setBankId) |  | Устанавливает идентификатор выбранного участника СБП. |
| public | [setPhone()](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#method_setPhone) |  | Устанавливает телефон, к которому привязан счет получателя выплаты в системе участника СБП. |
| public | [setRecipientChecked()](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md#method_setRecipientChecked) |  | Устанавливает признак тестовой операции |
| public | [toArray()](../classes/YooKassa-Common-AbstractObject.md#method_toArray) |  | Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации Является алиасом метода AbstractObject::jsonSerialize() |
| protected | [getUnknownProperties()](../classes/YooKassa-Common-AbstractObject.md#method_getUnknownProperties) |  | Возвращает массив свойств которые не существуют, но были заданы у объекта |
| protected | [setType()](../classes/YooKassa-Model-Payout-AbstractPayoutDestination.md#method_setType) |  | Устанавливает тип метода оплаты |

---
### Details
* File: [lib/Model/Payout/PayoutDestinationSbp.php](../../lib/Model/Payout/PayoutDestinationSbp.php)
* Package: YooKassa
* Class Hierarchy:  
  * [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)
  * [\YooKassa\Model\Payout\AbstractPayoutDestination](../classes/YooKassa-Model-Payout-AbstractPayoutDestination.md)
  * \YooKassa\Model\Payout\PayoutDestinationSbp

---
## Properties
<a name="property_bank_id"></a>
#### public $bank_id : string
---
***Description***

Идентификатор выбранного участника СБП — банка или платежного сервиса, подключенного к сервису

**Type:** <a href="string"><abbr title="string">string</abbr></a>

**Details:**


<a name="property_bankId"></a>
#### public $bankId : string
---
***Description***

Идентификатор выбранного участника СБП — банка или платежного сервиса, подключенного к сервису

**Type:** <a href="string"><abbr title="string">string</abbr></a>

**Details:**


<a name="property_phone"></a>
#### public $phone : string
---
***Description***

Телефон, к которому привязан счет получателя выплаты в системе участника СБП

**Type:** <a href="string"><abbr title="string">string</abbr></a>

**Details:**


<a name="property_recipient_checked"></a>
#### public $recipient_checked : string
---
***Description***

Проверка получателя выплаты

**Type:** <a href="string"><abbr title="string">string</abbr></a>

**Details:**


<a name="property_recipientChecked"></a>
#### public $recipientChecked : string
---
***Description***

Проверка получателя выплаты

**Type:** <a href="string"><abbr title="string">string</abbr></a>

**Details:**


<a name="property_type"></a>
#### public $type : string
---
***Description***

Тип объекта

**Type:** <a href="string"><abbr title="string">string</abbr></a>

**Details:**


<a name="property_type"></a>
#### public $type : string
---
***Description***

Тип метода оплаты

**Type:** <a href="string"><abbr title="string">string</abbr></a>

**Details:**
* Inherited From: [\YooKassa\Model\Payout\AbstractPayoutDestination](../classes/YooKassa-Model-Payout-AbstractPayoutDestination.md)



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() : mixed

```php
public __construct() : mixed
```

**Details:**
* Inherited From: [\YooKassa\Model\Payout\PayoutDestinationSbp](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md)

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


<a name="method_getBankId" class="anchor"></a>
#### public getBankId() : string

```php
public getBankId() : string
```

**Summary**

Возвращает идентификатор выбранного участника СБП.

**Details:**
* Inherited From: [\YooKassa\Model\Payout\PayoutDestinationSbp](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md)

**Returns:** string - Идентификатор выбранного участника СБП


<a name="method_getPhone" class="anchor"></a>
#### public getPhone() : string

```php
public getPhone() : string
```

**Summary**

Возвращает телефон, к которому привязан счет получателя выплаты в системе участника СБП.

**Details:**
* Inherited From: [\YooKassa\Model\Payout\PayoutDestinationSbp](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md)

**Returns:** string - Телефон, к которому привязан счет получателя выплаты в системе участника СБП


<a name="method_getRecipientChecked" class="anchor"></a>
#### public getRecipientChecked() : bool

```php
public getRecipientChecked() : bool
```

**Summary**

Возвращает признак тестовой операции

**Details:**
* Inherited From: [\YooKassa\Model\Payout\PayoutDestinationSbp](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md)

**Returns:** bool - Признак тестовой операции


<a name="method_getType" class="anchor"></a>
#### public getType() : string

```php
public getType() : string
```

**Summary**

Возвращает тип метода оплаты

**Details:**
* Inherited From: [\YooKassa\Model\Payout\AbstractPayoutDestination](../classes/YooKassa-Model-Payout-AbstractPayoutDestination.md)

**Returns:** string - Тип метода оплаты


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


<a name="method_setBankId" class="anchor"></a>
#### public setBankId() : $this

```php
public setBankId(string $bankId) : $this
```

**Summary**

Устанавливает идентификатор выбранного участника СБП.

**Details:**
* Inherited From: [\YooKassa\Model\Payout\PayoutDestinationSbp](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | bankId  | Идентификатор выбранного участника СБП |

**Returns:** $this - 


<a name="method_setPhone" class="anchor"></a>
#### public setPhone() : $this

```php
public setPhone(string $phone) : $this
```

**Summary**

Устанавливает телефон, к которому привязан счет получателя выплаты в системе участника СБП.

**Details:**
* Inherited From: [\YooKassa\Model\Payout\PayoutDestinationSbp](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | phone  | Телефон, к которому привязан счет получателя выплаты в системе участника СБП |

**Returns:** $this - 


<a name="method_setRecipientChecked" class="anchor"></a>
#### public setRecipientChecked() : mixed

```php
public setRecipientChecked(bool $value) : mixed
```

**Summary**

Устанавливает признак тестовой операции

**Details:**
* Inherited From: [\YooKassa\Model\Payout\PayoutDestinationSbp](../classes/YooKassa-Model-Payout-PayoutDestinationSbp.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">bool</code> | value  | Признак тестовой операции |

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


<a name="method_setType" class="anchor"></a>
#### protected setType() : mixed

```php
protected setType(string $value) : mixed
```

**Summary**

Устанавливает тип метода оплаты

**Details:**
* Inherited From: [\YooKassa\Model\Payout\AbstractPayoutDestination](../classes/YooKassa-Model-Payout-AbstractPayoutDestination.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | value  | Тип метода оплаты |

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