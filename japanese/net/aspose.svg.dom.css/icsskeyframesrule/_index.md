---
title: "ICSSKeyframesRule インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.ICSSKeyframesRule interface. CSSKeyframesRule インターフェイスは、単一のアニメーションに対する完全なキーフレームセットを表します。"
type: docs
weight: 2580
url: /ja/net/aspose.svg.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

CSSKeyframesRule インターフェイスは単一アニメーションのキー フレーム全体のセットを表します。

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icsskeyframesrule/cssrules/) { get; } | この属性はリスト内のキーフレームへのアクセスを提供します。 |
| [Name](../../aspose.svg.dom.css/icsskeyframesrule/name/) { get; } | この属性はキーフレームの名前で、‘animation-name’ プロパティで使用されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AppendRule](../../aspose.svg.dom.css/icsskeyframesrule/appendrule/)(*string*) | appendRule メソッドは、渡された CSSKeyframeRule を指定されたキーの位置にリストへ追加します。 |
| [DeleteRule](../../aspose.svg.dom.css/icsskeyframesrule/deleterule/)(*string*) | deleteRule メソッドは、渡されたキーを持つ CSSKeyframeRule を削除します。そのキーのルールが存在しない場合、メソッドは何もしません。 |
| [FindRule](../../aspose.svg.dom.css/icsskeyframesrule/findrule/)(*string*) | findRule メソッドは、渡されたキーと一致するルールを返します。そのようなルールが存在しない場合、null が返されます。 |

### 参照

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
