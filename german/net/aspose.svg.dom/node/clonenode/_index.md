---
title: "Node.CloneNode"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Node CloneNode‑Methode. Gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde"
type: docs
weight: 180
url: /de/net/aspose.svg.dom/node/clonenode/
---
## CloneNode() {#clonenode}

Gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde.

Das Klonen eines Knotens kopiert alle seine Attribute und deren Werte, einschließlich intrinsischer (inline) Listener. Es kopiert keine Event‑Listener, die mit [`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) hinzugefügt wurden, oder solche, die Element‑Eigenschaften zugewiesen sind (z. B. node.onclick = someFunction). Zusätzlich wird für ein HTMLCanvasElement‑Element das gemalte Bild nicht kopiert.

```csharp
public Node CloneNode()
```

### Rückgabewert

Der neue [`Node`](../) wurde geklont. Der geklonte Knoten hat keinen Elternknoten und ist nicht Teil des Dokuments, bis er mit [`AppendChild`](../appendchild/) oder einer ähnlichen Methode zu einem anderen Knoten, der Teil des Dokuments ist, hinzugefügt wird.

### Siehe auch

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CloneNode(*bool*) {#clonenode_1}

Gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Sein Parameter steuert, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht.

Das Klonen eines Knotens kopiert alle seine Attribute und deren Werte, einschließlich intrinsischer (inline) Listener. Es kopiert keine Event‑Listener, die mit [`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) hinzugefügt wurden, oder solche, die Element‑Eigenschaften zugewiesen sind (z. B. node.onclick = someFunction). Zusätzlich wird für ein HTMLCanvasElement‑Element das gemalte Bild nicht kopiert.

```csharp
public Node CloneNode(bool deep)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deep | Boolean | Wenn true, wird der Knoten und sein gesamter Unterbaum, einschließlich Text, der in Kind‑[`Text`](../../text/)‑Knoten enthalten sein kann, ebenfalls kopiert. |

### Rückgabewert

Der neue [`Node`](../) wurde geklont. Der geklonte Knoten hat keinen Elternknoten und ist nicht Teil des Dokuments, bis er mit [`AppendChild`](../appendchild/) oder einer ähnlichen Methode zu einem anderen Knoten, der Teil des Dokuments ist, hinzugefügt wird.

### Siehe auch

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
