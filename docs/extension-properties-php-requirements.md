# PHP Requirements Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement
```

PHP Versions and Thread-Safe support


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## requirement Type

`object` ([PHP Requirements](extension-properties-php-requirements.md))

# PHP Requirements Properties

| Property    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                    |
| :---------- | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [min](#min) | `string` | Optional | cannot be null | [Extension Definition](extension-properties-php-requirements-properties-php-minimum-version.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement/properties/min") |
| [max](#max) | `string` | Optional | cannot be null | [Extension Definition](extension-properties-php-requirements-properties-php-maximum-version.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement/properties/max") |
| [zts](#zts) | `string` | Optional | cannot be null | [Extension Definition](extension-properties-php-requirements-properties-php-zts.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement/properties/zts")             |
| [nts](#nts) | `string` | Optional | cannot be null | [Extension Definition](extension-properties-php-requirements-properties-php-nts.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement/properties/nts")             |

## min

PHP oldest supported version


`min`

-   is optional
-   Type: `string` ([PHP Minimum Version](extension-properties-php-requirements-properties-php-minimum-version.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-php-requirements-properties-php-minimum-version.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement/properties/min")

### min Type

`string` ([PHP Minimum Version](extension-properties-php-requirements-properties-php-minimum-version.md))

### min Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^(0|[1-9]\d*)\.(0|[1-9]\d*)\.(0|[1-9]\d*)(?:-((?:0|[1-9]\d*|\d*[a-zA-Z-][0-9a-zA-Z-]*)(?:\.(?:0|[1-9]\d*|\d*[a-zA-Z-][0-9a-zA-Z-]*))*))?(?:\+([0-9a-zA-Z-]+(?:\.[0-9a-zA-Z-]+)*))?$
```

[try pattern](https://regexr.com/?expression=%5E(0%7C%5B1-9%5D%5Cd*)%5C.(0%7C%5B1-9%5D%5Cd*)%5C.(0%7C%5B1-9%5D%5Cd*)(%3F%3A-((%3F%3A0%7C%5B1-9%5D%5Cd*%7C%5Cd*%5Ba-zA-Z-%5D%5B0-9a-zA-Z-%5D*)(%3F%3A%5C.(%3F%3A0%7C%5B1-9%5D%5Cd*%7C%5Cd*%5Ba-zA-Z-%5D%5B0-9a-zA-Z-%5D*))*))%3F(%3F%3A%5C%2B(%5B0-9a-zA-Z-%5D%2B(%3F%3A%5C.%5B0-9a-zA-Z-%5D%2B)*))%3F%24 "try regular expression with regexr.com")

### min Default Value

The default value is:

```json
"0.0.0"
```

### min Examples

```json
"7.2.0"
```

## max

PHP newest supported version


`max`

-   is optional
-   Type: `string` ([PHP Maximum Version](extension-properties-php-requirements-properties-php-maximum-version.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-php-requirements-properties-php-maximum-version.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement/properties/max")

### max Type

`string` ([PHP Maximum Version](extension-properties-php-requirements-properties-php-maximum-version.md))

### max Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^(0|[1-9]\d*)\.(0|[1-9]\d*)\.(0|[1-9]\d*)(?:-((?:0|[1-9]\d*|\d*[a-zA-Z-][0-9a-zA-Z-]*)(?:\.(?:0|[1-9]\d*|\d*[a-zA-Z-][0-9a-zA-Z-]*))*))?(?:\+([0-9a-zA-Z-]+(?:\.[0-9a-zA-Z-]+)*))?$
```

[try pattern](https://regexr.com/?expression=%5E(0%7C%5B1-9%5D%5Cd*)%5C.(0%7C%5B1-9%5D%5Cd*)%5C.(0%7C%5B1-9%5D%5Cd*)(%3F%3A-((%3F%3A0%7C%5B1-9%5D%5Cd*%7C%5Cd*%5Ba-zA-Z-%5D%5B0-9a-zA-Z-%5D*)(%3F%3A%5C.(%3F%3A0%7C%5B1-9%5D%5Cd*%7C%5Cd*%5Ba-zA-Z-%5D%5B0-9a-zA-Z-%5D*))*))%3F(%3F%3A%5C%2B(%5B0-9a-zA-Z-%5D%2B(%3F%3A%5C.%5B0-9a-zA-Z-%5D%2B)*))%3F%24 "try regular expression with regexr.com")

### max Default Value

The default value is:

```json
"99.99.99"
```

### max Examples

```json
"8.0.99"
```

## zts

PHP Zend Thread-Safe support


`zts`

-   is optional
-   Type: `string` ([PHP ZTS](extension-properties-php-requirements-properties-php-zts.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-php-requirements-properties-php-zts.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement/properties/zts")

### zts Type

`string` ([PHP ZTS](extension-properties-php-requirements-properties-php-zts.md))

### zts Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | ----------- |
| `"neutral"`     |             |
| `"required"`    |             |
| `"unsupported"` |             |

### zts Default Value

The default value is:

```json
"neutral"
```

## nts

PHP Non Thread-Safe support


`nts`

-   is optional
-   Type: `string` ([PHP NTS](extension-properties-php-requirements-properties-php-nts.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-php-requirements-properties-php-nts.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement/properties/nts")

### nts Type

`string` ([PHP NTS](extension-properties-php-requirements-properties-php-nts.md))

### nts Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | ----------- |
| `"neutral"`     |             |
| `"required"`    |             |
| `"unsupported"` |             |

### nts Default Value

The default value is:

```json
"neutral"
```
