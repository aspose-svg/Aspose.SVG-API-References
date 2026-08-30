---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGSVGElement CurrentScale‑egenskap. På ett yttersta svg‑element indikerar detta attribut den aktuella skalningsfaktorn relativt till den ursprungliga vyn för att ta hänsyn till användarförstoring och panorering enligt beskrivningen under Förstoring och panorering. DOM‑attributen currentScale och currentTranslate är ekvivalenta med 2x3‑matrisen a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Om förstoring är aktiverad, d.v.s. zoomAndPanmagnify, blir effekten som om en extra transformation placerades på den yttersta nivån i SVG‑dokumentfragmentet, dvs. utanför det yttersta svg‑elementet. När den nås på ett svg‑element som inte är ett yttersta svg‑element är det odefinierat vilket beteende detta attribut har."
type: docs
weight: 10
url: /sv/net/aspose.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

På ett yttersta svg‑element anger detta attribut den aktuella skalningsfaktorn i förhållande till den ursprungliga vyn för att ta hänsyn till användarmagnifiering och panorering, enligt beskrivningen under Magnification and panning. DOM‑attributen currentScale och currentTranslate är ekvivalenta med 2x3‑matrisen [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Om "magnification" är aktiverat (dvs. zoomAndPan="magnify"), blir effekten som om en extra transformation placerades på den yttersta nivån i SVG‑dokumentfragmentet (dvs. utanför det yttersta svg‑elementet). När det nås på ett ‘svg’-element som inte är ett ytterst svg‑element, är det odefinierat vilket beteende detta attribut har.

```csharp
public float CurrentScale { get; set; }
```

### Property Value

Den aktuella skalan.

### Se även

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
