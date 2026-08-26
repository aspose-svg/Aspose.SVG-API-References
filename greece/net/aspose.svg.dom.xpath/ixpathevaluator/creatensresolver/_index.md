---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος CreateNSResolver του IXPathEvaluator. Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση ονοματοχώρων ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 lookupNamespaceURI στους κόμβους, επιλύοντας το namespaceURI από ένα δεδομένο πρόθεμα χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία των κόμβων τη στιγμή που καλείται η lookupNamespaceURI, καθώς και επιλύοντας σωστά το έμμεσο πρόθεμα xml."
type: docs
weight: 20
url: /el/net/aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση ονομάτων χώρων ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 `lookupNamespaceURI` στους κόμβους για την επίλυση του namespaceURI από ένα δεδομένο πρόθεμα, χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου τη στιγμή που καλείται η lookupNamespaceURI, καθώς και επιλύοντας σωστά το έμμεσο πρόθεμα xml.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeResolver | Node | Ο κόμβος που θα χρησιμοποιηθεί ως πλαίσιο για την επίλυση ονοματοχώρων. |

### Τιμή Επιστροφής

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### Δείτε επίσης

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
