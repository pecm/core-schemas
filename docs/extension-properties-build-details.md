# Build Details Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build
```

Extension source code and build information


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## build Type

`object` ([Build Details](extension-properties-build-details.md))

# Build Details Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                      |
| :------------ | -------- | -------- | -------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [flag](#flag) | `string` | Optional | cannot be null | [Extension Definition](extension-properties-build-details-properties-build-flag.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build/properties/flag")    |
| [path](#path) | `string` | Optional | cannot be null | [Extension Definition](extension-properties-build-details-properties-build-path.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build/properties/path")    |
| [type](#type) | `string` | Required | cannot be null | [Extension Definition](extension-properties-build-details-properties-vcs-type.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build/properties/type")      |
| [url](#url)   | `string` | Required | cannot be null | [Extension Definition](extension-properties-build-details-properties-repository-url.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build/properties/url") |

## flag

Build flag passed to ./configure command


`flag`

-   is optional
-   Type: `string` ([Build Flag](extension-properties-build-details-properties-build-flag.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-build-details-properties-build-flag.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build/properties/flag")

### flag Type

`string` ([Build Flag](extension-properties-build-details-properties-build-flag.md))

### flag Constraints

**minimum length**: the minimum number of characters for this string is: `1`

### flag Examples

```json
"--with-pdo_sqlsrv"
```

## path

Path to extension's 'config.m4' file


`path`

-   is optional
-   Type: `string` ([Build Path](extension-properties-build-details-properties-build-path.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-build-details-properties-build-path.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build/properties/path")

### path Type

`string` ([Build Path](extension-properties-build-details-properties-build-path.md))

### path Constraints

**minimum length**: the minimum number of characters for this string is: `1`

### path Examples

```json
"source/pdo_sqlsrv"
```

## type

VCS software used by the repository


`type`

-   is required
-   Type: `string` ([VCS Type](extension-properties-build-details-properties-vcs-type.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-build-details-properties-vcs-type.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build/properties/type")

### type Type

`string` ([VCS Type](extension-properties-build-details-properties-vcs-type.md))

### type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value   | Explanation |
| :------ | ----------- |
| `"git"` |             |
| `"svn"` |             |

## url

URL to clone source code from


`url`

-   is required
-   Type: `string` ([Repository URL](extension-properties-build-details-properties-repository-url.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-build-details-properties-repository-url.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build/properties/url")

### url Type

`string` ([Repository URL](extension-properties-build-details-properties-repository-url.md))

### url Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")

### url Examples

```json
"https://github.com/Microsoft/msphpsql"
```
