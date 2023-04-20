---
title: Class FocusEvent
second_title: Aspose.SVG για Αναφορά API .NET
description: Aspose.Svg.Dom.Events.FocusEvent τάξη. Η διεπαφή FocusEvent παρέχει συγκεκριμένες πληροφορίες σχετικά με τα συμφραζόμενα που σχετίζονται με συμβάντα εστίασης.
type: docs
weight: 930
url: /el/net/aspose.svg.dom.events/focusevent/
---
## FocusEvent class

Η διεπαφή FocusEvent παρέχει συγκεκριμένες πληροφορίες σχετικά με τα συμφραζόμενα που σχετίζονται με συμβάντα εστίασης.

```csharp
public class FocusEvent : UIEvent
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [FocusEvent](focusevent/#constructor)(string) | Αρχικοποιεί μια νέα παρουσία του`FocusEvent` τάξη. |
| [FocusEvent](focusevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Αρχικοποιεί μια νέα παρουσία του`FocusEvent` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν είναι ή όχι συμβάν με φυσαλίδες. Εάν το συμβάν μπορεί να σχηματίσει φυσαλίδες, η τιμή είναι true, διαφορετικά η τιμή είναι false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν μπορεί να αποτρέψει την προεπιλεγμένη δράση του. Εάν η προεπιλεγμένη ενέργεια μπορεί να αποτραπεί, η τιμή είναι true, διαφορετικά η τιμή είναι false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Χρησιμοποιείται για την ένδειξη του[`IEventTarget`](../ieventtarget/) του οποίου[`IEventListener`](../ieventlistener/) s βρίσκονται υπό επεξεργασία. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη λήψη και τη δημιουργία φυσαλίδων. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Επιστρέφει true εάν κλήθηκε το preventDefault() ενώ η τιμή του ακυρώσιμου χαρακτηριστικού είναι true και false διαφορετικά. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Καθορίζει ορισμένες λεπτομέρειες σχετικά με το συμβάν, ανάλογα με τον τύπο του συμβάντος. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Χρησιμοποιείται για να υποδείξει ποια φάση της ροής συμβάντος αξιολογείται αυτήν τη στιγμή. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Το χαρακτηριστικό isTrusted πρέπει να επιστρέψει την τιμή στην οποία είχε αρχικοποιηθεί. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
| [RelatedTarget](../../aspose.svg.dom.events/focusevent/relatedtarget/) { get; } | Χρησιμοποιείται για τον προσδιορισμό ενός δευτερεύοντος στόχου συμβάντος που σχετίζεται με ένα συμβάν εστίασης, ανάλογα με τον τύπο του συμβάντος. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Χρησιμοποιείται για την ένδειξη του[`IEventTarget`](../ieventtarget/) στο οποίο στάλθηκε αρχικά το συμβάν. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Χρησιμοποιείται για τον καθορισμό της ώρας (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά την οποία δημιουργήθηκε το συμβάν. Λόγω του γεγονότος ότι ορισμένα συστήματα ενδέχεται να μην παρέχουν αυτές τις πληροφορίες, η τιμή του timeStamp ενδέχεται να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη , θα επιστραφεί μια τιμή 0. Παραδείγματα χρόνου εποχής είναι η ώρα έναρξης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι όνομα XML. |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | Το χαρακτηριστικό view προσδιορίζει το παράθυρο από το οποίο δημιουργήθηκε το συμβάν. Η μη αρχικοποιημένη τιμή αυτού του χαρακτηριστικού ΠΡΕΠΕΙ να είναι null. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση αντικειμένου ECMAScriptType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | Το[`InitEvent`](../event/initevent/) Η μέθοδος χρησιμοποιείται για την προετοιμασία της τιμής του an[`Event`](../event/) δημιουργήθηκε μέσω του [`IDocumentEvent`](../idocumentevent/) διεπαφή. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Εάν ένα συμβάν μπορεί να ακυρωθεί, το[`PreventDefault`](../event/preventdefault/) Η μέθοδος χρησιμοποιείται για να υποδηλώσει ότι το συμβάν πρόκειται να ακυρωθεί, που σημαίνει ότι δεν θα πραγματοποιηθεί οποιαδήποτε προεπιλεγμένη ενέργεια που πραγματοποιείται συνήθως από την υλοποίηση ως αποτέλεσμα του συμβάντος. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Η επίκληση αυτής της μεθόδου αποτρέπει το συμβάν να φτάσει σε οποιονδήποτε ακροατή συμβάντος που έχει καταχωρηθεί μετά το τρέχον και όταν αποστέλλεται σε δέντρο επίσης εμποδίζει το συμβάν να φτάσει σε άλλα αντικείμενα. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Το[`StopPropagation`](../event/stoppropagation/) χρησιμοποιείται η μέθοδος αποτρέπει την περαιτέρω διάδοση ενός συμβάντος κατά τη ροή συμβάντων. |

### Δείτε επίσης

* class [UIEvent](../uievent/)
* χώρος ονομάτων [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* συνέλευση [Aspose.SVG](../../)


