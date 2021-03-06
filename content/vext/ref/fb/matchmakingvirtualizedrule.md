---
title: MatchmakingVirtualizedRule
---

## Summary

### Constructors

|  |
| --- |
| **[MatchmakingVirtualizedRule](#constructor-0)**() |
| **[MatchmakingVirtualizedRule](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "minFitThreshold" >}} | string |
| {{< prop "virtualizationMode" >}} | [MatchmakingVirtualizationMode](/vext/ref/fb/matchmakingvirtualizationmode) |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [MatchmakingVirtualizedRule](/vext/ref/fb/matchmakingvirtualizedrule) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "MatchmakingVirtualizedRule" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### MatchmakingVirtualizedRule {#constructor-0}

> **MatchmakingVirtualizedRule**()

Creates a new [MatchmakingVirtualizedRule](/vext/ref/fb/matchmakingvirtualizedrule) frostbite instance.

### MatchmakingVirtualizedRule {#constructor-1}

> **MatchmakingVirtualizedRule**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [MatchmakingVirtualizedRule](/vext/ref/fb/matchmakingvirtualizedrule) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "minFitThreshold" %}}

> **string**

### {{% prop-heading "virtualizationMode" %}}

> **[MatchmakingVirtualizationMode](/vext/ref/fb/matchmakingvirtualizationmode)**

## Methods

### Clone {#clone}

> **Clone**(): [MatchmakingVirtualizedRule](/vext/ref/fb/matchmakingvirtualizedrule)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[MatchmakingVirtualizedRule](/vext/ref/fb/matchmakingvirtualizedrule)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [MatchmakingVirtualizedRule](/vext/ref/fb/matchmakingvirtualizedrule) type.

