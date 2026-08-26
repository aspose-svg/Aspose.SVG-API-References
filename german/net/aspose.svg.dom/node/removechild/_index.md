---
title: "Node.RemoveChild"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Node RemoveChild‑Methode. Entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück."
type: docs
weight: 270
url: /de/net/aspose.svg.dom/node/removechild/
---
## Node.RemoveChild method

Entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück.

Hinweis: Solange eine Referenz auf das entfernte Kind gehalten wird, existiert es weiterhin im Speicher, ist jedoch nicht mehr Teil des DOM. Es kann später im Code wiederverwendet werden. Wird der Rückgabewert von `RemoveChild` nicht gespeichert und es gibt keine weitere Referenz, wird es nach kurzer Zeit automatisch aus dem Speicher gelöscht.

```csharp
public Node RemoveChild(Node child)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| child | Node | Ein [`Node`](../), der der zu entfernende Kindknoten aus dem DOM ist. |

### Rückgabewert

Im Gegensatz zu [`CloneNode`](../clonenode/) bewahrt der Rückgabewert die damit verknüpften [`EventListener`](../../../aspose.svg.dom.events/ieventlistener/)‑Objekte.

### Siehe auch

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
