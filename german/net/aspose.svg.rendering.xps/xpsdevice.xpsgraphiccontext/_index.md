---
title: "XpsDevice.XpsGraphicContext Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Rendering.Xps.XpsDeviceXpsGraphicContext Klasse. Enthält aktuelle Grafiksteuerungsparameter für das XpsDevice. Diese Parameter definieren das globale Framework, innerhalb dessen die Grafikoperatoren ausgeführt werden."
type: docs
weight: 5130
url: /de/net/aspose.svg.rendering.xps/xpsdevice.xpsgraphiccontext/
---
## XpsDevice.XpsGraphicContext class

Enthält aktuelle Grafiksteuerungsparameter für das XpsDevice. Diese Parameter definieren das globale Framework, innerhalb dessen die Grafikoperatoren ausgeführt werden.

```csharp
public class XpsGraphicContext : GraphicContext
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XpsGraphicContext](../../aspose.svg.rendering.xps/xpsdevice.xpsgraphiccontext/.ctor)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.svg.rendering/graphiccontext/characterspacing/) { get; set; } | Setzt oder liest den Zeichenabstand. |
| [CurrentElement](../../aspose.svg.rendering/graphiccontext/currentelement/) { get; } | Liest das aktuell verarbeitete Element. |
| virtual [FillBrush](../../aspose.svg.rendering/graphiccontext/fillbrush/) { get; set; } | Setzt oder liest das Pinselobjekt, das zum Füllen der Innenbereiche von Pfaden verwendet wird. |
| virtual [Font](../../aspose.svg.rendering/graphiccontext/font/) { get; set; } | Setzt oder liest das True‑Type‑Schriftobjekt, das zum Rendern von Text verwendet wird. |
| virtual [FontSize](../../aspose.svg.rendering/graphiccontext/fontsize/) { get; set; } | Setzt oder liest die Schriftgröße des Textes. |
| virtual [FontStyle](../../aspose.svg.rendering/graphiccontext/fontstyle/) { get; set; } | Setzt oder liest den Schriftstil des Textes. |
| virtual [LineCap](../../aspose.svg.rendering/graphiccontext/linecap/) { get; set; } | Setzt oder liest den Code, der die Form der Endpunkte für jeden offenen, gestreckten Pfad festlegt. |
| virtual [LineDashOffset](../../aspose.svg.rendering/graphiccontext/linedashoffset/) { get; set; } | Setzt oder liest den Phasenversatz des aktuellen Strichmusters. |
| virtual [LineDashPattern](../../aspose.svg.rendering/graphiccontext/linedashpattern/) { get; set; } | Setzt oder liest die Beschreibung des Strichmusters, das beim Zeichnen von Pfaden verwendet wird. Kann auf null oder ein leeres Array gesetzt werden, um es zu deaktivieren. |
| virtual [LineJoin](../../aspose.svg.rendering/graphiccontext/linejoin/) { get; set; } | Setzt oder liest den Code, der die Form der Verbindungen zwischen verbundenen Segmenten eines gestreckten Pfades festlegt. |
| virtual [LineWidth](../../aspose.svg.rendering/graphiccontext/linewidth/) { get; set; } | Setzt oder liest die Dicke der zu zeichnenden Pfade. |
| virtual [MiterLimit](../../aspose.svg.rendering/graphiccontext/miterlimit/) { get; set; } | Setzt oder liest die maximale Länge von Gehrungs‑Linienverbindungen für gestreckte Pfade. Dieser Parameter begrenzt die Länge der \"Spitzen\", die entstehen, wenn Liniensegmente in scharfen Winkeln zusammenlaufen. |
| virtual [StrokeBrush](../../aspose.svg.rendering/graphiccontext/strokebrush/) { get; set; } | Setzt oder liest das Pinselobjekt, das für gestreckte Pfade verwendet wird. |
| virtual [TextInfo](../../aspose.svg.rendering/graphiccontext/textinfo/) { get; } | Liest ein [`TextInfo`](../../aspose.svg.rendering/textinfo/) Objekt, das Informationen über gerenderten Text enthält. |
| virtual [TransformationMatrix](../../aspose.svg.rendering/graphiccontext/transformationmatrix/) { get; set; } | Setzt oder liest die Transformationsmatrix. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.svg.rendering/graphiccontext/clone/)() | Erstellt eine neue Instanz einer GraphicContext‑Klasse mit denselben Eigenschaftswerten wie eine bestehende Instanz. |
| virtual [Transform](../../aspose.svg.rendering/graphiccontext/transform/)(*[IMatrix](../../aspose.svg.drawing/imatrix/)*) | Modifiziert die aktuelle Transformationsmatrix, indem die angegebene Matrix multipliziert wird. |

### Siehe auch

* class [GraphicContext](../../aspose.svg.rendering/graphiccontext/)
* class [XpsDevice](../xpsdevice/)
* namespace [Aspose.Svg.Rendering.Xps](../../aspose.svg.rendering.xps/)
* assembly [Aspose.SVG](../../)
