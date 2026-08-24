---
title: "TimeEvent 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Events.TimeEvent 类。TimeEvent 接口提供与时间事件相关的特定上下文信息。可以发生的不同类型的事件包括 beginEvent、endEvent 和 repeatEvent。"
type: docs
weight: 3720
url: /zh/net/aspose.svg.events/timeevent/
---
## TimeEvent class

TimeEvent 接口提供与时间事件相关的特定上下文信息。可能出现的事件类型有：beginEvent、endEvent 和 repeatEvent。

```csharp
public class TimeEvent : Event
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true；否则为 false。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | 用于指示事件是否可以阻止其默认行为。如果可以阻止默认行为，则值为 true，否则值为 false。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 用于指示当前正在处理其 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 的 [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)。这在捕获和冒泡阶段特别有用。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | 如果在 cancelable 属性为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [Detail](../../aspose.svg.events/timeevent/detail/) { get; } | 指定有关事件的详细信息，取决于事件的类型。对于此事件类型，指示动画的重复次数。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 用于指示当前正在评估的事件流阶段。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性必须返回其初始化时的值。事件创建时，该属性必须初始化为 false。 |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | 用于指示事件最初分派到的 [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)。 |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | 用于指定事件创建时的时间（相对于纪元的毫秒数）。由于某些系统可能不提供此信息，timeStamp 的值可能并非对所有事件都可用。若不可用，将返回 0。纪元时间的例子包括系统启动时间或 UTC 1970 年 1 月 1 日 0:0:0。 |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | 事件的名称（不区分大小写）。名称必须是 XML 名称。 |
| [View](../../aspose.svg.events/timeevent/view/) { get; } | view 属性标识生成事件的 AbstractView [DOM2VIEWS]。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | [`InitEvent`](../../aspose.svg.dom.events/event/initevent/) 方法用于初始化通过 [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/) 接口创建的 [`Event`](../../aspose.svg.dom.events/event/) 的值。 |
| [InitTimeEvent](../../aspose.svg.events/timeevent/inittimeevent/)(*string, [IAbstractView](../../aspose.svg.dom.views/iabstractview/), long*) | initTimeEvent 方法用于初始化通过 DocumentEvent 接口创建的 TimeEvent 的值。此方法只能在 TimeEvent 通过 dispatchEvent 方法分发之前调用，尽管在该阶段如有必要可以多次调用。如果多次调用，则以最后一次调用为准。 |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | 如果事件是可取消的，[`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/) 方法用于表示该事件将被取消，这意味着实现通常会因该事件而执行的任何默认操作都不会发生。 |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | 调用此方法可阻止事件到达在当前监听器之后注册的任何事件监听器，并且在树状分发时也阻止事件到达其他对象。 |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | 该 [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/) 方法用于防止在事件流期间进一步传播事件。 |

### 另请参阅

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
