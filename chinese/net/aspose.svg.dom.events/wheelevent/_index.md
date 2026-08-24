---
title: "WheelEvent 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Events.WheelEvent 类。WheelEvent 接口提供与滚轮事件相关的特定上下文信息。要创建 WheelEvent 接口的实例，请使用 WheelEvent 构造函数并传入可选的 WheelEventInit 字典。"
type: docs
weight: 3010
url: /zh/net/aspose.svg.dom.events/wheelevent/
---
## WheelEvent class

WheelEvent 接口提供与滚轮事件相关的特定上下文信息。要创建 WheelEvent 接口的实例，请使用 WheelEvent 构造函数，并传入可选的 WheelEventInit 字典。

```csharp
public class WheelEvent : MouseEvent
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(*string*) | 初始化 `WheelEvent` 类的新实例。 |
| [WheelEvent](wheelevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | 初始化 `WheelEvent` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/mouseevent/altkey/) { get; } | 请参阅 altKey 属性。 |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true；否则为 false。 |
| [Button](../../aspose.svg.dom.events/mouseevent/button/) { get; } | 在由鼠标按钮按下或释放引起的鼠标事件期间，必须使用 button 来指示哪个指针设备按钮状态发生了变化。 |
| [Buttons](../../aspose.svg.dom.events/mouseevent/buttons/) { get; } | 在任何鼠标事件期间，必须使用 buttons 来指示当前按下的鼠标按钮组合，以位掩码的形式表示。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | 用于指示事件是否可以阻止其默认行为。如果可以阻止默认行为，则值为 true，否则值为 false。 |
| [ClientX](../../aspose.svg.dom.events/mouseevent/clientx/) { get; } | 事件相对于其关联视口发生的水平坐标。 |
| [ClientY](../../aspose.svg.dom.events/mouseevent/clienty/) { get; } | 事件相对于其关联视口发生的垂直坐标。 |
| [CtrlKey](../../aspose.svg.dom.events/mouseevent/ctrlkey/) { get; } | 请参阅 ctrlKey 属性。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 用于指示当前正在处理其 [`IEventListener`](../ieventlistener/) 的 [`IEventTarget`](../ieventtarget/)。这在捕获和冒泡阶段特别有用。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | 如果在 cancelable 属性为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [DeltaMode](../../aspose.svg.dom.events/wheelevent/deltamode/) { get; } | deltaMode 属性指示 delta 值的计量单位。默认值为 DOM_DELTA_PIXEL（像素）。 |
| [DeltaX](../../aspose.svg.dom.events/wheelevent/deltax/) { get; } | 在默认操作为滚动的用户代理中，值必须是沿 x 轴的测量值（以像素、行或页为单位），用于在事件未被取消的情况下滚动。否则，这是围绕 x 轴的滚轮设备运动的实现特定测量（以像素、行或页为单位）。 |
| [DeltaY](../../aspose.svg.dom.events/wheelevent/deltay/) { get; } | 在默认操作为滚动的用户代理中，值必须是沿 y 轴的测量值（以像素、行或页为单位），用于在事件未被取消的情况下滚动。否则，这是围绕 y 轴的滚轮设备运动的实现特定测量（以像素、行或页为单位）。 |
| [DeltaZ](../../aspose.svg.dom.events/wheelevent/deltaz/) { get; } | 在默认操作为滚动的用户代理中，值必须是沿 z 轴的测量值（以像素、行或页为单位），用于在事件未被取消的情况下滚动。否则，这是围绕 z 轴的滚轮设备运动的实现特定测量（以像素、行或页为单位）。 |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | 根据事件类型，指定有关 Event 的一些详细信息。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 用于指示当前正在评估的事件流阶段。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性必须返回其初始化时的值。事件创建时，该属性必须初始化为 false。 |
| [MetaKey](../../aspose.svg.dom.events/mouseevent/metakey/) { get; } | 请参阅 metaKey 属性。 |
| [RelatedTarget](../../aspose.svg.dom.events/mouseevent/relatedtarget/) { get; } | 用于识别与 UI 事件相关的次要 EventTarget，取决于事件类型。 |
| [ScreenX](../../aspose.svg.dom.events/mouseevent/screenx/) { get; } | 事件相对于屏幕坐标系原点发生的水平坐标。 |
| [ScreenY](../../aspose.svg.dom.events/mouseevent/screeny/) { get; } | 事件相对于屏幕坐标系原点发生的垂直坐标。 |
| [ShiftKey](../../aspose.svg.dom.events/mouseevent/shiftkey/) { get; } | 请参阅 shiftKey 属性。 |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | 用于指示事件最初分发到的 [`IEventTarget`](../ieventtarget/)。 |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | 用于指定事件创建时的时间（相对于纪元的毫秒数）。由于某些系统可能不提供此信息，timeStamp 的值可能并非对所有事件都可用。若不可用，将返回 0。纪元时间的例子包括系统启动时间或 UTC 1970 年 1 月 1 日 0:0:0。 |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | 事件的名称（不区分大小写）。名称必须是 XML 名称。 |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | view 属性标识生成事件的 Window。此属性的未初始化值必须为 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | [`InitEvent`](../event/initevent/) 方法用于初始化通过 [`IDocumentEvent`](../idocumentevent/) 接口创建的 [`Event`](../event/) 的值。 |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | 如果事件是可取消的，则使用 [`PreventDefault`](../event/preventdefault/) 方法表示该事件应被取消，即实现通常因该事件而执行的任何默认操作都不会发生。 |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | 调用此方法可阻止事件到达在当前监听器之后注册的任何事件监听器，并且在树状分发时也阻止事件到达其他对象。 |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | [`StopPropagation`](../event/stoppropagation/) 方法用于阻止事件在事件流中的进一步传播。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DOM_DELTA_LINE](../../aspose.svg.dom.events/wheelevent/dom_delta_line/) | delta 的计量单位必须是单独的文本行。这在许多表单控件中适用。 |
| const [DOM_DELTA_PAGE](../../aspose.svg.dom.events/wheelevent/dom_delta_page/) | delta 的计量单位必须是页，可以定义为单个屏幕或划分的页面。 |
| const [DOM_DELTA_PIXEL](../../aspose.svg.dom.events/wheelevent/dom_delta_pixel/) | delta 的计量单位必须是像素。这是大多数操作系统和实现配置中最常见的情况。 |

### 另请参阅

* class [MouseEvent](../mouseevent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
