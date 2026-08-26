---
title: "IXPathEvaluator.CreateExpression"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος CreateExpression του IXPathEvaluator. Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένους ονοματοχώρους. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατή τη μεταγλώττιση της συμβολοσειράς της έκφρασης σε πιο αποδοτική εσωτερική μορφή και την προεπίλυση όλων των προθεμάτων ονοματοχώρων που εμφανίζονται στην έκφραση."
type: docs
weight: 10
url: /el/net/aspose.svg.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένα ονόματα χώρων. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατό το μεταγλωττισμό της συμβολοσειράς έκφρασης σε μια πιο αποδοτική εσωτερική μορφή και την προεπίλυση όλων των προθεμάτων ονομάτων χώρων που εμφανίζονται στην έκφραση.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expression | String | Η συμβολοσειρά της έκφρασης XPath που θα αναλυθεί. |
| resolver | IXPathNSResolver | Ο `resolver` επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του προθέματος ονοματοχώρου `xml`, μέσα στην έκφραση XPath σε κατάλληλα URIs ονοματοχώρων. Εάν αυτό οριστεί ως `null`, οποιοδήποτε πρόθεμα ονοματοχώρου μέσα στην έκφραση θα προκαλέσει την εξαίρεση [`DOMException`](../../../aspose.svg.dom/domexception/) με κώδικα `NAMESPACE_ERR`. |

### Τιμή Επιστροφής

Η μεταγλωττισμένη μορφή της έκφρασης XPath.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: Εμφανίζεται εάν η έκφραση δεν είναι έγκυρη σύμφωνα με τους κανόνες του [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: Εμφανίζεται εάν η έκφραση περιέχει προθέματα ονοματοχώρων που δεν μπορούν να επιλυθούν από τον καθορισμένο [`IXPathNSResolver`](../../ixpathnsresolver/). |

### Δείτε επίσης

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
