---
title: StatCategoryTreeCollection
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                           | Description                                                                                                                                 |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| StatCategoryTreeCollection()                                                          | Create a new instance of this container type.                                                                                               |
| StatCategoryTreeCollection(StatCategoryTreeCollection other)                          | Create a reference copy of an instance of the same type.                                                                                    |
| StatCategoryTreeCollection([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [StatCategoryTreeCollection](StatCategoryTreeCollection).                                      |
| StatCategoryTreeCollection([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [StatCategoryTreeCollection](StatCategoryTreeCollection). |

## Properties

| Name          | Type                                                 | Description |
| ------------- | ---------------------------------------------------- | ----------- |
| categoryTrees | [StatCategoriesBaseTree](StatCategoriesBaseTree)\[\] |             |

## Methods

| Type                                                     | Name            | Parameters                                     |
| -------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [StatCategoryTreeCollection](StatCategoryTreeCollection) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [StatCategoryTreeCollection](StatCategoryTreeCollection) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |