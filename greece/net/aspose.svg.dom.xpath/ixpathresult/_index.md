---
title: "IXPathResult Διεπαφή"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.XPath.IXPathResult interface. Η διεπαφή XPathResult αντιπροσωπεύει το αποτέλεσμα της αξιολόγησης μιας έκφρασης XPath 1.0 μέσα στο πλαίσιο ενός συγκεκριμένου κόμβου. Δεδομένου ότι η αξιολόγηση μιας έκφρασης XPath μπορεί να οδηγήσει σε διάφορους τύπους αποτελεσμάτων, αυτό το αντικείμενο καθιστά δυνατό το εντοπισμό και τη διαχείριση του τύπου και της τιμής του αποτελέσματος"
type: docs
weight: 3350
url: /el/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

Η διεπαφή `XPathResult` αναπαριστά το αποτέλεσμα της αξιολόγησης μιας έκφρασης XPath 1.0 στο πλαίσιο ενός συγκεκριμένου κόμβου. Δεδομένου ότι η αξιολόγηση μιας έκφρασης XPath μπορεί να οδηγήσει σε διάφορους τύπους αποτελεσμάτων, αυτό το αντικείμενο καθιστά δυνατό τον εντοπισμό και τη διαχείριση του τύπου και της τιμής του αποτελέσματος.

```csharp
public interface IXPathResult
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue/) { get; } | Η τιμή αυτού του λογικού αποτελέσματος. |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Δηλώνει ότι ο επαναλήπτης έχει γίνει άκυρος. Αληθές εάν το `resultType` είναι τύπου `UnorderedNodeIterator` ή `OrderedNodeIterator` και το έγγραφο έχει τροποποιηθεί από τη στιγμή που αυτό το αποτέλεσμα επιστράφηκε. |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue/) { get; } | Η τιμή αυτού του αριθμητικού αποτελέσματος. |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype/) { get; } | Ένας κώδικας που αντιπροσωπεύει τον τύπο αυτού του αποτελέσματος, όπως ορίζεται από το http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) enum. |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue/) { get; } | Η τιμή αυτού του μοναδικού αποτελέσματος κόμβου, η οποία μπορεί να είναι `null`. |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength/) { get; } | Ο αριθμός των κόμβων στη λήψη στιγμιότυπου του αποτελέσματος. Έγκυρες τιμές για τα ευρετήρια snapshotItem είναι από `0` έως `snapshotLength-1` συμπεριλαμβανομένα. |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue/) { get; } | Η τιμή αυτού του αποτελέσματος συμβολοσειράς. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext/)() | Επαναλαμβάνει και επιστρέφει τον επόμενο κόμβο από το σύνολο κόμβων ή `null` εάν δεν υπάρχουν άλλοι κόμβοι. |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem/)(*int*) | Επιστρέφει το στοιχείο `index` στη συλλογή στιγμιότυπου. Εάν το `index` είναι μεγαλύτερο ή ίσο με τον αριθμό των κόμβων στη λίστα, αυτή η μέθοδος επιστρέφει `null`. Σε αντίθεση με το αποτέλεσμα του επαναλήπτη, το στιγμιότυπο δεν γίνεται άκυρο, αλλά μπορεί να μην αντιστοιχεί στο τρέχον έγγραφο εάν αυτό τροποποιηθεί. |

### Δείτε επίσης

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
