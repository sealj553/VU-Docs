---
title: PersistenceStatGroup
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                     | Description                                                                                                                     |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| PersistenceStatGroup()                                                          | Create a new instance of this container type.                                                                                   |
| PersistenceStatGroup(PersistenceStatGroup other)                                | Create a reference copy of an instance of the same type.                                                                        |
| PersistenceStatGroup([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [PersistenceStatGroup](/vext/ref/fb/persistencestatgroup/). |

## Properties

| Name      | Type   | Description |
| --------- | ------ | ----------- |
| groupName | string |             |

## Methods

| Type                                         | Name            | Parameters                                     |
| -------------------------------------------- | --------------- | ---------------------------------------------- |
| [PersistenceStatGroup](/vext/ref/fb/persistencestatgroup/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [PersistenceStatGroup](/vext/ref/fb/persistencestatgroup/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |