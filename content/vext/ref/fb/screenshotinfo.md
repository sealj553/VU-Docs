---
title: ScreenshotInfo
---

## Summary

### Constructors

|  |
| --- |
| **[ScreenshotInfo](#constructor-0)**() |
| **[ScreenshotInfo](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "name" >}} | string |
| {{< prop "cropImageY1" >}} | int |
| {{< prop "cropImageX1" >}} | int |
| {{< prop "cropImageX2" >}} | int |
| {{< prop "cropImageY2" >}} | int |
| {{< prop "resizeOutputImageHeight" >}} | int |
| {{< prop "resizeOutputImageWidth" >}} | int |
| {{< prop "resizeOutputImage" >}} | bool |
| {{< prop "cropImage" >}} | bool |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [ScreenshotInfo](/vext/ref/fb/screenshotinfo) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "ScreenshotInfo" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### ScreenshotInfo {#constructor-0}

> **ScreenshotInfo**()

Creates a new [ScreenshotInfo](/vext/ref/fb/screenshotinfo) frostbite instance.

### ScreenshotInfo {#constructor-1}

> **ScreenshotInfo**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [ScreenshotInfo](/vext/ref/fb/screenshotinfo) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "name" %}}

> **string**

### {{% prop-heading "cropImageY1" %}}

> **int**

### {{% prop-heading "cropImageX1" %}}

> **int**

### {{% prop-heading "cropImageX2" %}}

> **int**

### {{% prop-heading "cropImageY2" %}}

> **int**

### {{% prop-heading "resizeOutputImageHeight" %}}

> **int**

### {{% prop-heading "resizeOutputImageWidth" %}}

> **int**

### {{% prop-heading "resizeOutputImage" %}}

> **bool**

### {{% prop-heading "cropImage" %}}

> **bool**

## Methods

### Clone {#clone}

> **Clone**(): [ScreenshotInfo](/vext/ref/fb/screenshotinfo)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[ScreenshotInfo](/vext/ref/fb/screenshotinfo)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [ScreenshotInfo](/vext/ref/fb/screenshotinfo) type.

