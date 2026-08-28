---
title: "CustomEvent.InitCustomEvent"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "CustomEvent InitCustomEvent メソッド。/// InitEvent メソッドは IDocumentEvent インターフェイスを通じて作成された Event の値を初期化するために使用されます"
type: docs
weight: 30
url: /ja/net/aspose.svg.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// [`InitEvent`](../../event/initevent/) メソッドは、[`IDocumentEvent`](../../idocumentevent/) インターフェイスを通じて作成された [`Event`](../../event/) の値を初期化するために使用されます。

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | String | イベントのタイプ。 |
| bubbles | Boolean | `true` に設定された場合 [bubbles]。 |
| キャンセル可能 | Boolean | `true` に設定された場合 [cancelable]。 |
| 詳細 | オブジェクト | カスタムデータです。 |

## 備考

このメソッドは、Event が [`DispatchEvent`](../../ieventtarget/dispatchevent/) メソッドを介してディスパッチされる前にのみ呼び出すことができますが、必要に応じてそのフェーズ中に複数回呼び出すことも可能です。複数回呼び出された場合、最後の呼び出しが優先されます。Event インターフェイスのサブクラスから呼び出された場合、initEvent メソッドで指定された値だけが変更され、他のすべての属性は変更されません。

### 参照

* class [CustomEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
