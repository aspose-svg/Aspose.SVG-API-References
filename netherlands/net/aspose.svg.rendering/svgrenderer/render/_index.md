---
title: "SvgRenderer.Render"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SvgRenderer Render-methode. Definieert methode voor het renderen van meerdere SVGDocuments naar een specifieke IDevice"
type: docs
weight: 20
url: /nl/net/aspose.svg.rendering/svgrenderer/render/
---
## Render(*[IDevice](../../idevice/), TimeSpan, params SVGDocument[]*) {#render_6}

Definieert methode voor het renderen van meerdere [`SVGDocument`](../../../aspose.svg/svgdocument/)s naar een specifieke [`IDevice`](../../idevice/).

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| timeout | TimeSpan | Een TimeSpan die het aantal milliseconden vertegenwoordigt om te wachten, of een TimeSpan die -1 milliseconde vertegenwoordigt om onbeperkt te wachten. |
| bronnen | SVGDocument[] | De SVG-documenten om te renderen. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params SVGDocument[]*) {#render_5}

Definieert een methode voor het renderen van meerdere [`SVGDocument`](../../../aspose.svg/svgdocument/)s naar een specifieke [`IDevice`](../../idevice/), met behulp van een annulerings-token om annulering van de bewerking aan te vragen.

```csharp
public override void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| cancellationToken | CancellationToken | Een annulerings-token om te observeren terwijl men wacht tot de taak voltooid is. |
| bronnen | SVGDocument[] | De SVG-documenten om te renderen. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
