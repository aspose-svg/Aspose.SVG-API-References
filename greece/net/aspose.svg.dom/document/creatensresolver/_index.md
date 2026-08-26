---
title: "Document.CreateNSResolver"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Document CreateNSResolver. Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση ονομάτων χώρων ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 lookupNamespaceURI στους κόμβους για την επίλυση του namespaceURI από ένα δεδομένο πρόθεμα, χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία των κόμβων τη στιγμή που καλείται η lookupNamespaceURI, καθώς και επιλύει σωστά το έμμεσο πρόθεμα xml"
type: docs
weight: 910
url: /el/net/aspose.svg.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση ονομάτων χώρων ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 `lookupNamespaceURI` στους κόμβους για την επίλυση του namespaceURI από ένα δεδομένο πρόθεμα, χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου τη στιγμή που καλείται η lookupNamespaceURI, καθώς και επιλύοντας σωστά το έμμεσο πρόθεμα xml.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeResolver | Node | Ο κόμβος που θα χρησιμοποιηθεί ως πλαίσιο για την επίλυση ονοματοχώρων. |

### Τιμή Επιστροφής

[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### Δείτε επίσης

* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
