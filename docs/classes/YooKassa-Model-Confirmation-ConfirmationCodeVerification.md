# [YooKassa API SDK](../home.md)

# Class: \YooKassa\Model\Confirmation\ConfirmationCodeVerification
### Namespace: [\YooKassa\Model\Confirmation](../namespaces/yookassa-model-confirmation.md)
---
**Summary:**

Сценарий при котором необходимо получить одноразовый код от плательщика для подтверждения платежа


---
### Constants
* No constants found

---
### Properties
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [$type](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md#property_type) |  |  |

---
### Methods
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [__construct()](../classes/YooKassa-Model-Confirmation-ConfirmationCodeVerification.md#method___construct) |  |  |
| public | [__get()](../classes/YooKassa-Common-AbstractObject.md#method___get) |  | Возвращает значение свойства |
| public | [__isset()](../classes/YooKassa-Common-AbstractObject.md#method___isset) |  | Проверяет наличие свойства |
| public | [__set()](../classes/YooKassa-Common-AbstractObject.md#method___set) |  | Устанавливает значение свойства |
| public | [__unset()](../classes/YooKassa-Common-AbstractObject.md#method___unset) |  | Удаляет свойство |
| public | [fromArray()](../classes/YooKassa-Common-AbstractObject.md#method_fromArray) |  | Устанавливает значения свойств текущего объекта из массива |
| public | [getConfirmationData()](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md#method_getConfirmationData) |  |  |
| public | [getConfirmationToken()](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md#method_getConfirmationToken) |  |  |
| public | [getConfirmationUrl()](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md#method_getConfirmationUrl) |  |  |
| public | [getType()](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md#method_getType) |  | Возвращает тип подтверждения платежа |
| public | [jsonSerialize()](../classes/YooKassa-Common-AbstractObject.md#method_jsonSerialize) |  |  |
| public | [offsetExists()](../classes/YooKassa-Common-AbstractObject.md#method_offsetExists) |  |  |
| public | [offsetGet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetGet) |  |  |
| public | [offsetSet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetSet) |  |  |
| public | [offsetUnset()](../classes/YooKassa-Common-AbstractObject.md#method_offsetUnset) |  |  |
| public | [toArray()](../classes/YooKassa-Common-AbstractObject.md#method_toArray) |  | Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации Является алиасом метода AbstractObject::jsonSerialize() |
| protected | [getUnknownProperties()](../classes/YooKassa-Common-AbstractObject.md#method_getUnknownProperties) |  | Возвращает массив свойств которые не существуют, но были заданы у объекта |
| protected | [setType()](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md#method_setType) |  | Устанавливает тип подтверждения платежа |

---
### Details
* File: [lib/Model/Confirmation/ConfirmationCodeVerification.php](../../lib/Model/Confirmation/ConfirmationCodeVerification.php)
* Package: YooKassa
* Class Hierarchy:  
  * [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)
  * [\YooKassa\Model\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md)
  * \YooKassa\Model\Confirmation\ConfirmationCodeVerification

---
## Properties
<a name="property_type"></a>
#### public $type : string
---
**Type:** <a href="string"><abbr title="string">string</abbr></a>

**Details:**
* Inherited From: [\YooKassa\Model\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md)



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() : mixed

```php
public __construct() : mixed
```

**Details:**
* Inherited From: [\YooKassa\Model\Confirmation\ConfirmationCodeVerification](../classes/YooKassa-Model-Confirmation-ConfirmationCodeVerification.md)

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


<a name="method_getConfirmationData" class="anchor"></a>
#### public getConfirmationData() : string

```php
public getConfirmationData() : string
```

**Description**

Для ConfirmationQr

**Details:**
* Inherited From: [\YooKassa\Model\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md)

**Returns:** string - 


<a name="method_getConfirmationToken" class="anchor"></a>
#### public getConfirmationToken() : string

```php
public getConfirmationToken() : string
```

**Description**

Для ConfirmationEmbedded

**Details:**
* Inherited From: [\YooKassa\Model\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md)

**Returns:** string - 


<a name="method_getConfirmationUrl" class="anchor"></a>
#### public getConfirmationUrl() : string

```php
public getConfirmationUrl() : string
```

**Description**

Для ConfirmationRedirect

**Details:**
* Inherited From: [\YooKassa\Model\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md)

**Returns:** string - 


<a name="method_getType" class="anchor"></a>
#### public getType() : string

```php
public getType() : string
```

**Summary**

Возвращает тип подтверждения платежа

**Details:**
* Inherited From: [\YooKassa\Model\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md)

**Returns:** string - 


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


<a name="method_setType" class="anchor"></a>
#### protected setType() : mixed

```php
protected setType(string $value) : mixed
```

**Summary**

Устанавливает тип подтверждения платежа

**Details:**
* Inherited From: [\YooKassa\Model\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Confirmation-AbstractConfirmation.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | value  |  |

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