---
title: "TimeEvent.InitTimeEvent"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "TimeEvent InitTimeEvent メソッド。initTimeEvent メソッドは DocumentEvent インターフェイスを通じて作成された TimeEvent の値を初期化するために使用されます。このメソッドは TimeEvent が dispatchEvent メソッドでディスパッチされる前にのみ呼び出すことができ、必要に応じてそのフェーズ内で複数回呼び出すことが可能です。複数回呼び出された場合は、最後の呼び出しが優先されます。"
type: docs
weight: 30
url: /ja/net/aspose.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

initTimeEvent メソッドは、DocumentEvent インターフェイスを介して作成された TimeEvent の値を初期化するために使用されます。このメソッドは、TimeEvent が dispatchEvent メソッドによってディスパッチされる前にのみ呼び出すことができ、必要に応じてそのフェーズ中に複数回呼び出すことができます。複数回呼び出された場合、最後の呼び出しが優先されます。

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| typeArg | String | イベントのタイプを指定します。 |
| viewArg | IAbstractView | イベントの AbstractView を指定します。 |
| detailArg | Int64 | イベントの detail を指定します。 |

### 参照

* interface [IAbstractView](../../../aspose.svg.dom.views/iabstractview/)
* class [TimeEvent](../)
* namespace [Aspose.Svg.Events](../../../aspose.svg.events/)
* assembly [Aspose.SVG](../../../)
