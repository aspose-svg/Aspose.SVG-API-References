---
title: "CSSValueList 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.CSSValueList 类。CSSValueList 接口提供了有序 CSS 值集合的抽象。"
type: docs
weight: 2500
url: /zh/net/aspose.svg.dom.css/cssvaluelist/
---
## CSSValueList class

CSSValueList 接口提供了有序 CSS 值集合的抽象。

```csharp
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | 初始化 `CSSValueList` 类的新实例。 |
| [CSSValueList](cssvaluelist/#constructor_1)(*params CSSValue[]*) | 初始化 `CSSValueList` 类的新实例。 |
| [CSSValueList](cssvaluelist/#constructor_2)(*IEnumerable&lt;CSSValue&gt;*) | 初始化 `CSSValueList` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [CSSText](../../aspose.svg.dom.css/cssvaluelist/csstext/) { get; set; } | [`CSSValue`](../cssvalue/) 接口的 CSSText 属性表示当前计算的 CSS 属性值。 |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | 定义该值类型的代码。 |
| [Item](../../aspose.svg.dom.css/cssvaluelist/item/) { get; } | 获取指定索引处的 [`CSSValue`](../cssvalue/)。 |
| [Length](../../aspose.svg.dom.css/cssvaluelist/length/) { get; } | CSSValueList 接口的 length 只读属性表示列表中 CSSValue 的数量。索引的有效取值范围为 0 到 length-1（含）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | 确定指定的 Object 是否等于此实例。 |
| [GetEnumerator](../../aspose.svg.dom.css/cssvaluelist/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | 返回此实例的哈希码。 |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvaluelist/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | 返回表示此实例的字符串。 |

### 另请参阅

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
