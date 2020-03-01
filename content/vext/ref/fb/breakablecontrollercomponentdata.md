---
title: BreakableControllerComponentData
---
### Base Classes

[DestructionControllerComponentData](/vext/ref/fb/destructioncontrollercomponentdata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                                                      | Description                                                                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BreakableControllerComponentData()                                                                               | Create a new instance of this container type.                                                                                                                                |
| BreakableControllerComponentData(BreakableControllerComponentData other)                                         | Create a reference copy of an instance of the same type.                                                                                                                     |
| BreakableControllerComponentData([DestructionControllerComponentData](/vext/ref/fb/destructioncontrollercomponentdata/) other) | Upcast an instance of type [DestructionControllerComponentData](/vext/ref/fb/destructioncontrollercomponentdata/) to [BreakableControllerComponentData](/vext/ref/fb/breakablecontrollercomponentdata/). |
| BreakableControllerComponentData([ComponentData](/vext/ref/fb/componentdata/) other)                                           | Upcast an instance of type [ComponentData](/vext/ref/fb/componentdata/) to [BreakableControllerComponentData](/vext/ref/fb/breakablecontrollercomponentdata/).                                           |
| BreakableControllerComponentData([GameObjectData](/vext/ref/fb/gameobjectdata/) other)                                         | Upcast an instance of type [GameObjectData](/vext/ref/fb/gameobjectdata/) to [BreakableControllerComponentData](/vext/ref/fb/breakablecontrollercomponentdata/).                                         |
| BreakableControllerComponentData([GameDataContainer](/vext/ref/fb/gamedatacontainer/) other)                                   | Upcast an instance of type [GameDataContainer](/vext/ref/fb/gamedatacontainer/) to [BreakableControllerComponentData](/vext/ref/fb/breakablecontrollercomponentdata/).                                   |
| BreakableControllerComponentData([DataContainer](/vext/ref/shared/class/datacontainer) other)                      | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [BreakableControllerComponentData](/vext/ref/fb/breakablecontrollercomponentdata/).                      |

## Properties

| Name               | Type   | Description |
| ------------------ | ------ | ----------- |
| breakablePartCount | number |             |
| networkIdCount     | number |             |

## Methods

| Type                                                                 | Name            | Parameters                                     |
| -------------------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [BreakableControllerComponentData](/vext/ref/fb/breakablecontrollercomponentdata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [BreakableControllerComponentData](/vext/ref/fb/breakablecontrollercomponentdata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |