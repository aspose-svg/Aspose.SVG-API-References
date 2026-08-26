---
title: "DocumentLoadErrorEvent Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Events.DocumentLoadErrorEvent κλάση. Το DocumentLoadErrorEvent συμβαίνει όταν ο ζητούμενος πόρος δεν είναι διαθέσιμος"
type: docs
weight: 2900
url: /el/net/aspose.svg.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

Το `DocumentLoadErrorEvent` συμβαίνει όταν ο ζητούμενος πόρος δεν είναι διαθέσιμος.

```csharp
public class DocumentLoadErrorEvent : ErrorEvent
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Χρησιμοποιείται για να υποδείξει αν ένα γεγονός είναι γεγονός φούσκωσης. Εάν το γεγονός μπορεί να φουσκώσει, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Χρησιμοποιείται για να υποδείξει αν ένα γεγονός μπορεί να αποτραπεί η προεπιλεγμένη του ενέργεια. Εάν η προεπιλεγμένη ενέργεια μπορεί να εμποδιστεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [ColNo](../../aspose.svg.dom.events/errorevent/colno/) { get; } | Το χαρακτηριστικό colno πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν το αντικείμενο δημιουργείται, αυτό το χαρακτηριστικό πρέπει να αρχικοποιηθεί στο μηδέν. Αντιπροσωπεύει τον αριθμό στήλης όπου συνέβη το σφάλμα στο script. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) του οποίου οι [`IEventListener`](../ieventlistener/)s επεξεργάζονται αυτή τη στιγμή. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη σύλληψη και τη φούσκωση. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Επιστρέφει true εάν κλήθηκε η preventDefault() ενώ η τιμή του χαρακτηριστικού cancelable είναι true, και false διαφορετικά. |
| [Error](../../aspose.svg.dom.events/errorevent/error/) { get; } | Το χαρακτηριστικό error πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται το αντικείμενο, αυτό το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε null. Όπου είναι κατάλληλο, ορίζεται στο αντικείμενο που αντιπροσωπεύει το σφάλμα (π.χ. το αντικείμενο εξαίρεσης σε περίπτωση μη πιασμένης εξαίρεσης DOM). |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Χρησιμοποιείται για να υποδείξει ποια φάση της ροής συμβάντων αξιολογείται αυτή τη στιγμή. |
| [FileName](../../aspose.svg.dom.events/errorevent/filename/) { get; } | Το χαρακτηριστικό filename πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται το αντικείμενο, αυτό το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε κενή συμβολοσειρά. Αντιπροσωπεύει το απόλυτο URL του script στο οποίο εμφανίστηκε αρχικά το σφάλμα. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Το χαρακτηριστικό isTrusted πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
| [LineNo](../../aspose.svg.dom.events/errorevent/lineno/) { get; } | Το χαρακτηριστικό lineno πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται το αντικείμενο, αυτό το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε μηδέν. Αντιπροσωπεύει τον αριθμό γραμμής όπου συνέβη το σφάλμα στο script. |
| [Message](../../aspose.svg.dom.events/errorevent/message/) { get; } | Το χαρακτηριστικό message πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται το αντικείμενο, αυτό το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε κενή συμβολοσειρά. Αντιπροσωπεύει το μήνυμα σφάλματος. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) στο οποίο αποστέλλεται αρχικά το συμβάν. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Χρησιμοποιείται για να καθορίσει τον χρόνο (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά τον οποίο δημιουργήθηκε το συμβάν. Λόγω του ότι ορισμένα συστήματα ενδέχεται να μην παρέχουν αυτήν την πληροφορία, η τιμή του timeStamp μπορεί να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη, επιστρέφεται τιμή 0. Παραδείγματα χρόνου εποχής είναι η ώρα εκκίνησης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι ένα όνομα XML. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Η μέθοδος [`InitEvent`](../event/initevent/) χρησιμοποιείται για την αρχικοποίηση της τιμής ενός [`Event`](../event/) που δημιουργείται μέσω της διεπαφής [`IDocumentEvent`](../idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Εάν ένα συμβάν είναι ακυρώσιμο, η μέθοδος [`PreventDefault`](../event/preventdefault/) χρησιμοποιείται για να υποδείξει ότι το συμβάν πρέπει να ακυρωθεί, πράγμα που σημαίνει ότι καμία προεπιλεγμένη ενέργεια που συνήθως εκτελείται από την υλοποίηση ως αποτέλεσμα του συμβάντος δεν θα συμβεί. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Η κλήση αυτής της μεθόδου εμποδίζει το συμβάν να φτάσει σε οποιονδήποτε ακροατή συμβάντων που είναι καταχωρημένος μετά τον τρέχοντα και, όταν αποστέλλεται σε δέντρο, εμποδίζει επίσης το συμβάν να φτάσει σε άλλα αντικείμενα. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Η μέθοδος [`StopPropagation`](../event/stoppropagation/) χρησιμοποιείται για την αποτροπή περαιτέρω διάδοσης ενός συμβάντος κατά τη ροή του συμβάντος. |

### Δείτε επίσης

* class [ErrorEvent](../errorevent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
