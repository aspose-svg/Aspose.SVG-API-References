---
title: "Διεπαφή IMediaList"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Διεπαφή Aspose.Svg.Dom.Css.IMediaList. Η διεπαφή MediaList παρέχει την αφαίρεση μιας διατεταγμένης συλλογής μέσων χωρίς να ορίζει ή να περιορίζει τον τρόπο υλοποίησης αυτής της συλλογής. Μια κενή λίστα είναι η ίδια με μια λίστα που περιέχει όλα τα μέσα."
type: docs
weight: 2730
url: /el/net/aspose.svg.dom.css/imedialist/
---
## IMediaList interface

Η διεπαφή MediaList παρέχει την αφηρημένη αναπαράσταση μιας ταξινομημένης συλλογής μέσων, χωρίς να ορίζει ή να περιορίζει τον τρόπο υλοποίησης αυτής της συλλογής. Μια κενή λίστα είναι η ίδια με μια λίστα που περιέχει το μέσο "all".

```csharp
public interface IMediaList : IEnumerable<string>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Item](../../aspose.svg.dom.css/imedialist/item/) { get; } | Επιστρέφει το στοιχείο με το δοσμένο δείκτη στη λίστα. Εάν ο δείκτης είναι μεγαλύτερος ή ίσος με τον αριθμό των μέσων στη λίστα, επιστρέφει null. Ο δείκτης μέσου. |
| [Length](../../aspose.svg.dom.css/imedialist/length/) { get; } | Ο αριθμός των μέσων στη λίστα. Το εύρος των έγκυρων μέσων είναι από 0 έως length-1, συμπεριλαμβανομένου. |
| [MediaText](../../aspose.svg.dom.css/imedialist/mediatext/) { get; } | Η αναγνώσιμη κειμενική αναπαράσταση της λίστας μέσων. Πρόκειται για λίστα μέσων διαχωρισμένη με κόμματα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AppendMedium](../../aspose.svg.dom.css/imedialist/appendmedium/)(*string*) | Προσθέτει το μέσο newMedium στο τέλος της λίστας. Εάν το newMedium χρησιμοποιείται ήδη, αφαιρείται πρώτα. |
| [DeleteMedium](../../aspose.svg.dom.css/imedialist/deletemedium/)(*string*) | Διαγράφει το μέσο που υποδεικνύεται από το oldMedium από τη λίστα. |

### Δείτε επίσης

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
