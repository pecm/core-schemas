# README

## Top-level Schemas

-   [Extension Definition](./extension.md "PHP Extension dependency and build details") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json`

## Other Schemas

### Objects

-   [Build Details](./extension-properties-build-details.md "Extension source code and build information") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/build`
-   [Dependencies](./extension-properties-dependencies.md "Dependencies grouped by OS") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps`
-   [Environment Variables](./extension-properties-dependencies-patternproperties-os-dependency-definition-properties-environment-variables.md "List of environment variables") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/env`
-   [File](./extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list-file.md "An ordinary file that will be downloaded and placed somewhere in the file system") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/files/items`
-   [Library](./extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list-library.md "Library build details") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/libraries/items`
-   [OS Dependency Definition](./extension-properties-dependencies-patternproperties-os-dependency-definition.md "A set of dependencies that are required to build the extension") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+`
-   [PHP Requirements](./extension-properties-php-requirements.md "PHP Versions and Thread-Safe support") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/requirement`
-   [Pecl](./extension-properties-pecl.md "Pecl information") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/pecl`

### Arrays

-   [Core Extension List](./extension-properties-dependencies-patternproperties-os-dependency-definition-properties-core-extension-list.md "List of core PHP Extensions to be installed") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/core-extensions`
-   [Extension List](./extension-properties-dependencies-patternproperties-os-dependency-definition-properties-extension-list.md "List of non-core PHP Extensions to be installed") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/extensions`
-   [File List](./extension-properties-dependencies-patternproperties-os-dependency-definition-properties-file-list.md "List of files to be downloaded") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/files`
-   [Key List](./extension-properties-dependencies-patternproperties-os-dependency-definition-properties-key-list.md "List of gpg keys used to sign packages") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/keys`
-   [Library List](./extension-properties-dependencies-patternproperties-os-dependency-definition-properties-library-list.md "List of libraries to be built") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/libraries`
-   [Package List](./extension-properties-dependencies-patternproperties-os-dependency-definition-properties-package-list.md "List of OS packages to be installed") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/packages`
-   [Source List](./extension-properties-dependencies-patternproperties-os-dependency-definition-properties-source-list.md "List of OS package sources") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/sources`
-   [Untrusted Package List](./extension-properties-dependencies-patternproperties-os-dependency-definition-properties-untrusted-package-list.md "List of untrusted OS packages to be installed") – `https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/deps/patternProperties/[a-z]+/properties/untrusted-packages`

## Version Note

The schemas linked above follow the JSON Schema Spec version: `https://json-schema.org/draft/2019-09/schema`
