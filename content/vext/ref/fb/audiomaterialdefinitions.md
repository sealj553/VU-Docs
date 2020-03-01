---
title: AudioMaterialDefinitions
---
### Base Classes

[Asset](/vext/ref/fb/asset/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                         | Description                                                                                                                             |
| ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| AudioMaterialDefinitions()                                                          | Create a new instance of this container type.                                                                                           |
| AudioMaterialDefinitions(AudioMaterialDefinitions other)                            | Create a reference copy of an instance of the same type.                                                                                |
| AudioMaterialDefinitions([Asset](/vext/ref/fb/asset/) other)                                      | Upcast an instance of type [Asset](/vext/ref/fb/asset/) to [AudioMaterialDefinitions](/vext/ref/fb/audiomaterialdefinitions/).                                      |
| AudioMaterialDefinitions([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [AudioMaterialDefinitions](/vext/ref/fb/audiomaterialdefinitions/). |

## Methods

| Type                                                 | Name            | Parameters                                     |
| ---------------------------------------------------- | --------------- | ---------------------------------------------- |
| [AudioMaterialDefinitions](/vext/ref/fb/audiomaterialdefinitions/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [AudioMaterialDefinitions](/vext/ref/fb/audiomaterialdefinitions/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |