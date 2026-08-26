---
title: "Κλάση Event"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Κλάση Aspose.Svg.Dom.Events.Event. Το Event χρησιμοποιείται για την παροχή πληροφοριών περιεχομένου σχετικά με ένα event στον χειριστή που επεξεργάζεται το event"
type: docs
weight: 2920
url: /el/net/aspose.svg.dom.events/event/
---
## Event class

Το `Event` χρησιμοποιείται για την παροχή πληροφοριών περιεχομένου σχετικά με ένα event στον χειριστή που επεξεργάζεται το event.

```csharp
public class Event : DOMObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Event](event/#constructor)(*string*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `Event`. |
| [Event](event/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `Event`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Χρησιμοποιείται για να υποδείξει αν ένα γεγονός είναι γεγονός φούσκωσης. Εάν το γεγονός μπορεί να φουσκώσει, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Χρησιμοποιείται για να υποδείξει αν ένα γεγονός μπορεί να αποτραπεί η προεπιλεγμένη του ενέργεια. Εάν η προεπιλεγμένη ενέργεια μπορεί να εμποδιστεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) του οποίου οι [`IEventListener`](../ieventlistener/)s επεξεργάζονται αυτή τη στιγμή. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη σύλληψη και τη φούσκωση. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Επιστρέφει true εάν κλήθηκε η preventDefault() ενώ η τιμή του χαρακτηριστικού cancelable είναι true, και false διαφορετικά. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Χρησιμοποιείται για να υποδείξει ποια φάση της ροής συμβάντων αξιολογείται αυτή τη στιγμή. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Το χαρακτηριστικό isTrusted πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) στο οποίο αποστέλλεται αρχικά το συμβάν. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Χρησιμοποιείται για να καθορίσει τον χρόνο (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά τον οποίο δημιουργήθηκε το συμβάν. Λόγω του ότι ορισμένα συστήματα ενδέχεται να μην παρέχουν αυτήν την πληροφορία, η τιμή του timeStamp μπορεί να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη, επιστρέφεται τιμή 0. Παραδείγματα χρόνου εποχής είναι η ώρα εκκίνησης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι ένα όνομα XML. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | Η μέθοδος [`InitEvent`](./initevent/) χρησιμοποιείται για την αρχικοποίηση της τιμής ενός `Event` που δημιουργείται μέσω του interface [`IDocumentEvent`](../idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Εάν ένα event είναι ακυρώσιμο, η μέθοδος [`PreventDefault`](./preventdefault/) χρησιμοποιείται για να υποδείξει ότι το event πρέπει να ακυρωθεί, πράγμα που σημαίνει ότι οποιαδήποτε προεπιλεγμένη ενέργεια που συνήθως λαμβάνει η υλοποίηση ως αποτέλεσμα του event δεν θα συμβεί. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Η κλήση αυτής της μεθόδου εμποδίζει το συμβάν να φτάσει σε οποιονδήποτε ακροατή συμβάντων που είναι καταχωρημένος μετά τον τρέχοντα και, όταν αποστέλλεται σε δέντρο, εμποδίζει επίσης το συμβάν να φτάσει σε άλλα αντικείμενα. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Η μέθοδος [`StopPropagation`](./stoppropagation/) χρησιμοποιείται για την αποτροπή περαιτέρω διάδοσης ενός event κατά τη ροή του event. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [AtTargetPhase](../../aspose.svg.dom.events/event/attargetphase/) | Η τρέχουσα φάση του event είναι η φάση σύλληψης. |
| const [BubblingPhase](../../aspose.svg.dom.events/event/bubblingphase/) | Η τρέχουσα φάση του event είναι η φάση φυσαλίδωσης. |
| const [CapturingPhase](../../aspose.svg.dom.events/event/capturingphase/) | Το event αξιολογείται επί του παρόντος στον στόχο [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../aspose.svg.dom.events/event/nonephase/) | Τα events που δεν έχουν αποσταλεί επί του παρόντος βρίσκονται σε αυτή τη φάση. |

## Παρατηρήσεις

Ένα αντικείμενο που υλοποιεί το `Event` γενικά περνιέται ως η πρώτη παράμετρος σε έναν χειριστή event. Πιο συγκεκριμένες πληροφορίες περιεχομένου περνιούνται στους χειριστές event μέσω της κληρονομίας πρόσθετων interfaces από το `Event`, τα οποία περιέχουν πληροφορίες που σχετίζονται άμεσα με τον τύπο του event που συνοδεύουν. Αυτά τα παράγωγα interfaces υλοποιούνται επίσης από το αντικείμενο που περνιέται στον ακροατή του event.

### Δείτε επίσης

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
