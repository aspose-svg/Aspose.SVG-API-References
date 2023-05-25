---
title: IStyleSheet Interface
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Dom.Css.IStyleSheet interface. The StyleSheet interface is the abstract base interface for any type of style sheet. It represents a single style sheet associated with a structured document
type: docs
weight: 750
url: /net/aspose.svg.dom.css/istylesheet/
---
## IStyleSheet interface

The StyleSheet interface is the abstract base interface for any type of style sheet. It represents a single style sheet associated with a structured document.

```csharp
public interface IStyleSheet
```

## Properties

| Name | Description |
| --- | --- |
| [Disabled](../../aspose.svg.dom.css/istylesheet/disabled/) { get; set; } | false if the style sheet is applied to the document. true if it is not. Modifying this attribute may cause a new resolution of style for the document. A stylesheet only applies if both an appropriate medium definition is present and the disabled attribute is false. So, if the media doesn't apply to the current user agent, the disabled attribute is ignored. |
| [Href](../../aspose.svg.dom.css/istylesheet/href/) { get; } | If the style sheet is a linked style sheet, the value of its attribute is its location. For inline style sheets, the value of this attribute is null. |
| [Media](../../aspose.svg.dom.css/istylesheet/media/) { get; } | The intended destination media for style information. |
| [OwnerNode](../../aspose.svg.dom.css/istylesheet/ownernode/) { get; } | The node that associates this style sheet with the document. For HTML, this may be the corresponding LINK or STYLE element. For XML, it may be the linking processing instruction. For style sheets that are included by other style sheets, the value of this attribute is null. |
| [ParentStyleSheet](../../aspose.svg.dom.css/istylesheet/parentstylesheet/) { get; } | For style sheet languages that support the concept of style sheet inclusion, this attribute represents the including style sheet, if one exists. If the style sheet is a top-level style sheet, or the style sheet language does not support inclusion, the value of this attribute is null. |
| [Title](../../aspose.svg.dom.css/istylesheet/title/) { get; } | The advisory title. |
| [Type](../../aspose.svg.dom.css/istylesheet/type/) { get; } | This specifies the style sheet language for this style sheet. The style sheet language is specified as a content type (e.g. "text/css"). |

### See Also

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
