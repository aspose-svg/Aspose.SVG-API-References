---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGSVGElement CurrentScale‑eigenschap. Op een buitenste svg‑element geeft dit attribuut de huidige schaalfactor weer ten opzichte van de initiële weergave, rekening houdend met gebruikersvergroting en pan‑operaties zoals beschreven onder Vergroting en pannen. DOM‑attributen currentScale en currentTranslate zijn gelijk aan de 2x3‑matrix a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Als vergroting is ingeschakeld, d.w.z. zoomAndPanmagnify, is het effect alsof er een extra transformatie wordt geplaatst op het buitenste niveau van het SVG‑documentfragment, d.w.z. buiten het buitenste svg‑element. Wanneer dit wordt benaderd op een svg‑element dat geen buitenste svg‑element is, is het gedrag van dit attribuut ongedefinieerd."
type: docs
weight: 10
url: /nl/net/aspose.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

Op een buitenste svg‑element geeft dit attribuut de huidige schaalfactor weer ten opzichte van de initiële weergave, rekening houdend met gebruikersvergroting en pan‑bewerkingen, zoals beschreven onder Vergroting en pannen. DOM‑attributen currentScale en currentTranslate zijn equivalent aan de 2x3‑matrix [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Als \"magnification\" is ingeschakeld (d.w.z. zoomAndPan=\"magnify\"), dan is het effect alsof er een extra transformatie op het buitenste niveau van het SVG‑documentfragment is geplaatst (d.w.z. buiten het buitenste svg‑element). Wanneer dit wordt opgevraagd op een ‘svg’-element dat geen buitenste svg‑element is, is het gedrag van dit attribuut ongedefinieerd.

```csharp
public float CurrentScale { get; set; }
```

### Property Value

De huidige schaal.

### Zie ook

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
