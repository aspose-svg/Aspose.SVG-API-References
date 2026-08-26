---
title: "Κλάση EntityReference"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Κλάση Aspose.Svg.Dom.EntityReference. Οι κόμβοι EntityReference μπορούν να χρησιμοποιηθούν για την αναπαράσταση μιας αναφοράς οντότητας στο δέντρο."
type: docs
weight: 2860
url: /el/net/aspose.svg.dom/entityreference/
---
## EntityReference class

Οι κόμβοι EntityReference μπορούν να χρησιμοποιηθούν για την αναπαράσταση μιας αναφοράς οντότητας στο δέντρο.

```csharp
public class EntityReference : Node
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Επιστρέφει το απόλυτο βασικό URL του εγγράφου που περιέχει τον κόμβο. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Επιστρέφει μια ζωντανή λίστα [`NodeList`](../../aspose.svg.collections/nodelist/) των παιδικών κόμβων του δεδομένου στοιχείου, όπου ο πρώτος παιδικός κόμβος έχει δείκτη 0. Οι παιδικοί κόμβοι περιλαμβάνουν στοιχεία, κείμενο και σχόλια. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Επιστρέφει το πρώτο παιδί του κόμβου στο δέντρο, ή null εάν ο κόμβος δεν έχει παιδιά. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Επιστρέφει το τελευταίο παιδί του κόμβου. Εάν ο γονέας του είναι ένα στοιχείο, τότε το παιδί είναι γενικά ένας κόμβος στοιχείου, ένας κόμβος κειμένου ή ένας κόμβος σχολίου. Επιστρέφει null εάν δεν υπάρχουν παιδικά στοιχεία. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Επιστρέφει το τοπικό μέρος του πλήρους ονόματος αυτού του κόμβου. Για κόμβους οποιουδήποτε τύπου εκτός από [`ELEMENT_NODE`](../node/element_node/) και [`ATTRIBUTE_NODE`](../node/attribute_node/) και κόμβους που δημιουργήθηκαν με μέθοδο DOM Level 1, όπως το [`CreateElement`](../document/createelement/), αυτό είναι πάντα null. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Επιστρέφει το URI του ονοματοχώρου του στοιχείου, ή null εάν το στοιχείο δεν βρίσκεται σε ονοματοχώρο. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Επιστρέφει τον κόμβο που ακολουθεί αμέσως τον καθορισμένο στο γονέα τους [`ChildNodes`](../node/childnodes/), ή επιστρέφει null εάν ο καθορισμένος κόμβος είναι το τελευταίο παιδί στο γονικό στοιχείο. |
| override [NodeName](../../aspose.svg.dom/entityreference/nodename/) { get; } | Το όνομα αυτού του κόμβου, ανάλογα με τον τύπο του. |
| override [NodeType](../../aspose.svg.dom/entityreference/nodetype/) { get; } | Ένας κώδικας που αντιπροσωπεύει τον τύπο του υποκείμενου αντικειμένου. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Επιστρέφει ή ορίζει την τιμή του τρέχοντος κόμβου. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Επιστρέφει το αντικείμενο εγγράφου ανώτερου επιπέδου του κόμβου. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Επιστρέφει τον γονέα του κόμβου DOM [`Element`](../element/), ή null εάν ο κόμβος δεν έχει γονέα ή ο γονέας του δεν είναι στοιχείο DOM. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Επιστρέφει το πρόθεμα ονοματοχώρου του συγκεκριμένου στοιχείου, ή null εάν δεν έχει καθοριστεί πρόθεμα. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Επιστρέφει τον κόμβο που προηγείται αμέσως του καθορισμένου στη λίστα [`ChildNodes`](../node/childnodes/) του γονέα του, ή null εάν ο καθορισμένος κόμβος είναι ο πρώτος σε αυτή τη λίστα. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Αναπαριστά το κείμενο περιεχομένου του κόμβου και των απογόνων του. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Προσθέτει έναν κόμβο στο τέλος της λίστας παιδιών ενός καθορισμένου γονικού κόμβου. Εάν το δοσμένο παιδί είναι αναφορά σε έναν υπάρχοντα κόμβο στο έγγραφο, [`AppendChild`](../node/appendchild/) τον μετακινεί από την τρέχουσα θέση του στη νέα θέση (δεν απαιτείται να αφαιρεθεί ο κόμβος από τον γονέα του πριν προστεθεί σε κάποιο άλλο κόμβο). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρος του ελέγχει εάν το υποδέντρο που περιέχεται σε έναν κόμβο κλωνοποιείται επίσης ή όχι. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Αποστέλλει ένα Event στον καθορισμένο [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (συγχρόνως) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του φάσματος σύλληψης και της προαιρετικής φάσης φούσκας) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με το [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Επιστρέφει μια λογική τιμή που υποδεικνύει εάν ο δοσμένος [`Node`](../node/) έχει παιδικούς κόμβους ή όχι. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Εισάγει τον κόμβο πριν από τον υπάρχοντα παιδικό κόμβο child. Εάν child είναι null, εισάγει τον κόμβο στο τέλος της λίστας παιδιών. Εάν child είναι αντικείμενο DocumentFragment, όλα τα παιδιά του εισάγονται, με την ίδια σειρά, πριν από child. Εάν το παιδί βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Αυτή η μέθοδος ελέγχει εάν το καθορισμένο namespaceURI είναι ο προεπιλεγμένος χώρος ονομάτων ή όχι. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Δοκιμάζει εάν δύο κόμβοι είναι ίσοι. Αυτή η μέθοδος ελέγχει την ισότητα των κόμβων, όχι την ταυτότητα (π.χ., εάν οι δύο κόμβοι είναι αναφορές στο ίδιο αντικείμενο) η οποία μπορεί να ελεγχθεί με Node.isSameNode(). Όλοι οι κόμβοι που είναι τα ίδια θα είναι επίσης ίσοι, αν και το αντίστροφο μπορεί να μην ισχύει. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Η μέθοδος είναι ένας παλαιός ψευδώνυμος για τον τελεστή αυστηρής ισότητας ===. Δηλαδή, ελέγχει εάν δύο κόμβοι είναι τα ίδια (με άλλα λόγια, εάν αναφέρονται στο ίδιο αντικείμενο). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Αναζητήστε το URI του χώρου ονομάτων που σχετίζεται με το δοσμένο πρόθεμα, ξεκινώντας από αυτόν τον κόμβο. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Αναζητήστε το πρόθεμα που σχετίζεται με το δοσμένο URI του χώρου ονομάτων, ξεκινώντας από αυτόν τον κόμβο. Οι δηλώσεις του προεπιλεγμένου χώρου ονομάτων αγνοούνται από αυτή τη μέθοδο. Δείτε το Namespace Prefix Lookup για λεπτομέρειες σχετικά με τον αλγόριθμο που χρησιμοποιείται από αυτή τη μέθοδο. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Τοποθετεί όλους τους κόμβους Text σε πλήρη βάθος του υποδέντρου κάτω από αυτόν τον Node, συμπεριλαμβανομένων των κόμβων attribute, σε μια \"κανονική\" μορφή όπου μόνο η δομή (π.χ., στοιχεία, σχόλια, οδηγίες επεξεργασίας, ενότητες CDATA και αναφορές οντοτήτων) διαχωρίζει τους κόμβους Text, δηλαδή δεν υπάρχουν ούτε γειτονικοί κόμβοι Text ούτε κενά κόμβοι Text. Αυτό μπορεί να χρησιμοποιηθεί για να εξασφαλιστεί ότι η προβολή DOM ενός εγγράφου είναι η ίδια όπως θα ήταν αν αποθηκευτεί και ξαναφορτωθεί, και είναι χρήσιμο όταν εκτελούνται λειτουργίες (όπως αναζητήσεις XPointer [XPointer]) που εξαρτώνται από μια συγκεκριμένη δομή δέντρου εγγράφου. Εάν η παράμετρος \"normalize-characters\" του αντικειμένου DOMConfiguration που είναι συνδεδεμένο με το Node.ownerDocument είναι true, αυτή η μέθοδος θα κανονικοποιήσει επίσης πλήρως τους χαρακτήρες των κόμβων Text. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Αφαιρεί έναν κόμβο-παιδί από το DOM και επιστρέφει τον αφαιρεθέντα κόμβο. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών γεγονότων από τον στόχο του γεγονότος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές γεγονότων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών γεγονότων από τον στόχο του γεγονότος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές γεγονότων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών γεγονότων από τον στόχο του γεγονότος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές γεγονότων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Αντικαθιστά τον κόμβο-παιδί oldChild με το newChild στη λίστα των παιδιών και επιστρέφει τον κόμβο oldChild. Εάν το newChild είναι αντικείμενο DocumentFragment, ο oldChild αντικαθίσταται από όλα τα παιδιά του DocumentFragment, τα οποία εισάγονται με την ίδια σειρά. Εάν το newChild βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία. |

### Δείτε επίσης

* class [Node](../node/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
