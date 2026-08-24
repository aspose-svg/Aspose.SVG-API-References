---
title: "ICSSKeyframesRule 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.ICSSKeyframesRule 接口。CSSKeyframesRule 接口表示单个动画的完整关键帧集合。"
type: docs
weight: 2580
url: /zh/net/aspose.svg.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

CSSKeyframesRule 接口表示单个动画的完整关键帧集合。

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icsskeyframesrule/cssrules/) { get; } | 此属性提供对列表中关键帧的访问 |
| [Name](../../aspose.svg.dom.css/icsskeyframesrule/name/) { get; } | 此属性是关键帧的名称，供 ‘animation-name’ 属性使用。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AppendRule](../../aspose.svg.dom.css/icsskeyframesrule/appendrule/)(*string*) | appendRule 方法将传入的 CSSKeyframeRule 追加到列表中对应的键位置。 |
| [DeleteRule](../../aspose.svg.dom.css/icsskeyframesrule/deleterule/)(*string*) | deleteRule 方法会删除具有给定键的 CSSKeyframeRule。如果不存在具有该键的规则，方法不执行任何操作。 |
| [FindRule](../../aspose.svg.dom.css/icsskeyframesrule/findrule/)(*string*) | findRule 方法返回键与给定键匹配的规则。如果不存在此类规则，则返回 null 值。 |

### 另请参阅

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
