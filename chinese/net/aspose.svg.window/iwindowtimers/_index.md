---
title: "IWindowTimers 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Window.IWindowTimers 接口。允许作者安排基于计时器的回调"
type: docs
weight: 5940
url: /zh/net/aspose.svg.window/iwindowtimers/
---
## IWindowTimers interface

允许作者安排基于计时器的回调。

```csharp
public interface IWindowTimers
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [ClearInterval](../../aspose.svg.window/iwindowtimers/clearinterval/)(*int*) | 取消由 handle 标识的 setInterval() 设置的超时 |
| [ClearTimeout](../../aspose.svg.window/iwindowtimers/cleartimeout/)(*int*) | 取消由 handle 标识的 setTimeout() 设置的超时。 |
| [SetInterval](../../aspose.svg.window/iwindowtimers/setinterval/)(*object, int, params object[]*) | 安排一个超时，使 handler 每隔 timeout 毫秒运行一次。任何参数都会直接传递给 handler。 |
| [SetTimeout](../../aspose.svg.window/iwindowtimers/settimeout/)(*object, int, params object[]*) | 安排一个超时，使 handler 在 timeout 毫秒后运行。任何参数都会直接传递给 handler。 |

### 另请参阅

* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
