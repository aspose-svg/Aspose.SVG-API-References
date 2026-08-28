---
title: "IMediaList インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.IMediaList インターフェイス。MediaList インターフェイスは、実装方法を定義したり制約したりせずに、メディアの順序付けられたコレクションの抽象化を提供します。空のリストは、すべてのメディアを含むリストと同じです。"
type: docs
weight: 2730
url: /ja/net/aspose.svg.dom.css/imedialist/
---
## IMediaList interface

MediaList インターフェイスは、実装方法を定義または制約せずに、メディアの順序付けされたコレクションの抽象化を提供します。空のリストは、メディア "all" を含むリストと同等です。

```csharp
public interface IMediaList : IEnumerable<string>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Item](../../aspose.svg.dom.css/imedialist/item/) { get; } | リスト内の index 番目を返します。index がリスト内のメディア数以上の場合、null を返します。メディアインデックス。 |
| [Length](../../aspose.svg.dom.css/imedialist/length/) { get; } | リスト内のメディア数です。有効なメディアの範囲は 0 から length-1 まで（両端含む）です。 |
| [MediaText](../../aspose.svg.dom.css/imedialist/mediatext/) { get; } | メディアリストの解析可能なテキスト表現です。これはメディアをカンマで区切ったリストです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AppendMedium](../../aspose.svg.dom.css/imedialist/appendmedium/)(*string*) | newMedium メディアをリストの末尾に追加します。newMedium がすでに使用されている場合は、まず削除されます。 |
| [DeleteMedium](../../aspose.svg.dom.css/imedialist/deletemedium/)(*string*) | oldMedium が示すメディアをリストから削除します。 |

### 参照

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
