---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGSVGElement CurrentScale‑Eigenschaft. Bei einem äußersten svg‑Element gibt dieses Attribut den aktuellen Skalierungsfaktor relativ zur Anfangsansicht an, um die Benutzermagnifikation und Schwenkoperationen zu berücksichtigen, wie unter Magnification und panning beschrieben. Die DOM‑Attribute currentScale und currentTranslate entsprechen der 2x3‑Matrix a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Wenn die Vergrößerung aktiviert ist, d. h. zoomAndPanmagnify, wirkt es, als ob eine zusätzliche Transformation auf der äußersten Ebene des SVG‑Dokumentfragments platziert wäre, also außerhalb des äußersten svg‑Elements. Wenn sie bei einem svg‑Element abgerufen wird, das nicht das äußerste svg‑Element ist, ist das Verhalten dieses Attributs nicht definiert."
type: docs
weight: 10
url: /de/net/aspose.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

Bei einem äußersten svg-Element gibt dieses Attribut den aktuellen Skalierungsfaktor relativ zur Ausgangsansicht an, um die Benutzervergrößerung und Schwenkoperationen zu berücksichtigen, wie unter Vergrößerung und Schwenken beschrieben. Die DOM-Attribute currentScale und currentTranslate entsprechen der 2x3-Matrix [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Wenn \"magnification\" aktiviert ist (d.h. zoomAndPan=\"magnify\"), wirkt es, als ob eine zusätzliche Transformation auf der äußersten Ebene des SVG-Dokumentfragments (d.h. außerhalb des äußersten svg-Elements) platziert würde. Wird es auf einem ‘svg’-Element verwendet, das kein äußerstes svg-Element ist, ist das Verhalten dieses Attributs nicht definiert.

```csharp
public float CurrentScale { get; set; }
```

### Property Value

Der aktuelle Maßstab.

### Siehe auch

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
