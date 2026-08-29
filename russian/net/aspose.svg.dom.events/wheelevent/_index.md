---
title: "Класс WheelEvent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Dom.Events.WheelEvent. Интерфейс WheelEvent предоставляет специфическую контекстную информацию, связанную с событиями колеса. Чтобы создать экземпляр интерфейса WheelEvent, используйте конструктор WheelEvent, передавая необязательный словарь WheelEventInit."
type: docs
weight: 3010
url: /ru/net/aspose.svg.dom.events/wheelevent/
---
## WheelEvent class

Интерфейс WheelEvent предоставляет специфическую контекстную информацию, связанную с событиями колесика. Чтобы создать экземпляр интерфейса WheelEvent, используйте конструктор WheelEvent, передавая необязательный словарь WheelEventInit.

```csharp
public class WheelEvent : MouseEvent
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(*string*) | Инициализирует новый экземпляр класса `WheelEvent`. |
| [WheelEvent](wheelevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Инициализирует новый экземпляр класса `WheelEvent`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/mouseevent/altkey/) { get; } | См. атрибут altKey. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Используется для указания, является ли событие всплывающим. Если событие может всплывать, значение true, иначе false. |
| [Button](../../aspose.svg.dom.events/mouseevent/button/) { get; } | Во время событий мыши, вызванных нажатием или отпусканием кнопки мыши, параметр button ДОЛЖЕН использоваться для указания, какая кнопка указательного устройства изменила состояние. |
| [Buttons](../../aspose.svg.dom.events/mouseevent/buttons/) { get; } | Во время любых событий мыши параметр buttons ДОЛЖЕН использоваться для указания, какая комбинация кнопок мыши в данный момент нажата, выраженная в виде битовой маски. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Используется для указания, может ли действие события быть предотвращено. Если действие может быть предотвращено, значение true, иначе false. |
| [ClientX](../../aspose.svg.dom.events/mouseevent/clientx/) { get; } | Горизонтальная координата, в которой произошло событие относительно области просмотра, связанной с событием. |
| [ClientY](../../aspose.svg.dom.events/mouseevent/clienty/) { get; } | Вертикальная координата, в которой произошло событие относительно области просмотра, связанной с событием. |
| [CtrlKey](../../aspose.svg.dom.events/mouseevent/ctrlkey/) { get; } | См. атрибут ctrlKey. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Используется для указания [`IEventTarget`](../ieventtarget/), чьи [`IEventListener`](../ieventlistener/) в данный момент обрабатываются. Это особенно полезно во время захвата и всплытия. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Возвращает true, если был вызван preventDefault() при значении атрибута cancelable, равном true, и false в противном случае. |
| [DeltaMode](../../aspose.svg.dom.events/wheelevent/deltamode/) { get; } | Атрибут deltaMode содержит указание единиц измерения для значений дельты. Значение по умолчанию — DOM_DELTA_PIXEL (пиксели). |
| [DeltaX](../../aspose.svg.dom.events/wheelevent/deltax/) { get; } | В пользовательских агентах, где действие по умолчанию события колеса — прокрутка, значение ДОЛЖНО быть измерением вдоль оси x (в пикселях, строках или страницах), которое будет прокручено, если событие не отменено. В противном случае это измерение, специфичное для реализации (в пикселях, строках или страницах) перемещения устройства колеса вокруг оси x. |
| [DeltaY](../../aspose.svg.dom.events/wheelevent/deltay/) { get; } | В пользовательских агентах, где действие по умолчанию события колеса — прокрутка, значение ДОЛЖНО быть измерением вдоль оси y (в пикселях, строках или страницах), которое будет прокручено, если событие не отменено. В противном случае это измерение, специфичное для реализации (в пикселях, строках или страницах) перемещения устройства колеса вокруг оси y. |
| [DeltaZ](../../aspose.svg.dom.events/wheelevent/deltaz/) { get; } | В пользовательских агентах, где действие по умолчанию события колеса — прокрутка, значение ДОЛЖНО быть измерением вдоль оси z (в пикселях, строках или страницах), которое будет прокручено, если событие не отменено. В противном случае это измерение, специфичное для реализации (в пикселях, строках или страницах) перемещения устройства колеса вокруг оси z. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Указывает некоторую детальную информацию о событии, в зависимости от типа события. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Используется для указания, какая фаза потока событий в данный момент оценивается. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Атрибут isTrusted должен возвращать значение, к которому он был инициализирован. При создании события атрибут должен быть инициализирован значением false. |
| [MetaKey](../../aspose.svg.dom.events/mouseevent/metakey/) { get; } | См. атрибут metaKey. |
| [RelatedTarget](../../aspose.svg.dom.events/mouseevent/relatedtarget/) { get; } | Используется для идентификации вторичного EventTarget, связанного с UI‑событием, в зависимости от типа события. |
| [ScreenX](../../aspose.svg.dom.events/mouseevent/screenx/) { get; } | Горизонтальная координата, в которой произошло событие относительно начала системы координат экрана. |
| [ScreenY](../../aspose.svg.dom.events/mouseevent/screeny/) { get; } | Вертикальная координата, в которой произошло событие относительно начала системы координат экрана. |
| [ShiftKey](../../aspose.svg.dom.events/mouseevent/shiftkey/) { get; } | См. атрибут shiftKey. |
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
| const [DOM_DELTA_LINE](../../aspose.svg.dom.events/wheelevent/dom_delta_line/) | Единицы измерения дельты ДОЛЖНЫ быть отдельными строками текста. Это характерно для многих элементов управления формой. |
| const [DOM_DELTA_PAGE](../../aspose.svg.dom.events/wheelevent/dom_delta_page/) | Единицы измерения дельты ДОЛЖНЫ быть страницами, определяемыми как один экран или как отдельная страница. |
| const [DOM_DELTA_PIXEL](../../aspose.svg.dom.events/wheelevent/dom_delta_pixel/) | Единицы измерения дельты ДОЛЖНЫ быть пикселями. Это наиболее типичный случай в большинстве операционных систем и конфигураций реализации. |

### См. также

* class [MouseEvent](../mouseevent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
