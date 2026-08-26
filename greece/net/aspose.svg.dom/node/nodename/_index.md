---
title: "Node.NodeName"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Ιδιότητα Node.NodeName. Επιστρέφει το όνομα του τρέχοντος κόμβου ως συμβολοσειρά."
type: docs
weight: 80
url: /el/net/aspose.svg.dom/node/nodename/
---
## Node.NodeName property

Επιστρέφει το όνομα του τρέχοντος κόμβου ως συμβολοσειρά.

```csharp
public abstract string NodeName { get; }
```

### Property Value

Μια συμβολοσειρά, οι τιμές για τους διαφορετικούς τύπους κόμβων είναι:

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The string "#cdata-section".[`Comment`](../../comment/) - The string "#comment".[`Document`](../../document/) - The string "#document".[`DocumentFragment`](../../documentfragment/) - The string "#document-fragment".[`DocumentType`](../../documenttype/) - The value of [`Name`](../../documenttype/name/)[`Element`](../../element/) - The value of [`TagName`](../../element/tagname/), that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like an SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of [`Target`](../../processinginstruction/target/)[`Text`](../../text/) - The string "#text".

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-nodename).

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
