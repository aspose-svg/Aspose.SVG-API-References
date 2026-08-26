---
title: "IElementTraversal Διεπαφή"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Διεπαφή Aspose.Svg.Dom.Traversal.IElementTraversal. Η διεπαφή ElementTraversal είναι ένα σύνολο χαρακτηριστικών μόνο για ανάγνωση που επιτρέπουν σε έναν συγγραφέα να πλοηγείται εύκολα μεταξύ των στοιχείων σε ένα έγγραφο. Σε συμβατές υλοποιήσεις του Element Traversal, όλα τα αντικείμενα που υλοποιούν το Element πρέπει επίσης να υλοποιούν τη διεπαφή ElementTraversal."
type: docs
weight: 3230
url: /el/net/aspose.svg.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

Η διεπαφή ElementTraversal είναι ένα σύνολο χαρακτηριστικών μόνο για ανάγνωση που επιτρέπουν σε έναν δημιουργό να πλοηγείται εύκολα μεταξύ στοιχείων σε ένα έγγραφο. Σε συμμορφούμενες υλοποιήσεις του Element Traversal, όλα τα αντικείμενα που υλοποιούν το Element πρέπει επίσης να υλοποιούν τη διεπαφή ElementTraversal.

```csharp
public interface IElementTraversal
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom.traversal/ielementtraversal/childelementcount/) { get; } | Επιστρέφει τον τρέχοντα αριθμό κόμβων στοιχείων που είναι παιδιά αυτού του στοιχείου. 0 εάν αυτό το στοιχείο δεν έχει κόμβους παιδία που είναι τύπου nodeType 1. |
| [FirstElementChild](../../aspose.svg.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Επιστρέφει τον πρώτο κόμβο παιδικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδικά στοιχεία. |
| [LastElementChild](../../aspose.svg.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Επιστρέφει τον τελευταίο κόμβο στοιχείου παιδί αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδιά στοιχεία. |
| [NextElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Επιστρέφει τον επόμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς κόμβους στοιχείου που έρχονται μετά από αυτό στο δέντρο του εγγράφου. |
| [PreviousElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Επιστρέφει τον προηγούμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς κόμβους στοιχείου που έρχονται πριν από αυτό στο δέντρο του εγγράφου. |

### Δείτε επίσης

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
