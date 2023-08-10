---
title: Sandbox Enum
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Sandbox enum. A sandboxing flag set is a set of zero or more of the following flags which are used to restrict the abilities that potentially untrusted resources
type: docs
weight: 610
url: /net/aspose.svg/sandbox/
---
## Sandbox enumeration

A sandboxing flag set is a set of zero or more of the following flags, which are used to restrict the abilities that potentially untrusted resources.

```csharp
[Flags]
public enum Sandbox
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No flag is set, every sandbox feature is accepted |
| Navigation | `1` | This flag prevents content from navigating browsing contexts other than the sandboxed browsing context itself (or browsing contexts further nested inside it), auxiliary browsing contexts (which are protected by the sandboxed auxiliary navigation browsing context flag defined next), and the top-level browsing context (which is protected by the sandboxed top-level navigation browsing context flag defined below). If the sandboxed auxiliary navigation browsing context flag is not set, then in certain cases the restrictions nonetheless allow popups (new top-level browsing contexts) to be opened. These browsing contexts always have one permitted sandboxed navigator, set when the browsing context is created, which allows the browsing context that created them to actually navigate them. (Otherwise, the sandboxed navigation browsing context flag would prevent them from being navigated even if they were opened. |
| AuxiliaryNavigation | `2` | This flag prevents content from creating new auxiliary browsing contexts, e.g. using the target attribute, or the window.open() method. |
| TopLevelNavigation | `4` | This flag prevents content from navigating their top-level browsing context and prevents content from closing their top-level browsing context. When the sandboxed top-level navigation browsing context flag is not set, content can navigate its top-level browsing context, but other browsing contexts are still protected by the sandboxed navigation browsing context flag and possibly the sandboxed auxiliary navigation browsing context flag. |
| Plugins | `8` | This flag prevents content from instantiating plugins, whether using the embed element, the object element, the applet element, or through navigation of a nested browsing context, unless those plugins can be secured. |
| Origin | `10` | This flag forces content into a unique origin, thus preventing it from accessing other content from the same origin. |
| Forms | `20` | This flag blocks form submission. |
| PointerLock | `40` | This flag disables the Pointer Lock API. |
| Scripts | `80` | This flag blocks script execution. |
| AutomaticFeatures | `100` | This flag blocks features that trigger automatically, such as automatically playing a video or automatically focusing a form control. |
| Fullscreen | `200` | This flag prevents content from using the requestFullscreen() method. |
| DocumentDomain | `400` | This flag prevents content from using the document.domain feature to change the effective script origin. |
| Images | `800` | This flag disables image loading. |

### See Also

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
