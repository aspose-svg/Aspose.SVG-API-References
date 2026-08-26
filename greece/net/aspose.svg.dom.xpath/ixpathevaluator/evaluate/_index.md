---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Evaluate του IXPathEvaluator. Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου, εφόσον είναι δυνατόν."
type: docs
weight: 30
url: /el/net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου, εφόσον είναι δυνατόν.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expression | String | Η συμβολοσειρά της έκφρασης XPath που θα αναλυθεί και αξιολογηθεί. |
| contextNode | Node | Το `context` είναι ο κόμβος περιβάλλοντος για την αξιολόγηση αυτής της έκφρασης XPath. Εάν το [`IXPathEvaluator`](../) αποκτήθηκε με μετατροπή του [`Document`](../../../aspose.svg.dom/document/), τότε αυτό πρέπει να ανήκει στο ίδιο έγγραφο και πρέπει να είναι ένα [`Document`](../../../aspose.svg.dom/document/), [`Element`](../../../aspose.svg.dom/element/), [`Attr`](../../../aspose.svg.dom/attr/), [`Text`](../../../aspose.svg.dom/text/), [`CDATASection`](../../../aspose.svg.dom/cdatasection/), [`Comment`](../../../aspose.svg.dom/comment/), [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/), ή κόμβος XPathNamespace. Εάν ο κόμβος περιβάλλοντος είναι ένα [`Text`](../../../aspose.svg.dom/text/) ή ένα [`CDATASection`](../../../aspose.svg.dom/cdatasection/), τότε το περιβάλλον ερμηνεύεται ως ολόκληρος ο λογικός κόμβος κειμένου όπως τον βλέπει το XPath, εκτός εάν ο κόμβος είναι κενός, οπότε δεν μπορεί να λειτουργήσει ως περιβάλλον XPath. |
| resolver | IXPathNSResolver | Ο `resolver` επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του προθέματος ονοματοχώρου `xml`, μέσα στην έκφραση XPath σε κατάλληλα URIs ονοματοχώρων. Εάν αυτό οριστεί ως `null`, οποιοδήποτε πρόθεμα ονοματοχώρου μέσα στην έκφραση θα προκαλέσει την εξαίρεση [`DOMException`](../../../aspose.svg.dom/domexception/) με κώδικα `NAMESPACE_ERR`. |
| type | XPathResultType | Εάν καθοριστεί συγκεκριμένο `type`, τότε το αποτέλεσμα θα επιστραφεί ως ο αντίστοιχος τύπος. Για αποτελέσματα XPath 1.0, αυτό πρέπει να είναι μία από τις τιμές του enum [`XPathResultType`](../../xpathresulttype/). |
| result | Object | Το `result` καθορίζει ένα συγκεκριμένο αντικείμενο αποτελέσματος που μπορεί να επαναχρησιμοποιηθεί και να επιστραφεί από αυτή τη μέθοδο. Εάν αυτό οριστεί ως `null` ή η υλοποίηση δεν επαναχρησιμοποιήσει το καθορισμένο αποτέλεσμα, θα δημιουργηθεί και θα επιστραφεί ένα νέο αντικείμενο αποτελέσματος. Για αποτελέσματα XPath 1.0, αυτό το αντικείμενο θα είναι τύπου [`IXPathResult`](../../ixpathresult/). |

### Τιμή Επιστροφής

Το αποτέλεσμα της αξιολόγησης της έκφρασης XPath. Για αποτελέσματα XPath 1.0, αυτό το αντικείμενο θα είναι τύπου [`IXPathResult`](../../ixpathresult/).

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: Εμφανίζεται εάν η έκφραση δεν είναι έγκυρη σύμφωνα με τους κανόνες του [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: Εμφανίζεται εάν το αποτέλεσμα δεν μπορεί να μετατραπεί ώστε να επιστρέψει τον καθορισμένο τύπο. |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: Εμφανίζεται εάν η έκφραση περιέχει προθέματα ονοματοχώρων που δεν μπορούν να επιλυθούν από τον καθορισμένο [`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: Ο Node προέρχεται από έγγραφο που δεν υποστηρίζεται από αυτό το [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Ο Node δεν είναι τύπος που επιτρέπεται ως κόμβος περιβάλλοντος XPath ή ο τύπος αιτήματος δεν επιτρέπεται από αυτό το [`IXPathEvaluator`](../). |

### Δείτε επίσης

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
