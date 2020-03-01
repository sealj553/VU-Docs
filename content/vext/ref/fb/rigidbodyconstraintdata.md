---
title: RigidBodyConstraintData
---
### Base Classes

[GameObjectData](/vext/ref/fb/gameobjectdata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                        | Description                                                                                                                           |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| RigidBodyConstraintData()                                                          | Create a new instance of this container type.                                                                                         |
| RigidBodyConstraintData(RigidBodyConstraintData other)                             | Create a reference copy of an instance of the same type.                                                                              |
| RigidBodyConstraintData([GameObjectData](/vext/ref/fb/gameobjectdata/) other)                    | Upcast an instance of type [GameObjectData](/vext/ref/fb/gameobjectdata/) to [RigidBodyConstraintData](/vext/ref/fb/rigidbodyconstraintdata/).                    |
| RigidBodyConstraintData([GameDataContainer](/vext/ref/fb/gamedatacontainer/) other)              | Upcast an instance of type [GameDataContainer](/vext/ref/fb/gamedatacontainer/) to [RigidBodyConstraintData](/vext/ref/fb/rigidbodyconstraintdata/).              |
| RigidBodyConstraintData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [RigidBodyConstraintData](/vext/ref/fb/rigidbodyconstraintdata/). |

## Properties

| Name           | Type                                                    | Description |
| -------------- | ------------------------------------------------------- | ----------- |
| transform      | [LinearTransform](/vext/ref/shared/class/lineartransform) |             |
| parentBody     | [DataContainer](/vext/ref/shared/class/datacontainer)     |             |
| breakThreshold | number                                                  |             |
| isBreakable    | bool                                                    |             |

## Methods

| Type                                               | Name            | Parameters                                     |
| -------------------------------------------------- | --------------- | ---------------------------------------------- |
| [RigidBodyConstraintData](/vext/ref/fb/rigidbodyconstraintdata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [RigidBodyConstraintData](/vext/ref/fb/rigidbodyconstraintdata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |