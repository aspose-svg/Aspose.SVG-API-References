---
title: Interface ITreeWalker
second_title: Aspose.SVG για Αναφορά API .NET
description: Aspose.Svg.Dom.Traversal.ITreeWalker διεπαφή. Τα αντικείμενα TreeWalker χρησιμοποιούνται για την πλοήγηση σε ένα δέντρο εγγράφου ή σε ένα υποδέντρο χρησιμοποιώντας την προβολή του εγγράφου που ορίζεται από τις σημαίες και το φίλτρο whatToShow αν υπάρχει. Οποιαδήποτε συνάρτηση που εκτελεί πλοήγηση χρησιμοποιώντας ένα TreeWalker θα υποστηρίζει αυτόματα οποιαδήποτε προβολή που ορίζεται από ένα TreeWalker.
type: docs
weight: 1270
url: /el/net/aspose.svg.dom.traversal/itreewalker/
---
## ITreeWalker interface

Τα αντικείμενα TreeWalker χρησιμοποιούνται για την πλοήγηση σε ένα δέντρο εγγράφου ή σε ένα υποδέντρο χρησιμοποιώντας την προβολή του εγγράφου που ορίζεται από τις σημαίες και το φίλτρο whatToShow (αν υπάρχει). Οποιαδήποτε συνάρτηση που εκτελεί πλοήγηση χρησιμοποιώντας ένα TreeWalker θα υποστηρίζει αυτόματα οποιαδήποτε προβολή που ορίζεται από ένα TreeWalker.

Η παράλειψη κόμβων από τη λογική προβολή ενός υποδέντρου μπορεί να οδηγήσει σε μια δομή που είναι ουσιαστικά διαφορετική από το ίδιο υποδέντρο στο πλήρες, μη φιλτραρισμένο έγγραφο . Οι κόμβοι που είναι αδέλφια στην προβολή TreeWalker μπορεί να είναι παιδιά διαφορετικών, ευρέως διαχωρισμένων κόμβων στην αρχική προβολή. Για παράδειγμα, θεωρήστε ένα NodeFilter που παρακάμπτει όλους τους κόμβους εκτός από τους κόμβους κειμένου και τον ριζικό κόμβο ενός εγγράφου. Στη λογική προβολή που προκύπτει, όλοι οι κόμβοι κειμένου θα είναι αδέλφια και θα εμφανίζονται ως απευθείας παιδιά του ριζικού κόμβου, ανεξάρτητα από το πόσο βαθιά είναι η δομή του αρχικού εγγράφου.

Δείτε επίσης το[Μοντέλο αντικειμένου εγγράφου (DOM) Επίπεδο 2 Προδιαγραφή διέλευσης και εύρους](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITreeWalker : ITraversal
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CurrentNode](../../aspose.svg.dom.traversal/itreewalker/currentnode/) { get; set; } | Ο κόμβος στον οποίο βρίσκεται επί του παρόντος το TreeWalker. Οι αλλαγές στο δέντρο DOM μπορεί να κάνουν τον τρέχοντα κόμβο να μην γίνεται πλέον αποδεκτός από το συσχετισμένο φίλτρο του TreeWalker. currentNode μπορεί επίσης να οριστεί ρητά σε οποιονδήποτε κόμβο,_x00 εντός του υποδέντρου που καθορίζεται από τον ριζικό κόμβο ή θα γινόταν αποδεκτό από τα σημαίες φίλτρου and whatToShow. Περαιτέρω διέλευση λαμβάνει χώρα σε σχέση με το currentNode, ακόμα κι αν δεν αποτελεί μέρος της τρέχουσας προβολής, εφαρμόζοντας τα φίλτρα στην ζητούμενη κατεύθυνση. εάν δεν υπάρχει δυνατότητα traversal , το currentNode δεν αλλάζει. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [FirstChild](../../aspose.svg.dom.traversal/itreewalker/firstchild/)() | Μετακινεί το TreeWalker στο πρώτο ορατό παιδί του τρέχοντος κόμβου και επιστρέφει τον νέο κόμβο. Εάν ο τρέχων κόμβος έχει no ορατά παιδιά, επιστρέφει null και διατηρεί τον κόμβο current . |
| [LastChild](../../aspose.svg.dom.traversal/itreewalker/lastchild/)() | Μετακινεί το TreeWalker στο τελευταίο ορατό παιδί του τρέχοντος κόμβου και επιστρέφει τον νέο κόμβο. Εάν ο τρέχων κόμβος έχει no ορατά παιδιά, επιστρέφει null και διατηρεί τον κόμβο current . |
| [NextNode](../../aspose.svg.dom.traversal/itreewalker/nextnode/)() | Μετακινεί το TreeWalker στον επόμενο ορατό κόμβο με σειρά document σε σχέση με τον τρέχοντα κόμβο και επιστρέφει τον νέο κόμβο. Εάν ο τρέχων κόμβος δεν έχει επόμενο κόμβο ή εάν η αναζήτηση για το nextNode επιχειρεί να προχωρήσει προς τα πάνω από τον κόμβο root του TreeWalker, επιστρέφει null και διατηρεί τον τρέχοντα κόμβο. |
| [NextSibling](../../aspose.svg.dom.traversal/itreewalker/nextsibling/)() | Μετακινεί το TreeWalker στον επόμενο αδερφό του τρέχοντος κόμβου και επιστρέφει τον νέο κόμβο. Εάν ο τρέχων κόμβος δεν έχει visual επόμενο αδελφό, επιστρέφει null και διατηρεί τον τρέχοντα κόμβο. |
| [ParentNode](../../aspose.svg.dom.traversal/itreewalker/parentnode/)() | Μετακινείται και επιστρέφει τον πλησιέστερο ορατό προγονικό κόμβο του τρέχοντος κόμβου. Εάν η αναζήτηση για το parentNode επιχειρήσει να ανέβει από τον ριζικό κόμβο του TreeWalker, ή εάν δεν βρει έναν ορατό κόμβο προγονικού, αυτή η μέθοδος διατηρεί την τρέχουσα θέση the και επιστρέφει null. |
| [PreviousNode](../../aspose.svg.dom.traversal/itreewalker/previousnode/)() | Μετακινεί το TreeWalker στην προηγούμενη σειρά εγγράφου ορατού κόμβου in σε σχέση με τον τρέχοντα κόμβο και επιστρέφει τον κόμβο new . Εάν ο τρέχων κόμβος δεν έχει προηγούμενο κόμβο ή εάν η αναζήτηση για previousNode επιχειρήσει να προχωρήσει προς τα πάνω από τον ριζικό κόμβο του the TreeWalker, επιστρέφει null και διατηρεί τον τρέχοντα κόμβο. |
| [PreviousSibling](../../aspose.svg.dom.traversal/itreewalker/previoussibling/)() | Μετακινεί το TreeWalker στον προηγούμενο αδερφό του τρέχοντος κόμβου και επιστρέφει τον νέο κόμβο. Εάν ο τρέχων κόμβος έχει no ορατό προηγούμενο αδελφό, επιστρέφει null και διατηρεί τον τρέχοντα κόμβο. |

### Δείτε επίσης

* interface [ITraversal](../itraversal/)
* χώρος ονομάτων [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* συνέλευση [Aspose.SVG](../../)

