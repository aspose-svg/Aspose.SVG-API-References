---
title: "SVGStyleElementBuilder.AddRule"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGStyleElementBuilder AddRule メソッド。スタイル要素に CSS ルールを追加します。"
type: docs
weight: 30
url: /ja/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

スタイル要素に CSS ルールを追加します。

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| セレクタ | String | ルールの CSS セレクタです。 |
| rules | String | 文字列としての CSS ルールです。 |

### 戻り値

チェーン用の SVGStyleElementBuilder インスタンスです。

### 参照

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

RuleBuilder を使用してスタイル要素に CSS ルールを追加します。

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| セレクタ | String | ルールの CSS セレクタです。 |
| configureRule | Action`1 | RuleBuilder を使用してルールを構成するためのデリゲートです。 |

### 戻り値

チェーン用の SVGStyleElementBuilder インスタンスです。

### 参照

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
