---
title: "BlendMode Aufzählung"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.BlendMode Aufzählung. Gibt die verfügbaren Mischmodi zum Kombinieren von Bildern oder Elementen in SVG an"
type: docs
weight: 80
url: /de/net/aspose.svg.builder/blendmode/
---
## BlendMode enumeration

Gibt die verfügbaren Mischmodi zum Kombinieren von Bildern oder Elementen in SVG an.

```csharp
public enum BlendMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Normal | `0` | Zeigt das Quellbild unverändert an, ohne jegliche Mischung. |
| Multiply | `1` | Multipliziert die Farben des Quellbildes und des Hintergrunds. Das Ergebnis ist ein dunkleres Bild. |
| Screen | `2` | Macht die dunklen Bereiche des Quellbildes heller, während die hellen Bereiche unverändert bleiben. |
| Overlay | `3` | Kombiniert die Mischmodi Multiply und Screen, um den Kontrast zu verstärken. |
| Darken | `4` | Verdunkelt den Hintergrund basierend auf den Farben des Quellbildes. |
| Lighten | `5` | Hellt den Hintergrund basierend auf den Farben des Quellbildes auf. |
| ColorDodge | `6` | Hellt den Hintergrund auf, um das Quellbild widerzuspiegeln. |
| ColorBurn | `7` | Verdunkelt den Hintergrund, um das Quellbild widerzuspiegeln. |
| HardLight | `8` | Erzeugt einen Hard-Light-Effekt basierend auf der Helligkeit des Quellbildes. |
| SoftLight | `9` | Erzeugt einen Soft-Light-Effekt basierend auf der Helligkeit des Quellbildes. |
| Difference | `10` | Hebt die Unterschiede zwischen dem Quellbild und dem Hintergrund hervor. |
| Exclusion | `11` | Erzeugt einen Effekt, der dem Difference-Modus ähnelt, jedoch mit geringerem Kontrast. |
| Hue | `12` | Verwendet den Farbton des Quellbildes kombiniert mit der Luminanz und Sättigung des Hintergrunds. |
| Saturation | `13` | Verwendet die Sättigung des Quellbildes kombiniert mit dem Farbton und der Luminanz des Hintergrunds. |
| Color | `14` | Verwendet den Farbton und die Sättigung des Quellbildes kombiniert mit der Luminanz des Hintergrunds. |
| Luminosity | `15` | Verwendet die Luminanz des Quellbildes kombiniert mit dem Farbton und der Sättigung des Hintergrunds. |

## Hinweise

Blending-Modi in SVG werden verwendet, um zu bestimmen, wie zwei Ebenen miteinander vermischt werden. Dieses Enum bietet eine Vielzahl von Optionen, die steuern, wie die Farben der gemischten Ebenen sich vermischen und unterschiedliche visuelle Effekte erzeugen.

### Siehe auch

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
