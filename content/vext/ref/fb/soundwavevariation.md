---
title: SoundWaveVariation
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                   | Description                                                                                                                 |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| SoundWaveVariation()                                                          | Create a new instance of this container type.                                                                               |
| SoundWaveVariation(SoundWaveVariation other)                                  | Create a reference copy of an instance of the same type.                                                                    |
| SoundWaveVariation([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [SoundWaveVariation](/vext/ref/fb/soundwavevariation/). |

## Properties

| Name                  | Type                                                       | Description |
| --------------------- | ---------------------------------------------------------- | ----------- |
| subtitles             | [SoundWaveSubtitle](/vext/ref/fb/soundwavesubtitle/)\[\]                 |             |
| seekTablesSize        | number                                                     |             |
| segments              | [SoundWaveVariationSegment](/vext/ref/fb/soundwavevariationsegment/)\[\] |             |
| chunkIndex            | number                                                     |             |
| firstLoopSegmentIndex | number                                                     |             |
| lastLoopSegmentIndex  | number                                                     |             |

## Methods

| Type                                     | Name            | Parameters                                     |
| ---------------------------------------- | --------------- | ---------------------------------------------- |
| [SoundWaveVariation](/vext/ref/fb/soundwavevariation/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [SoundWaveVariation](/vext/ref/fb/soundwavevariation/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |