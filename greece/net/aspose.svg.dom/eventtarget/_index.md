---
title: "EventTarget Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.EventTarget κλάση. Η διεπαφή EventTarget υλοποιείται από όλους τους Node σε μια υλοποίηση που υποστηρίζει το μοντέλο συμβάντων DOM. Συνεπώς, αυτή η διεπαφή μπορεί να προκύψει χρησιμοποιώντας μεθόδους μετατροπής ειδικές για το binding σε μια παρουσία της διεπαφής Node. Η διεπαφή επιτρέπει την εγγραφή και την αφαίρεση των Event Listeners σε ένα EventTarget και την αποστολή συμβάντων προς αυτό το IEventTarget."
type: docs
weight: 2870
url: /el/net/aspose.svg.dom/eventtarget/
---
## EventTarget class

Η διεπαφή `EventTarget` υλοποιείται από όλους τους Node σε μια υλοποίηση που υποστηρίζει το μοντέλο συμβάντων DOM. Συνεπώς, αυτή η διεπαφή μπορεί να προκύψει χρησιμοποιώντας μεθόδους μετατροπής ειδικές για το binding σε μια παρουσία της διεπαφής Node. Η διεπαφή επιτρέπει την εγγραφή και την αφαίρεση των Event Listeners σε ένα `EventTarget` και την αποστολή συμβάντων προς το [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/).

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [EventTarget](eventtarget/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/#addeventlistener_2)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Αποστέλλει ένα Event στον καθορισμένο [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (συγχρόνως) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του φάσματος σύλληψης και της προαιρετικής φάσης φούσκας) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με το [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα `EventTarget` ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα `EventTarget` ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα `EventTarget` ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |

### Δείτε επίσης

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
