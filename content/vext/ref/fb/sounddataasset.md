---
title: SoundDataAsset
---
### Base Classes

[Asset](/vext/ref/fb/asset/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                               | Description                                                                                                         |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| SoundDataAsset()                                                          | Create a new instance of this container type.                                                                       |
| SoundDataAsset(SoundDataAsset other)                                      | Create a reference copy of an instance of the same type.                                                            |
| SoundDataAsset([Asset](/vext/ref/fb/asset/) other)                                      | Upcast an instance of type [Asset](/vext/ref/fb/asset/) to [SoundDataAsset](/vext/ref/fb/sounddataasset/).                                      |
| SoundDataAsset([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [SoundDataAsset](/vext/ref/fb/sounddataasset/). |

## Properties

| Name     | Type                                 | Description |
| -------- | ------------------------------------ | ----------- |
| nameHash | number                               |             |
| chunks   | [SoundDataChunk](/vext/ref/fb/sounddatachunk/)\[\] |             |

## Methods

| Type                             | Name            | Parameters                                     |
| -------------------------------- | --------------- | ---------------------------------------------- |
| [SoundDataAsset](/vext/ref/fb/sounddataasset/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [SoundDataAsset](/vext/ref/fb/sounddataasset/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |