---
title: "Event.StopPropagation"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Event StopPropagation メソッド。StopPropagation メソッドは、イベントフロー中にイベントのさらなる伝播を防止するために使用されます。"
type: docs
weight: 140
url: /ja/net/aspose.svg.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

`StopPropagation` メソッドは、イベントフロー中にイベントのさらなる伝播を防止するために使用されます。

```csharp
public void StopPropagation()
```

## 備考

このメソッドが任意の [`IEventListener`](../../ieventlistener/) によって呼び出された場合、イベントはツリー内での伝播を停止します。イベントは現在の [`IEventTarget`](../../ieventtarget/) 上のすべてのリスナーへのディスパッチが完了した後に、イベントフローが停止します。このメソッドはイベントフローの任意の段階で使用できます。

### 参照

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
