# OS Dependency Definition Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+
```

A set of dependencies that are required to build the extension


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## \[a-z]+ Type

`object` ([OS Dependency Definition](extension-properties-dependencies-patternproperties-os-dependency-definition.md))

# OS Dependency Definition Properties

| Property                                  | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                |
| :---------------------------------------- | --------- | -------- | -------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [disabled](#disabled)                     | `boolean` | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-os-build-flag.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/disabled")                    |
| [env](#env)                               | `object`  | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-environment-variables.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/env")                 |
| [files](#files)                           | `array`   | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/files")                           |
| [keys](#keys)                             | `array`   | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-key-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/keys")                             |
| [sources](#sources)                       | `array`   | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-source-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/sources")                       |
| [untrusted-packages](#untrusted-packages) | `array`   | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-untrusted-package-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/untrusted-packages") |
| [packages](#packages)                     | `array`   | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-package-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/packages")                     |
| [libraries](#libraries)                   | `array`   | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/libraries")                    |
| [core-extensions](#core-extensions)       | `array`   | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-core-extension-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/core-extensions")       |
| [extensions](#extensions)                 | `array`   | Optional | cannot be null | [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-extension-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/extensions")                 |

## disabled

Disables OS support


`disabled`

-   is optional
-   Type: `boolean` ([OS Build Flag](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-os-build-flag.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-os-build-flag.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/disabled")

### disabled Type

`boolean` ([OS Build Flag](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-os-build-flag.md))

## env

List of environment variables


`env`

-   is optional
-   Type: `object` ([Environment Variables](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-environment-variables.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-environment-variables.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/env")

### env Type

`object` ([Environment Variables](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-environment-variables.md))

### env Constraints

**minimum number of properties**: the minimum number of properties for this object is: `1`

## files

List of files to be downloaded


`files`

-   is optional
-   Type: `object[]` ([File](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/files")

### files Type

`object[]` ([File](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file.md))

### files Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## keys

List of gpg keys used to sign packages


`keys`

-   is optional
-   Type: `string[]` ([Key URL](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-key-list-key-url.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-key-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/keys")

### keys Type

`string[]` ([Key URL](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-key-list-key-url.md))

### keys Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## sources

List of OS package sources


`sources`

-   is optional
-   Type: `string[]` ([Package Source URL](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-source-list-package-source-url.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-source-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/sources")

### sources Type

`string[]` ([Package Source URL](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-source-list-package-source-url.md))

### sources Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## untrusted-packages

List of untrusted OS packages to be installed


`untrusted-packages`

-   is optional
-   Type: `string[]` ([Package Name](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-untrusted-package-list-package-name.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-untrusted-package-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/untrusted-packages")

### untrusted-packages Type

`string[]` ([Package Name](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-untrusted-package-list-package-name.md))

### untrusted-packages Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## packages

List of OS packages to be installed


`packages`

-   is optional
-   Type: `string[]` ([Package name](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-package-list-package-name.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-package-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/packages")

### packages Type

`string[]` ([Package name](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-package-list-package-name.md))

### packages Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## libraries

List of libraries to be built


`libraries`

-   is optional
-   Type: `object[]` ([Library](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/libraries")

### libraries Type

`object[]` ([Library](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library.md))

### libraries Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## core-extensions

List of core PHP Extensions to be installed


`core-extensions`

-   is optional
-   Type: `string[]` ([Extension Name](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-core-extension-list-extension-name.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-core-extension-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/core-extensions")

### core-extensions Type

`string[]` ([Extension Name](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-core-extension-list-extension-name.md))

### core-extensions Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## extensions

List of non-core PHP Extensions to be installed


`extensions`

-   is optional
-   Type: `string[]` ([Extension Name](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-extension-list-extension-name.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-extension-list.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/\[a-z]+/properties/extensions")

### extensions Type

`string[]` ([Extension Name](extension-properties-dependencies-patternproperties-os-dependency-definition-properties-extension-list-extension-name.md))

### extensions Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.
