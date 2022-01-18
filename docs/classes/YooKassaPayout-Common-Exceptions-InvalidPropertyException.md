# [YooKassa Payout API SDK](../home.md)

# Class: \YooKassaPayout\Common\Exceptions\InvalidPropertyException
### Namespace: [\YooKassaPayout\Common\Exceptions](../namespaces/yookassapayout-common-exceptions.md)
---
**Summary:**

Class InvalidPropertyException

---
### Constants
* No constants found
---
### Methods
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [__construct()](../classes/YooKassaPayout-Common-Exceptions-InvalidPropertyException.md#method___construct) |  | InvalidValueException constructor. |
| public | [getProperty()](../classes/YooKassaPayout-Common-Exceptions-InvalidPropertyException.md#method_getProperty) |  | Возвращает название свойства |
---
### Details
* File: [lib/Common/Exceptions/InvalidPropertyException.php](../../lib/Common/Exceptions/InvalidPropertyException.php)
* Package: YooKassaPayout
* Class Hierarchy: 
  * [\InvalidArgumentException](\InvalidArgumentException)
  * \YooKassaPayout\Common\Exceptions\InvalidPropertyException

---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() : mixed

```php
public __construct(string $message = '', int $code, string $property = '') : mixed
```

**Summary**

InvalidValueException constructor.

**Details:**
* Inherited From: [\YooKassaPayout\Common\Exceptions\InvalidPropertyException](../classes/YooKassaPayout-Common-Exceptions-InvalidPropertyException.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | message  | Сообщение об ошибке |
| <code lang="php">int</code> | code  | Код ошибки |
| <code lang="php">string</code> | property  | Название свойства |

**Returns:** mixed - 


<a name="method_getProperty" class="anchor"></a>
#### public getProperty() : string

```php
public getProperty() : string
```

**Summary**

Возвращает название свойства

**Details:**
* Inherited From: [\YooKassaPayout\Common\Exceptions\InvalidPropertyException](../classes/YooKassaPayout-Common-Exceptions-InvalidPropertyException.md)

**Returns:** string - Название свойства



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