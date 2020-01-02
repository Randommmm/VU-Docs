---
title: UIDelayedCommandsCompData
---
### Base Classes

[UIComponentData](UIComponentData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                          | Description                                                                                                                               |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- |
| UIDelayedCommandsCompData()                                                          | Create a new instance of this container type.                                                                                             |
| UIDelayedCommandsCompData(UIDelayedCommandsCompData other)                           | Create a reference copy of an instance of the same type.                                                                                  |
| UIDelayedCommandsCompData([UIComponentData](UIComponentData) other)                  | Upcast an instance of type [UIComponentData](UIComponentData) to [UIDelayedCommandsCompData](UIDelayedCommandsCompData).                  |
| UIDelayedCommandsCompData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIDelayedCommandsCompData](UIDelayedCommandsCompData).                                      |
| UIDelayedCommandsCompData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UIDelayedCommandsCompData](UIDelayedCommandsCompData). |

## Methods

| Type                                                   | Name            | Parameters                                     |
| ------------------------------------------------------ | --------------- | ---------------------------------------------- |
| [UIDelayedCommandsCompData](UIDelayedCommandsCompData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UIDelayedCommandsCompData](UIDelayedCommandsCompData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |