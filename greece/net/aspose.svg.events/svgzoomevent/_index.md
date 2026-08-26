---
title: "Κλάση SVGZoomEvent"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Κλάση Aspose.Svg.Events.SVGZoomEvent. Το γεγονός ζουμ συμβαίνει όταν ο χρήστης εκκινεί μια ενέργεια που προκαλεί την επανακλίμακα της τρέχουσας προβολής του τμήματος του εγγράφου SVG. Οι χειριστές γεγονότων αναγνωρίζονται μόνο σε στοιχεία svg."
type: docs
weight: 3710
url: /el/net/aspose.svg.events/svgzoomevent/
---
## SVGZoomEvent class

Το γεγονός ζουμ συμβαίνει όταν ο χρήστης εκκινεί μια ενέργεια που προκαλεί την επανακλίμακα της τρέχουσας προβολής του τμήματος του εγγράφου SVG. Οι διαχειριστές γεγονότων αναγνωρίζονται μόνο στα στοιχεία ‘svg’.

```csharp
public class SVGZoomEvent : Event
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Χρησιμοποιείται για να υποδείξει αν ένα γεγονός είναι γεγονός φούσκωσης. Εάν το γεγονός μπορεί να φουσκώσει, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Χρησιμοποιείται για να υποδείξει αν ένα γεγονός μπορεί να αποτραπεί η προεπιλεγμένη του ενέργεια. Εάν η προεπιλεγμένη ενέργεια μπορεί να εμποδιστεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) του οποίου οι [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)s επεξεργάζονται επί του παρόντος. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη διάρκεια του capture και του bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Επιστρέφει true εάν κλήθηκε η preventDefault() ενώ η τιμή του χαρακτηριστικού cancelable είναι true, και false διαφορετικά. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Χρησιμοποιείται για να υποδείξει ποια φάση της ροής συμβάντων αξιολογείται αυτή τη στιγμή. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Το χαρακτηριστικό isTrusted πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
| [NewScale](../../aspose.svg.events/svgzoomevent/newscale/) { get; } | Ο συντελεστής κλίμακας που θα ισχύει μετά την επεξεργασία της λειτουργίας ζουμ. |
| [NewTranslate](../../aspose.svg.events/svgzoomevent/newtranslate/) { get; } | Οι τιμές μετάφρασης που θα ισχύουν μετά την επεξεργασία της λειτουργίας ζουμ. Το αντικείμενο SVGPoint είναι μόνο για ανάγνωση. |
| [PreviousScale](../../aspose.svg.events/svgzoomevent/previousscale/) { get; } | Ο συντελεστής κλίμακας από προηγούμενες λειτουργίες ζουμ που ήταν σε ισχύ πριν συμβεί η τρέχουσα λειτουργία ζουμ. |
| [PreviousTranslate](../../aspose.svg.events/svgzoomevent/previoustranslate/) { get; } | Οι τιμές μετάφρασης από προηγούμενες λειτουργίες ζουμ που ήταν σε ισχύ πριν συμβεί η τρέχουσα λειτουργία ζουμ. Το αντικείμενο SVGPoint είναι μόνο για ανάγνωση. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) στο οποίο το γεγονός αποστέλλεται αρχικά. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Χρησιμοποιείται για να καθορίσει τον χρόνο (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά τον οποίο δημιουργήθηκε το συμβάν. Λόγω του ότι ορισμένα συστήματα ενδέχεται να μην παρέχουν αυτήν την πληροφορία, η τιμή του timeStamp μπορεί να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη, επιστρέφεται τιμή 0. Παραδείγματα χρόνου εποχής είναι η ώρα εκκίνησης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι ένα όνομα XML. |
| [ZoomRectScreen](../../aspose.svg.events/svgzoomevent/zoomrectscreen/) { get; } | Το καθορισμένο ορθογώνιο ζουμ σε μονάδες οθόνης. Το αντικείμενο SVGRect είναι μόνο για ανάγνωση. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Η μέθοδος [`InitEvent`](../../aspose.svg.dom.events/event/initevent/) χρησιμοποιείται για την αρχικοποίηση της τιμής ενός [`Event`](../../aspose.svg.dom.events/event/) που δημιουργείται μέσω της διεπαφής [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Εάν ένα γεγονός είναι ακυρώσιμο, η μέθοδος [`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/) χρησιμοποιείται για να υποδείξει ότι το γεγονός θα ακυρωθεί, πράγμα που σημαίνει ότι οποιαδήποτε προεπιλεγμένη ενέργεια που συνήθως εκτελείται από την υλοποίηση ως αποτέλεσμα του γεγονότος δεν θα συμβεί. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Η κλήση αυτής της μεθόδου εμποδίζει το συμβάν να φτάσει σε οποιονδήποτε ακροατή συμβάντων που είναι καταχωρημένος μετά τον τρέχοντα και, όταν αποστέλλεται σε δέντρο, εμποδίζει επίσης το συμβάν να φτάσει σε άλλα αντικείμενα. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Η μέθοδος [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/) χρησιμοποιείται για την αποτροπή περαιτέρω διάδοσης ενός γεγονότος κατά τη ροή του γεγονότος. |

### Δείτε επίσης

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
