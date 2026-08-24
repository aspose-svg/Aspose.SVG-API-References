---
title: "ErrorEvent 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Events.ErrorEvent 类。ErrorEvent 提供关于运行时发生的错误的上下文信息。"
type: docs
weight: 2910
url: /zh/net/aspose.svg.dom.events/errorevent/
---
## ErrorEvent class

`ErrorEvent` 提供关于运行时发生的错误的上下文信息。

```csharp
public class ErrorEvent : Event
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(*Exception*) | 初始化 `ErrorEvent` 类的新实例。 |
| [ErrorEvent](errorevent/#constructor)(*IDictionary&lt;string, object&gt;*) | 初始化 `ErrorEvent` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true；否则为 false。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | 用于指示事件是否可以阻止其默认行为。如果可以阻止默认行为，则值为 true，否则值为 false。 |
| [ColNo](../../aspose.svg.dom.events/errorevent/colno/) { get; } | colno 属性必须返回其初始化时的值。对象创建时，该属性必须初始化为零。它表示脚本中错误发生的列号。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 用于指示当前正在处理其 [`IEventListener`](../ieventlistener/) 的 [`IEventTarget`](../ieventtarget/)。这在捕获和冒泡阶段特别有用。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | 如果在 cancelable 属性为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [Error](../../aspose.svg.dom.events/errorevent/error/) { get; } | error 属性必须返回其初始化时的值。对象创建时，该属性必须初始化为 null。在适当情况下，它会被设置为表示错误的对象（例如未捕获的 DOM 异常的异常对象）。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 用于指示当前正在评估的事件流阶段。 |
| [FileName](../../aspose.svg.dom.events/errorevent/filename/) { get; } | filename 属性必须返回其初始化时的值。对象创建时，该属性必须初始化为空字符串。它表示错误最初发生的脚本的绝对 URL。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性必须返回其初始化时的值。事件创建时，该属性必须初始化为 false。 |
| [LineNo](../../aspose.svg.dom.events/errorevent/lineno/) { get; } | lineno 属性必须返回其初始化时的值。对象创建时，该属性必须初始化为零。它表示脚本中错误发生的行号。 |
| [Message](../../aspose.svg.dom.events/errorevent/message/) { get; } | message 属性必须返回其初始化时的值。对象创建时，该属性必须初始化为空字符串。它表示错误信息。 |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | 用于指示事件最初分发到的 [`IEventTarget`](../ieventtarget/)。 |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | 用于指定事件创建时的时间（相对于纪元的毫秒数）。由于某些系统可能不提供此信息，timeStamp 的值可能并非对所有事件都可用。若不可用，将返回 0。纪元时间的例子包括系统启动时间或 UTC 1970 年 1 月 1 日 0:0:0。 |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | 事件的名称（不区分大小写）。名称必须是 XML 名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | [`InitEvent`](../event/initevent/) 方法用于初始化通过 [`IDocumentEvent`](../idocumentevent/) 接口创建的 [`Event`](../event/) 的值。 |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | 如果事件是可取消的，则使用 [`PreventDefault`](../event/preventdefault/) 方法表示该事件应被取消，即实现通常因该事件而执行的任何默认操作都不会发生。 |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | 调用此方法可阻止事件到达在当前监听器之后注册的任何事件监听器，并且在树状分发时也阻止事件到达其他对象。 |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | [`StopPropagation`](../event/stoppropagation/) 方法用于阻止事件在事件流中的进一步传播。 |

### 另请参阅

* class [Event](../event/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
