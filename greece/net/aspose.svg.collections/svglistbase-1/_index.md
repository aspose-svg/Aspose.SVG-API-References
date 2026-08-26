---
title: "SVGListBaseT Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Collections.SVGListBase1T κλάση. Αυτό το interface ορίζει μια βασική λίστα όλων των λιστών SVG."
type: docs
weight: 2040
url: /el/net/aspose.svg.collections/svglistbase-1/
---
## SVGListBase<T> class

Αυτό το interface ορίζει μια βασική λίστα όλων των λιστών SVG.

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος του στοιχείου που αποθηκεύεται στη λίστα. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Item](../../aspose.svg.collections/svglistbase-1/item/) { get; set; } | Επιστρέφει το στοιχείο με δείκτη index στη λίστα. |
| [Length](../../aspose.svg.collections/svglistbase-1/length/) { get; } | Ο αριθμός των στοιχείων στη λίστα. |
| [NumberOfItems](../../aspose.svg.collections/svglistbase-1/numberofitems/) { get; } | Ο αριθμός των στοιχείων στη λίστα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AppendItem](../../aspose.svg.collections/svglistbase-1/appenditem/)(*T*) | Εισάγει ένα νέο στοιχείο στο τέλος της λίστας. |
| [Clear](../../aspose.svg.collections/svglistbase-1/clear/)() | Καθαρίζει όλα τα υπάρχοντα τρέχοντα στοιχεία από τη λίστα, με αποτέλεσμα μια κενή λίστα. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| [GetEnumerator](../../aspose.svg.collections/svglistbase-1/getenumerator/)() | Λαμβάνει τον απαριθμητή. |
| [GetItem](../../aspose.svg.collections/svglistbase-1/getitem/)(*ulong*) | Επιστρέφει το καθορισμένο στοιχείο από τη λίστα. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [Initialize](../../aspose.svg.collections/svglistbase-1/initialize/)(*T*) | Καθαρίζει όλα τα υπάρχοντα τρέχοντα στοιχεία από τη λίστα και επανεκκινεί τη λίστα ώστε να περιέχει το μοναδικό στοιχείο που καθορίζεται από την παράμετρο. |
| [InsertItemBefore](../../aspose.svg.collections/svglistbase-1/insertitembefore/)(*T, ulong*) | Εισάγει ένα νέο στοιχείο στη λίστα στη καθορισμένη θέση. Το πρώτο στοιχείο είναι ο αριθμός 0. |
| [RemoveItem](../../aspose.svg.collections/svglistbase-1/removeitem/)(*ulong*) | Αφαιρεί ένα υπάρχον στοιχείο από τη λίστα. |
| [ReplaceItem](../../aspose.svg.collections/svglistbase-1/replaceitem/)(*T, ulong*) | Αντικαθιστά ένα υπάρχον στοιχείο στη λίστα με ένα νέο στοιχείο. |

### Δείτε επίσης

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
