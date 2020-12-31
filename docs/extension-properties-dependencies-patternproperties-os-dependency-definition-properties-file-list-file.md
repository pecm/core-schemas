# File Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/files/items
```

An ordinary file that will be downloaded and placed somewhere in the file system


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## items Type

`object` ([File](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file.md))

# File Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                      |
| :------------ | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [url](#url)   | `string` | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file-properties-file-url.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/files/items/properties/url")   |
| [name](#name) | `string` | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file-properties-file-path.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/files/items/properties/name") |

## url

URL to download file from


`url`

-   is optional
-   Type: `string` ([File URL](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file-properties-file-url.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file-properties-file-url.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/files/items/properties/url")

### url Type

`string` ([File URL](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file-properties-file-url.md))

### url Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")

### url Examples

```json
"https://packages.microsoft.com/config/debian/10/prod.list"
```

## name

Path to save file after download


`name`

-   is optional
-   Type: `string` ([File Path](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file-properties-file-path.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file-properties-file-path.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/files/items/properties/name")

### name Type

`string` ([File Path](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file-properties-file-path.md))

### name Constraints

**minimum length**: the minimum number of characters for this string is: `1`

### name Examples

```json
"/etc/apt/sources.list.d/mssql-release.list"
```
