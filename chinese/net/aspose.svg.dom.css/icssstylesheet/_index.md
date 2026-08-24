---
title: "ICSSStyleSheet 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.ICSSStyleSheet 接口。CSSStyleSheet 接口是一个具体接口，用于表示 CSS 样式表，即内容类型为 text/css 的样式表。"
type: docs
weight: 2660
url: /zh/net/aspose.svg.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet 接口是用于表示 CSS 样式表的具体接口，即内容类型为 "text/css" 的样式表。

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icssstylesheet/cssrules/) { get; } | 样式表中包含的所有 CSS 规则的列表。包括规则集和 at-rule。 |
| [OwnerRule](../../aspose.svg.dom.css/icssstylesheet/ownerrule/) { get; } | 如果此样式表来自 @import 规则，ownerRule 属性将包含 CSSImportRule。在这种情况下，StyleSheet 接口中的 ownerNode 属性将为 null。如果样式表来自元素或处理指令，ownerRule 属性将为 null，ownerNode 属性将包含 Node。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [DeleteRule](../../aspose.svg.dom.css/icssstylesheet/deleterule/)(*int*) | 用于从样式表中删除规则。 |
| [InsertRule](../../aspose.svg.dom.css/icssstylesheet/insertrule/)(*string, int*) | 用于向样式表中插入新规则。新规则现在成为层叠的一部分。 |

### 另请参阅

* interface [IStyleSheet](../istylesheet/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
