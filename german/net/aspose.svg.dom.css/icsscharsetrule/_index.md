---
title: "ICSSCharsetRule Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.ICSSCharsetRule Schnittstelle. Die CSSCharsetRule Schnittstelle stellt eine Zeichensatzregel in einem CSS-Stylesheet dar. Der Wert des encoding‑Attributs beeinflusst nicht die Kodierung von Textdaten in den DOM‑Objekten; diese Kodierung ist immer UTF‑16. Nachdem ein Stylesheet geladen wurde, ist der Wert des encoding‑Attributs der im charset‑Regel gefundene Wert. Wenn im ursprünglichen Dokument kein charset vorhanden war, wird keine CSSCharsetRule erstellt. Der Wert des encoding‑Attributs kann auch als Hinweis für die bei der Serialisierung des Stylesheets zu verwendende Kodierung dienen."
type: docs
weight: 2530
url: /de/net/aspose.svg.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

Das CSSCharsetRule-Interface repräsentiert eine @charset-Regel in einem CSS-Stylesheet. Der Wert des encoding-Attributs beeinflusst nicht die Kodierung von Textdaten in den DOM-Objekten; diese Kodierung ist stets UTF-16. Nachdem ein Stylesheet geladen wurde, ist der Wert des encoding-Attributs der in der @charset-Regel gefundene Wert. Wenn im Originaldokument keine @charset vorhanden war, wird kein CSSCharsetRule erstellt. Der Wert des encoding-Attributs kann auch als Hinweis für die bei der Serialisierung des Stylesheets verwendete Kodierung dienen.

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Encoding](../../aspose.svg.dom.css/icsscharsetrule/encoding/) { get; set; } | Die in dieser @charset‑Regel verwendeten Kodierungsinformationen. |

### Siehe auch

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
