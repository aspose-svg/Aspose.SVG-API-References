---
title: IWindowTimers Interface
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Window.IWindowTimers interface. Allows authors to schedule timer-based callbacks
type: docs
weight: 5940
url: /net/aspose.svg.window/iwindowtimers/
---
## IWindowTimers interface

Allows authors to schedule timer-based callbacks.

```csharp
public interface IWindowTimers
```

## Methods

| Name | Description |
| --- | --- |
| [ClearInterval](../../aspose.svg.window/iwindowtimers/clearinterval/)(*int*) | Cancels the timeout set with setInterval() identified by handle |
| [ClearTimeout](../../aspose.svg.window/iwindowtimers/cleartimeout/)(*int*) | Cancels the timeout set with setTimeout() identified by handle. |
| [SetInterval](../../aspose.svg.window/iwindowtimers/setinterval/)(*object, int, params object[]*) | Schedules a timeout to run handler every timeout milliseconds. Any arguments are passed straight through to the handler. |
| [SetTimeout](../../aspose.svg.window/iwindowtimers/settimeout/)(*object, int, params object[]*) | Schedules a timeout to run handler after timeout milliseconds. Any arguments are passed straight through to the handler. |

### See Also

* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
