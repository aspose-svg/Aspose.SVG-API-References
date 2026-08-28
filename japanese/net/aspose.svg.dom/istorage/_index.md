---
title: "IStorage インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.IStorage インターフェイス。Web Storage API のこのインターフェイスは、特定のドメインのセッションまたはローカルストレージへのアクセスを提供します。Web Storage 仕様をご覧ください https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /ja/net/aspose.svg.dom/istorage/
---
## IStorage interface

Web Storage API のこのインターフェイスは、特定のドメインのセッションまたはローカルストレージへのアクセスを提供します。Web Storage 仕様をご覧ください: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | キー/値ペアの数を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | 存在する場合、すべてのキー/バリュー ペアを削除します。 |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | 指定されたキーに関連付けられた現在の値を返します。キーが存在しない場合は null を返します。 |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | n 番目のキーの名前を返します。n がキー/バリュー ペアの数以上の場合は null を返します。 |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | 指定されたキーのキー/バリュー ペアが存在する場合、それを削除します。 |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | キーで識別されるペアの値を value に設定し、以前にキーが存在しなかった場合は新しいキー/バリュー ペアを作成します。 |

### 参照

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
