---
title: "SVGSVGElement.CreateEvent"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGSVGElement CreateEvent メソッド。実装がサポートするタイプの Event を作成します。"
type: docs
weight: 110
url: /ja/net/aspose.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

実装がサポートするタイプの [`Event`](../../../aspose.svg.dom.events/event/) を作成します。

```csharp
public Event CreateEvent(string eventType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| eventType | String | eventType パラメータは、作成する [`Event`](../../../aspose.svg.dom.events/event/) インターフェイスのタイプを指定します。指定された [`Event`](../../../aspose.svg.dom.events/event/) インターフェイスが実装でサポートされている場合、このメソッドは要求されたインターフェイスタイプの新しい [`Event`](../../../aspose.svg.dom.events/event/) を返します。[`Event`](../../../aspose.svg.dom.events/event/) を [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) メソッドでディスパッチする場合、作成後に適切な [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/) メソッドを呼び出して [`Event`](../../../aspose.svg.dom.events/event/) の値を初期化する必要があります。 |

### 戻り値

新しく作成された [`Event`](../../../aspose.svg.dom.events/event/)

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: 要求された [`Event`](../../../aspose.svg.dom.events/event/) インターフェイスのタイプが実装でサポートされていない場合に発生します |

### 参照

* class [Event](../../../aspose.svg.dom.events/event/)
* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
