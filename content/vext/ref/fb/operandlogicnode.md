---
title: OperandLogicNode
---
### Base Classes

[UINodeData](UINodeData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                 | Description                                                                                                             |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| OperandLogicNode()                                                          | Create a new instance of this container type.                                                                           |
| OperandLogicNode(OperandLogicNode other)                                    | Create a reference copy of an instance of the same type.                                                                |
| OperandLogicNode([UINodeData](UINodeData) other)                            | Upcast an instance of type [UINodeData](UINodeData) to [OperandLogicNode](OperandLogicNode).                            |
| OperandLogicNode([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [OperandLogicNode](OperandLogicNode). |

## Properties

| Name                | Type                                 | Description |
| ------------------- | ------------------------------------ | ----------- |
| leftDataSourceInfo  | [UIDataSourceInfo](UIDataSourceInfo) |             |
| operator            | [UILogicOperator](UILogicOperator)   |             |
| rightDataSourceInfo | [UIDataSourceInfo](UIDataSourceInfo) |             |
| rightLiteralOperand | number                               |             |
| inValue             | [UINodePort](UINodePort)             |             |
| trueValue           | [UINodePort](UINodePort)             |             |
| falseValue          | [UINodePort](UINodePort)             |             |

## Methods

| Type                                 | Name            | Parameters                                     |
| ------------------------------------ | --------------- | ---------------------------------------------- |
| [OperandLogicNode](OperandLogicNode) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [OperandLogicNode](OperandLogicNode) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |