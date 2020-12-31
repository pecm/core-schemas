# Variable Name Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/env/propertyNames
```

Name by which the variable is recognized by the OS


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## propertyNames Type

`string` ([Variable Name](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-environment-variables-variable-name.md))

## propertyNames Constraints

**minimum length**: the minimum number of characters for this string is: `1`

## propertyNames Examples

```json
"DEBIAN_FRONTEND"
```
