---
title: "Κλάση Location"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Κλάση Aspose.Svg.Window.Location. Τα αντικείμενα Location παρέχουν μια αναπαράσταση της διεύθυνσης του ενεργού εγγράφου του περιβάλλοντος περιήγησης των εγγράφων τους και επιτρέπουν την αλλαγή της τρέχουσας καταχώρισης του ιστορικού συνεδρίας του περιβάλλοντος περιήγησης προσθέτοντας ή αντικαθιστώντας καταχωρίσεις στο αντικείμενο ιστορικού."
type: docs
weight: 5950
url: /el/net/aspose.svg.window/location/
---
## Location class

Τα αντικείμενα Location παρέχουν μια αναπαράσταση της διεύθυνσης του ενεργού εγγράφου του περιβάλλοντος περιήγησης του Document τους, και επιτρέπουν την αλλαγή της τρέχουσας καταχώρισης του ιστορικού συνεδρίας του περιβάλλοντος περιήγησης, προσθέτοντας ή αντικαθιστώντας καταχωρίσεις στο αντικείμενο ιστορικού.

```csharp
public sealed class Location : DOMObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Hash](../../aspose.svg.window/location/hash/) { get; set; } | Επιστρέφει το τμήμα (fragment) του URL του αντικειμένου Location (περιλαμβάνει το αρχικό "#" εάν δεν είναι κενό). Μπορεί να οριστεί, για να μεταβεί στην ίδια URL με αλλαγμένο τμήμα (αγνοεί το αρχικό "#"). |
| [Host](../../aspose.svg.window/location/host/) { get; set; } | Επιστρέφει το Location object's URL's host and port (εάν είναι διαφορετικό από την προεπιλεγμένη θύρα για το σχήμα). Μπορεί να οριστεί, για να μεταβείτε στην ίδια URL με αλλαγμένο host και port. |
| [Hostname](../../aspose.svg.window/location/hostname/) { get; set; } | Επιστρέφει το Location object's URL's host. Μπορεί να οριστεί, για να μεταβείτε στην ίδια URL με αλλαγμένο host. |
| [Href](../../aspose.svg.window/location/href/) { get; set; } | Επιστρέφει το Location object's URL. Μπορεί να οριστεί, για να μεταβείτε στην καθορισμένη URL. |
| [Origin](../../aspose.svg.window/location/origin/) { get; } | Επιστρέφει το Location object's URL's origin. |
| [Pathname](../../aspose.svg.window/location/pathname/) { get; set; } | Επιστρέφει το Location object's URL's path. Μπορεί να οριστεί, για να μεταβείτε στην ίδια URL με αλλαγμένο path. |
| [Port](../../aspose.svg.window/location/port/) { get; set; } | Επιστρέφει το Location object's URL's port. Μπορεί να οριστεί, για να μεταβείτε στην ίδια URL με αλλαγμένο port. |
| [Protocol](../../aspose.svg.window/location/protocol/) { get; set; } | Επιστρέφει το Location object's URL's scheme. Μπορεί να οριστεί, για να μεταβείτε στην ίδια URL με αλλαγμένο scheme. |
| [Search](../../aspose.svg.window/location/search/) { get; set; } | Επιστρέφει το Location object's URL's query (περιλαμβάνει το αρχικό "?" εάν δεν είναι κενό). Μπορεί να οριστεί, για να μεταβείτε στην ίδια URL με αλλαγμένο query (αγνοεί το αρχικό "?"). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Assign](../../aspose.svg.window/location/assign/)(*string*) | Μεταβαίνει στη δοσμένη σελίδα. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [Reload](../../aspose.svg.window/location/reload/)() | Επαναφορτώνει την τρέχουσα σελίδα. |
| [Replace](../../aspose.svg.window/location/replace/)(*string*) | Αφαιρεί την τρέχουσα σελίδα από το ιστορικό συνεδρίας και μεταβαίνει στη δοσμένη σελίδα. |
| override [ToString](../../aspose.svg.window/location/tostring/)() | Επιστρέφει το Location object's URL. |

### Δείτε επίσης

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
