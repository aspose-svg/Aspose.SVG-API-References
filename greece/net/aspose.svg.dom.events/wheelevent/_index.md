---
title: "Κλάση WheelEvent"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Κλάση Aspose.Svg.Dom.Events.WheelEvent. Η διεπαφή WheelEvent παρέχει συγκεκριμένες συμφραζόμενες πληροφορίες που σχετίζονται με συμβάντα τροχού. Για να δημιουργήσετε μια παρουσία της διεπαφής WheelEvent, χρησιμοποιήστε τον κατασκευαστή WheelEvent περνώντας ένα προαιρετικό λεξικό WheelEventInit."
type: docs
weight: 3010
url: /el/net/aspose.svg.dom.events/wheelevent/
---
## WheelEvent class

Η διεπαφή WheelEvent παρέχει συγκεκριμένες πληροφορίες συμφραζομένων που σχετίζονται με γεγονότα τροχού. Για να δημιουργήσετε μια παρουσία της διεπαφής WheelEvent, χρησιμοποιήστε τον κατασκευαστή WheelEvent, περνώντας ένα προαιρετικό λεξικό WheelEventInit.

```csharp
public class WheelEvent : MouseEvent
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(*string*) | Αρχικοποιεί μια νέα παρουσία της κλάσης `WheelEvent`. |
| [WheelEvent](wheelevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Αρχικοποιεί μια νέα παρουσία της κλάσης `WheelEvent`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/mouseevent/altkey/) { get; } | Αναφερθείτε στο χαρακτηριστικό altKey. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Χρησιμοποιείται για να υποδείξει αν ένα γεγονός είναι γεγονός φούσκωσης. Εάν το γεγονός μπορεί να φουσκώσει, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [Button](../../aspose.svg.dom.events/mouseevent/button/) { get; } | Κατά τη διάρκεια των συμβάντων ποντικιού που προκαλούνται από την πίεση ή την απελευθέρωση ενός κουμπιού του ποντικιού, το πεδίο button ΠΡΕΠΕΙ να χρησιμοποιείται για να υποδεικνύει ποιο κουμπί της συσκευής δείκτη άλλαξε κατάσταση. |
| [Buttons](../../aspose.svg.dom.events/mouseevent/buttons/) { get; } | Κατά τη διάρκεια οποιωνδήποτε συμβάντων ποντικιού, το πεδίο buttons ΠΡΕΠΕΙ να χρησιμοποιείται για να υποδεικνύει ποιος συνδυασμός κουμπιών ποντικιού είναι αυτή τη στιγμή πατημένος, εκφρασμένος ως bitmask. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Χρησιμοποιείται για να υποδείξει αν ένα γεγονός μπορεί να αποτραπεί η προεπιλεγμένη του ενέργεια. Εάν η προεπιλεγμένη ενέργεια μπορεί να εμποδιστεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [ClientX](../../aspose.svg.dom.events/mouseevent/clientx/) { get; } | Η οριζόντια συντεταγμένη στην οποία συνέβη το γεγονός σε σχέση με το παράθυρο προβολής που σχετίζεται με το γεγονός. |
| [ClientY](../../aspose.svg.dom.events/mouseevent/clienty/) { get; } | Η κάθετη συντεταγμένη στην οποία συνέβη το γεγονός σε σχέση με το παράθυρο προβολής που σχετίζεται με το γεγονός. |
| [CtrlKey](../../aspose.svg.dom.events/mouseevent/ctrlkey/) { get; } | Αναφερθείτε στο χαρακτηριστικό ctrlKey. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) του οποίου οι [`IEventListener`](../ieventlistener/)s επεξεργάζονται αυτή τη στιγμή. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη σύλληψη και τη φούσκωση. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Επιστρέφει true εάν κλήθηκε η preventDefault() ενώ η τιμή του χαρακτηριστικού cancelable είναι true, και false διαφορετικά. |
| [DeltaMode](../../aspose.svg.dom.events/wheelevent/deltamode/) { get; } | Η ιδιότητα deltaMode περιέχει μια ένδειξη των μονάδων μέτρησης για τις τιμές delta. Η προεπιλεγμένη τιμή είναι DOM_DELTA_PIXEL (pixels). |
| [DeltaX](../../aspose.svg.dom.events/wheelevent/deltax/) { get; } | Σε προγράμματα περιήγησης όπου η προεπιλεγμένη ενέργεια του γεγονότος wheel είναι η κύλιση, η τιμή MUST να είναι η μέτρηση κατά τον άξονα x (in pixels, lines, or pages) που θα κυλιστεί στην περίπτωση που το γεγονός δεν ακυρωθεί. Διαφορετικά, αυτή είναι μια υλοποιήση-συγκεκριμένη μέτρηση (in pixels, lines, or pages) της κίνησης μιας συσκευής τροχού γύρω από τον άξονα x. |
| [DeltaY](../../aspose.svg.dom.events/wheelevent/deltay/) { get; } | Σε προγράμματα περιήγησης όπου η προεπιλεγμένη ενέργεια του γεγονότος wheel είναι η κύλιση, η τιμή MUST να είναι η μέτρηση κατά τον άξονα y (in pixels, lines, or pages) που θα κυλιστεί στην περίπτωση που το γεγονός δεν ακυρωθεί. Διαφορετικά, αυτή είναι μια υλοποιήση-συγκεκριμένη μέτρηση (in pixels, lines, or pages) της κίνησης μιας συσκευής τροχού γύρω από τον άξονα y. |
| [DeltaZ](../../aspose.svg.dom.events/wheelevent/deltaz/) { get; } | Σε προγράμματα περιήγησης όπου η προεπιλεγμένη ενέργεια του γεγονότος wheel είναι η κύλιση, η τιμή MUST να είναι η μέτρηση κατά τον άξονα z (in pixels, lines, or pages) που θα κυλιστεί στην περίπτωση που το γεγονός δεν ακυρωθεί. Διαφορετικά, αυτή είναι μια υλοποιήση-συγκεκριμένη μέτρηση (in pixels, lines, or pages) της κίνησης μιας συσκευής τροχού γύρω από τον άξονα z. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Καθορίζει κάποιες λεπτομερείς πληροφορίες σχετικά με το Event, ανάλογα με τον τύπο του συμβάντος. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Χρησιμοποιείται για να υποδείξει ποια φάση της ροής συμβάντων αξιολογείται αυτή τη στιγμή. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Το χαρακτηριστικό isTrusted πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
| [MetaKey](../../aspose.svg.dom.events/mouseevent/metakey/) { get; } | Αναφερθείτε στο χαρακτηριστικό metaKey. |
| [RelatedTarget](../../aspose.svg.dom.events/mouseevent/relatedtarget/) { get; } | Χρησιμοποιείται για την ταυτοποίηση ενός δευτερεύοντος EventTarget που σχετίζεται με ένα συμβάν UI, ανάλογα με τον τύπο του συμβάντος. |
| [ScreenX](../../aspose.svg.dom.events/mouseevent/screenx/) { get; } | Η οριζόντια συντεταγμένη στην οποία συνέβη το γεγονός σε σχέση με το αρχικό σημείο του συστήματος συντεταγμένων της οθόνης. |
| [ScreenY](../../aspose.svg.dom.events/mouseevent/screeny/) { get; } | Η κάθετη συντεταγμένη στην οποία συνέβη το γεγονός σε σχέση με το αρχικό σημείο του συστήματος συντεταγμένων της οθόνης. |
| [ShiftKey](../../aspose.svg.dom.events/mouseevent/shiftkey/) { get; } | Αναφερθείτε στο χαρακτηριστικό shiftKey. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) στο οποίο αποστέλλεται αρχικά το συμβάν. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Χρησιμοποιείται για να καθορίσει τον χρόνο (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά τον οποίο δημιουργήθηκε το συμβάν. Λόγω του ότι ορισμένα συστήματα ενδέχεται να μην παρέχουν αυτήν την πληροφορία, η τιμή του timeStamp μπορεί να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη, επιστρέφεται τιμή 0. Παραδείγματα χρόνου εποχής είναι η ώρα εκκίνησης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι ένα όνομα XML. |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | Το χαρακτηριστικό view προσδιορίζει το Window από το οποίο δημιουργήθηκε το γεγονός. Η μη αρχικοποιημένη τιμή αυτού του χαρακτηριστικού ΠΡΕΠΕΙ να είναι null. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Η μέθοδος [`InitEvent`](../event/initevent/) χρησιμοποιείται για την αρχικοποίηση της τιμής ενός [`Event`](../event/) που δημιουργείται μέσω της διεπαφής [`IDocumentEvent`](../idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Εάν ένα συμβάν είναι ακυρώσιμο, η μέθοδος [`PreventDefault`](../event/preventdefault/) χρησιμοποιείται για να υποδείξει ότι το συμβάν πρέπει να ακυρωθεί, πράγμα που σημαίνει ότι καμία προεπιλεγμένη ενέργεια που συνήθως εκτελείται από την υλοποίηση ως αποτέλεσμα του συμβάντος δεν θα συμβεί. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Η κλήση αυτής της μεθόδου εμποδίζει το συμβάν να φτάσει σε οποιονδήποτε ακροατή συμβάντων που είναι καταχωρημένος μετά τον τρέχοντα και, όταν αποστέλλεται σε δέντρο, εμποδίζει επίσης το συμβάν να φτάσει σε άλλα αντικείμενα. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Η μέθοδος [`StopPropagation`](../event/stoppropagation/) χρησιμοποιείται για την αποτροπή περαιτέρω διάδοσης ενός συμβάντος κατά τη ροή του συμβάντος. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [DOM_DELTA_LINE](../../aspose.svg.dom.events/wheelevent/dom_delta_line/) | Οι μονάδες μέτρησης για το delta MUST να είναι μεμονωμένες γραμμές κειμένου. Αυτό ισχύει για πολλά στοιχεία φόρμας. |
| const [DOM_DELTA_PAGE](../../aspose.svg.dom.events/wheelevent/dom_delta_page/) | Οι μονάδες μέτρησης για το delta MUST να είναι σελίδες, είτε ορισμένες ως μία ενιαία οθόνη είτε ως μια διαχωρισμένη σελίδα. |
| const [DOM_DELTA_PIXEL](../../aspose.svg.dom.events/wheelevent/dom_delta_pixel/) | Οι μονάδες μέτρησης για το delta MUST να είναι pixels. Αυτή είναι η πιο συνηθισμένη περίπτωση στα περισσότερα λειτουργικά συστήματα και ρυθμίσεις υλοποίησης. |

### Δείτε επίσης

* class [MouseEvent](../mouseevent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
