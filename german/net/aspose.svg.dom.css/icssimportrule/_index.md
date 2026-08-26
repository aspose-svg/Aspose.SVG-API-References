---
title: "ICSSImportRule Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.ICSSImportRule Schnittstelle. Die CSSImportRule Schnittstelle stellt eine Importregel innerhalb eines CSS-Stylesheets dar. Die Importregel wird verwendet, um Stilregeln aus anderen Stylesheets zu importieren."
type: docs
weight: 2560
url: /de/net/aspose.svg.dom.css/icssimportrule/
---
## ICSSImportRule interface

Das CSSImportRule-Interface repräsentiert eine @import-Regel innerhalb eines CSS-Stylesheets. Die @import-Regel wird verwendet, um Stilregeln aus anderen Stylesheets zu importieren.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Href](../../aspose.svg.dom.css/icssimportrule/href/) { get; } | Der Speicherort des zu importierenden Stylesheets. Das Attribut enthält nicht den "url(...)"-Spezifizierer um die URI. |
| [Media](../../aspose.svg.dom.css/icssimportrule/media/) { get; } | Eine Liste von Medientypen, für die dieses Stylesheet verwendet werden kann. |
| [StyleSheet](../../aspose.svg.dom.css/icssimportrule/stylesheet/) { get; } | Das von dieser Regel referenzierte Stylesheet, falls es geladen wurde. Der Wert dieses Attributs ist null, wenn das Stylesheet noch nicht geladen wurde oder nicht geladen wird (z. B. wenn das Stylesheet für einen Medientyp bestimmt ist, der vom User‑Agent nicht unterstützt wird). |

### Siehe auch

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
