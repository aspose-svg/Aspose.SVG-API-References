---
title: "IWindow 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Window.IWindow 接口。window 对象表示包含 DOM 文档的窗口"
type: docs
weight: 5920
url: /zh/net/aspose.svg.window/iwindow/
---
## IWindow interface

window 对象表示包含 DOM 文档的窗口。

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | document 属性必须返回 Window 对象的最新 Document 对象。 |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | Document 的 frameElement 对象。 |
| [LocalStorage](../../aspose.svg.window/iwindow/localstorage/) { get; } | 返回一个 Storage 对象，允许您在用户代理中保存键/值对。 |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | Window 接口的 location 属性必须返回该 Window 对象的 Document 所对应的 Location 对象。 |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | Window 对象的 name 属性在获取时必须返回当前浏览上下文的名称，在设置时必须将浏览上下文的名称设为新值。 |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | Window 对象的 opener IDL 属性在获取时必须返回创建当前浏览上下文的浏览上下文（其 opener 浏览上下文）的 WindowProxy 对象（如果存在且仍可用，并且当前浏览上下文尚未放弃其 opener）；否则必须返回 null。在设置时，如果新值为 null，则当前浏览上下文必须放弃其 opener；如果新值为其他任何值，则用户代理必须调用 Window 对象的 [[DefineOwnProperty]] 内部方法，传入属性名 "opener" 作为属性键，以及属性描述符 { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true }，其中 value 为新值。 |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | 浏览上下文 b 中 Document 的 Window 对象的 parent IDL 属性必须返回父浏览上下文的 WindowProxy 对象（如果存在，即 b 为子浏览上下文），否则返回浏览上下文 b 本身的 WindowProxy 对象（即它是顶层浏览上下文或已分离的嵌套浏览上下文）。 |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | 返回 Window 对象的浏览上下文的 WindowProxy 对象。 |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | 浏览上下文 b 中 Document 的 Window 对象的 top IDL 属性必须返回其顶层浏览上下文的 WindowProxy 对象（如果它本身是顶层浏览上下文，则该对象即为其自身的 WindowProxy），如果不存在，则返回其自身的 WindowProxy 对象（例如，它是已分离的嵌套浏览上下文）。 |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | 返回 Window 对象的浏览上下文的 WindowProxy 对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(*string*) | 显示带有给定消息的模态警报，并等待用户将其关闭。 |
| [Atob](../../aspose.svg.window/iwindow/atob/)(*string*) | 获取输入数据，形式为包含 base64 编码二进制数据的 Unicode 字符串，解码后返回一个字符串，该字符串由 U+0000 到 U+00FF 范围内的字符组成，每个字符分别表示值为 0x00 到 0xFF 的二进制字节，对应于该二进制数据。 |
| [Btoa](../../aspose.svg.window/iwindow/btoa/)(*string*) | 获取输入数据，形式为仅包含 U+0000 到 U+00FF 范围字符的 Unicode 字符串，每个字符分别表示值为 0x00 到 0xFF 的二进制字节，并将其转换为 base64 表示形式并返回。 |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(*string*) | 显示带有给定消息的模态 OK/Cancel 提示框，等待用户关闭，并在用户点击 OK 时返回 true，点击 Cancel 时返回 false。 |
| [MatchMedia](../../aspose.svg.window/iwindow/matchmedia/)(*string*) | 返回一个新的 MediaQueryList 对象，可用于确定文档是否匹配媒体查询字符串，并监视文档以检测何时匹配（或停止匹配）该媒体查询。参见 CSSOM View Module 规范： [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(*string, string*) | 显示带有给定消息的模态文本输入提示框，等待用户关闭，并返回用户输入的值。如果用户取消提示，则返回 null。如果提供了第二个参数，则使用给定的值作为默认值。 |

### 另请参阅

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
