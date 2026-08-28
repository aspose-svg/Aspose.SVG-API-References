---
title: "KeyboardEvent.Repeat"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "KeyboardEvent Repeat プロパティ。キーが持続的に押された場合に true です。キーを押し続けると、システム設定で決定されたレートで、keydown、beforeinput、input のイベントがこの順序で繰り返されなければなりません。長押し動作を持つモバイルデバイスでは、repeat 属性が true の最初のキーイベントが長押しの指標として機能しなければなりません。繰り返しが開始されるまでにキーを押し続ける必要がある時間は、設定に依存します。"
type: docs
weight: 90
url: /ja/net/aspose.svg.dom.events/keyboardevent/repeat/
---
## KeyboardEvent.Repeat property

キーが長時間押し続けられた場合は true。キーを押し続けると、システム設定で決定されたレートで、keydown、beforeinput、input のイベントがこの順序で繰り返し発生しなければなりません。長押し動作を持つモバイルデバイスでは、repeat 属性が true の最初のキーイベントが長押しの指標として機能しなければなりません。繰り返しが開始されるまでにキーを押し続ける必要がある時間は、設定に依存します。

```csharp
public bool Repeat { get; }
```

### Property Value

`true` はリピートの場合、そうでなければ `false`。

### 参照

* class [KeyboardEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
