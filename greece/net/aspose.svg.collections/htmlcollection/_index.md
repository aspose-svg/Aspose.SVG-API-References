---
title: "HTMLCollection Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Collections.HTMLCollection κλάση. Η HTMLCollection αντιπροσωπεύει μια γενική συλλογή στοιχείων Element"
type: docs
weight: 2010
url: /el/net/aspose.svg.collections/htmlcollection/
---
## HTMLCollection class

Η `HTMLCollection` αντιπροσωπεύει μια γενική συλλογή του [`Element`](../../aspose.svg.dom/element/).

```csharp
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/htmlcollection/item/) { get; } | Επιστρέφει το στοιχείο με δείκτη index στην συλλογή. Εάν το index είναι μεγαλύτερο ή ίσο με τον αριθμό των κόμβων στη λίστα, επιστρέφει null. |
| abstract [Length](../../aspose.svg.collections/htmlcollection/length/) { get; } | Ο αριθμός των κόμβων στη λίστα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/htmlcollection/getenumerator/)() | Λαμβάνει τον απαριθμητή. |
| override [GetPlatformType](../../aspose.svg.collections/htmlcollection/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου αντικειμένου ECMAScript. |
| [NamedItem](../../aspose.svg.collections/htmlcollection/nameditem/)(*string*) | Επιστρέφει το στοιχείο στη συλλογή που ταιριάζει με το καθορισμένο όνομα. |

### Δείτε επίσης

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Element](../../aspose.svg.dom/element/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
