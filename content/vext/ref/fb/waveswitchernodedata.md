---
title: WaveSwitcherNodeData
---
### Base Classes

[AudioGraphNodeData](/vext/ref/fb/audiographnodedata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                     | Description                                                                                                                     |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| WaveSwitcherNodeData()                                                          | Create a new instance of this container type.                                                                                   |
| WaveSwitcherNodeData(WaveSwitcherNodeData other)                                | Create a reference copy of an instance of the same type.                                                                        |
| WaveSwitcherNodeData([AudioGraphNodeData](/vext/ref/fb/audiographnodedata/) other)            | Upcast an instance of type [AudioGraphNodeData](/vext/ref/fb/audiographnodedata/) to [WaveSwitcherNodeData](/vext/ref/fb/waveswitchernodedata/).            |
| WaveSwitcherNodeData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [WaveSwitcherNodeData](/vext/ref/fb/waveswitchernodedata/). |

## Properties

| Name             | Type                                     | Description |
| ---------------- | ---------------------------------------- | ----------- |
| index            | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| advance          | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| wave             | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| indexChanged     | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| waves            | [SoundWaveAsset](/vext/ref/fb/soundwaveasset/)\[\]     |             |
| defaultIndex     | number                                   |             |
| isRandom         | bool                                     |             |
| randomStartIndex | bool                                     |             |

## Methods

| Type                                         | Name            | Parameters                                     |
| -------------------------------------------- | --------------- | ---------------------------------------------- |
| [WaveSwitcherNodeData](/vext/ref/fb/waveswitchernodedata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [WaveSwitcherNodeData](/vext/ref/fb/waveswitchernodedata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |