---
title: "TypeInfo 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.TypeInfo 类。TypeInfo 表示在与文档关联的模式中指定的 Element 或 Attr 节点引用的类型"
type: docs
weight: 3280
url: /zh/net/aspose.svg.dom/typeinfo/
---
## TypeInfo class

TypeInfo 表示从 Element 或 Attr 节点引用的类型，该类型在与文档关联的模式中指定。

```csharp
public class TypeInfo : DOMObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [TypeName](../../aspose.svg.dom/typeinfo/typename/) { get; } | 为关联的元素或属性声明的类型名称，如果未知则为 null。 |
| [TypeNamespace](../../aspose.svg.dom/typeinfo/typenamespace/) { get; } | 获取类型命名空间。如果为关联的元素或属性声明了类型，则返回该类型的命名空间；如果元素没有声明或没有可用的命名空间信息，则返回 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [IsDerivedFrom](../../aspose.svg.dom/typeinfo/isderivedfrom/)(*string, string, ulong*) | 此方法返回引用类型定义（即调用该方法的 TypeInfo）与另一个类型定义（即作为参数传入的类型）之间是否存在派生关系。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.svg.dom/typeinfo/derivation_extension/) | 如果文档的模式是 XML Schema [XML Schema Part 1]，此常量表示通过扩展的派生。 |
| const [DERIVATION_LIST](../../aspose.svg.dom/typeinfo/derivation_list/) | 如果文档的模式是 XML Schema [XML Schema Part 1]，此常量表示列表。 |
| const [DERIVATION_RESTRICTION](../../aspose.svg.dom/typeinfo/derivation_restriction/) | 如果文档的模式是 XML Schema [XML Schema Part 1]，此常量在涉及复合类型时表示通过限制的派生，在涉及简单类型时表示限制。 |
| const [DERIVATION_UNION](../../aspose.svg.dom/typeinfo/derivation_union/) | 如果文档的模式是 XML Schema [XML Schema Part 1]，此常量在涉及简单类型时表示联合。 |

### 另请参阅

* class [DOMObject](../domobject/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
