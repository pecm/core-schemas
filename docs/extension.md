# Extension Definition Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json
```

PHP Extension dependency and build details


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                   |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ---------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [extension.schema.json](../out/extension.schema.json "open original schema") |

## Extension Definition Type

`object` ([Extension Definition](extension.md))

# Extension Definition Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                      |
| :-------------------------- | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [deps](#deps)               | `object` | Optional | cannot be null | [Extension Definition](extension-properties-dependencies.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps")            |
| [pecl](#pecl)               | `object` | Optional | cannot be null | [Extension Definition](extension-properties-pecl.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/pecl")                    |
| [build](#build)             | `object` | Required | cannot be null | [Extension Definition](extension-properties-build-details.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build")          |
| [requirement](#requirement) | `object` | Optional | cannot be null | [Extension Definition](extension-properties-php-requirements.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement") |
| [summary](#summary)         | `string` | Required | cannot be null | [Extension Definition](extension-properties-extension-summary.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/summary")    |

## deps

Dependencies grouped by OS


`deps`

-   is optional
-   Type: `object` ([Dependencies](extension-properties-dependencies.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps")

### deps Type

`object` ([Dependencies](extension-properties-dependencies.md))

## pecl

Pecl information


`pecl`

-   is optional
-   Type: `object` ([Pecl](extension-properties-pecl.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-pecl.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/pecl")

### pecl Type

`object` ([Pecl](extension-properties-pecl.md))

## build

Extension source code and build information


`build`

-   is required
-   Type: `object` ([Build Details](extension-properties-build-details.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-build-details.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build")

### build Type

`object` ([Build Details](extension-properties-build-details.md))

## requirement

PHP Versions and Thread-Safe support


`requirement`

-   is optional
-   Type: `object` ([PHP Requirements](extension-properties-php-requirements.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-php-requirements.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement")

### requirement Type

`object` ([PHP Requirements](extension-properties-php-requirements.md))

## summary

A brief description about the extension


`summary`

-   is required
-   Type: `string` ([Extension Summary](extension-properties-extension-summary.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-extension-summary.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/summary")

### summary Type

`string` ([Extension Summary](extension-properties-extension-summary.md))

### summary Constraints

**minimum length**: the minimum number of characters for this string is: `1`

### summary Examples

```json
"Microsoft Drivers for PHP for SQL Server (PDO_SQLSRV)"
```
