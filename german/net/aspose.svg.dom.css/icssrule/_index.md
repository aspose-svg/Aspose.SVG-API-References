---
title: "ICSSRule Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.ICSSRule Schnittstelle. Die CSSRule‑Schnittstelle ist die abstrakte Basisschnittstelle für jede Art von CSS‑Anweisung. Dies schließt sowohl Regelsets als auch At‑Regeln ein. Von einer Implementierung wird erwartet, dass sie alle in einem CSS‑Stylesheet angegebenen Regeln beibehält, selbst wenn die Regel vom Parser nicht erkannt wird. Nicht erkannte Regeln werden mittels der ICSSUnknownRule‑Schnittstelle dargestellt."
type: docs
weight: 2620
url: /de/net/aspose.svg.dom.css/icssrule/
---
## ICSSRule interface

Das CSSRule-Interface ist das abstrakte Basisschnittstelle für jede Art von CSS-Anweisung. Dies umfasst sowohl Regelsets als auch At-Regeln. Von einer Implementierung wird erwartet, dass sie alle im CSS-Stylesheet angegebenen Regeln beibehält, selbst wenn die Regel vom Parser nicht erkannt wird. Nicht erkannte Regeln werden mittels des ICSSUnknownRule-Interfaces dargestellt.

```csharp
public interface ICSSRule
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssrule/csstext/) { get; set; } | Die parsbare Textdarstellung der Regel. Diese spiegelt den aktuellen Zustand der Regel wider und nicht ihren Anfangswert. |
| [ParentRule](../../aspose.svg.dom.css/icssrule/parentrule/) { get; } | Wenn diese Regel innerhalb einer anderen Regel enthalten ist (z. B. eine Stilregel innerhalb eines @media‑Blocks), ist dies die umgebende Regel. Wenn diese Regel nicht in einer anderen Regel verschachtelt ist, wird null zurückgegeben. |
| [ParentStyleSheet](../../aspose.svg.dom.css/icssrule/parentstylesheet/) { get; } | Das Stylesheet, das diese Regel enthält. |
| [Type](../../aspose.svg.dom.css/icssrule/type/) { get; } | Der Typ der Regel, wie oben definiert. Es wird erwartet, dass bindungsspezifische Casting‑Methoden verwendet werden können, um von einer Instanz der CSSRule‑Schnittstelle auf die spezifische abgeleitete Schnittstelle zu casten, die durch den Typ impliziert wird. |

### Siehe auch

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
