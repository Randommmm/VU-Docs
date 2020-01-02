---
title: UpdateAlphaLevelScaleData
---
### Base Classes

[ProcessorData](ProcessorData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                          | Description                                                                                                                               |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- |
| UpdateAlphaLevelScaleData()                                                          | Create a new instance of this container type.                                                                                             |
| UpdateAlphaLevelScaleData(UpdateAlphaLevelScaleData other)                           | Create a reference copy of an instance of the same type.                                                                                  |
| UpdateAlphaLevelScaleData([ProcessorData](ProcessorData) other)                      | Upcast an instance of type [ProcessorData](ProcessorData) to [UpdateAlphaLevelScaleData](UpdateAlphaLevelScaleData).                      |
| UpdateAlphaLevelScaleData([EmitterComponentData](EmitterComponentData) other)        | Upcast an instance of type [EmitterComponentData](EmitterComponentData) to [UpdateAlphaLevelScaleData](UpdateAlphaLevelScaleData).        |
| UpdateAlphaLevelScaleData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UpdateAlphaLevelScaleData](UpdateAlphaLevelScaleData). |

## Properties

| Name     | Type   | Description |
| -------- | ------ | ----------- |
| exponent | number |             |

## Methods

| Type                                                   | Name            | Parameters                                     |
| ------------------------------------------------------ | --------------- | ---------------------------------------------- |
| [UpdateAlphaLevelScaleData](UpdateAlphaLevelScaleData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UpdateAlphaLevelScaleData](UpdateAlphaLevelScaleData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |