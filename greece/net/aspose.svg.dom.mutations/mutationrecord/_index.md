---
title: "MutationRecord Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Mutations.MutationRecord κλάση. Ένα MutationRecord αντιπροσωπεύει μια μεμονωμένη μεταβολή DOM. Είναι το αντικείμενο που περνιέται στο MutationObservers MutationCallback"
type: docs
weight: 3130
url: /el/net/aspose.svg.dom.mutations/mutationrecord/
---
## MutationRecord class

Ένα MutationRecord αντιπροσωπεύει μια μεμονωμένη μεταβολή DOM. Είναι το αντικείμενο που περνιέται στο [`MutationObserver`](../mutationobserver/) του [`MutationCallback`](../mutationcallback/).

```csharp
public class MutationRecord : DOMObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AddedNodes](../../aspose.svg.dom.mutations/mutationrecord/addednodes/) { get; } | Επιστρέψτε τους προστιθέμενους κόμβους. |
| [AttributeName](../../aspose.svg.dom.mutations/mutationrecord/attributename/) { get; } | Επιστρέφει το τοπικό όνομα του τροποποιημένου χαρακτηριστικού, και null διαφορετικά. |
| [AttributeNamespace](../../aspose.svg.dom.mutations/mutationrecord/attributenamespace/) { get; } | Επιστρέφει το namespace του τροποποιημένου χαρακτηριστικού, και null διαφορετικά. |
| [NextSibling](../../aspose.svg.dom.mutations/mutationrecord/nextsibling/) { get; } | Επιστρέψτε τον επόμενο αδερφό των προστιθέμενων ή αφαιρεθέντων κόμβων, ή null. |
| [OldValue](../../aspose.svg.dom.mutations/mutationrecord/oldvalue/) { get; } | Η τιμή επιστροφής εξαρτάται από τον τύπο. Για \"attributes\", είναι η τιμή του τροποποιημένου χαρακτηριστικού πριν την αλλαγή. Για \"characterData\", είναι τα δεδομένα του τροποποιημένου κόμβου πριν την αλλαγή. Για \"childList\", είναι null. |
| [PreviousSibling](../../aspose.svg.dom.mutations/mutationrecord/previoussibling/) { get; } | Επιστρέφει τον προηγούμενο αδερφό των προστιθέμενων ή αφαιρεθέντων κόμβων, ή null. |
| [RemovedNodes](../../aspose.svg.dom.mutations/mutationrecord/removednodes/) { get; } | Επιστρέψτε τους αφαιρεθέντες κόμβους. |
| [Target](../../aspose.svg.dom.mutations/mutationrecord/target/) { get; } | Επιστρέφει τον κόμβο που επηρεάστηκε από τη μεταβολή, ανάλογα με τον τύπο. Για \"attributes\", είναι το στοιχείο του οποίου το χαρακτηριστικό άλλαξε. Για \"characterData\", είναι ο κόμβος CharacterData. Για \"childList\", είναι ο κόμβος του οποίου τα παιδιά άλλαξαν. |
| [Type](../../aspose.svg.dom.mutations/mutationrecord/type/) { get; } | Επιστρέφει \"attributes\" αν ήταν μεταβολή χαρακτηριστικού, \"characterData\" αν ήταν μεταβολή σε κόμβο CharacterData και \"childList\" αν ήταν μεταβολή στο δέντρο των κόμβων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |

### Δείτε επίσης

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
