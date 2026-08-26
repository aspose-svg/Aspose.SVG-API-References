---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "ITreeWalker CurrentNode ιδιότητα. Ο κόμβος στον οποίο βρίσκεται το TreeWalker αυτή τη στιγμή. Αλλαγές στο δέντρο DOM μπορεί να κάνουν τον τρέχοντα κόμβο να μην γίνεται πλέον αποδεκτός από το συνδεδεμένο φίλτρο του TreeWalker. Το currentNode μπορεί επίσης να οριστεί ρητά σε οποιονδήποτε κόμβο, ανεξαρτήτως του αν βρίσκεται μέσα στο υποδέντρο που καθορίζεται από τον ριζικό κόμβο ή θα γινόταν αποδεκτό από το φίλτρο και τις σημαίες whatToShow. Περαιτέρω περιήγηση πραγματοποιείται σε σχέση με το currentNode ακόμη και αν δεν αποτελεί μέρος της τρέχουσας προβολής, εφαρμόζοντας τα φίλτρα στην ζητούμενη κατεύθυνση· εάν δεν είναι δυνατή η περιήγηση, το currentNode δεν αλλάζει."
type: docs
weight: 10
url: /el/net/aspose.svg.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Ο κόμβος στον οποίο βρίσκεται αυτή τη στιγμή ο TreeWalker. Τροποποιήσεις στο δέντρο DOM μπορεί να κάνουν τον τρέχοντα κόμβο να μην γίνεται πλέον αποδεκτός από το συνδεδεμένο φίλτρο του TreeWalker. Το currentNode μπορεί επίσης να οριστεί ρητά σε οποιονδήποτε κόμβο, ανεξάρτητα από το αν βρίσκεται μέσα στο υποδέντρο που ορίζεται από τον ριζικό κόμβο ή θα γινόταν αποδεκτό από το φίλτρο και τις σημαίες whatToShow. Περαιτέρω διασχίσεις πραγματοποιούνται σε σχέση με το currentNode ακόμη και αν δεν αποτελεί μέρος της τρέχουσας προβολής, εφαρμόζοντας τα φίλτρα στην ζητούμενη κατεύθυνση· εάν δεν είναι δυνατή καμία διασχίση, το currentNode δεν αλλάζει.

```csharp
public Node CurrentNode { get; set; }
```

### Property Value

Ο τρέχων κόμβος.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν γίνει προσπάθεια να οριστεί το currentNode σε null. |

### Δείτε επίσης

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
