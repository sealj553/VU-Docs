---
title: TerrainSettings
---

Inherits from [DataContainer](/vext/ref/shared/type/datacontainer)

## Summary

### Constructors

|  |
| --- |
| **[TerrainSettings](#constructor-0)**() |
| **[TerrainSettings](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[TerrainSettings](#constructor-2)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "heightQueryCacheSize" >}} | int |
| {{< prop "modifiersCapacity" >}} | int |
| {{< prop "intersectingModifiersMax" >}} | int |
| {{< prop "modifierDepthFactor" >}} | float |
| {{< prop "modifierSlopeMax" >}} | float |
| {{< prop "modifiersEnable" >}} | bool |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "TerrainSettings" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### TerrainSettings {#constructor-0}

> **TerrainSettings**()

Creates a new [TerrainSettings](/vext/ref/fb/terrainsettings) frostbite instance.

### TerrainSettings {#constructor-1}

> **TerrainSettings**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [TerrainSettings](/vext/ref/fb/terrainsettings) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### TerrainSettings {#constructor-2}

> **TerrainSettings**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [TerrainSettings](/vext/ref/fb/terrainsettings). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [TerrainSettings](/vext/ref/fb/terrainsettings). |

## Properties

### {{% prop-heading "heightQueryCacheSize" %}}

> **int**

### {{% prop-heading "modifiersCapacity" %}}

> **int**

### {{% prop-heading "intersectingModifiersMax" %}}

> **int**

### {{% prop-heading "modifierDepthFactor" %}}

> **float**

### {{% prop-heading "modifierSlopeMax" %}}

> **float**

### {{% prop-heading "modifiersEnable" %}}

> **bool**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [TerrainSettings](/vext/ref/fb/terrainsettings) type.

