# Library Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/libraries/items
```

Library build details


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## items Type

`object` ([Library](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library.md))

# Library Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                    |
| :------------ | -------- | -------- | -------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [flag](#flag) | `string` | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-build-flag.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/libraries/items/properties/flag")    |
| [path](#path) | `string` | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-build-path.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/libraries/items/properties/path")    |
| [type](#type) | `string` | Required | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-vcs-type.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/libraries/items/properties/type")      |
| [url](#url)   | `string` | Required | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-repository-url.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/libraries/items/properties/url") |

## flag

Build flag passed to ./configure command


`flag`

-   is optional
-   Type: `string` ([Build Flag](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-build-flag.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-build-flag.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/libraries/items/properties/flag")

### flag Type

`string` ([Build Flag](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-build-flag.md))

### flag Constraints

**minimum length**: the minimum number of characters for this string is: `1`

### flag Examples

```json
""
```

## path

Path to extension's 'config.m4' file


`path`

-   is optional
-   Type: `string` ([Build Path](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-build-path.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-build-path.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/libraries/items/properties/path")

### path Type

`string` ([Build Path](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-build-path.md))

### path Constraints

**minimum length**: the minimum number of characters for this string is: `1`

### path Examples

```json
""
```

## type

VCS software used by the repository


`type`

-   is required
-   Type: `string` ([VCS Type](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-vcs-type.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-vcs-type.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/libraries/items/properties/type")

### type Type

`string` ([VCS Type](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-vcs-type.md))

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
-   Type: `string` ([Repository URL](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-repository-url.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-repository-url.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/libraries/items/properties/url")

### url Type

`string` ([Repository URL](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library-properties-repository-url.md))

### url Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")

### url Examples

```json
""
```
