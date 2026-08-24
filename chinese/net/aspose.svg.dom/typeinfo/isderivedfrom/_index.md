---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.SVG for .NET API 参考"
description: "TypeInfo IsDerivedFrom 方法。此方法返回参考类型定义（即调用该方法的 TypeInfo）与另一个类型定义（即作为参数传入的类型）之间是否存在派生关系。"
type: docs
weight: 30
url: /zh/net/aspose.svg.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

此方法返回引用类型定义（即调用该方法的 TypeInfo）与另一个类型定义（即作为参数传入的类型）之间是否存在派生关系。

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeNamespaceArg | String | 另一个类型定义的命名空间 |
| typeNameArg | String | 另一个类型定义的名称。 |
| derivationMethod | UInt64 | 两种类型之间的派生类型及其适用条件，详见此接口提供的常量列表。 |

### 返回值

如果文档的模式是 DTD 或文档未关联任何模式，此方法始终返回 false。如果文档的模式是 XML Schema，则当参考类型定义根据 derivation 参数从另一个类型定义派生时，方法返回 true。如果参数的值为 0（即 derivationMethod 参数的位均未设置为 1），则当可以通过从参考类型定义递归任意组合的 {base type definition}、{item type definition} 或 {member type definitions} 到达另一个类型定义时，方法返回 true。

### 另请参阅

* class [TypeInfo](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
