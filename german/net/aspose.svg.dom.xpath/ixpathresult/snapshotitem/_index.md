---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IXPathResult SnapshotItem-Methode. Gibt das Element an der angegebenen Position im Snapshot‑Sammlung zurück. Wenn der Index größer oder gleich der Anzahl der Knoten in der Liste ist, gibt diese Methode null zurück. Im Gegensatz zum Iterator‑Ergebnis wird der Snapshot nicht ungültig, kann jedoch bei Änderungen des Dokuments nicht mehr dem aktuellen Dokument entsprechen."
type: docs
weight: 90
url: /de/net/aspose.svg.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Gibt das `index`‑te Element in der Snapshot‑Sammlung zurück. Wenn `index` größer oder gleich der Anzahl der Knoten in der Liste ist, liefert diese Methode `null`. Im Gegensatz zum Iterator‑Ergebnis wird der Snapshot nicht ungültig, kann jedoch bei einer Veränderung des Dokuments nicht mehr dem aktuellen Dokument entsprechen.

```csharp
public Node SnapshotItem(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index in die Snapshot‑Sammlung. |

### Rückgabewert

Der Knoten an der `index`‑ten Position in der `NodeList` oder `null`, wenn dies kein gültiger Index ist.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: ausgelöst, wenn `resultType` nicht vom Typ `UnorderedNodeSnapshot` oder `OrderedNodeSnapshot` ist. |

### Siehe auch

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
