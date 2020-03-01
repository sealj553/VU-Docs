---
title: PersistenceStatTable
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                     | Description                                                                                                                     |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| PersistenceStatTable()                                                          | Create a new instance of this container type.                                                                                   |
| PersistenceStatTable(PersistenceStatTable other)                                | Create a reference copy of an instance of the same type.                                                                        |
| PersistenceStatTable([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [PersistenceStatTable](/vext/ref/fb/persistencestattable/). |

## Properties

| Name                 | Type                                               | Description |
| -------------------- | -------------------------------------------------- | ----------- |
| tableName            | string                                             |             |
| ownerPersistenceData | [AbstractPersistenceData](/vext/ref/fb/abstractpersistencedata/) |             |

## Methods

| Type                                         | Name            | Parameters                                     |
| -------------------------------------------- | --------------- | ---------------------------------------------- |
| [PersistenceStatTable](/vext/ref/fb/persistencestattable/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [PersistenceStatTable](/vext/ref/fb/persistencestattable/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |