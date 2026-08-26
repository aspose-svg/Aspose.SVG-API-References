---
title: "Document.Evaluate"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Document Evaluate. Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου εάν είναι δυνατόν."
type: docs
weight: 950
url: /el/net/aspose.svg.dom/document/evaluate/
---
## Document.Evaluate method

Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου, εφόσον είναι δυνατόν.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expression | String | Η συμβολοσειρά της έκφρασης XPath που θα αναλυθεί και αξιολογηθεί. |
| contextNode | Node | Το πλαίσιο είναι ο κόμβος πλαισίου για την αξιολόγηση αυτής της έκφρασης XPath. |
| επίλυση | IXPathNSResolver | Ο resolver επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του προθέματος του χώρου ονομάτων xml, μέσα στην έκφραση XPath σε κατάλληλα URIs χώρου ονομάτων. |
| type | XPathResultType | Εάν καθοριστεί ένας συγκεκριμένος τύπος, τότε το αποτέλεσμα θα επιστραφεί ως ο αντίστοιχος τύπος. |
| result | Αντικείμενο | Το αποτέλεσμα καθορίζει ένα συγκεκριμένο αντικείμενο αποτελέσματος που μπορεί να επαναχρησιμοποιηθεί και να επιστραφεί από αυτή τη μέθοδο. |

### Τιμή Επιστροφής

Το αποτέλεσμα της αξιολόγησης της έκφρασης XPath.

### Δείτε επίσης

* interface [IXPathResult](../../../aspose.svg.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.svg.dom.xpath/xpathresulttype/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
