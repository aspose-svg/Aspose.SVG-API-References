---
title: "Node.AppendChild"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Node AppendChild-Methode. Fügt einen Knoten am Ende der Kindliste eines angegebenen Elternknotens hinzu. Wenn das übergebene Kind eine Referenz zu einem bereits im Dokument vorhandenen Knoten ist, verschiebt AppendChild ihn von seiner aktuellen Position zur neuen Position; es ist nicht erforderlich, den Knoten vom Elternknoten zu entfernen, bevor er an einen anderen Knoten angehängt wird."
type: docs
weight: 170
url: /de/net/aspose.svg.dom/node/appendchild/
---
## Node.AppendChild method

Fügt einen Knoten am Ende der Kindliste eines angegebenen Elternknotens hinzu. Wenn das übergebene Kind eine Referenz zu einem bereits im Dokument vorhandenen Knoten ist, verschiebt `AppendChild` ihn von seiner aktuellen Position zur neuen Position (es ist nicht erforderlich, den Knoten vom Elternknoten zu entfernen, bevor er an einen anderen Knoten angehängt wird).

Das bedeutet, dass ein Knoten nicht gleichzeitig an zwei Stellen im Dokument existieren kann. Hat der Knoten bereits ein Elternteil, wird er zuerst entfernt und dann an der neuen Position angehängt. Die [`CloneNode`](../clonenode/)-Methode kann verwendet werden, um vor dem Anhängen unter dem neuen Elternknoten eine Kopie des Knotens zu erstellen. Mit [`CloneNode`](../clonenode/) erstellte Kopien werden nicht automatisch synchron gehalten.

```csharp
public Node AppendChild(Node node)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | Node | Der Knoten, der an den angegebenen Elternknoten angehängt werden soll (in der Regel ein Element). |

### Rückgabewert

Ein Node, der das angehängte Kind ist, außer wenn das Kind ein [`DocumentFragment`](../../documentfragment/) ist; in diesem Fall wird das leere [`DocumentFragment`](../../documentfragment/) zurückgegeben.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| DOMException | Wird ausgelöst, wenn die Einschränkungen des DOM-Baums verletzt werden. |

### Siehe auch

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
