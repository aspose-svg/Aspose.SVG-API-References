---
title: Class InputEvent
second_title: Aspose.SVG for .NET API 参考
description: Aspose.Svg.Dom.Events.InputEvent 班级. 每当更新 DOM 时输入事件都会作为通知发送
type: docs
weight: 970
url: /zh/net/aspose.svg.dom.events/inputevent/
---
## InputEvent class

每当更新 DOM 时，输入事件都会作为通知发送。

```csharp
public class InputEvent : UIEvent
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [InputEvent](inputevent/#constructor)(string) | 初始化一个新的实例`InputEvent`类. |
| [InputEvent](inputevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | 初始化一个新的实例`InputEvent`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | 用于表示事件是否为冒泡事件。如果事件可以冒泡则值为真，否则值为假。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | 用于指示事件是否可以阻止其默认操作。如果可以阻止默认操作，则值为 true，否则值为 false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 用于表示[`IEventTarget`](../ieventtarget/)谁的[`IEventListener`](../ieventlistener/)当前正在处理中。 这在捕获和冒泡期间特别有用。 |
| [Data](../../aspose.svg.dom.events/inputevent/data/) { get; } | 该数据保存输入法生成的字符值。这可以是单个 Unicode 字符或 Unicode 字符的非空序列 [Unicode]。字符应该按照 [UAX15] 中定义的 Unicode 规范化形式 NFC 的定义进行规范化。该属性可以包含空字符串。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | 如果在可取消属性值为真时调用了 preventDefault()，则返回真，否则返回假。 |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | 指定有关事件的一些详细信息，具体取决于事件的类型。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 用于指示当前正在评估事件流的哪个阶段。 |
| [IsComposing](../../aspose.svg.dom.events/inputevent/iscomposing/) { get; } | 如果输入事件作为组合会话的一部分发生，即在组合开始事件之后和相应的组合结束事件之前，则为真。此属性的未初始化值必须为 false. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性必须返回它被初始化的值。创建事件时，必须将属性初始化为 false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | 用于表示[`IEventTarget`](../ieventtarget/)事件最初发送到的位置。 |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | 用于指定事件创建的时间（相对于纪元的毫秒数）。 由于某些系统可能不提供此信息，timeStamp 的值可能不适用于所有事件。 不可用时，将返回值 0。 纪元时间的示例是系统启动时间或 0:0:0 UTC 1970 年 1 月 1 日。 |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | 事件的名称（不区分大小写）。名称必须是 XML 名称。 |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | 视图属性标识生成事件的窗口。 此属性的未初始化值必须为空。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | 的[`InitEvent`](../event/initevent/)方法用于初始化一个值[`Event`](../event/)通过 the 创建[`IDocumentEvent`](../idocumentevent/)接口. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | 如果事件是可取消的，则[`PreventDefault`](../event/preventdefault/)方法用于表示事件将被取消， 表示作为事件结果通常由实现执行的任何默认操作都不会发生。 |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | 调用此方法可防止事件到达在当前事件之后注册的任何事件侦听器，并且在树中分派时也可防止事件到达任何其他对象。 |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | 的[`StopPropagation`](../event/stoppropagation/)方法用于防止事件流期间事件的进一步传播。 |

### 也可以看看

* class [UIEvent](../uievent/)
* 命名空间 [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* 部件 [Aspose.SVG](../../)


