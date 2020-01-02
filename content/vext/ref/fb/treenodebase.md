---
title: TreeNodeBase
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                             | Description                                                                                                     |
| ----------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| TreeNodeBase()                                                          | Create a new instance of this container type.                                                                   |
| TreeNodeBase(TreeNodeBase other)                                        | Create a reference copy of an instance of the same type.                                                        |
| TreeNodeBase([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [TreeNodeBase](TreeNodeBase). |

## Properties

| Name     | Type   | Description |
| -------- | ------ | ----------- |
| nodeName | string |             |

## Methods

| Type                         | Name            | Parameters                                     |
| ---------------------------- | --------------- | ---------------------------------------------- |
| [TreeNodeBase](TreeNodeBase) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [TreeNodeBase](TreeNodeBase) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |