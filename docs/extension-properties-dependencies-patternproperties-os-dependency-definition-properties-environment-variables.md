# Environment Variables Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/env
```

List of environment variables


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## env Type

`object` ([Environment Variables](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-environment-variables.md))

## env Constraints

**minimum number of properties**: the minimum number of properties for this object is: `1`

# Environment Variables Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                    |
| :-------------------- | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Additional Properties | `string` | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-environment-variables-variable-value.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/env/additionalProperties") |

## Additional Properties

Additional properties are allowed, as long as they follow this schema:

Variable value set in the OS


-   is optional
-   Type: `string` ([Variable Value](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-environment-variables-variable-value.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-environment-variables-variable-value.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/env/additionalProperties")

### additionalProperties Type

`string` ([Variable Value](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-environment-variables-variable-value.md))

### additionalProperties Examples

```json
"noninteractive"
```
