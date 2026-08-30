---
title: "SvgRenderer.Render"
second_title: "Aspose.SVG för .NET API-referens"
description: "SvgRenderer Render-metod. Definierar metod för rendering av flera SVGDocuments till en specifik IDevice."
type: docs
weight: 20
url: /sv/net/aspose.svg.rendering/svgrenderer/render/
---
## Render(*[IDevice](../../idevice/), TimeSpan, params SVGDocument[]*) {#render_6}

Definierar metod för rendering av flera [`SVGDocument`](../../../aspose.svg/svgdocument/) till en specifik [`IDevice`](../../idevice/).

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Utdataenheten. |
| timeout | TimeSpan | En TimeSpan som representerar antalet millisekunder att vänta, eller en TimeSpan som representerar -1 millisekund för att vänta på obestämd tid. |
| källor | SVGDocument[] | SVG-dokumenten som ska renderas. |

### Se även

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params SVGDocument[]*) {#render_5}

Definierar en metod för att rendera flera [`SVGDocument`](../../../aspose.svg/svgdocument/)s till en specifik [`IDevice`](../../idevice/), med en avbokningstoken för att begära avbrytning av operationen.

```csharp
public override void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Utdataenheten. |
| cancellationToken | CancellationToken | En avbokningstoken att observera medan du väntar på att uppgiften ska slutföras. |
| källor | SVGDocument[] | SVG-dokumenten som ska renderas. |

### Se även

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
