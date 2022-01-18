# [YooKassa Payout API SDK](../home.md)

# Class: \YooKassaPayout\Model\FormatType
### Namespace: [\YooKassaPayout\Model](../namespaces/yookassapayout-model.md)
---
**Summary:**

FormatType - формат запроса

---
### Constants
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [JSON](../classes/YooKassaPayout-Model-FormatType.md#constant_JSON) |  | Формат json |
| public | [XML](../classes/YooKassaPayout-Model-FormatType.md#constant_XML) |  | Формат xml |
---
### Properties
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| protected | [$validValues](../classes/YooKassaPayout-Model-FormatType.md#property_validValues) |  | Массив принимаемых enum'ом значений |
---
### Methods
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [getEnabledValues()](../classes/YooKassaPayout-Common-AbstractEnum.md#method_getEnabledValues) |  | Возвращает значения в enum'е значения которых разрешены |
| public | [getValidValues()](../classes/YooKassaPayout-Common-AbstractEnum.md#method_getValidValues) |  | Возвращает все значения в enum'e |
| public | [valueExists()](../classes/YooKassaPayout-Common-AbstractEnum.md#method_valueExists) |  | Проверяет наличие значения в enum'e |
---
### Details
* File: [lib/Model/FormatType.php](../../lib/Model/FormatType.php)
* Package: YooKassaPayout
* Class Hierarchy: 
  * [\YooKassaPayout\Common\AbstractEnum](../classes/YooKassaPayout-Common-AbstractEnum.md)
  * \YooKassaPayout\Model\FormatType
---
## Constants
<a name="constant_JSON" class="anchor"></a>
###### JSON
Формат json

```php
JSON = 'json'
```


<a name="constant_XML" class="anchor"></a>
###### XML
Формат xml

```php
XML = 'xml'
```


---
## Properties
<a name="property_validValues"></a>
#### protected $validValues : array
---
**Summary**

Массив принимаемых enum'ом значений

**Type:** <a href="../array"><abbr title="array">array</abbr></a>

**Details:**



---
## Methods
<a name="method_getEnabledValues" class="anchor"></a>
#### public getEnabledValues() : string[]

```php
static public getEnabledValues() : string[]
```

**Summary**

Возвращает значения в enum'е значения которых разрешены

**Details:**
* Inherited From: [\YooKassaPayout\Common\AbstractEnum](../classes/YooKassaPayout-Common-AbstractEnum.md)

**Returns:** string[] - Массив разрешённых значений


<a name="method_getValidValues" class="anchor"></a>
#### public getValidValues() : array

```php
static public getValidValues() : array
```

**Summary**

Возвращает все значения в enum'e

**Details:**
* Inherited From: [\YooKassaPayout\Common\AbstractEnum](../classes/YooKassaPayout-Common-AbstractEnum.md)

**Returns:** array - Массив значений в перечислении


<a name="method_valueExists" class="anchor"></a>
#### public valueExists() : bool

```php
static public valueExists(mixed $value) : bool
```

**Summary**

Проверяет наличие значения в enum'e

**Details:**
* Inherited From: [\YooKassaPayout\Common\AbstractEnum](../classes/YooKassaPayout-Common-AbstractEnum.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">mixed</code> | value  | Проверяемое значение |

**Returns:** bool - True если значение имеется, false если нет



---

### Top Namespaces

* [\YooKassaPayout](../namespaces/yookassapayout.md)

---

### Reports
* [Errors - 0](../reports/errors.md)
* [Markers - 0](../reports/markers.md)
* [Deprecated - 1](../reports/deprecated.md)

---

This document was automatically generated from source code comments on 2022-01-18 using [phpDocumentor](http://www.phpdoc.org/)

&copy; 2022 YooMoney