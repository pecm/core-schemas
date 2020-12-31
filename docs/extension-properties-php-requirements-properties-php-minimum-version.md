# PHP Minimum Version Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement/properties/min
```

PHP oldest supported version


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## min Type

`string` ([PHP Minimum Version](extension-properties-php-requirements-properties-php-minimum-version.md))

## min Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^(0|[1-9]\d*)\.(0|[1-9]\d*)\.(0|[1-9]\d*)(?:-((?:0|[1-9]\d*|\d*[a-zA-Z-][0-9a-zA-Z-]*)(?:\.(?:0|[1-9]\d*|\d*[a-zA-Z-][0-9a-zA-Z-]*))*))?(?:\+([0-9a-zA-Z-]+(?:\.[0-9a-zA-Z-]+)*))?$
```

[try pattern](https://regexr.com/?expression=%5E(0%7C%5B1-9%5D%5Cd*)%5C.(0%7C%5B1-9%5D%5Cd*)%5C.(0%7C%5B1-9%5D%5Cd*)(%3F%3A-((%3F%3A0%7C%5B1-9%5D%5Cd*%7C%5Cd*%5Ba-zA-Z-%5D%5B0-9a-zA-Z-%5D*)(%3F%3A%5C.(%3F%3A0%7C%5B1-9%5D%5Cd*%7C%5Cd*%5Ba-zA-Z-%5D%5B0-9a-zA-Z-%5D*))*))%3F(%3F%3A%5C%2B(%5B0-9a-zA-Z-%5D%2B(%3F%3A%5C.%5B0-9a-zA-Z-%5D%2B)*))%3F%24 "try regular expression with regexr.com")

## min Default Value

The default value is:

```json
"0.0.0"
```

## min Examples

```json
"7.2.0"
```
