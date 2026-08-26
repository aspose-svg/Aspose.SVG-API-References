---
title: "Διεπαφή IXPathEvaluator"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Διεπαφή Aspose.Svg.Dom.XPath.IXPathEvaluator. Η αξιολόγηση των εκφράσεων XPath παρέχεται από IXPathEvaluator"
type: docs
weight: 3310
url: /el/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Η αξιολόγηση των εκφράσεων XPath παρέχεται από `IXPathEvaluator`.

```csharp
public interface IXPathEvaluator
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(*string, [IXPathNSResolver](../ixpathnsresolver/)*) | Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένα ονόματα χώρων. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατό το μεταγλωττισμό της συμβολοσειράς έκφρασης σε μια πιο αποδοτική εσωτερική μορφή και την προεπίλυση όλων των προθεμάτων ονομάτων χώρων που εμφανίζονται στην έκφραση. |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(*[Node](../../aspose.svg.dom/node/)*) | Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση ονομάτων χώρων ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 `lookupNamespaceURI` στους κόμβους για την επίλυση του namespaceURI από ένα δεδομένο πρόθεμα, χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου τη στιγμή που καλείται η lookupNamespaceURI, καθώς και επιλύοντας σωστά το έμμεσο πρόθεμα xml. |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(*string, [Node](../../aspose.svg.dom/node/), [IXPathNSResolver](../ixpathnsresolver/), [XPathResultType](../xpathresulttype/), object*) | Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου, εφόσον είναι δυνατόν. |

### Δείτε επίσης

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
