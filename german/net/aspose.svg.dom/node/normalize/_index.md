---
title: "Node.Normalize"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Node Normalize-Methode. Platziert alle Textknoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine Normalform, bei der nur die Struktur – z. B. Elemente, Kommentare, Verarbeitungsanweisungen, CDATA‑Abschnitte und Entity‑Referenzen – Textknoten trennt, d. h. es gibt weder benachbarte noch leere Textknoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM‑Ansicht eines Dokuments dieselbe ist, als wäre sie gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen wie XPointer‑Lookups, die von einer bestimmten Dokumentbaumstruktur abhängen, verwendet werden sollen. Ist der Parameter normalize-characters des DOMConfiguration‑Objekts, das an Node.ownerDocument angehängt ist, auf true gesetzt, normalisiert diese Methode außerdem vollständig die Zeichen der Textknoten."
type: docs
weight: 260
url: /de/net/aspose.svg.dom/node/normalize/
---
## Node.Normalize method

Setzt alle Textknoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine "normale" Form, bei der nur die Struktur (z. B. Elemente, Kommentare, Verarbeitungsanweisungen, CDATA-Abschnitte und Entity-Referenzen) Textknoten trennt, d. h. es gibt weder benachbarte Textknoten noch leere Textknoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM-Ansicht eines Dokuments dieselbe ist, als wäre sie gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen (wie XPointer [XPointer]-Nachschlagen), die von einer bestimmten Dokumentbaumstruktur abhängen, verwendet werden sollen. Wenn der Parameter "normalize-characters" des DOMConfiguration-Objekts, das an Node.ownerDocument angehängt ist, true ist, normalisiert diese Methode auch vollständig die Zeichen der Textknoten.

```csharp
public void Normalize()
```

### Siehe auch

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
