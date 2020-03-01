---
title: PresenceMatchFeedServiceData
---
### Base Classes

[PresenceServiceData](/vext/ref/fb/presenceservicedata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                             | Description                                                                                                                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| PresenceMatchFeedServiceData()                                                          | Create a new instance of this container type.                                                                                                   |
| PresenceMatchFeedServiceData(PresenceMatchFeedServiceData other)                        | Create a reference copy of an instance of the same type.                                                                                        |
| PresenceMatchFeedServiceData([PresenceServiceData](/vext/ref/fb/presenceservicedata/) other)          | Upcast an instance of type [PresenceServiceData](/vext/ref/fb/presenceservicedata/) to [PresenceMatchFeedServiceData](/vext/ref/fb/presencematchfeedservicedata/).          |
| PresenceMatchFeedServiceData([Asset](/vext/ref/fb/asset/) other)                                      | Upcast an instance of type [Asset](/vext/ref/fb/asset/) to [PresenceMatchFeedServiceData](/vext/ref/fb/presencematchfeedservicedata/).                                      |
| PresenceMatchFeedServiceData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [PresenceMatchFeedServiceData](/vext/ref/fb/presencematchfeedservicedata/). |

## Methods

| Type                                                         | Name            | Parameters                                     |
| ------------------------------------------------------------ | --------------- | ---------------------------------------------- |
| [PresenceMatchFeedServiceData](/vext/ref/fb/presencematchfeedservicedata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [PresenceMatchFeedServiceData](/vext/ref/fb/presencematchfeedservicedata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |