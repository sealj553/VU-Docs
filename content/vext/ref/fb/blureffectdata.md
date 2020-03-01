---
title: BlurEffectData
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                          | Description                                              |
| ------------------------------------ | -------------------------------------------------------- |
| BlurEffectData()                     | Create a new instance of this structure type.            |
| BlurEffectData(BlurEffectData other) | Create a reference copy of a structure of the same type. |

## Properties

| Name                  | Type   | Description |
| --------------------- | ------ | ----------- |
| dispersionStrength    | number |             |
| dispersionThreshhold  | number |             |
| explosionStrength     | number |             |
| bulletStrength        | number |             |
| explosionFalloffSpeed | number |             |
| bulletFalloffSpeed    | number |             |

## Methods

| Type                             | Name            | Parameters |
| -------------------------------- | --------------- | ---------- |
| [BlurEffectData](/vext/ref/fb/blureffectdata/) | [Clone](#clone) |            |

### Clone

> [BlurEffectData](/vext/ref/fb/blureffectdata/) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone).