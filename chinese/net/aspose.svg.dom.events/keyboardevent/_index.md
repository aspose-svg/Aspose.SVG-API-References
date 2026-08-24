---
title: "KeyboardEvent 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Events.KeyboardEvent 类。KeyboardEvent 接口提供与键盘设备相关的特定上下文信息。每个键盘事件使用一个值引用一个键。键盘事件通常针对具有焦点的元素。"
type: docs
weight: 2980
url: /zh/net/aspose.svg.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent 接口提供与键盘设备相关的特定上下文信息。每个键盘事件使用一个值引用一个键。键盘事件通常针对拥有焦点的元素。

```csharp
public class KeyboardEvent : UIEvent
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(*string*) | 初始化 `KeyboardEvent` 类的新实例。 |
| [KeyboardEvent](keyboardevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | 初始化 `KeyboardEvent` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/keyboardevent/altkey/) { get; } | 如果 Alt（替代）键（或 “Option” 键）修饰键处于激活状态，则为 true。该属性未初始化时的值必须为 false。 |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | 用于指示事件是否为冒泡事件。如果事件可以冒泡，则值为 true；否则为 false。 |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | 用于指示事件是否可以阻止其默认行为。如果可以阻止默认行为，则值为 true，否则值为 false。 |
| [Code](../../aspose.svg.dom.events/keyboardevent/code/) { get; } | code 保存一个字符串，用于标识被按下的物理键。该值不受当前键盘布局或修饰键状态的影响，因此特定键始终返回相同的值。 |
| [CtrlKey](../../aspose.svg.dom.events/keyboardevent/ctrlkey/) { get; } | 如果 Control（控制）键修饰键处于激活状态，则为 true。该属性未初始化时的值必须为 false。 |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | 用于指示当前正在处理其 [`IEventListener`](../ieventlistener/) 的 [`IEventTarget`](../ieventtarget/)。这在捕获和冒泡阶段特别有用。 |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | 如果在 cancelable 属性为 true 时调用了 preventDefault()，则返回 true，否则返回 false。 |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | 根据事件类型，指定有关 Event 的一些详细信息。 |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | 用于指示当前正在评估的事件流阶段。 |
| [IsComposing](../../aspose.svg.dom.events/keyboardevent/iscomposing/) { get; } | 如果键事件作为组合会话的一部分发生，即在 compositionstart 事件之后且在相应的 compositionend 事件之前，则为 true。此属性的未初始化值必须为 false。 |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted 属性必须返回其初始化时的值。事件创建时，该属性必须初始化为 false。 |
| [Key](../../aspose.svg.dom.events/keyboardevent/key/) { get; } | key 保存所按键的键值。如果该值具有可打印表示，则它必须是一个非空的 Unicode 字符串，符合本规范中定义的键值确定算法。如果该值是没有可打印表示的控制键，则它必须是键值集合中定义的键值之一，由键值确定算法决定。无法识别键的实现必须使用键值 Unidentified。 |
| [Location](../../aspose.svg.dom.events/keyboardevent/location/) { get; } | location 属性包含键在设备上的逻辑位置指示。 |
| [MetaKey](../../aspose.svg.dom.events/keyboardevent/metakey/) { get; } | 如果 meta (Meta) 键修饰符处于激活状态，则为 true。 |
| [Repeat](../../aspose.svg.dom.events/keyboardevent/repeat/) { get; } | 如果键被持续按下，则为 true。长按键必须导致按顺序重复触发 keydown、beforeinput、input 事件，重复速率由系统配置决定。对于具有长按行为的移动设备，第一个 repeat 属性值为 true 的键事件必须作为长按的指示。开始重复所需的按键时长取决于配置。 |
| [ShiftKey](../../aspose.svg.dom.events/keyboardevent/shiftkey/) { get; } | 如果 shift (Shift) 键修饰符处于激活状态，则为 true。 |
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
| const [DOM_KEY_LOCATION_LEFT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_left/) | 激活的键来源于左侧键位置（当该键有多个可能位置时）。 |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_numpad/) | 键激活来源于数字键盘或对应数字键盘的虚拟键（当该键有多个可能位置时）。请注意，NumLock 键应始终使用 DOM_KEY_LOCATION_STANDARD 位置进行编码。 |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_right/) | 键激活来源于右侧键位置（当该键有多个可能位置时）。 |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_standard/) | 键激活不得区分为左侧或右侧版本，并且（除 NumLock 键外）未来源于数字键盘（也未来源于对应数字键盘的虚拟键）。 |

### 另请参阅

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
