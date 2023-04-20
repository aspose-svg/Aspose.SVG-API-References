---
title: Interface ICSSKeyframesRule
second_title: Aspose.SVG for .NET API リファレンス
description: Aspose.Svg.Dom.Css.ICSSKeyframesRule インターフェース. CSSKeyframesRule インターフェイスは1 つのアニメーションの完全なキーフレーム セットを表します
type: docs
weight: 580
url: /ja/net/aspose.svg.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

CSSKeyframesRule インターフェイスは、1 つのアニメーションの完全なキーフレーム セットを表します

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icsskeyframesrule/cssrules/) { get; } | この属性は、list 内のキーフレームへのアクセスを提供します |
| [Name](../../aspose.svg.dom.css/icsskeyframesrule/name/) { get; } | この属性は、「animation-name」プロパティで使用されるキーフレームの名前です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AppendRule](../../aspose.svg.dom.css/icsskeyframesrule/appendrule/)(string) | appendRule メソッドは、渡された CSSKeyframeRule をリストの渡された key に追加します。 |
| [DeleteRule](../../aspose.svg.dom.css/icsskeyframesrule/deleterule/)(string) | deleteRule メソッドは、渡されたキーで CSSKeyframeRule を削除します。このキーを持つルールが存在しない場合、メソッドは何もしません |
| [FindRule](../../aspose.svg.dom.css/icsskeyframesrule/findrule/)(string) | findRule メソッドは、渡されたキーと一致するキーを持つルールを返します。そのようなルールが存在しない場合は、null 値が返されます |

### 関連項目

* interface [ICSSRule](../icssrule/)
* 名前空間 [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* 組み立て [Aspose.SVG](../../)


