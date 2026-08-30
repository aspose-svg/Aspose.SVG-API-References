---
title: "Aspose.Svg.ImageVectorization"
second_title: "Aspose.SVG för .NET API-referens"
description: "Den Aspose.Svg.ImageVectorization namnutrymmet innehåller klasser för att vektorisera rasterbilder och konvertera dem till SVG-dokument. Denna process innebär att reducera bitmappar till geometriska former bestående av banelement och lagra dem som SVG. Namnutrymmet inkluderar klasser för att bygga bansegment, förenkla och jämna ut spårpunkter samt konfigurera vektoriseringsalternativ."
type: docs
weight: 190
url: /sv/net/aspose.svg.imagevectorization/
---
Den **Aspose.Svg.ImageVectorization**-namnrymden innehåller klasser för att vektorisera rasterbilder och konvertera dem till SVG-dokument. Denna process innebär att reducera bitmappar till geometriska former bestående av path‑element och lagra dem som SVG. Namnrymden inkluderar klasser för att bygga path‑segment, förenkla och jämna ut spårpunkter samt konfigurera vektoriseringalternativ.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [BezierPathBuilder](./bezierpathbuilder/) | Klassen [`BezierPathBuilder`](../aspose.svg.imagevectorization/bezierpathbuilder/) ansvarar för att konstruera en Bézier-bana från en given mängd punkter. Den approximerar ett spår av punkter med en Bézier-kurva, optimerar antalet segment för att nära matcha det ursprungliga spåret samtidigt som den minimerar komplexiteten. |
| [ImageTraceSimplifier](./imagetracesimplifier/) | Klassen ImageTraceSimplifier ansvarar för att minska antalet punkter i en kurva som approximeras av en serie spårpunkter. |
| [ImageTraceSmoother](./imagetracesmoother/) | Klassen ImageTraceSimplifier ansvarar för att jämna ut antalet punkter i en kurva som approximeras av en serie spårpunkter. Denna klass implementerar närmaste-granne-metoden. |
| [ImageVectorizer](./imagevectorizer/) | Denna ImageVectorizer-klass vektoriserar rasterbilder som PNG, JPG, GIF, BMP med mera... och returnerar ett SVGDocument. Med vektorisering menas processen att reducera bitmappar till geometriska former bestående av banelement och lagrade som SVG. |
| [ImageVectorizerConfiguration](./imagevectorizerconfiguration/) | Klassen [`ImageVectorizerConfiguration`](../aspose.svg.imagevectorization/imagevectorizerconfiguration/) definierar en konfiguration av metoder och alternativ för bildvektorisering. Konfigurationen används för att initiera en ImageVectorizer och tillhandahåller konfigurationsalternativ för att vektorisera bilder. |
| [SplinePathBuilder](./splinepathbuilder/) | Klassen [`SplinePathBuilder`](../aspose.svg.imagevectorization/splinepathbuilder/) är utformad för att konstruera en jämn bana genom att omvandla centripetala Catmull–Rom-splines till Bézier-kurvor. Den erbjuder en metod för att generera en bana som jämnt interpolerar genom en uppsättning punkter, vilket ger en balans mellan noggrannhet mot punkterna och kurvans släthet. |
| [StencilConfiguration](./stencilconfiguration/) | Klassen [`StencilConfiguration`](../aspose.svg.imagevectorization/stencilconfiguration/) definierar en konfiguration av stencil-effektalternativ. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IImageTraceSimplifier](./iimagetracesimplifier/) | Gränssnittet IImageTraceSimplifier ansvarar för att reducera antalet punkter i spåret. |
| [IImageTraceSmoother](./iimagetracesmoother/) | Gränssnittet IImageTraceSmoother ansvarar för att jämna ut spåret. |
| [IPathBuilder](./ipathbuilder/) | Gränssnittet IPathBuilder ansvarar för att bygga bansegment [`SVGPathSeg`](../aspose.svg.paths/svgpathseg/) från en lista med spårpunkter. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [StencilType](./stenciltype/) | Enumen [`StencilType`](../aspose.svg.imagevectorization/stenciltype/) definierar stenciltyper. |
