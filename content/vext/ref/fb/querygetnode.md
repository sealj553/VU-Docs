---
title: QueryGetNode
---

Inherits from [UINodeData](/vext/ref/fb/uinodedata)

## Summary

### Constructors

|  |
| --- |
| **[QueryGetNode](#constructor-0)**() |
| **[QueryGetNode](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[QueryGetNode](#constructor-2)**(other: [UINodeData](/vext/ref/fb/uinodedata)) |
| **[QueryGetNode](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "inValue" >}} | [UINodePort](/vext/ref/fb/uinodeport) \| nil |
| {{< prop "out" >}} | [UINodePort](/vext/ref/fb/uinodeport) \| nil |
| {{< prop "dataSource" >}} | [UIDataSourceInfo](/vext/ref/fb/uidatasourceinfo) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "QueryGetNode" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### QueryGetNode {#constructor-0}

> **QueryGetNode**()

Creates a new [QueryGetNode](/vext/ref/fb/querygetnode) frostbite instance.

### QueryGetNode {#constructor-1}

> **QueryGetNode**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [QueryGetNode](/vext/ref/fb/querygetnode) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### QueryGetNode {#constructor-2}

> **QueryGetNode**(other: [UINodeData](/vext/ref/fb/uinodedata))

Casts an instance of type [UINodeData](/vext/ref/fb/uinodedata) to [QueryGetNode](/vext/ref/fb/querygetnode). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [UINodeData](/vext/ref/fb/uinodedata) | The instance to cast to [QueryGetNode](/vext/ref/fb/querygetnode). |

### QueryGetNode {#constructor-3}

> **QueryGetNode**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [QueryGetNode](/vext/ref/fb/querygetnode). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [QueryGetNode](/vext/ref/fb/querygetnode). |

## Properties

### {{% prop-heading "inValue" %}}

> **[UINodePort](/vext/ref/fb/uinodeport)** \| **nil**

### {{% prop-heading "out" %}}

> **[UINodePort](/vext/ref/fb/uinodeport)** \| **nil**

### {{% prop-heading "dataSource" %}}

> **[UIDataSourceInfo](/vext/ref/fb/uidatasourceinfo)**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [QueryGetNode](/vext/ref/fb/querygetnode) type.

