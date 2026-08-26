---
title: "Aspose.Svg.ImageVectorization"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Der Aspose.Svg.ImageVectorization Namespace enthält Klassen zum Vektorisieren von Rasterbildern und deren Umwandlung in SVG-Dokumente. Dieser Prozess umfasst das Reduzieren von Bitmaps zu geometrischen Formen, die aus Pfadelementen bestehen, und das Speichern als SVG. Der Namespace beinhaltet Klassen zum Erstellen von Pfadsegmenten, zum Vereinfachen und Glätten von Trace-Punkten sowie zum Konfigurieren von Vektorisierungsoptionen."
type: docs
weight: 190
url: /de/net/aspose.svg.imagevectorization/
---
Der **Aspose.Svg.ImageVectorization** Namespace enthält Klassen zum Vektorisieren von Rasterbildern und deren Umwandlung in SVG‑Dokumente. Dieser Vorgang beinhaltet das Reduzieren von Bitmaps zu geometrischen Formen, die aus Pfadelementen bestehen, und deren Speicherung als SVG. Der Namespace umfasst Klassen zum Erstellen von Pfadsegmenten, zum Vereinfachen und Glätten von Trace‑Punkten sowie zum Konfigurieren von Vektorisierungsoptionen.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [BezierPathBuilder](./bezierpathbuilder/) | Die [`BezierPathBuilder`](../aspose.svg.imagevectorization/bezierpathbuilder/) Klasse ist dafür verantwortlich, einen Bézier-Pfad aus einer gegebenen Menge von Punkten zu konstruieren. Sie approximiert eine Punktspur mit einer Bézier-Kurve und optimiert die Anzahl der Segmente, um die ursprüngliche Spur möglichst genau zu treffen, während die Komplexität minimiert wird. |
| [ImageTraceSimplifier](./imagetracesimplifier/) | Die ImageTraceSimplifier Klasse ist dafür verantwortlich, die Anzahl der Punkte in einer Kurve zu reduzieren, die durch eine Reihe von Trace-Punkten approximiert wird. |
| [ImageTraceSmoother](./imagetracesmoother/) | Die ImageTraceSimplifier Klasse ist dafür verantwortlich, die Anzahl der Punkte in einer Kurve zu glätten, die durch eine Reihe von Trace-Punkten approximiert wird. Diese Klasse implementiert einen Nearest‑Neighbor‑Ansatz. |
| [ImageVectorizer](./imagevectorizer/) | Diese ImageVectorizer Klasse vektorisiert Rasterbilder wie PNG, JPG, GIF, BMP usw. und gibt ein SVGDocument zurück. Unter Vektorisierung verstehen wir den Prozess, Bitmaps zu geometrischen Formen zu reduzieren, die aus Pfadelementen bestehen und als SVG gespeichert werden. |
| [ImageVectorizerConfiguration](./imagevectorizerconfiguration/) | Die [`ImageVectorizerConfiguration`](../aspose.svg.imagevectorization/imagevectorizerconfiguration/) Klasse definiert eine Konfiguration von Bildvektorisierungsmethoden und -optionen. Die Konfiguration wird verwendet, um einen ImageVectorizer zu initialisieren und stellt die Konfigurationsoptionen für die Vektorisierung von Bildern bereit. |
| [SplinePathBuilder](./splinepathbuilder/) | Die [`SplinePathBuilder`](../aspose.svg.imagevectorization/splinepathbuilder/) Klasse ist dazu entworfen, einen glatten Pfad zu erstellen, indem zentripetale Catmull–Rom‑Splines in Bézier‑Kurven umgewandelt werden. Sie bietet eine Methode zur Erzeugung eines Pfades, der sanft durch eine Menge von Punkten interpoliert und dabei ein Gleichgewicht zwischen Genauigkeit der Punkte und Glätte der Kurve bietet. |
| [StencilConfiguration](./stencilconfiguration/) | Die [`StencilConfiguration`](../aspose.svg.imagevectorization/stencilconfiguration/) Klasse definiert eine Konfiguration von Stencil‑Effektoptionen. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IImageTraceSimplifier](./iimagetracesimplifier/) | Die IImageTraceSimplifier Schnittstelle ist dafür verantwortlich, Punkte in der Spur zu reduzieren. |
| [IImageTraceSmoother](./iimagetracesmoother/) | Die IImageTraceSmoother Schnittstelle ist dafür verantwortlich, die Spur zu glätten. |
| [IPathBuilder](./ipathbuilder/) | Das IPathBuilder-Interface ist dafür verantwortlich, Pfadsegmente [`SVGPathSeg`](../aspose.svg.paths/svgpathseg/) aus einer Liste von Trace-Punkten zu erstellen. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [StencilType](./stenciltype/) | Das [`StencilType`](../aspose.svg.imagevectorization/stenciltype/) Enum definiert Schablonentypen. |
