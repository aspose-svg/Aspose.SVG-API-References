---
title: "Κλάση NamedNodeMap"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Κλάση Aspose.Svg.Collections.NamedNodeMap. Αντιπροσωπεύει συλλογές χαρακτηριστικών που μπορούν να προσπελαστούν με όνομα."
type: docs
weight: 2020
url: /el/net/aspose.svg.collections/namednodemap/
---
## NamedNodeMap class

Αντιπροσωπεύει συλλογές χαρακτηριστικών που μπορούν να προσπελαστούν με όνομα.

```csharp
public class NamedNodeMap : DOMObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Item](../../aspose.svg.collections/namednodemap/item/) { get; } | Επιστρέφει το στοιχείο με δείκτη index στον χάρτη. Εάν ο δείκτης είναι μεγαλύτερος ή ίσος με τον αριθμό των κόμβων σε αυτόν τον χάρτη, επιστρέφει null. (2 δείκτες) |
| [Length](../../aspose.svg.collections/namednodemap/length/) { get; } | Ο αριθμός των κόμβων σε αυτόν τον χάρτη. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetNamedItem](../../aspose.svg.collections/namednodemap/getnameditem/)(*string*) | Ανακτά έναν κόμβο που καθορίζεται με όνομα. |
| [GetNamedItemNS](../../aspose.svg.collections/namednodemap/getnameditemns/)(*string, string*) | Ανακτά έναν κόμβο που καθορίζεται με τοπικό όνομα και URI ονοματοχώρου. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [RemoveNamedItem](../../aspose.svg.collections/namednodemap/removenameditem/)(*string*) | Αφαιρεί έναν κόμβο που καθορίζεται με όνομα. |
| [RemoveNamedItemNS](../../aspose.svg.collections/namednodemap/removenameditemns/)(*string, string*) | Αφαιρεί έναν κόμβο που καθορίζεται με τοπικό όνομα και URI ονοματοχώρου. |
| [SetNamedItem](../../aspose.svg.collections/namednodemap/setnameditem/)(*[Attr](../../aspose.svg.dom/attr/)*) | Προσθέτει έναν κόμβο χρησιμοποιώντας το χαρακτηριστικό nodeName του. Εάν υπάρχει ήδη ένας κόμβος με αυτό το όνομα σε αυτόν τον χάρτη, αντικαθίσταται από το νέο. Η αντικατάσταση ενός κόμβου από τον ίδιο δεν έχει καμία επίδραση. |
| [SetNamedItemNS](../../aspose.svg.collections/namednodemap/setnameditemns/)(*[Attr](../../aspose.svg.dom/attr/)*) | Προσθέτει έναν κόμβο χρησιμοποιώντας το namespaceURI και το localName του. Εάν υπάρχει ήδη ένας κόμβος με αυτό το namespace URI και αυτό το local name σε αυτόν τον χάρτη, αντικαθίσταται από το νέο. Η αντικατάσταση ενός κόμβου από τον ίδιο δεν έχει καμία επίδραση. |

### Δείτε επίσης

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
