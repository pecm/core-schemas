# Build Flag Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build/properties/flag
```

Build flag passed to ./configure command


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## flag Type

`string` ([Build Flag](extension-properties-build-details-properties-build-flag.md))

## flag Constraints

**minimum length**: the minimum number of characters for this string is: `1`

## flag Examples

```json
"--with-pdo_sqlsrv"
```
