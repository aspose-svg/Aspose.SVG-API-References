---
title: "ICSSStyleSheet インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.ICSSStyleSheet インターフェイス。CSSStyleSheet インターフェイスは、CSSスタイルシート（コンテンツタイプが text/css のスタイルシート）を表す具体的なインターフェイスです。"
type: docs
weight: 2660
url: /ja/net/aspose.svg.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet インターフェイスは、コンテンツタイプが "text/css" のスタイルシート、すなわち CSS スタイルシートを表す具体的なインターフェイスです。

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icssstylesheet/cssrules/) { get; } | スタイルシートに含まれるすべての CSS ルールのリストです。ルールセットと at-rule の両方が含まれます。 |
| [OwnerRule](../../aspose.svg.dom.css/icssstylesheet/ownerrule/) { get; } | @import ルールからこのスタイルシートが来た場合、ownerRule 属性には CSSImportRule が含まれます。その場合、StyleSheet インターフェイスの ownerNode 属性は null になります。スタイルシートが要素または処理命令から来た場合、ownerRule 属性は null となり、ownerNode 属性には Node が含まれます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [DeleteRule](../../aspose.svg.dom.css/icssstylesheet/deleterule/)(*int*) | スタイルシートからルールを削除するために使用されます。 |
| [InsertRule](../../aspose.svg.dom.css/icssstylesheet/insertrule/)(*string, int*) | スタイルシートに新しいルールを挿入するために使用されます。新しいルールはカスケードの一部になります。 |

### 参照

* interface [IStyleSheet](../istylesheet/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
