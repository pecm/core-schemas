# PHP NTS Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement/properties/nts
```

PHP Non Thread-Safe support


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## nts Type

`string` ([PHP NTS](extension-properties-php-requirements-properties-php-nts.md))

## nts Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | ----------- |
| `"neutral"`     |             |
| `"required"`    |             |
| `"unsupported"` |             |

## nts Default Value

The default value is:

```json
"neutral"
```
