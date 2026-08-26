---
title: "Κλάση MediaQueryList"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Κλάση Aspose.Svg.Window.MediaQueryList. Ένα αντικείμενο MediaQueryList αποθηκεύει πληροφορίες σχετικά με ένα ερώτημα μέσου που εφαρμόζεται σε ένα έγγραφο, με υποστήριξη τόσο άμεσης όσο και συμβάν-κατευθυνόμενης αντιστοίχισης με την κατάσταση του εγγράφου. Δείτε την προδιαγραφή του CSSOM View Module https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /el/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

Ένα αντικείμενο MediaQueryList αποθηκεύει πληροφορίες σχετικά με ένα ερώτημα μέσου που εφαρμόζεται σε ένα έγγραφο, με υποστήριξη τόσο άμεσης όσο και βασισμένης σε γεγονότα αντιστοίχισης με την κατάσταση του εγγράφου. Δείτε την προδιαγραφή του CSSOM View Module: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Το έγγραφο που σχετίζεται με το αντικείμενο Context. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | Μια λογική τιμή που επιστρέφει true εάν το έγγραφο τρέχοντα ταιριάζει με τη λίστα ερωτημάτων μέσου, ή false εάν όχι. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | Ένα string που αντιπροσωπεύει ένα σειριοποιημένο ερώτημα μέσου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Προσθήκη ακροατή συμβάντος αλλαγής κατάστασης αντιστοίχισης MediaQueryList. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Αποστέλλει ένα Event στον καθορισμένο [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (συγχρόνως) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του φάσματος σύλληψης και της προαιρετικής φάσης φούσκας) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με το [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση ακροατών συμβάντων από τον στόχο του συμβάντος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../../aspose.svg.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση ακροατών συμβάντων από τον στόχο του συμβάντος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../../aspose.svg.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση ακροατών συμβάντων από τον στόχο του συμβάντος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../../aspose.svg.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Αφαίρεση ακροατή συμβάντος αλλαγής κατάστασης αντιστοίχισης MediaQueryList. |

## Συμβάντα

| Όνομα | Περιγραφή |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | Συμβάν που εκτελείται στο MediaQueryList όταν η κατάσταση αντιστοίχισης αλλάζει. |

### Δείτε επίσης

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
