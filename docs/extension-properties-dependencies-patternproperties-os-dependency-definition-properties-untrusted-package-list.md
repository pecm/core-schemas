# Untrusted Package List Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/untrusted-packages
```

List of untrusted OS packages to be installed


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## untrusted-packages Type

`string[]` ([Package Name](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-untrusted-package-list-package-name.md))

## untrusted-packages Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.
