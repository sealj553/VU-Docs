---
title: MissileUnguidedData
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                                    | Description                                              |
| ---------------------------------------------- | -------------------------------------------------------- |
| MissileUnguidedData()                          | Create a new instance of this structure type.            |
| MissileUnguidedData(MissileUnguidedData other) | Create a reference copy of a structure of the same type. |

## Properties

| Name                 | Type                              | Description |
| -------------------- | --------------------------------- | ----------- |
| staticPosition       | [Vec2](/vext/ref/shared/class/vec2) |             |
| targetPositionOffset | [Vec2](/vext/ref/shared/class/vec2) |             |
| useTargetPosition    | bool                              |             |
| useStaticPosition    | bool                              |             |

## Methods

| Type                                       | Name            | Parameters |
| ------------------------------------------ | --------------- | ---------- |
| [MissileUnguidedData](/vext/ref/fb/missileunguideddata/) | [Clone](#clone) |            |

### Clone

> [MissileUnguidedData](/vext/ref/fb/missileunguideddata/) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone).