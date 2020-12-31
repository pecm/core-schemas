# Pecl Schema

```txt
https://github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/pecl
```

Pecl information


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [extension.schema.json\*](../out/extension.schema.json "open original schema") |

## pecl Type

`object` ([Pecl](extension-properties-pecl.md))

# Pecl Properties

| Property                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                     |
| :---------------------- | --------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [available](#available) | `boolean` | Optional | cannot be null | [Extension Definition](extension-properties-pecl-properties-pecl-availability.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/pecl/properties/available") |
| [state](#state)         | `string`  | Optional | cannot be null | [Extension Definition](extension-properties-pecl-properties-version-stability.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/pecl/properties/state")     |

## available

If extension is available through Pecl


`available`

-   is optional
-   Type: `boolean` ([Pecl Availability](extension-properties-pecl-properties-pecl-availability.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-pecl-properties-pecl-availability.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/pecl/properties/available")

### available Type

`boolean` ([Pecl Availability](extension-properties-pecl-properties-pecl-availability.md))

### available Default Value

The default value is:

```json
true
```

## state

Extension stability state


`state`

-   is optional
-   Type: `string` ([Version Stability](extension-properties-pecl-properties-version-stability.md))
-   cannot be null
-   defined in: [Extension Definition](extension-properties-pecl-properties-version-stability.md "https&#x3A;//github.com/php-ext-com/build-engine/blob/main/src/Schema/extension.json#/properties/pecl/properties/state")

### state Type

`string` ([Version Stability](extension-properties-pecl-properties-version-stability.md))

### state Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | ----------- |
| `"stable"` |             |
| `"beta"`   |             |
| `"alpha"`  |             |

### state Default Value

The default value is:

```json
"stable"
```
