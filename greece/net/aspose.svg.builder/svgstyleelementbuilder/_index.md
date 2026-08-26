---
title: "SVGStyleElementBuilder Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Builder.SVGStyleElementBuilder κλάση. Μια κλάση builder για τη δημιουργία ενός στοιχείου στυλ SVG. Αυτή η κλάση διευκολύνει τη δημιουργία και τη διαμόρφωση ενός στοιχείου στυλ SVG με κανόνες CSS."
type: docs
weight: 1630
url: /el/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

Μια κατηγορία builder για τη δημιουργία ενός στοιχείου SVG 'style'. Αυτή η κατηγορία διευκολύνει τη δημιουργία και τη διαμόρφωση ενός στοιχείου στυλ SVG με κανόνες CSS.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | Προσθέτει ένα σχόλιο στο περιεχόμενο του στυλ. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | Προσθέτει έναν κανόνα CSS στο στοιχείο στυλ χρησιμοποιώντας ένα RuleBuilder. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | Προσθέτει έναν κανόνα CSS στο στοιχείο στυλ. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Δημιουργεί το στοιχείο στυλ SVG με τους συσσωρευμένους κανόνες CSS και το προσθέτει στο καθορισμένο έγγραφο. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | Ορίζει το χαρακτηριστικό 'media' του στοιχείου SVG 'style'. Αυτό το χαρακτηριστικό καθορίζει τα μέσα για τα οποία προορίζονται τα στυλ, επιτρέποντας στα στυλ να είναι υπό συνθήκη του τύπου μέσου. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | Ορίζει το χαρακτηριστικό 'title' του στοιχείου SVG 'style'. Αυτό το χαρακτηριστικό παρέχει έναν συμβουλευτικό τίτλο για το στοιχείο στυλ, ο οποίος μπορεί να είναι χρήσιμος για την προσβασιμότητα και το κείμενο συμβουλής εργαλείου. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | Ορίζει το χαρακτηριστικό 'type' του στοιχείου SVG 'style'. Αυτό το χαρακτηριστικό καθορίζει τη γλώσσα του φύλλου στυλ του περιεχομένου του στοιχείου. |

### Δείτε επίσης

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
