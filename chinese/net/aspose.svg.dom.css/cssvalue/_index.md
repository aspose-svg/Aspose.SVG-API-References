---
title: "CSSValue 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.CSSValue 类。表示一个简单或复杂的值。CSSValue 对象仅在 CSS 属性的上下文中出现。"
type: docs
weight: 2490
url: /zh/net/aspose.svg.dom.css/cssvalue/
---
## CSSValue class

表示简单或复杂的值。CSSValue 对象仅在 CSS 属性的上下文中出现。

```csharp
public abstract class CSSValue : DOMObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | `CSSValue` 接口的 CSSText 属性表示当前计算的 CSS 属性值。 |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | 定义该值类型的代码。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | 确定指定的 Object 是否等于此实例。 |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | 返回此实例的哈希码。 |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | 返回表示此实例的字符串。 |
| [operator ==](../../aspose.svg.dom.css/cssvalue/op_equality/) | 实现运算符 ==。 |
| [operator !=](../../aspose.svg.dom.css/cssvalue/op_inequality/) | 实现运算符 !=。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.svg.dom.css/cssvalue/css_custom/) | 该值是自定义值。 |
| const [CSS_INHERIT](../../aspose.svg.dom.css/cssvalue/css_inherit/) | 该值是继承的，且 cssText 包含 \"inherit\"。 |
| const [CSS_PRIMITIVE_VALUE](../../aspose.svg.dom.css/cssvalue/css_primitive_value/) | 该值是原始值，可通过在此 CSSValue 接口实例上使用特定绑定的强制转换方法获取 CSSPrimitiveValue 接口的实例。 |
| const [CSS_VALUE_LIST](../../aspose.svg.dom.css/cssvalue/css_value_list/) | 该值是 CSSValue 列表，可通过在此 CSSValue 接口实例上使用特定绑定的强制转换方法获取 CSSValueList 接口的实例。 |

### 另请参阅

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
