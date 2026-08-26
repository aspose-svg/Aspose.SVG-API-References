---
title: "TypeInfo Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.TypeInfo κλάση. Το TypeInfo αντιπροσωπεύει έναν τύπο που αναφέρεται από κόμβους Element ή Attr που καθορίζονται στα σχήματα που συνδέονται με το έγγραφο."
type: docs
weight: 3280
url: /el/net/aspose.svg.dom/typeinfo/
---
## TypeInfo class

Η TypeInfo αντιπροσωπεύει έναν τύπο που αναφέρεται από κόμβους Element ή Attr, όπως ορίζεται στα σχήματα που σχετίζονται με το έγγραφο.

```csharp
public class TypeInfo : DOMObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [TypeName](../../aspose.svg.dom/typeinfo/typename/) { get; } | Το όνομα ενός τύπου που δηλώνεται για το σχετικό στοιχείο ή χαρακτηριστικό, ή null εάν είναι άγνωστο. |
| [TypeNamespace](../../aspose.svg.dom/typeinfo/typenamespace/) { get; } | Λαμβάνει το χώρο ονομάτων του τύπου. Ο χώρος ονομάτων του τύπου που δηλώνεται για το σχετικό στοιχείο ή χαρακτηριστικό ή null εάν το στοιχείο δεν έχει δήλωση ή εάν δεν υπάρχουν πληροφορίες χώρου ονομάτων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [IsDerivedFrom](../../aspose.svg.dom/typeinfo/isderivedfrom/)(*string, string, ulong*) | Αυτή η μέθοδος επιστρέφει εάν υπάρχει παράγωγος μεταξύ του ορισμού τύπου αναφοράς, δηλαδή του TypeInfo στο οποίο καλείται η μέθοδος, και του άλλου ορισμού τύπου, δηλαδή αυτού που περνιέται ως παράμετρος. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.svg.dom/typeinfo/derivation_extension/) | Εάν το σχήμα του εγγράφου είναι ένα XML Schema [XML Schema Part 1], αυτή η σταθερά αντιπροσωπεύει την παράγωγο με επέκταση. |
| const [DERIVATION_LIST](../../aspose.svg.dom/typeinfo/derivation_list/) | Εάν το σχήμα του εγγράφου είναι ένα XML Schema [XML Schema Part 1], αυτή η σταθερά αντιπροσωπεύει τη λίστα. |
| const [DERIVATION_RESTRICTION](../../aspose.svg.dom/typeinfo/derivation_restriction/) | Εάν το σχήμα του εγγράφου είναι ένα XML Schema [XML Schema Part 1], αυτή η σταθερά αντιπροσωπεύει την παράγωγο με περιορισμό εάν εμπλέκονται σύνθετοι τύποι, ή έναν περιορισμό εάν εμπλέκονται απλοί τύποι. |
| const [DERIVATION_UNION](../../aspose.svg.dom/typeinfo/derivation_union/) | Εάν το σχήμα του εγγράφου είναι ένα XML Schema [XML Schema Part 1], αυτή η σταθερά αντιπροσωπεύει την ένωση εάν εμπλέκονται απλοί τύποι. |

### Δείτε επίσης

* class [DOMObject](../domobject/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
