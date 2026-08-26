---
title: "NodeFilter Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Traversal.Filters.NodeFilter class. Τα φίλτρα είναι αντικείμενα που ξέρουν πώς να φιλτράρουν κόμβους."
type: docs
weight: 3210
url: /el/net/aspose.svg.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Τα φίλτρα είναι αντικείμενα που γνωρίζουν πώς να "φιλτράρουν" κόμβους.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [AcceptNode](../../aspose.svg.dom.traversal.filters/nodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | Δοκιμάστε αν ένας καθορισμένος κόμβος είναι ορατός στην λογική προβολή ενός TreeWalker ή NodeIterator. Αυτή η λειτουργία θα κληθεί από την υλοποίηση του TreeWalker και του NodeIterator· δεν καλείται συνήθως απευθείας από κώδικα χρήστη. (Ωστόσο, μπορείτε να το κάνετε εάν θέλετε να χρησιμοποιήσετε το ίδιο φίλτρο για να καθοδηγήσετε τη λογική της δικής σας εφαρμογής.) |
| override [GetPlatformType](../../aspose.svg.dom.traversal.filters/nodefilter/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου αντικειμένου ECMAScript. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_accept/) | Αποδοχή του κόμβου. Οι μεθόδους πλοήγησης που ορίζονται για NodeIterator ή TreeWalker θα επιστρέψουν αυτόν τον κόμβο. |
| const [FILTER_REJECT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_reject/) | Απόρριψη του κόμβου. Οι μέθοδοι πλοήγησης που ορίζονται για NodeIterator ή TreeWalker δεν θα επιστρέψουν αυτόν τον κόμβο. Για το TreeWalker, τα παιδιά αυτού του κόμβου θα απορριφθούν επίσης. Οι NodeIterators θεωρούν αυτό ως συνώνυμο του FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.svg.dom.traversal.filters/nodefilter/filter_skip/) | Παράλειψη αυτού του μοναδικού κόμβου. Οι μέθοδοι πλοήγησης που ορίζονται για NodeIterator ή TreeWalker δεν θα επιστρέψουν αυτόν τον κόμβο. Για τόσο το NodeIterator όσο και το TreeWalker, τα παιδιά αυτού του κόμβου θα εξακολουθούν να λαμβάνονται υπόψη. |
| const [SHOW_ALL](../../aspose.svg.dom.traversal.filters/nodefilter/show_all/) | Εμφάνιση όλων των Nodes. |
| const [SHOW_ATTRIBUTE](../../aspose.svg.dom.traversal.filters/nodefilter/show_attribute/) | Εμφάνιση κόμβων Attr. Αυτό έχει νόημα μόνο όταν δημιουργείται ένας iterator ή tree-walker με έναν κόμβο χαρακτηριστικού ως ρίζα· σε αυτήν την περίπτωση, σημαίνει ότι ο κόμβος χαρακτηριστικού θα εμφανίζεται στην πρώτη θέση της επανάληψης ή της διέλευσης. Δεδομένου ότι τα χαρακτηριστικά δεν είναι ποτέ παιδιά άλλων κόμβων, δεν εμφανίζονται κατά τη διέλευση του δέντρου του εγγράφου. |
| const [SHOW_CDATA_SECTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_cdata_section/) | Εμφάνιση κόμβων CDATASection. |
| const [SHOW_COMMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_comment/) | Εμφάνιση κόμβων Comment. |
| const [SHOW_DOCUMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document/) | Εμφάνιση κόμβων Document. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_fragment/) | Εμφάνιση κόμβων DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_type/) | Εμφάνιση κόμβων DocumentType. |
| const [SHOW_ELEMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_element/) | Εμφάνιση κόμβων Element. |
| const [SHOW_ENTITY](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity/) | Εμφάνιση κόμβων Entity. Αυτό έχει νόημα μόνο όταν δημιουργείται ένας επαναλήπτης ή περιηγητής δέντρου με έναν κόμβο Entity ως ρίζα· σε αυτήν την περίπτωση, σημαίνει ότι ο κόμβος Entity θα εμφανιστεί στην πρώτη θέση της διαδρομής. Δεδομένου ότι οι οντότητες δεν αποτελούν μέρος του δέντρου εγγράφου, δεν εμφανίζονται κατά την περιήγηση του δέντρου εγγράφου. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity_reference/) | Εμφάνιση κόμβων EntityReference. |
| const [SHOW_NOTATION](../../aspose.svg.dom.traversal.filters/nodefilter/show_notation/) | Εμφάνιση κόμβων Notation. Αυτό έχει νόημα μόνο όταν δημιουργείται ένας επαναλήπτης ή περιηγητής δέντρου με έναν κόμβο Notation ως ρίζα· σε αυτήν την περίπτωση, σημαίνει ότι ο κόμβος Notation θα εμφανιστεί στην πρώτη θέση της διαδρομής. Δεδομένου ότι οι σημειώσεις δεν αποτελούν μέρος του δέντρου εγγράφου, δεν εμφανίζονται κατά την περιήγηση του δέντρου εγγράφου. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_processing_instruction/) | Εμφάνιση κόμβων ProcessingInstruction. |
| const [SHOW_TEXT](../../aspose.svg.dom.traversal.filters/nodefilter/show_text/) | Εμφάνιση κόμβων Text. |

### Δείτε επίσης

* class [DOMObject](../../aspose.svg.dom/domobject/)
* interface [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../)
