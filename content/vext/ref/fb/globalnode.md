---
title: GlobalNode
---
### Base Classes

[UINodeData](UINodeData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                           | Description                                                                                                 |
| --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| GlobalNode()                                                          | Create a new instance of this container type.                                                               |
| GlobalNode(GlobalNode other)                                          | Create a reference copy of an instance of the same type.                                                    |
| GlobalNode([UINodeData](UINodeData) other)                            | Upcast an instance of type [UINodeData](UINodeData) to [GlobalNode](GlobalNode).                            |
| GlobalNode([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [GlobalNode](GlobalNode). |

## Properties

| Name    | Type                         | Description |
| ------- | ---------------------------- | ----------- |
| outputs | [UINodePort](UINodePort)\[\] |             |

## Methods

| Type                     | Name            | Parameters                                     |
| ------------------------ | --------------- | ---------------------------------------------- |
| [GlobalNode](GlobalNode) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [GlobalNode](GlobalNode) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |