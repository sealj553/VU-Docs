---
title: SaveGameLoadedEntityData
---
### Base Classes

[EntityData](/vext/ref/fb/entitydata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                         | Description                                                                                                                             |
| ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| SaveGameLoadedEntityData()                                                          | Create a new instance of this container type.                                                                                           |
| SaveGameLoadedEntityData(SaveGameLoadedEntityData other)                            | Create a reference copy of an instance of the same type.                                                                                |
| SaveGameLoadedEntityData([EntityData](/vext/ref/fb/entitydata/) other)                            | Upcast an instance of type [EntityData](/vext/ref/fb/entitydata/) to [SaveGameLoadedEntityData](/vext/ref/fb/savegameloadedentitydata/).                            |
| SaveGameLoadedEntityData([GameObjectData](/vext/ref/fb/gameobjectdata/) other)                    | Upcast an instance of type [GameObjectData](/vext/ref/fb/gameobjectdata/) to [SaveGameLoadedEntityData](/vext/ref/fb/savegameloadedentitydata/).                    |
| SaveGameLoadedEntityData([GameDataContainer](/vext/ref/fb/gamedatacontainer/) other)              | Upcast an instance of type [GameDataContainer](/vext/ref/fb/gamedatacontainer/) to [SaveGameLoadedEntityData](/vext/ref/fb/savegameloadedentitydata/).              |
| SaveGameLoadedEntityData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [SaveGameLoadedEntityData](/vext/ref/fb/savegameloadedentitydata/). |

## Methods

| Type                                                 | Name            | Parameters                                     |
| ---------------------------------------------------- | --------------- | ---------------------------------------------- |
| [SaveGameLoadedEntityData](/vext/ref/fb/savegameloadedentitydata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [SaveGameLoadedEntityData](/vext/ref/fb/savegameloadedentitydata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |