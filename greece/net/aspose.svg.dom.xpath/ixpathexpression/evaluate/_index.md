---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Evaluate του IXPathExpression. Αξιολογεί αυτήν την έκφραση XPath και επιστρέφει ένα αποτέλεσμα"
type: docs
weight: 10
url: /el/net/aspose.svg.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Αξιολογεί αυτήν την έκφραση XPath και επιστρέφει ένα αποτέλεσμα.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| contextNode | Node | Το `context` είναι ο κόμβος περιβάλλοντος για την αξιολόγηση αυτής της έκφρασης XPath. Εάν το [`IXPathEvaluator`](../../ixpathevaluator/) αποκτήθηκε με μετατροπή του [`Document`](../../../aspose.svg.dom/document/), τότε αυτό πρέπει να ανήκει στο ίδιο έγγραφο και πρέπει να είναι ένα [`Document`](../../../aspose.svg.dom/document/), [`Element`](../../../aspose.svg.dom/element/), [`Attr`](../../../aspose.svg.dom/attr/), [`Text`](../../../aspose.svg.dom/text/), [`CDATASection`](../../../aspose.svg.dom/cdatasection/), [`Comment`](../../../aspose.svg.dom/comment/), [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/), ή κόμβος XPathNamespace. Εάν ο κόμβος περιβάλλοντος είναι ένα [`Text`](../../../aspose.svg.dom/text/) ή ένα [`CDATASection`](../../../aspose.svg.dom/cdatasection/), τότε το περιβάλλον ερμηνεύεται ως ολόκληρος ο λογικός κόμβος κειμένου όπως φαίνεται από το XPath, εκτός εάν ο κόμβος είναι κενός, οπότε μπορεί να μην λειτουργεί ως περιβάλλον XPath. |
| type | XPathResultType | Εάν καθοριστεί ένα συγκεκριμένο `type`, τότε το αποτέλεσμα θα μετατραπεί ώστε να επιστρέψει τον καθορισμένο τύπο, βασιζόμενο στις μετατροπές XPath, και θα αποτύχει εάν η επιθυμητή μετατροπή δεν είναι δυνατή. Αυτό πρέπει να είναι μία από τις τιμές του [`XPathResultType`](../../xpathresulttype/). |
| result | Object | Το `result` καθορίζει ένα συγκεκριμένο αντικείμενο αποτελέσματος που μπορεί να επαναχρησιμοποιηθεί και να επιστραφεί από αυτή τη μέθοδο. Εάν αυτό οριστεί ως `null` ή η υλοποίηση δεν επαναχρησιμοποιήσει το καθορισμένο αποτέλεσμα, θα δημιουργηθεί και θα επιστραφεί ένα νέο αντικείμενο αποτελέσματος. Για αποτελέσματα XPath 1.0, αυτό το αντικείμενο θα είναι τύπου [`IXPathResult`](../../ixpathresult/). |

### Τιμή Επιστροφής

Το αποτέλεσμα της αξιολόγησης της έκφρασης XPath. Για αποτελέσματα XPath 1.0, αυτό το αντικείμενο θα είναι τύπου [`IXPathResult`](../../ixpathresult/).

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: Εμφανίζεται εάν το αποτέλεσμα δεν μπορεί να μετατραπεί ώστε να επιστρέψει τον καθορισμένο τύπο. |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: Ο Node προέρχεται από έγγραφο που δεν υποστηρίζεται από το [`IXPathEvaluator`](../../ixpathevaluator/) που δημιούργησε αυτό το [`IXPathExpression`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Ο Node δεν είναι τύπος που επιτρέπεται ως κόμβος περιβάλλοντος XPath ή ο τύπος αιτήματος δεν επιτρέπεται από αυτό το [`IXPathExpression`](../). |

### Δείτε επίσης

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
