---
title: "Класс KeyboardEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Events.KeyboardEvent class. Интерфейс KeyboardEvent предоставляет специфическую контекстную информацию, связанную с клавиатурными устройствами. Каждое событие клавиатуры ссылается на клавишу с помощью значения. События клавиатуры обычно направляются к элементу, имеющему фокус."
type: docs
weight: 2980
url: /ru/net/aspose.svg.dom.events/keyboardevent/
---
## KeyboardEvent class

Интерфейс KeyboardEvent предоставляет специфическую контекстную информацию, связанную с клавиатурными устройствами. Каждое клавиатурное событие ссылается на клавишу с помощью значения. Клавиатурные события обычно направлены на элемент, имеющий фокус.

```csharp
public class KeyboardEvent : UIEvent
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(*string*) | Инициализирует новый экземпляр класса `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Инициализирует новый экземпляр класса `KeyboardEvent`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/keyboardevent/altkey/) { get; } | true, если модификатор клавиши Alt (alternative) (или \"Option\") был активен. Неинициализированное значение этого атрибута ДОЛЖНО быть false. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Используется для указания, может ли действие события быть предотвращено. Если действие может быть предотвращено, значение true, иначе false. |
| [Code](../../aspose.svg.dom.events/keyboardevent/code/) { get; } | Код содержит строку, идентифицирующую физическую клавишу, которая нажата. Значение не зависит от текущей раскладки клавиатуры или состояния модификаторов, поэтому конкретная клавиша всегда будет возвращать одно и то же значение. |
| [CtrlKey](../../aspose.svg.dom.events/keyboardevent/ctrlkey/) { get; } | true, если модификатор клавиши Control (control) был активен. Неинициализированное значение этого атрибута ДОЛЖНО быть false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Используется для указания [`IEventTarget`](../ieventtarget/), чьи [`IEventListener`](../ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, и false в противном случае. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Указывает некоторую детальную информацию о событии, в зависимости от типа события. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [IsComposing](../../aspose.svg.dom.events/keyboardevent/iscomposing/) { get; } | true, если событие клавиши происходит в рамках сессии композиции, то есть после события compositionstart и до соответствующего события compositionend. Неинициализированное значение этого атрибута ДОЛЖНО быть false. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Атрибут isTrusted должен возвращать значение, к которому он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [Key](../../aspose.svg.dom.events/keyboardevent/key/) { get; } | Ключ содержит значение клавиши, которая была нажата. Если значение имеет печатное представление, оно ДОЛЖНО быть непустой строкой Unicode‑символов, соответствующей алгоритму определения значения клавиши, определённому в этой спецификации. Если значение является управляющей клавишей без печатного представления, оно ДОЛЖНО быть одним из значений клавиш, определённых в наборе значений клавиш, как определяется алгоритмом определения значения клавиши. Реализации, которые не могут идентифицировать клавишу, ДОЛЖНЫ использовать значение клавиши Unidentified. |
| [Location](../../aspose.svg.dom.events/keyboardevent/location/) { get; } | Атрибут location содержит указание логического расположения клавиши на устройстве. |
| [MetaKey](../../aspose.svg.dom.events/keyboardevent/metakey/) { get; } | true, если модификатор клавиши meta (Meta) был активен. |
| [Repeat](../../aspose.svg.dom.events/keyboardevent/repeat/) { get; } | true, если клавиша удерживается длительное время. Удерживание клавиши ДОЛЖНО приводить к повторению событий keydown, beforeinput, input в указанном порядке, с частотой, определяемой конфигурацией системы. Для мобильных устройств с поведением длительного нажатия первая клавиша‑событие с атрибутом repeat, равным true, ДОЛЖНА служить индикатором длительного нажатия. Длительность, в течение которой клавиша ДОЛЖНА быть удержана, чтобы началось повторение, зависит от конфигурации. |
| [ShiftKey](../../aspose.svg.dom.events/keyboardevent/shiftkey/) { get; } | true, если модификатор клавиши shift (Shift) был активен. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Используется для указания [`IEventTarget`](../ieventtarget/), которому событие изначально было отправлено. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Используется для указания времени (в миллисекундах относительно эпохи), когда событие было создано. Поскольку некоторые системы могут не предоставлять эту информацию, значение timeStamp может быть недоступно для некоторых событий. Если недоступно, будет возвращено значение 0. Примерами времени эпохи являются время запуска системы или 0:0:0 UTC 1 января 1970 года. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Имя события (без учёта регистра). Имя должно быть XML‑именем. |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | Атрибут view идентифицирует окно (Window), из которого было сгенерировано событие. Неинициализированное значение этого атрибута ДОЛЖНО быть null. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Метод [`InitEvent`](../event/initevent/) используется для инициализации значения [`Event`](../event/), созданного через интерфейс [`IDocumentEvent`](../idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Если событие отменяемо, метод [`PreventDefault`](../event/preventdefault/) используется для указания, что событие должно быть отменено, то есть любое действие по умолчанию, обычно выполняемое реализацией в результате события, не будет выполнено. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Вызов этого метода предотвращает доставку события к любым обработчикам, зарегистрированным после текущего, а при распространении в дереве также предотвращает доставку события к другим объектам. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Метод [`StopPropagation`](../event/stoppropagation/) используется для предотвращения дальнейшего распространения события во время потока событий. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_left/) | Активированная клавиша произошла из левого расположения клавиши (когда существует более одного возможного расположения этой клавиши). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_numpad/) | Активация клавиши произошла на цифровой клавиатуре или с помощью виртуальной клавиши, соответствующей цифровой клавиатуре (когда существует более одного возможного расположения этой клавиши). Обратите внимание, что клавиша NumLock всегда должна кодироваться с расположением DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_right/) | Активация клавиши произошла из правого расположения клавиши (когда существует более одного возможного расположения этой клавиши). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_standard/) | Активация клавиши НЕ ДОЛЖНА различаться как левая или правая версия клавиши, и (за исключением клавиши NumLock) не происходила с цифровой клавиатуры (или не происходила с виртуальной клавишей, соответствующей цифровой клавиатуре). |

### См. также

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
