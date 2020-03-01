---
title: UISessionDataComponentData
---
### Base Classes

[UIComponentData](/vext/ref/fb/uicomponentdata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                           | Description                                                                                                                                 |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| UISessionDataComponentData()                                                          | Create a new instance of this container type.                                                                                               |
| UISessionDataComponentData(UISessionDataComponentData other)                          | Create a reference copy of an instance of the same type.                                                                                    |
| UISessionDataComponentData([UIComponentData](/vext/ref/fb/uicomponentdata/) other)                  | Upcast an instance of type [UIComponentData](/vext/ref/fb/uicomponentdata/) to [UISessionDataComponentData](/vext/ref/fb/uisessiondatacomponentdata/).                  |
| UISessionDataComponentData([Asset](/vext/ref/fb/asset/) other)                                      | Upcast an instance of type [Asset](/vext/ref/fb/asset/) to [UISessionDataComponentData](/vext/ref/fb/uisessiondatacomponentdata/).                                      |
| UISessionDataComponentData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UISessionDataComponentData](/vext/ref/fb/uisessiondatacomponentdata/). |

## Methods

| Type                                                     | Name            | Parameters                                     |
| -------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [UISessionDataComponentData](/vext/ref/fb/uisessiondatacomponentdata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UISessionDataComponentData](/vext/ref/fb/uisessiondatacomponentdata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |