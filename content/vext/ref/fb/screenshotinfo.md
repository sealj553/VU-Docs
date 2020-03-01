---
title: ScreenshotInfo
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                          | Description                                              |
| ------------------------------------ | -------------------------------------------------------- |
| ScreenshotInfo()                     | Create a new instance of this structure type.            |
| ScreenshotInfo(ScreenshotInfo other) | Create a reference copy of a structure of the same type. |

## Properties

| Name                    | Type   | Description |
| ----------------------- | ------ | ----------- |
| name                    | string |             |
| cropImageY1             | number |             |
| cropImageX1             | number |             |
| cropImageX2             | number |             |
| cropImageY2             | number |             |
| resizeOutputImageHeight | number |             |
| resizeOutputImageWidth  | number |             |
| resizeOutputImage       | bool   |             |
| cropImage               | bool   |             |

## Methods

| Type                             | Name            | Parameters |
| -------------------------------- | --------------- | ---------- |
| [ScreenshotInfo](/vext/ref/fb/screenshotinfo/) | [Clone](#clone) |            |

### Clone

> [ScreenshotInfo](/vext/ref/fb/screenshotinfo/) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone).