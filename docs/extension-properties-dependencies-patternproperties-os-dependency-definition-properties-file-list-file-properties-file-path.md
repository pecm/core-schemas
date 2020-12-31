# File Path Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/files/items/properties/name
```

Path to save file after download


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## name Type

`string` ([File Path](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file-properties-file-path.md))

## name Constraints

**minimum length**: the minimum number of characters for this string is: `1`

## name Examples

```json
"/etc/apt/sources.list.d/mssql-release.list"
```
