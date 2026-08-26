---
title: "XPathResultType Enum"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.XPath.XPathResultType Enum. Ein unsigned short, der angibt, welchen Typ dieses Ergebnis hat. Wenn ein bestimmter Typ angegeben ist, wird das Ergebnis als entsprechender Typ zurückgegeben, wobei bei Bedarf und Möglichkeit XPath‑Typkonvertierungen verwendet werden."
type: docs
weight: 3360
url: /de/net/aspose.svg.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Ein unsigned short, das angibt, welcher Ergebnis­typ vorliegt. Wenn ein spezifischer `type` angegeben ist, wird das Ergebnis als entsprechender Typ zurückgegeben, wobei bei Bedarf und Möglichkeit XPath‑Typkonvertierungen verwendet werden.

```csharp
public enum XPathResultType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Any | `0` | Dieser Code stellt keinen spezifischen Typ dar. Die Auswertung eines XPath‑Ausdrucks wird niemals diesen Typ erzeugen. Wird dieser Typ angefordert, gibt die Auswertung den natürlich aus der Auswertung des Ausdrucks resultierenden Typ zurück. Wenn das natürliche Ergebnis ein Knotensatz ist, wenn der Typ `Any` angefordert wurde, ist `UnorderedNodeIterator` stets der resultierende Typ. Jede andere Darstellung eines Knotensatzes muss explizit angefordert werden. |
| Number | `1` | Das Ergebnis ist eine Zahl, wie in [XPath 1.0] definiert. Eine Dokumentenänderung macht die Zahl nicht ungültig, kann jedoch bedeuten, dass eine erneute Auswertung nicht dieselbe Zahl liefert. |
| String | `2` | Das Ergebnis ist eine Zeichenkette, wie in [XPath 1.0] definiert. Eine Dokumentenänderung macht die Zeichenkette nicht ungültig, kann jedoch bedeuten, dass die Zeichenkette nicht mehr dem aktuellen Dokument entspricht. |
| Boolean | `3` | Das Ergebnis ist ein boolescher Wert, wie in [XPath 1.0] definiert. Eine Dokumentenänderung macht den booleschen Wert nicht ungültig, kann jedoch bedeuten, dass eine erneute Auswertung nicht denselben booleschen Wert liefert. |
| UnorderedNodeIterator | `4` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der iterativ abgerufen wird und möglicherweise keine Knoten in einer bestimmten Reihenfolge liefert. Eine Dokumentenänderung macht die Iteration ungültig. Dies ist der Standardtyp, der zurückgegeben wird, wenn das Ergebnis ein Knotensatz ist und der Typ `Any` angefordert wird. |
| OrderedNodeIterator | `5` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der iterativ abgerufen wird und dokumentgeordneten Knoten erzeugt. Eine Dokumentänderung macht die Iteration ungültig. |
| UnorderedNodeSnapshot | `6` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der als Schnappschuss-Liste von Knoten abgerufen wird, die möglicherweise nicht in einer bestimmten Reihenfolge vorliegen. Eine Dokumentänderung macht den Schnappschuss nicht ungültig, kann jedoch bedeuten, dass eine erneute Auswertung nicht denselben Schnappschuss liefert und Knoten im Schnappschuss verändert, verschoben oder aus dem Dokument entfernt wurden. |
| OrderedNodeSnapshot | `7` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der als Schnappschuss-Liste von Knoten abgerufen wird, die in der ursprünglichen Dokumentreihenfolge stehen. Eine Dokumentänderung macht den Schnappschuss nicht ungültig, kann jedoch bedeuten, dass eine erneute Auswertung nicht denselben Schnappschuss liefert und Knoten im Schnappschuss verändert, verschoben oder aus dem Dokument entfernt wurden. |
| AnyUnorderedNode | `8` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, und wird als einzelner Knoten abgerufen, der `null` sein kann, wenn der Knotensatz leer ist. Eine Dokumentänderung macht den Knoten nicht ungültig, kann jedoch bedeuten, dass der Ergebnis‑Knoten nicht mehr dem aktuellen Dokument entspricht. Dies ist eine Bequemlichkeit, die Optimierungen ermöglicht, da die Implementierung stoppen kann, sobald irgendein Knoten im Ergebnis‑Satz gefunden wurde. Gibt es mehr als einen Knoten im tatsächlichen Ergebnis, kann der zurückgegebene einzelne Knoten nicht der erste in Dokumentreihenfolge sein. |
| FirstOrderedNode | `9` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, und wird als einzelner Knoten abgerufen, der `null` sein kann, wenn der Knotensatz leer ist. Eine Dokumentänderung macht den Knoten nicht ungültig, kann jedoch bedeuten, dass der Ergebnis‑Knoten nicht mehr dem aktuellen Dokument entspricht. Dies ist eine Bequemlichkeit, die Optimierungen ermöglicht, da die Implementierung stoppen kann, sobald der erste Knoten in Dokumentreihenfolge des Ergebnis‑Satzes gefunden wurde. Gibt es mehr als einen Knoten im tatsächlichen Ergebnis, wird der zurückgegebene einzelne Knoten der erste in Dokumentreihenfolge sein. |

### Siehe auch

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
