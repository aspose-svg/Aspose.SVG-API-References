---
title: "Интерфейс IWindow"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Window.IWindow. Объект window представляет окно, содержащее DOM‑документ"
type: docs
weight: 5920
url: /ru/net/aspose.svg.window/iwindow/
---
## IWindow interface

Объект window представляет окно, содержащее DOM‑документ.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | Атрибут document должен возвращать самый новый объект Document окна Window. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | Объект frameElement документа Document. |
| [LocalStorage](../../aspose.svg.window/iwindow/localstorage/) { get; } | Возвращает объект Storage, позволяющий сохранять пары ключ/значение в пользовательском агенте. |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | Атрибут location интерфейса Window должен возвращать объект Location для документа объекта Window. |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | Атрибут name объекта Window при чтении должен возвращать текущее имя контекста просмотра, а при установке — задавать имя контекста просмотра новым значением. |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | IDL‑атрибут opener у объекта Window при чтении должен возвращать объект WindowProxy контекста просмотра, из которого был создан текущий контекст просмотра (его открывающий контекст), если такой существует, он всё ещё доступен и текущий контекст просмотра не отказался от своего открывателя; в противном случае он должен возвращать null. При установке, если новое значение равно null, текущий контекст просмотра должен отказаться от своего открывателя; если новое значение отличается от null, пользовательский агент должен вызвать внутренний метод [[DefineOwnProperty]] объекта Window, передавая имя свойства "opener" в качестве ключа свойства и дескриптор свойства { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true }, где value — новое значение. |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | IDL‑атрибут parent у объекта Window документа в контексте просмотра b должен возвращать объект WindowProxy родительского контекста просмотра, если он существует (т.е. если b является дочерним контекстом), либо объект WindowProxy самого контекста b в остальных случаях (т.е. если это верхний контекст просмотра или отсоединённый вложенный контекст). |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | Возвращает объект WindowProxy контекста просмотра объекта Window. |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | IDL‑атрибут top у объекта Window документа в контексте просмотра b должен возвращать объект WindowProxy его верхнего (top‑level) контекста просмотра (который будет его собственным объектом WindowProxy, если он сам является верхним контекстом), если такой существует, либо его собственный объект WindowProxy в противном случае (например, если это отсоединённый вложенный контекст). |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | Возвращает объект WindowProxy контекста просмотра объекта Window. |

## Методы

| Имя | Описание |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(*string*) | Отображает модальное окно alert с указанным сообщением и ждёт, пока пользователь его закроет. |
| [Atob](../../aspose.svg.window/iwindow/atob/)(*string*) | Принимает входные данные в виде Unicode‑строки, содержащей бинарные данные, закодированные в base64, декодирует их и возвращает строку, состоящую из символов в диапазоне U+0000–U+00FF, каждый из которых представляет бинарный байт со значением от 0x00 до 0xFF соответственно, соответствующий этим бинарным данным. |
| [Btoa](../../aspose.svg.window/iwindow/btoa/)(*string*) | Принимает входные данные в виде строки Unicode, содержащей только символы в диапазоне U+0000–U+00FF, каждый из которых представляет бинарный байт со значениями 0x00–0xFF соответственно, и преобразует её в представление base64, которое возвращает. |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(*string*) | Отображает модальное окно с запросом ОК/Отмена с указанным сообщением, ждёт, пока пользователь закроет его, и возвращает true, если пользователь нажал ОК, и false, если нажал Отмена. |
| [MatchMedia](../../aspose.svg.window/iwindow/matchmedia/)(*string*) | Возвращает новый объект MediaQueryList, который затем можно использовать для определения, соответствует ли документ строке медиазапроса, а также для мониторинга документа с целью обнаружения, когда он соответствует (или перестаёт соответствовать) этому медиазапросу. См. спецификацию CSSOM View Module: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(*string, string*) | Отображает модальное окно с полем ввода текста и указанным сообщением, ждёт, пока пользователь закроет его, и возвращает введённое пользователем значение. Если пользователь отменил запрос, возвращается null. Если присутствует второй аргумент, то указанное значение используется как значение по умолчанию. |

### См. также

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
