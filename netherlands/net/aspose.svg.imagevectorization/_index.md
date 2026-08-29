---
title: "Aspose.Svg.ImageVectorization"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "De Aspose.Svg.ImageVectorization namespace bevat klassen voor het vectoriseren van rasterafbeeldingen en het converteren ervan naar SVG‑documenten. Dit proces omvat het reduceren van bitmaps tot geometrische vormen die bestaan uit pad‑elementen en het opslaan ervan als SVG. De namespace omvat klassen voor het bouwen van padsegmenten, het vereenvoudigen en gladstrijken van traceerpunt­en, en het configureren van vectorisatie‑opties."
type: docs
weight: 190
url: /nl/net/aspose.svg.imagevectorization/
---
De **Aspose.Svg.ImageVectorization** naamruimte bevat klassen voor het vectoriseren van rasterafbeeldingen en het converteren ervan naar SVG‑documenten. Dit proces omvat het reduceren van bitmap‑afbeeldingen tot geometrische vormen die bestaan uit pad‑elementen en deze opslaan als SVG. De naamruimte omvat klassen voor het bouwen van padsegmenten, het vereenvoudigen en gladstrijken van traceerpunt­en, en het configureren van vectorisatie‑opties.

## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [BezierPathBuilder](./bezierpathbuilder/) | De [`BezierPathBuilder`](../aspose.svg.imagevectorization/bezierpathbuilder/) klasse is verantwoordelijk voor het construeren van een Bezier‑pad uit een gegeven set punten. Het benadert een trace van punten met een Bezier‑curve, waarbij het aantal segmenten wordt geoptimaliseerd om nauwkeurig overeen te komen met de oorspronkelijke trace terwijl de complexiteit wordt geminimaliseerd. |
| [ImageTraceSimplifier](./imagetracesimplifier/) | De ImageTraceSimplifier‑klasse is verantwoordelijk voor het verminderen van het aantal punten in een curve die wordt benaderd door een reeks traceerpunt­en. |
| [ImageTraceSmoother](./imagetracesmoother/) | De ImageTraceSimplifier‑klasse is verantwoordelijk voor het gladstrijken van het aantal punten in een curve die wordt benaderd door een reeks traceerpunt­en. Deze klasse implementeert een nearest‑neighbor‑benadering. |
| [ImageVectorizer](./imagevectorizer/) | Deze ImageVectorizer-klasse vectoriseert rasterafbeeldingen zoals PNG, JPG, GIF, BMP enzovoort... en retourneert een SVGDocument. Onder vectorisatie verstaan we het proces waarbij bitmap‑beelden worden gereduceerd tot geometrische vormen die bestaan uit pad‑elementen en als SVG worden opgeslagen. |
| [ImageVectorizerConfiguration](./imagevectorizerconfiguration/) | De [`ImageVectorizerConfiguration`](../aspose.svg.imagevectorization/imagevectorizerconfiguration/)‑klasse definieert een configuratie van methoden en opties voor afbeeldingvectorisatie. De configuratie wordt gebruikt om een ImageVectorizer te initialiseren en biedt de configuratie‑opties voor het vectoriseren van afbeeldingen. |
| [SplinePathBuilder](./splinepathbuilder/) | De [`SplinePathBuilder`](../aspose.svg.imagevectorization/splinepathbuilder/)‑klasse is ontworpen om een glad pad te construeren door Centripetal Catmull–Rom‑splines om te zetten in Bézier‑curves. Hij biedt een methode om een pad te genereren dat soepel interpoleert tussen een reeks punten, waardoor een evenwicht ontstaat tussen nauwkeurigheid ten opzichte van de punten en de gladheid van de curve. |
| [StencilConfiguration](./stencilconfiguration/) | De [`StencilConfiguration`](../aspose.svg.imagevectorization/stencilconfiguration/)‑klasse definieert een configuratie van stencil‑effectopties. |
## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [IImageTraceSimplifier](./iimagetracesimplifier/) | De IImageTraceSimplifier‑interface is verantwoordelijk voor het reduceren van punten in de trace. |
| [IImageTraceSmoother](./iimagetracesmoother/) | De IImageTraceSmoother‑interface is verantwoordelijk voor het gladstrijken van de trace. |
| [IPathBuilder](./ipathbuilder/) | De IPathBuilder‑interface is verantwoordelijk voor het bouwen van padsegmenten [`SVGPathSeg`](../aspose.svg.paths/svgpathseg/) vanuit een lijst met trace‑punten. |
## Enumeratie

| Enumeratie | Beschrijving |
| --- | --- |
| [StencilType](./stenciltype/) | De [`StencilType`](../aspose.svg.imagevectorization/stenciltype/)‑enum definieert stencil‑typen. |
