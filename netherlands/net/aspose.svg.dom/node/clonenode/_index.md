---
title: "Node.CloneNode"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Node CloneNode methode. Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen"
type: docs
weight: 180
url: /nl/net/aspose.svg.dom/node/clonenode/
---
## CloneNode() {#clonenode}

Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen.

Het klonen van een knooppunt kopieert al zijn attributen en hun waarden, inclusief intrinsieke (inline) listeners. Het kopieert geen event listeners die zijn toegevoegd met [`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) of die aan elementeigenschappen zijn toegewezen (bijv. node.onclick = someFunction). Bovendien wordt voor een HTMLCanvasElement-element de geschilderde afbeelding niet gekopieerd.

```csharp
public Node CloneNode()
```

### Retourwaarde

De nieuwe [`Node`](../) gekloond. Het gekloonde knooppunt heeft geen ouder en maakt geen deel uit van het document, totdat het wordt toegevoegd aan een ander knooppunt dat deel uitmaakt van het document, met behulp van [`AppendChild`](../appendchild/) of een vergelijkbare methode.

### Zie ook

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CloneNode(*bool*) {#clonenode_1}

Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen. De parameter bepaalt of de in een knooppunt aanwezige subboom ook wordt gekloond al dan niet.

Het klonen van een knooppunt kopieert al zijn attributen en hun waarden, inclusief intrinsieke (inline) listeners. Het kopieert geen event listeners die zijn toegevoegd met [`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) of die aan elementeigenschappen zijn toegewezen (bijv. node.onclick = someFunction). Bovendien wordt voor een HTMLCanvasElement-element de geschilderde afbeelding niet gekopieerd.

```csharp
public Node CloneNode(bool deep)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| deep | Boolean | Indien true, wordt het knooppunt en zijn volledige subboom, inclusief tekst die zich mogelijk in kind [`Text`](../../text/) knooppunten bevindt, ook gekopieerd. |

### Retourwaarde

De nieuwe [`Node`](../) gekloond. Het gekloonde knooppunt heeft geen ouder en maakt geen deel uit van het document, totdat het wordt toegevoegd aan een ander knooppunt dat deel uitmaakt van het document, met behulp van [`AppendChild`](../appendchild/) of een vergelijkbare methode.

### Zie ook

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
