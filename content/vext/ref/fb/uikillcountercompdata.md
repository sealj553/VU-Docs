---
title: UIKillCounterCompData
---
### Base Classes

[UIComponentData](/vext/ref/fb/uicomponentdata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                      | Description                                                                                                                       |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| UIKillCounterCompData()                                                          | Create a new instance of this container type.                                                                                     |
| UIKillCounterCompData(UIKillCounterCompData other)                               | Create a reference copy of an instance of the same type.                                                                          |
| UIKillCounterCompData([UIComponentData](/vext/ref/fb/uicomponentdata/) other)                  | Upcast an instance of type [UIComponentData](/vext/ref/fb/uicomponentdata/) to [UIKillCounterCompData](/vext/ref/fb/uikillcountercompdata/).                  |
| UIKillCounterCompData([Asset](/vext/ref/fb/asset/) other)                                      | Upcast an instance of type [Asset](/vext/ref/fb/asset/) to [UIKillCounterCompData](/vext/ref/fb/uikillcountercompdata/).                                      |
| UIKillCounterCompData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UIKillCounterCompData](/vext/ref/fb/uikillcountercompdata/). |

## Methods

| Type                                           | Name            | Parameters                                     |
| ---------------------------------------------- | --------------- | ---------------------------------------------- |
| [UIKillCounterCompData](/vext/ref/fb/uikillcountercompdata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UIKillCounterCompData](/vext/ref/fb/uikillcountercompdata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |