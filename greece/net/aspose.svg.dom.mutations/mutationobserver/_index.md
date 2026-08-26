---
title: "MutationObserver Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Mutations.MutationObserver κλάση. Ένα αντικείμενο MutationObserver μπορεί να χρησιμοποιηθεί για την παρακολούθηση μεταβολών στο δέντρο του Node."
type: docs
weight: 3110
url: /el/net/aspose.svg.dom.mutations/mutationobserver/
---
## MutationObserver class

Ένα αντικείμενο `MutationObserver` μπορεί να χρησιμοποιηθεί για την παρακολούθηση μεταβολών στο δέντρο του [`Node`](../../aspose.svg.dom/node/).

```csharp
public class MutationObserver : DOMObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MutationObserver](mutationobserver/)(*[MutationCallback](../mutationcallback/)*) | Δημιουργεί ένα αντικείμενο MutationObserver και ορίζει το [`MutationCallback`](../mutationcallback/) του σε callback. Το callback καλείται με μια λίστα αντικειμένων MutationRecord ως πρώτο όρισμα και το κατασκευασμένο αντικείμενο MutationObserver ως δεύτερο όρισμα. Καλείται μετά από μεταβολή των κόμβων που έχουν εγγραφεί με τη μέθοδο [`Observe`](./observe/). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Disconnect](../../aspose.svg.dom.mutations/mutationobserver/disconnect/)() | Σταματά το observer από το να παρακολουθεί οποιεσδήποτε μεταβολές. Μέχρι να χρησιμοποιηθεί ξανά η μέθοδος observe(), το callback του observer δεν θα κληθεί. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe)(*[Node](../../aspose.svg.dom/node/)*) | Οδηγεί τον user agent να παρακολουθεί έναν συγκεκριμένο στόχο (ένα node) και να αναφέρει τυχόν μεταβολές βάσει των κριτηρίων που δίνονται από τις options (ένα αντικείμενο). Το όρισμα options επιτρέπει τον ορισμό επιλογών παρακολούθησης μεταβολών μέσω των μελών του αντικειμένου. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe_1)(*[Node](../../aspose.svg.dom/node/), [MutationObserverInit](../mutationobserverinit/)*) | Οδηγεί τον user agent να παρακολουθεί έναν συγκεκριμένο στόχο (ένα node) και να αναφέρει τυχόν μεταβολές βάσει των κριτηρίων που δίνονται από τις options (ένα αντικείμενο). Το όρισμα options επιτρέπει τον ορισμό επιλογών παρακολούθησης μεταβολών μέσω των μελών του αντικειμένου. |
| [TakeRecords](../../aspose.svg.dom.mutations/mutationobserver/takerecords/)() | Η μέθοδος επιστρέφει ένα αντίγραφο της ουράς εγγραφών και στη συνέχεια αδειάζει την ουρά εγγραφών. |

### Δείτε επίσης

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
