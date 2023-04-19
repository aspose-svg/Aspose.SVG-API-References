---
title: IWindow Interface
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Window.IWindow interface. The window object represents a window containing a DOM document
type: docs
weight: 3820
url: /net/aspose.svg.window/iwindow/
---
## IWindow interface

The window object represents a window containing a DOM document.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | The document attribute must return the Window object's newest Document object. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | The frameElement object of a Document. |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | The location attribute of the Window interface must return the Location object for that Window object's Document. |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | The opener IDL attribute on the Window object, on getting, must return the WindowProxy object of the browsing context from which the current browsing context was created (its opener browsing context), if there is one, if it is still available, and if the current browsing context has not disowned its opener; otherwise, it must return null. On setting, if the new value is null then the current browsing context must disown its opener; if the new value is anything else then the user agent must call the [[DefineOwnProperty]] internal method of the Window object, passing the property name "opener" as the property key, and the Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } as the property descriptor, where value is the new value. |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | The parent IDL attribute on the Window object of a Document in a browsing context b must return the WindowProxy object of the parent browsing context, if there is one (i.e. if b is a child browsing context), or the WindowProxy object of the browsing context b itself, otherwise (i.e. if it is a top-level browsing context or a detached nested browsing context). |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | Returns the Window object's browsing context's WindowProxy object. |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | The top IDL attribute on the Window object of a Document in a browsing context b must return the WindowProxy object of its top-level browsing context (which would be its own WindowProxy object if it was a top-level browsing context itself), if it has one, or its own WindowProxy object otherwise (e.g. if it was a detached nested browsing context). |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | Returns the Window object's browsing context's WindowProxy object. |

## Methods

| Name | Description |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(string) | Displays a modal alert with the given message, and waits for the user to dismiss it |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(string) | Displays a modal OK/Cancel prompt with the given message, waits for the user to dismiss it, and returns true if the user clicks OK and false if the user clicks Cancel. |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(string, string) | Displays a modal text field prompt with the given message, waits for the user to dismiss it, and returns the value that the user entered. If the user cancels the prompt, then returns null instead. If the second argument is present, then the given value is used as a default. |

### See Also

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
