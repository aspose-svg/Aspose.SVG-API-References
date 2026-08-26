---
title: "Κλάση InputEvent"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Κλάση Aspose.Svg.Dom.Events.InputEvent. Τα input events αποστέλλονται ως ειδοποιήσεις κάθε φορά που το DOM ενημερώνεται"
type: docs
weight: 2970
url: /el/net/aspose.svg.dom.events/inputevent/
---
## InputEvent class

Τα γεγονότα εισόδου αποστέλλονται ως ειδοποιήσεις όποτε ενημερώνεται το DOM.

```csharp
public class InputEvent : UIEvent
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [InputEvent](inputevent/#constructor)(*string*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `InputEvent`. |
| [InputEvent](inputevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `InputEvent`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Χρησιμοποιείται για να υποδείξει αν ένα γεγονός είναι γεγονός φούσκωσης. Εάν το γεγονός μπορεί να φουσκώσει, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Χρησιμοποιείται για να υποδείξει αν ένα γεγονός μπορεί να αποτραπεί η προεπιλεγμένη του ενέργεια. Εάν η προεπιλεγμένη ενέργεια μπορεί να εμποδιστεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) του οποίου οι [`IEventListener`](../ieventlistener/)s επεξεργάζονται αυτή τη στιγμή. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη σύλληψη και τη φούσκωση. |
| [Data](../../aspose.svg.dom.events/inputevent/data/) { get; } | Τα δεδομένα περιέχουν την τιμή των χαρακτήρων που παράγονται από μια μέθοδο εισόδου. Αυτό ΜΠΟΡΕΙ να είναι ένας μοναδικός χαρακτήρας Unicode ή μια μη κενή ακολουθία χαρακτήρων Unicode [Unicode]. Οι χαρακτήρες ΠΡΕΠΕΙ να είναι κανονικοποιημένοι σύμφωνα με τη μορφή κανονικοποίησης Unicode NFC, όπως ορίζεται στο [UAX15]. Αυτό το χαρακτηριστικό ΜΠΟΡΕΙ να περιέχει το κενό string. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Επιστρέφει true εάν κλήθηκε η preventDefault() ενώ η τιμή του χαρακτηριστικού cancelable είναι true, και false διαφορετικά. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Καθορίζει κάποιες λεπτομερείς πληροφορίες σχετικά με το Event, ανάλογα με τον τύπο του συμβάντος. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Χρησιμοποιείται για να υποδείξει ποια φάση της ροής συμβάντων αξιολογείται αυτή τη στιγμή. |
| [IsComposing](../../aspose.svg.dom.events/inputevent/iscomposing/) { get; } | αληθές εάν το input event συμβαίνει ως μέρος μιας συνεδρίας σύνθεσης, δηλαδή μετά από ένα compositionstart event και πριν από το αντίστοιχο compositionend event. Η μη αρχικοποιημένη τιμή αυτού του χαρακτηριστικού ΠΡΕΠΕΙ να είναι ψευδής. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Το χαρακτηριστικό isTrusted πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
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

### Δείτε επίσης

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
