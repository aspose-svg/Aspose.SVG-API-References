---
title: SVGZoomEvent
second_title: Aspose.SVG for .NET API 参考
description: 当用户启动导致 SVG 文档片段的当前视图重新缩放的操作时会发生缩放事件事件处理程序仅在svg元素上被识别
type: docs
weight: 1610
url: /zh/net/aspose.svg.events/svgzoomevent/
---
## SVGZoomEvent class

当用户启动导致 SVG 文档片段的当前视图重新缩放的操作时，会发生缩放事件。事件处理程序仅在“svg”元素上被识别。

```csharp
public class SVGZoomEvent : Event
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles) { get; } | 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true，否则值为 false。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable) { get; } | 用于指示事件是否可以阻止其默认操作。如果可以阻止默认操作，则值为 true，否则值为 false。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget) { get; } | 用于表示[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget)的[`IEventListener`](../../aspose.svg.dom.events/ieventlistener)s 当前正在处理中。 这在捕获和冒泡时特别有用。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented) { get; } | 如果在可取消属性值为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase) { get; } | 用于指示当前正在评估事件流的哪个阶段。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted) { get; } | isTrusted 属性必须返回它被初始化的值。创建事件时，必须将属性初始化为 false。 |
| [NewScale](../../aspose.svg.events/svgzoomevent/newscale) { get; } | 处理完缩放操作后的比例因子。 |
| [NewTranslate](../../aspose.svg.events/svgzoomevent/newtranslate) { get; } | 处理完缩放操作后的平移值。 SVGPoint 对象是只读的。 |
| [PreviousScale](../../aspose.svg.events/svgzoomevent/previousscale) { get; } | 缩放操作发生之前存在的先前缩放操作的比例因子。 |
| [PreviousTranslate](../../aspose.svg.events/svgzoomevent/previoustranslate) { get; } | 在缩放操作发生之前存在的先前缩放操作的转换值。 SVGPoint 对象是只读的。 |
| [Target](../../aspose.svg.dom.events/event/target) { get; } | 用于指示最初将事件调度到的[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget)。 |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp) { get; } | 用于指定创建事件的时间（相对于纪元的毫秒数）。 由于某些系统可能不提供此信息，timeStamp 的值可能不适用于所有事件。 不可用时，将返回值 0。 纪元时间的示例是系统启动时间或 1970 年 1 月 1 日 0:0:0 UTC。 |
| [Type](../../aspose.svg.dom.events/event/type) { get; } | 事件的名称（不区分大小写）。该名称必须是 XML 名称。 |
| [ZoomRectScreen](../../aspose.svg.events/svgzoomevent/zoomrectscreen) { get; } | 以屏幕为单位的指定缩放矩形。 SVGRect 对象是只读的。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | 此方法用于检索 ECMAScript 对象Type。 |
| [InitEvent](../../aspose.svg.dom.events/event/initevent)(string, bool, bool) | [`InitEvent`](../../aspose.svg.dom.events/event/initevent)方法用于初始化通过 [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent)接口创建的[`Event`](../../aspose.svg.dom.events/event)的值。 |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault)() | 如果一个事件是可取消的，[`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault)方法用于表示该事件将被取消， 表示实现通常作为事件结果而采取的任何默认操作都不会发生。 |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation)() | 调用此方法可防止事件到达在当前事件侦听器之后注册的任何事件侦听器，并且在树中分派时还可防止事件到达任何其他对象。 |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation)() | [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation)方法用于防止在事件流期间进一步传播事件。 |

### 也可以看看

* class [Event](../../aspose.svg.dom.events/event)
* 命名空间 [Aspose.Svg.Events](../../aspose.svg.events)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
