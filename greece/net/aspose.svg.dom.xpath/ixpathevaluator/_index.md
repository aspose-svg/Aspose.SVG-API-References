---
title: Interface IXPathEvaluator
second_title: Aspose.SVG για Αναφορά API .NET
description: Aspose.Svg.Dom.XPath.IXPathEvaluator διεπαφή. Η αξιολόγηση των παραστάσεων XPath παρέχεται απόIXPathEvaluator .
type: docs
weight: 1310
url: /el/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Η αξιολόγηση των παραστάσεων XPath παρέχεται από`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένους χώρους ονομάτων. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατή την να μεταγλωττίσει τη συμβολοσειρά έκφρασης σε μια πιο αποτελεσματική εσωτερική μορφή και να επιλύσει εκ των προτέρων όλα τα προθέματα χώρου ονομάτων που εμφανίζονται μέσα στην έκφραση. |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση χώρων ονομάτων, έτσι ώστε μια έκφραση XPath να μπορεί εύκολα να αξιολογηθεί σε σχέση με το περιβάλλον του κόμβου όπου εμφανίστηκε στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3`lookupNamespaceURI` σε κόμβους για την επίλυση του namespaceURI από ένα δεδομένο πρόθεμα χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου στο time lookupNamespaceURI καλείται, επιλύοντας επίσης σωστά το σιωπηρό πρόθεμα xml. |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου εάν είναι δυνατόν. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* συνέλευση [Aspose.SVG](../../)


