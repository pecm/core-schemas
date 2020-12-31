# Dependencies Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps
```

Dependencies grouped by OS


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## deps Type

`object` ([Dependencies](extension-properties-dependencies.md))

# Dependencies Properties

| Property | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                |
| :------- | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[a-z]+` | `object` | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+") |

## Pattern: `[a-z]+`

A set of dependencies that are required to build the extension


`[a-z]+`

-   is optional
-   Type: `object` ([OS Dependency Definition](extension-properties-dependencies-patternproperties-os-dependency-definition.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+")

### \[a-z]+ Type

`object` ([OS Dependency Definition](extension-properties-dependencies-patternproperties-os-dependency-definition.md))
