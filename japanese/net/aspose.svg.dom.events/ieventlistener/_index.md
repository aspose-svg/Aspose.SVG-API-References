---
title: "IEventListener インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Events.IEventListener インターフェイス。IEventListener インターフェイスは、イベント処理の主要な手段です。ユーザーは IEventListener インターフェイスを実装し、AddEventListener メソッドを使用して EventTarget にリスナーを登録します。ユーザーは、リスナーの使用が完了した後、EventTarget から IEventListener を削除すべきです。"
type: docs
weight: 2950
url: /ja/net/aspose.svg.dom.events/ieventlistener/
---
## IEventListener interface

`IEventListener` インターフェイスは、イベント処理の主要な手段です。ユーザーは `IEventListener` インターフェイスを実装し、[`EventTarget`](../../aspose.svg.dom/eventtarget/) 上で [`AddEventListener`](../../aspose.svg.dom/eventtarget/addeventlistener/) メソッドを使用してリスナーを登録します。ユーザーは、リスナーの使用が完了した後、その [`EventTarget`](../../aspose.svg.dom/eventtarget/) から `IEventListener` を削除すべきです。

```csharp
public interface IEventListener
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [HandleEvent](../../aspose.svg.dom.events/ieventlistener/handleevent/)(*[Event](../event/)*) | このメソッドは、`IEventListener` インターフェイスが登録されたタイプのイベントが発生するたびに呼び出されます。 |

## 備考

cloneNode メソッドでノードをコピーすると、元ノードに付随していたイベントリスナーはコピーされたノードには付随しません。ユーザーが同じイベントリスナーを新しく作成されたコピーに追加したい場合は、手動で追加する必要があります。

### 参照

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
