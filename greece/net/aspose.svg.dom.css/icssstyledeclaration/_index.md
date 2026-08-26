---
title: "Διεπαφή ICSSStyleDeclaration"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Διεπαφή Aspose.Svg.Dom.Css.ICSSStyleDeclaration. Η διεπαφή CSSStyleDeclaration αντιπροσωπεύει ένα μοναδικό μπλοκ δήλωσης CSS. Αυτή η διεπαφή μπορεί να χρησιμοποιηθεί για τον προσδιορισμό των ιδιοτήτων στυλ που είναι τρέχουσες στο μπλοκ ή για την ρητή ορισμό ιδιοτήτων στυλ εντός του μπλοκ."
type: docs
weight: 2640
url: /el/net/aspose.svg.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

Η διεπαφή CSSStyleDeclaration αντιπροσωπεύει ένα μοναδικό μπλοκ δήλωσης CSS. Αυτή η διεπαφή μπορεί να χρησιμοποιηθεί για τον προσδιορισμό των ιδιοτήτων στυλ που είναι τρέχουσες στο μπλοκ ή για τον ορισμό ιδιοτήτων στυλ ρητά μέσα στο μπλοκ.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssstyledeclaration/csstext/) { get; set; } | Η αναγνώσιμη κειμενική αναπαράσταση του μπλοκ δήλωσης (χωρίς τις περιβάλλουσες αγκύλες). Ορισμός αυτού του χαρακτηριστικού θα έχει ως αποτέλεσμα την ανάλυση της νέας τιμής και την επαναφορά όλων των ιδιοτήτων στο μπλοκ δήλωσης, συμπεριλαμβανομένης της αφαίρεσης ή προσθήκης ιδιοτήτων. |
| [Item](../../aspose.svg.dom.css/icssstyledeclaration/item/) { get; } | Χρησιμοποιείται για την ανάκτηση των ιδιοτήτων που έχουν οριστεί ρητά σε αυτό το μπλοκ δήλωσης. Η σειρά των ιδιοτήτων που ανακτώνται με αυτή τη μέθοδο δεν χρειάζεται να είναι η σειρά με την οποία ορίστηκαν. Αυτή η μέθοδος μπορεί να χρησιμοποιηθεί για επανάληψη σε όλες τις ιδιότητες σε αυτό το μπλοκ δήλωσης. |
| [Length](../../aspose.svg.dom.css/icssstyledeclaration/length/) { get; } | Ο αριθμός των ιδιοτήτων που έχουν οριστεί ρητά σε αυτό το μπλοκ δήλωσης. Η περιοχή των έγκυρων δεικτών είναι από 0 έως length-1 συμπεριλαμβανομένου. |
| [ParentRule](../../aspose.svg.dom.css/icssstyledeclaration/parentrule/) { get; } | Ο κανόνας CSS που περιέχει αυτό το μπλοκ δήλωσης ή null εάν αυτό το CSSStyleDeclaration δεν είναι συνδεδεμένο με έναν CSSRule. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertycssvalue/)(*string*) | Χρησιμοποιείται για την ανάκτηση της αντικειμενικής αναπαράστασης της τιμής μιας ιδιότητας CSS εάν έχει οριστεί ρητά μέσα σε αυτό το μπλοκ δήλωσης. Αυτή η μέθοδος επιστρέφει null εάν η ιδιότητα είναι συντομευμένη. Οι τιμές συντομευμένων ιδιοτήτων μπορούν να προσπελαστούν και να τροποποιηθούν μόνο ως συμβολοσειρές, χρησιμοποιώντας τις μεθόδους getPropertyValue και setProperty. |
| [GetPropertyPriority](../../aspose.svg.dom.css/icssstyledeclaration/getpropertypriority/)(*string*) | Χρησιμοποιείται για την ανάκτηση της προτεραιότητας μιας ιδιότητας CSS (π.χ. ο χαρακτηρισμός "important") εάν η ιδιότητα έχει οριστεί ρητά σε αυτό το μπλοκ δήλωσης. |
| [GetPropertyValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertyvalue/)(*string*) | Χρησιμοποιείται για την ανάκτηση της τιμής μιας ιδιότητας CSS εάν έχει οριστεί ρητά μέσα σε αυτό το μπλοκ δήλωσης. |
| [RemoveProperty](../../aspose.svg.dom.css/icssstyledeclaration/removeproperty/)(*string*) | Χρησιμοποιείται για την αφαίρεση μιας ιδιότητας CSS εάν έχει οριστεί ρητά μέσα σε αυτό το μπλοκ δήλωσης. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty)(*string, string*) | Χρησιμοποιείται για τον ορισμό μιας τιμής ιδιότητας με προεπιλεγμένη προτεραιότητα μέσα σε αυτό το μπλοκ δήλωσης. Η προεπιλεγμένη προτεραιότητα δεν είναι "important", δηλαδή String.Empty |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(*string, string, string*) | Χρησιμοποιείται για τον ορισμό μιας τιμής ιδιότητας και προτεραιότητας μέσα σε αυτό το μπλοκ δήλωσης. |

### Δείτε επίσης

* interface [ICSS2Properties](../icss2properties/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
