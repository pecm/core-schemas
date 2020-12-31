# PHP ZTS Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement/properties/zts
```

PHP Zend Thread-Safe support


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## zts Type

`string` ([PHP ZTS](extension-properties-php-requirements-properties-php-zts.md))

## zts Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | ----------- |
| `"neutral"`     |             |
| `"required"`    |             |
| `"unsupported"` |             |

## zts Default Value

The default value is:

```json
"neutral"
```
