---
title: CriteriaGateList
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                 | Description                                                                                                             |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| CriteriaGateList()                                                          | Create a new instance of this container type.                                                                           |
| CriteriaGateList(CriteriaGateList other)                                    | Create a reference copy of an instance of the same type.                                                                |
| CriteriaGateList([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [CriteriaGateList](CriteriaGateList).                                      |
| CriteriaGateList([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [CriteriaGateList](CriteriaGateList). |

## Properties

| Name          | Type       | Description |
| ------------- | ---------- | ----------- |
| criteriaGates | number\[\] |             |

## Methods

| Type                                 | Name            | Parameters                                     |
| ------------------------------------ | --------------- | ---------------------------------------------- |
| [CriteriaGateList](CriteriaGateList) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [CriteriaGateList](CriteriaGateList) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |