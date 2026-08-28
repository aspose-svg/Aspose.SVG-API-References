---
title: "Event.PreventDefault"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Event PreventDefault メソッド。イベントがキャンセル可能な場合、PreventDefault メソッドはそのイベントがキャンセルされることを示すために使用され、結果として実装が通常行うデフォルトアクションは実行されません。"
type: docs
weight: 120
url: /ja/net/aspose.svg.dom.events/event/preventdefault/
---
## Event.PreventDefault method

イベントがキャンセル可能な場合、`PreventDefault` メソッドはそのイベントがキャンセルされることを示すために使用され、結果として実装が通常行うデフォルトアクションは実行されません。

```csharp
public void PreventDefault()
```

## 備考

イベントフローの任意の段階で `PreventDefault` メソッドが呼び出された場合、イベントはキャンセルされます。イベントに関連付けられたデフォルトアクションは実行されません。キャンセル不可能なイベントに対してこのメソッドを呼び出しても効果はありません。`PreventDefault` が一度呼び出されると、イベントの伝播が残りの間ずっと有効です。このメソッドはイベントフローの任意の段階で使用できます。

### 参照

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
