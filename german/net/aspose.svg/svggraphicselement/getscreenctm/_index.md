---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGGraphicsElement GetScreenCTM Methode. Gibt die Transformationsmatrix von den aktuellen Benutzereinheiten zurück, d. h. nach Anwendung des Attributs transform, falls vorhanden, auf die vom Benutzeragenten als Pixel wahrgenommene Einheit. Für Anzeigegeräte stellt sie idealerweise ein physikalisches Bildschirmpixel dar. Für andere Geräte oder Umgebungen, in denen die physikalische Pixelgröße nicht bekannt ist, kann stattdessen ein Algorithmus verwendet werden, der der CSS2-Definition eines Pixels ähnelt. Hinweis: Null wird zurückgegeben, wenn dieses Element nicht in den Dokumentbaum eingebunden ist. Diese Methode hätte passenderweise getClientCTM heißen können, aber der Name getScreenCTM wird aus historischen Gründen beibehalten."
type: docs
weight: 90
url: /de/net/aspose.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Gibt die Transformationsmatrix von den aktuellen Benutzereinheiten (d. h. nach Anwendung des Attributs ‘transform’, falls vorhanden) zur Wahrnehmung eines "Pixel" durch den übergeordneten User‑Agent zurück. Für Anzeigegeräte entspricht dies idealerweise einem physischen Bildschirm‑Pixel. Für andere Geräte oder Umgebungen, in denen die physischen Pixelgrößen nicht bekannt sind, kann stattdessen ein Algorithmus verwendet werden, der der CSS2‑Definition eines "Pixels" ähnelt. Hinweis: Es wird null zurückgegeben, wenn dieses Element nicht im Dokumentbaum verankert ist. Diese Methode hätte besser getClientCTM heißen können, aber der Name getScreenCTM wird aus historischen Gründen beibehalten.

```csharp
public SVGMatrix GetScreenCTM()
```

### Rückgabewert

Ein SVGMatrix-Objekt, das die gegebene Transformationsmatrix definiert.

### Siehe auch

* class [SVGMatrix](../../../aspose.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
