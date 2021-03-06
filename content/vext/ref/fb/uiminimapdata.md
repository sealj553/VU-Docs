---
title: UIMinimapData
---

## Summary

### Constructors

|  |
| --- |
| **[UIMinimapData](#constructor-0)**() |
| **[UIMinimapData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "worldCenter" >}} | [Vec2](/vext/ref/shared/type/vec2) |
| {{< prop "combatAreaColor" >}} | [Vec4](/vext/ref/shared/type/vec4) |
| {{< prop "detailTextureTint" >}} | [Vec4](/vext/ref/shared/type/vec4) |
| {{< prop "combatAreaMultiplyWrapAmount" >}} | [Vec2](/vext/ref/shared/type/vec2) |
| {{< prop "vegetation" >}} | [UIMinimapDistanceFieldParams](/vext/ref/fb/uiminimapdistancefieldparams) |
| {{< prop "fadeTexture" >}} | [TextureAsset](/vext/ref/fb/textureasset) \| nil |
| {{< prop "streamingMinimapDelay" >}} | float |
| {{< prop "airRadarFadeTexture" >}} | [TextureAsset](/vext/ref/fb/textureasset) \| nil |
| {{< prop "detailTexture" >}} | [TextureAsset](/vext/ref/fb/textureasset) \| nil |
| {{< prop "detail" >}} | [UIMinimapDistanceFieldParams](/vext/ref/fb/uiminimapdistancefieldparams) |
| {{< prop "streamingMinimapTransitionSpeed" >}} | float |
| {{< prop "worldRotation" >}} | float |
| {{< prop "worldRange" >}} | float |
| {{< prop "combatAreaDistanceScale" >}} | float |
| {{< prop "combatAreaFadeSpeed" >}} | float |
| {{< prop "combatAreaAlphaThreshold" >}} | float |
| {{< prop "combatAreaMultiplyTexture" >}} | [TextureAsset](/vext/ref/fb/textureasset) \| nil |
| {{< prop "worldSize" >}} | float |
| {{< prop "airRadarRange" >}} | float |
| {{< prop "combatAreaScale" >}} | float |
| {{< prop "useStreamingMinimap" >}} | bool |
| {{< prop "useCombatAreaTexture" >}} | bool |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [UIMinimapData](/vext/ref/fb/uiminimapdata) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "UIMinimapData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### UIMinimapData {#constructor-0}

> **UIMinimapData**()

Creates a new [UIMinimapData](/vext/ref/fb/uiminimapdata) frostbite instance.

### UIMinimapData {#constructor-1}

> **UIMinimapData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [UIMinimapData](/vext/ref/fb/uiminimapdata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "worldCenter" %}}

> **[Vec2](/vext/ref/shared/type/vec2)**

### {{% prop-heading "combatAreaColor" %}}

> **[Vec4](/vext/ref/shared/type/vec4)**

### {{% prop-heading "detailTextureTint" %}}

> **[Vec4](/vext/ref/shared/type/vec4)**

### {{% prop-heading "combatAreaMultiplyWrapAmount" %}}

> **[Vec2](/vext/ref/shared/type/vec2)**

### {{% prop-heading "vegetation" %}}

> **[UIMinimapDistanceFieldParams](/vext/ref/fb/uiminimapdistancefieldparams)**

### {{% prop-heading "fadeTexture" %}}

> **[TextureAsset](/vext/ref/fb/textureasset)** \| **nil**

### {{% prop-heading "streamingMinimapDelay" %}}

> **float**

### {{% prop-heading "airRadarFadeTexture" %}}

> **[TextureAsset](/vext/ref/fb/textureasset)** \| **nil**

### {{% prop-heading "detailTexture" %}}

> **[TextureAsset](/vext/ref/fb/textureasset)** \| **nil**

### {{% prop-heading "detail" %}}

> **[UIMinimapDistanceFieldParams](/vext/ref/fb/uiminimapdistancefieldparams)**

### {{% prop-heading "streamingMinimapTransitionSpeed" %}}

> **float**

### {{% prop-heading "worldRotation" %}}

> **float**

### {{% prop-heading "worldRange" %}}

> **float**

### {{% prop-heading "combatAreaDistanceScale" %}}

> **float**

### {{% prop-heading "combatAreaFadeSpeed" %}}

> **float**

### {{% prop-heading "combatAreaAlphaThreshold" %}}

> **float**

### {{% prop-heading "combatAreaMultiplyTexture" %}}

> **[TextureAsset](/vext/ref/fb/textureasset)** \| **nil**

### {{% prop-heading "worldSize" %}}

> **float**

### {{% prop-heading "airRadarRange" %}}

> **float**

### {{% prop-heading "combatAreaScale" %}}

> **float**

### {{% prop-heading "useStreamingMinimap" %}}

> **bool**

### {{% prop-heading "useCombatAreaTexture" %}}

> **bool**

## Methods

### Clone {#clone}

> **Clone**(): [UIMinimapData](/vext/ref/fb/uiminimapdata)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[UIMinimapData](/vext/ref/fb/uiminimapdata)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [UIMinimapData](/vext/ref/fb/uiminimapdata) type.

