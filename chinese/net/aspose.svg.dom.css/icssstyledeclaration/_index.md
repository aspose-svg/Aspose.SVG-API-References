---
title: "ICSSStyleDeclaration 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.ICSSStyleDeclaration 接口。CSSStyleDeclaration 接口表示单个 CSS 声明块。此接口可用于确定块中当前设置的样式属性，或在块内显式设置样式属性。"
type: docs
weight: 2640
url: /zh/net/aspose.svg.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration 接口表示单个 CSS 声明块。该接口可用于确定块中当前设置的样式属性或在块内显式设置样式属性。

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssstyledeclaration/csstext/) { get; set; } | 声明块的可解析文本表示（不包括外围的大括号）。设置此属性将导致解析新值并重置声明块中的所有属性，包括属性的删除或添加。 |
| [Item](../../aspose.svg.dom.css/icssstyledeclaration/item/) { get; } | 用于检索在此声明块中显式设置的属性。使用此方法检索的属性顺序不必与设置时的顺序相同。此方法可用于遍历此声明块中的所有属性。 |
| [Length](../../aspose.svg.dom.css/icssstyledeclaration/length/) { get; } | 在此声明块中显式设置的属性数量。有效索引范围为 0 到 length-1（含）。 |
| [ParentRule](../../aspose.svg.dom.css/icssstyledeclaration/parentrule/) { get; } | 包含此声明块的 CSS 规则；如果此 CSSStyleDeclaration 未附加到 CSSRule，则为 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertycssvalue/)(*string*) | 用于检索在此声明块中显式设置的 CSS 属性值的对象表示。如果属性是简写属性，则此方法返回 null。简写属性的值只能通过字符串访问和修改，使用 getPropertyValue 和 setProperty 方法。 |
| [GetPropertyPriority](../../aspose.svg.dom.css/icssstyledeclaration/getpropertypriority/)(*string*) | 用于检索在此声明块中显式设置的 CSS 属性的优先级（例如 \"important\" 修饰符）。 |
| [GetPropertyValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertyvalue/)(*string*) | 用于检索在此声明块中显式设置的 CSS 属性的值。 |
| [RemoveProperty](../../aspose.svg.dom.css/icssstyledeclaration/removeproperty/)(*string*) | 用于删除在此声明块中显式设置的 CSS 属性。 |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty)(*string, string*) | 用于在此声明块中以默认优先级设置属性值。默认优先级不是 \"important\"，即 String.Empty。 |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(*string, string, string*) | 用于在此声明块中设置属性值及其优先级。 |

### 另请参阅

* interface [ICSS2Properties](../icss2properties/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
