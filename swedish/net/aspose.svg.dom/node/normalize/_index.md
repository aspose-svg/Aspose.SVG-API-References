---
title: "Node.Normalize"
second_title: "Aspose.SVG för .NET API-referens"
description: "Node Normalize‑metod. Omvandlar alla Text‑noder i hela djupet av delträdet under denna Node, inklusive attributnoder, till ett normaliserat format där endast strukturella element (t.ex. element, kommentarer, processinstruktioner, CDATA‑sektioner och enhetsreferenser) separerar Text‑noder, dvs. det finns inga intilliggande eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och lästes in igen, och är användbart när operationer såsom XPointer‑uppslag som beror på en specifik dokumentträdstruktur ska användas. Om parametern normalize-characters i DOMConfiguration‑objektet som är kopplat till Node.ownerDocument är true, normaliserar metoden även tecknen i Text‑noderna fullt ut."
type: docs
weight: 260
url: /sv/net/aspose.svg.dom/node/normalize/
---
## Node.Normalize method

Placera alla Text‑noder i hela djupet av delträdet under denna Node, inklusive attributnoder, i ett "normal" format där endast strukturen (t.ex. element, kommentarer, processinstruktioner, CDATA‑sektioner och entitetsreferenser) separerar Text‑noder, d.v.s. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (såsom XPointer [XPointer] uppslag) som beror på en specifik dokumentträdstruktur ska användas. Om parametern "normalize-characters" för DOMConfiguration‑objektet som är kopplat till Node.ownerDocument är true, kommer denna metod också att fullt ut normalisera tecknen i Text‑noderna.

```csharp
public void Normalize()
```

### Se även

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
