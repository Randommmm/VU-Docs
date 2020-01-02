---
title: DialogNode
---
### Base Classes

[StateNode](StateNode)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                           | Description                                                                                                 |
| --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| DialogNode()                                                          | Create a new instance of this container type.                                                               |
| DialogNode(DialogNode other)                                          | Create a reference copy of an instance of the same type.                                                    |
| DialogNode([StateNode](StateNode) other)                              | Upcast an instance of type [StateNode](StateNode) to [DialogNode](DialogNode).                              |
| DialogNode([UINodeData](UINodeData) other)                            | Upcast an instance of type [UINodeData](UINodeData) to [DialogNode](DialogNode).                            |
| DialogNode([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [DialogNode](DialogNode). |

## Properties

| Name        | Type                               | Description |
| ----------- | ---------------------------------- | ----------- |
| dialogTitle | string                             |             |
| dialogText  | string                             |             |
| buttons     | [UIPopupButton](UIPopupButton)\[\] |             |

## Methods

| Type                     | Name            | Parameters                                     |
| ------------------------ | --------------- | ---------------------------------------------- |
| [DialogNode](DialogNode) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [DialogNode](DialogNode) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |