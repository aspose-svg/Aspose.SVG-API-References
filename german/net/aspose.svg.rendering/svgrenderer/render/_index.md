---
title: "SvgRenderer.Render"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SvgRenderer Render-Methode. Definiert eine Methode zum Rendern mehrerer SVGDocuments in ein bestimmtes IDevice"
type: docs
weight: 20
url: /de/net/aspose.svg.rendering/svgrenderer/render/
---
## Render(*[IDevice](../../idevice/), TimeSpan, params SVGDocument[]*) {#render_6}

Definiert eine Methode zum Rendern mehrerer [`SVGDocument`](../../../aspose.svg/svgdocument/)s in ein bestimmtes [`IDevice`](../../idevice/).

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| timeout | TimeSpan | Ein TimeSpan, der die Anzahl der Millisekunden zum Warten darstellt, oder ein TimeSpan, der -1 Millisekunde für unbegrenztes Warten darstellt. |
| Quellen | SVGDocument[] | Die SVG-Dokumente zum Rendern. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params SVGDocument[]*) {#render_5}

Definiert eine Methode zum Rendern mehrerer [`SVGDocument`](../../../aspose.svg/svgdocument/)s in ein bestimmtes [`IDevice`](../../idevice/), unter Verwendung eines Abbruch‑Tokens, um die Operation abzubrechen.

```csharp
public override void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| cancellationToken | CancellationToken | Ein Abbruch-Token, das während des Wartens auf den Abschluss der Aufgabe beobachtet werden soll. |
| Quellen | SVGDocument[] | Die SVG-Dokumente zum Rendern. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
