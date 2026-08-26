---
title: "INodeIterator Διεπαφή"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Διεπαφή Aspose.Svg.Dom.Traversal.INodeIterator. Οι επαναλήπτες χρησιμοποιούνται για την προσαρμογή μέσα σε ένα σύνολο κόμβων, π.χ. το σύνολο των κόμβων σε ένα NodeList, το υποδέντρο του εγγράφου που διέπεται από έναν συγκεκριμένο Node, τα αποτελέσματα ενός ερωτήματος ή οποιοδήποτε άλλο σύνολο κόμβων. Το σύνολο των κόμβων που θα επαναληφθεί καθορίζεται από την υλοποίηση του NodeIterator. Το DOM Level 2 ορίζει μια μοναδική υλοποίηση NodeIterator για περιήγηση με σειρά εγγράφου ενός υποδέντρου εγγράφου. Παραδείγματα αυτών των επαναληπτών δημιουργούνται με την κλήση του DocumentTraversal .createNodeIterator"
type: docs
weight: 3250
url: /el/net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

Οι επαναλήπτες χρησιμοποιούνται για να προχωρούν μέσα σε ένα σύνολο κόμβων, π.χ. το σύνολο κόμβων σε μια NodeList, το υποδέντρο του εγγράφου που διέπεται από έναν συγκεκριμένο Node, τα αποτελέσματα ενός ερωτήματος ή οποιοδήποτε άλλο σύνολο κόμβων. Το σύνολο των κόμβων που θα επαναληφθεί καθορίζεται από την υλοποίηση του NodeIterator. Το DOM Level 2 ορίζει μια μοναδική υλοποίηση NodeIterator για τη διέλευση κατά σειρά εγγράφου ενός υποδέντρου εγγράφου. Παραδείγματα αυτών των επαναληπτών δημιουργούνται καλώντας το DocumentTraversal .createNodeIterator().

Δείτε επίσης το [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | Η τιμή αυτού του σημαίας καθορίζει εάν τα παιδιά των κόμβων αναφοράς οντότητας είναι ορατά στον επαναλήπτη. Εάν είναι false, αυτά και τα απογόνους τους θα απορριφθούν. Σημειώστε ότι αυτή η απόρριψη έχει προτεραιότητα έναντι του whatToShow και του φίλτρου. Επίσης, σημειώστε ότι αυτή είναι επί του παρόντος η μόνη κατάσταση όπου οι NodeIterators μπορούν να απορρίψουν ολόκληρο ένα υποδέντρο αντί να παραλείπουν μεμονωμένους κόμβους. Για να δημιουργήσετε μια προβολή του εγγράφου που έχει επεκταμένες αναφορές οντότητας και δεν εκθέτει τον ίδιο τον κόμβο αναφοράς οντότητας, χρησιμοποιήστε τα flags whatToShow για να κρύψετε τον κόμβο αναφοράς οντότητας και ορίστε το expandEntityReferences σε true κατά τη δημιουργία του επαναλήπτη. Για να δημιουργήσετε μια προβολή του εγγράφου που έχει κόμβους αναφοράς οντότητας αλλά χωρίς επέκταση οντότητας, χρησιμοποιήστε τα flags whatToShow για να εμφανίσετε τον κόμβο αναφοράς οντότητας και ορίστε το expandEntityReferences σε false. |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode/) { get; } | Ο τρέχων κόμβος αναφοράς. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach/)() | Αποσυνδέει το NodeIterator από το σύνολο που επεξεργάστηκε, απελευθερώνοντας τυχόν υπολογιστικούς πόρους και τοποθετώντας τον επαναλήπτη στην κατάσταση INVALID. Μετά την κλήση του detach, οι κλήσεις σε nextNode ή previousNode θα προκαλέσουν την εξαίρεση INVALID_STATE_ERR. |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode/)() | Επιστρέφει τον επόμενο κόμβο στο σύνολο και προχωρά τη θέση του επαναλήπτη στο σύνολο. Μετά τη δημιουργία ενός NodeIterator, η πρώτη κλήση στο nextNode() επιστρέφει τον πρώτο κόμβο στο σύνολο. |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode/)() | Επιστρέφει τον προηγούμενο κόμβο στο σύνολο και μετακινεί τη θέση του NodeIterator προς τα πίσω στο σύνολο. |

### Δείτε επίσης

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
