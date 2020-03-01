---
title: TextUnlockPartData
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                   | Description                                                                                                                 |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| TextUnlockPartData()                                                          | Create a new instance of this container type.                                                                               |
| TextUnlockPartData(TextUnlockPartData other)                                  | Create a reference copy of an instance of the same type.                                                                    |
| TextUnlockPartData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [TextUnlockPartData](/vext/ref/fb/textunlockpartdata/). |

## Properties

| Name           | Type                               | Description |
| -------------- | ---------------------------------- | ----------- |
| shaderNodeName | string                             |             |
| meshBlueprint  | [ObjectBlueprint](/vext/ref/fb/objectblueprint/) |             |

## Methods

| Type                                     | Name            | Parameters                                     |
| ---------------------------------------- | --------------- | ---------------------------------------------- |
| [TextUnlockPartData](/vext/ref/fb/textunlockpartdata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [TextUnlockPartData](/vext/ref/fb/textunlockpartdata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |