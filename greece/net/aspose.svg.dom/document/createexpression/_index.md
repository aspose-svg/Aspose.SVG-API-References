---
title: "Document.CreateExpression"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Document CreateExpression method. Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένα ονόματα χώρων. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατή τη μεταγλώττιση του κειμένου της έκφρασης σε πιο αποδοτική εσωτερική μορφή και την προεπίλυση όλων των προθεμάτων ονομάτων χώρων που εμφανίζονται στην έκφραση."
type: docs
weight: 890
url: /el/net/aspose.svg.dom/document/createexpression/
---
## Document.CreateExpression method

Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένα ονόματα χώρων. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατό το μεταγλωττισμό της συμβολοσειράς έκφρασης σε μια πιο αποδοτική εσωτερική μορφή και την προεπίλυση όλων των προθεμάτων ονομάτων χώρων που εμφανίζονται στην έκφραση.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expression | String | Η συμβολοσειρά της έκφρασης XPath που θα αναλυθεί. |
| resolver | IXPathNSResolver | Ο `resolver` επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του προθέματος ονόματος χώρου `xml`, μέσα στην έκφραση XPath σε κατάλληλα URI ονομάτων χώρων. Εάν αυτό οριστεί ως `null`, οποιοδήποτε πρόθεμα ονόματος χώρου μέσα στην έκφραση θα προκαλέσει την εξαίρεση [`DOMException`](../../domexception/) με κώδικα `NAMESPACE_ERR`. |

### Τιμή Επιστροφής

Η μεταγλωττισμένη μορφή της έκφρασης XPath.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Εμφανίζεται εάν η έκφραση δεν είναι νόμιμη σύμφωνα με τους κανόνες του [`IXPathEvaluator`](../../../aspose.svg.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: Εμφανίζεται εάν η έκφραση περιέχει προθέματα ονομάτων χώρων που δεν μπορούν να επιλυθούν από τον καθορισμένο [`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/). |

### Δείτε επίσης

* interface [IXPathExpression](../../../aspose.svg.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
