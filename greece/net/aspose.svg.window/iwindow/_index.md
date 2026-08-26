---
title: "Διεπαφή IWindow"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Window.IWindow interface. Το αντικείμενο window αντιπροσωπεύει ένα παράθυρο που περιέχει ένα έγγραφο DOM"
type: docs
weight: 5920
url: /el/net/aspose.svg.window/iwindow/
---
## IWindow interface

Το αντικείμενο window αντιπροσωπεύει ένα παράθυρο που περιέχει ένα έγγραφο DOM.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | Το χαρακτηριστικό document πρέπει να επιστρέφει το πιο πρόσφατο αντικείμενο Document του αντικειμένου Window. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | Το αντικείμενο frameElement ενός Document. |
| [LocalStorage](../../aspose.svg.window/iwindow/localstorage/) { get; } | Επιστρέφει ένα αντικείμενο Storage που επιτρέπει την αποθήκευση ζευγών κλειδιού/τιμής στον πράκτορα χρήστη. |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | Το χαρακτηριστικό location της διεπαφής Window πρέπει να επιστρέφει το αντικείμενο Location για το Document του αντικειμένου Window. |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | Το χαρακτηριστικό name του αντικειμένου Window πρέπει, κατά την ανάγνωση, να επιστρέφει το τρέχον όνομα του περιβάλλοντος περιήγησης, και, κατά τη ρύθμιση, να ορίζει το όνομα του περιβάλλοντος περιήγησης στην νέα τιμή. |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | Το χαρακτηριστικό IDL opener στο αντικείμενο Window, κατά την ανάγνωση, πρέπει να επιστρέφει το αντικείμενο WindowProxy του περιβάλλοντος περιήγησης από το οποίο δημιουργήθηκε το τρέχον περιβάλλον περιήγησης (το περιβάλλον περιήγησης opener), εάν υπάρχει, εάν είναι ακόμη διαθέσιμο, και εάν το τρέχον περιβάλλον περιήγησης δεν έχει αποχωρήσει από το opener του· διαφορετικά, πρέπει να επιστρέφει null. Κατά τη ρύθμιση, εάν η νέα τιμή είναι null τότε το τρέχον περιβάλλον περιήγησης πρέπει να αποχωρήσει από το opener του· εάν η νέα τιμή είναι οτιδήποτε άλλο, τότε ο πράκτορας χρήστη πρέπει να καλέσει τη εσωτερική μέθοδο [[DefineOwnProperty]] του αντικειμένου Window, περνώντας το όνομα ιδιότητας \"opener\" ως κλειδί ιδιότητας, και τον Περιγραφέα Ιδιοτήτων { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } ως περιγραφέα ιδιότητας, όπου value είναι η νέα τιμή. |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | Το χαρακτηριστικό IDL parent στο αντικείμενο Window ενός Document σε ένα περιβάλλον περιήγησης b πρέπει να επιστρέφει το αντικείμενο WindowProxy του γονικού περιβάλλοντος περιήγησης, εάν υπάρχει (π.χ. εάν το b είναι παιδικό περιβάλλον περιήγησης), ή το αντικείμενο WindowProxy του ίδιου περιβάλλοντος περιήγησης b, διαφορετικά (π.χ. εάν είναι ένα ανώτερο επίπεδο περιβάλλοντος περιήγησης ή ένα αποσπασμένο ένθετο περιβάλλον περιήγησης). |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | Επιστρέφει το αντικείμενο WindowProxy του περιβάλλοντος περιήγησης του αντικειμένου Window. |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | Το χαρακτηριστικό IDL top στο αντικείμενο Window ενός Document σε ένα περιβάλλον περιήγησης b πρέπει να επιστρέφει το αντικείμενο WindowProxy του ανώτερου επιπέδου περιβάλλοντος περιήγησης (το οποίο θα ήταν το δικό του αντικείμενο WindowProxy εάν ήταν ανώτερο επίπεδο περιβάλλοντος περιήγησης), εάν υπάρχει, ή το δικό του αντικείμενο WindowProxy διαφορετικά (π.χ. εάν ήταν αποσπασμένο ένθετο περιβάλλον περιήγησης). |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | Επιστρέφει το αντικείμενο WindowProxy του περιβάλλοντος περιήγησης του αντικειμένου Window. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(*string*) | Εμφανίζει ένα modal alert με το δοσμένο μήνυμα και περιμένει ο χρήστης να το κλείσει. |
| [Atob](../../aspose.svg.window/iwindow/atob/)(*string*) | Λαμβάνει τα δεδομένα εισόδου, με τη μορφή μιας συμβολοσειράς Unicode που περιέχει δυαδικά δεδομένα κωδικοποιημένα σε base64, τα αποκωδικοποιεί και επιστρέφει μια συμβολοσειρά που αποτελείται από χαρακτήρες στο εύρος U+0000 έως U+00FF, ο καθένας από τους οποίους αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, που αντιστοιχεί σε αυτά τα δυαδικά δεδομένα. |
| [Btoa](../../aspose.svg.window/iwindow/btoa/)(*string*) | Δέχεται τα δεδομένα εισόδου, με τη μορφή μιας συμβολοσειράς Unicode που περιέχει μόνο χαρακτήρες στο εύρος U+0000 έως U+00FF, ο καθένας αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, και το μετατρέπει στην αναπαράσταση base64, την οποία επιστρέφει. |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(*string*) | Εμφανίζει ένα μοντέλο προτροπής OK/Cancel με το δεδομένο μήνυμα, περιμένει ο χρήστης να το κλείσει, και επιστρέφει true εάν ο χρήστης κάνει κλικ στο OK και false εάν κάνει κλικ στο Cancel. |
| [MatchMedia](../../aspose.svg.window/iwindow/matchmedia/)(*string*) | Επιστρέφει ένα νέο αντικείμενο MediaQueryList που μπορεί στη συνέχεια να χρησιμοποιηθεί για να προσδιορίσει εάν το έγγραφο ταιριάζει με τη συμβολοσειρά ερωτήματος μέσου, καθώς και για να παρακολουθεί το έγγραφο ώστε να εντοπίζει πότε ταιριάζει (ή σταματά να ταιριάζει) με αυτό το ερώτημα μέσου. Δείτε την προδιαγραφή του CSSOM View Module: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(*string, string*) | Εμφανίζει μια μοντέλο προτροπή πεδίου κειμένου με το δεδομένο μήνυμα, περιμένει ο χρήστης να το κλείσει, και επιστρέφει την τιμή που εισήγαγε ο χρήστης. Εάν ο χρήστης ακυρώσει την προτροπή, τότε επιστρέφει null. Εάν υπάρχει το δεύτερο όρισμα, τότε η δοθείσα τιμή χρησιμοποιείται ως προεπιλογή. |

### Δείτε επίσης

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
