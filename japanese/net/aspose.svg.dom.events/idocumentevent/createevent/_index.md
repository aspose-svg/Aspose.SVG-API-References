---
title: "IDocumentEvent.CreateEvent"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IDocumentEvent CreateEvent メソッド。実装がサポートするタイプの Event を作成します。"
type: docs
weight: 10
url: /ja/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

実装がサポートするタイプの [`Event`](../../event/) を作成します。

```csharp
public Event CreateEvent(string eventType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| eventType | String | `eventType` パラメータは作成する [`Event`](../../event/) インターフェイスのタイプを指定します。指定された [`Event`](../../event/) インターフェイスが実装でサポートされている場合、このメソッドは要求されたインターフェイス型の新しい [`Event`](../../event/) を返します。[`Event`](../../event/) を [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) メソッドでディスパッチする場合、作成後に適切な [`InitEvent`](../../event/initevent/) メソッドを呼び出して [`Event`](../../event/) の値を初期化する必要があります。 |

### 戻り値

新しく作成された [`Event`](../../event/)

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: 実装が要求された [`Event`](../../event/) インターフェイスのタイプをサポートしていない場合に発生します。 |

### 参照

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
