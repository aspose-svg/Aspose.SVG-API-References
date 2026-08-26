---
title: "Κατηγορία Element"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Element class. Η διεπαφή Element αντιπροσωπεύει ένα στοιχείο σε ένα έγγραφο HTML ή XML."
type: docs
weight: 2840
url: /el/net/aspose.svg.dom/element/
---
## Element class

Η διεπαφή Element αντιπροσωπεύει ένα στοιχείο σε ένα έγγραφο HTML ή XML.

```csharp
public class Element : Node, IChildNode, IParentNode
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Element](element/)(*[QualifiedName](../qualifiedname/), [Document](../document/)*) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Element`. Μην καλέσετε αυτόν τον κατασκευαστή άμεσα, χρησιμοποιήστε [`CreateElement`](../document/createelement/) ή [`CreateElementNS`](../document/createelementns/). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Attributes](../../aspose.svg.dom/element/attributes/) { get; } | Ένα NamedNodeMap που περιέχει τα χαρακτηριστικά αυτού του κόμβου (αν είναι Element) ή null διαφορετικά. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Επιστρέφει το απόλυτο βασικό URL του εγγράφου που περιέχει τον κόμβο. |
| [ChildElementCount](../../aspose.svg.dom/element/childelementcount/) { get; } | Επιστρέφει τον τρέχοντα αριθμό κόμβων στοιχείων που είναι παιδιά αυτού του στοιχείου. 0 εάν αυτό το στοιχείο δεν έχει κόμβους παιδία που είναι τύπου nodeType 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Επιστρέφει μια ζωντανή λίστα [`NodeList`](../../aspose.svg.collections/nodelist/) των παιδικών κόμβων του δεδομένου στοιχείου, όπου ο πρώτος παιδικός κόμβος έχει δείκτη 0. Οι παιδικοί κόμβοι περιλαμβάνουν στοιχεία, κείμενο και σχόλια. |
| [Children](../../aspose.svg.dom/element/children/) { get; } | Επιστρέφει τα θυγατρικά στοιχεία του τρέχοντος στοιχείου. |
| [ClassList](../../aspose.svg.dom/element/classlist/) { get; } | Επιστρέφει μια ζωντανή DOMTokenList που περιέχει διακριτικά που λήφθηκαν από την ανάλυση του χαρακτηριστικού \"class\". |
| [ClassName](../../aspose.svg.dom/element/classname/) { get; set; } | Το χαρακτηριστικό class του στοιχείου. Αυτό το χαρακτηριστικό έχει μετονομαστεί λόγω συγκρούσεων με τη λέξη-κλειδί \"class\" που εκτίθεται από πολλές γλώσσες. Δείτε τον ορισμό του χαρακτηριστικού class στο HTML 4.01. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Επιστρέφει το πρώτο παιδί του κόμβου στο δέντρο, ή null εάν ο κόμβος δεν έχει παιδιά. |
| [FirstElementChild](../../aspose.svg.dom/element/firstelementchild/) { get; } | Επιστρέφει τον πρώτο κόμβο παιδικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδικά στοιχεία. |
| [Id](../../aspose.svg.dom/element/id/) { get; set; } | Το αναγνωριστικό του στοιχείου. Δείτε τον ορισμό του χαρακτηριστικού id στο HTML 4.01. |
| [InnerHTML](../../aspose.svg.dom/element/innerhtml/) { get; set; } | Επιστρέφει ένα τμήμα HTML ή XML που αντιπροσωπεύει το περιεχόμενο του στοιχείου. Μπορεί να οριστεί, για να αντικαταστήσει το περιεχόμενο του στοιχείου με κόμβους που αναλύονται από τη δοθείσα συμβολοσειρά. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Επιστρέφει το τελευταίο παιδί του κόμβου. Εάν ο γονέας του είναι ένα στοιχείο, τότε το παιδί είναι γενικά ένας κόμβος στοιχείου, ένας κόμβος κειμένου ή ένας κόμβος σχολίου. Επιστρέφει null εάν δεν υπάρχουν παιδικά στοιχεία. |
| [LastElementChild](../../aspose.svg.dom/element/lastelementchild/) { get; } | Επιστρέφει τον τελευταίο κόμβο στοιχείου παιδί αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδιά στοιχεία. |
| override [LocalName](../../aspose.svg.dom/element/localname/) { get; } | Επιστρέφει το τοπικό μέρος του πλήρους ονόματος αυτού του κόμβου. Για κόμβους οποιουδήποτε τύπου εκτός από ELEMENT_NODE και ATTRIBUTE_NODE και κόμβους που δημιουργήθηκαν με μέθοδο DOM Level 1, όπως Document.createElement(), αυτό είναι πάντα null. |
| override [NamespaceURI](../../aspose.svg.dom/element/namespaceuri/) { get; } | Το URI του χώρου ονομάτων αυτού του κόμβου, ή null εάν δεν έχει οριστεί. |
| [NextElementSibling](../../aspose.svg.dom/element/nextelementsibling/) { get; } | Επιστρέφει τον επόμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς κόμβους στοιχείου που έρχονται μετά από αυτό στο δέντρο του εγγράφου. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Επιστρέφει τον κόμβο που ακολουθεί αμέσως τον καθορισμένο στο γονέα τους [`ChildNodes`](../node/childnodes/), ή επιστρέφει null εάν ο καθορισμένος κόμβος είναι το τελευταίο παιδί στο γονικό στοιχείο. |
| override [NodeName](../../aspose.svg.dom/element/nodename/) { get; } | Το όνομα αυτού του κόμβου, ανάλογα με τον τύπο του. |
| override [NodeType](../../aspose.svg.dom/element/nodetype/) { get; } | Ένας κώδικας που αντιπροσωπεύει τον τύπο του υποκείμενου αντικειμένου. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Επιστρέφει ή ορίζει την τιμή του τρέχοντος κόμβου. |
| [OuterHTML](../../aspose.svg.dom/element/outerhtml/) { get; set; } | Επιστρέφει ένα τμήμα HTML ή XML που αντιπροσωπεύει το στοιχείο και το περιεχόμενό του. Μπορεί να οριστεί, για να αντικαταστήσει το στοιχείο με κόμβους που αναλύονται από τη δοθείσα συμβολοσειρά. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Επιστρέφει το αντικείμενο εγγράφου ανώτερου επιπέδου του κόμβου. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Επιστρέφει το γονικό `Element` του κόμβου DOM, ή null εάν ο κόμβος δεν έχει γονέα ή ο γονέας του δεν είναι DOM Element. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM. |
| override [Prefix](../../aspose.svg.dom/element/prefix/) { get; } | Το πρόθεμα χώρου ονομάτων αυτού του κόμβου, ή null εάν δεν έχει οριστεί. Όταν ορίζεται ως null, η ρύθμιση του δεν έχει καμία επίδραση. |
| [PreviousElementSibling](../../aspose.svg.dom/element/previouselementsibling/) { get; } | Επιστρέφει τον προηγούμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς κόμβους στοιχείου που έρχονται πριν από αυτό στο δέντρο του εγγράφου. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Επιστρέφει τον κόμβο που προηγείται αμέσως του καθορισμένου στη λίστα [`ChildNodes`](../node/childnodes/) του γονέα του, ή null εάν ο καθορισμένος κόμβος είναι ο πρώτος σε αυτή τη λίστα. |
| [ShadowRoot](../../aspose.svg.dom/element/shadowroot/) { get; } | Επιστρέφει το shadowRoot που αποθηκεύεται σε αυτό το στοιχείο ή null εάν είναι κλειστό. |
| [TagName](../../aspose.svg.dom/element/tagname/) { get; } | Το όνομα του στοιχείου. |
| override [TextContent](../../aspose.svg.dom/element/textcontent/) { get; set; } | Αυτό το χαρακτηριστικό επιστρέφει το κείμενο περιεχομένου αυτού του κόμβου και των απογόνων του. Όταν ορίζεται ως null, η ρύθμιση του δεν έχει καμία επίδραση. Κατά τη ρύθμιση, όλα τα πιθανά παιδιά που μπορεί να έχει αυτός ο κόμβος αφαιρούνται και, εάν η νέα συμβολοσειρά δεν είναι κενή ή null, αντικαθίστανται από έναν μοναδικό κόμβο Text που περιέχει τη συμβολοσειρά στην οποία ορίζεται το χαρακτηριστικό. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Προσθέτει έναν κόμβο στο τέλος της λίστας παιδιών ενός καθορισμένου γονικού κόμβου. Εάν το δοσμένο παιδί είναι αναφορά σε έναν υπάρχοντα κόμβο στο έγγραφο, [`AppendChild`](../node/appendchild/) τον μετακινεί από την τρέχουσα θέση του στη νέα θέση (δεν απαιτείται να αφαιρεθεί ο κόμβος από τον γονέα του πριν προστεθεί σε κάποιο άλλο κόμβο). |
| [AttachShadow](../../aspose.svg.dom/element/attachshadow/)(*[ShadowRootMode](../shadowrootmode/)*) | Δημιουργεί shadow root και το συνδέει με το τρέχον στοιχείο. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρος του ελέγχει εάν το υποδέντρο που περιέχεται σε έναν κόμβο κλωνοποιείται επίσης ή όχι. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Αποστέλλει ένα Event στον καθορισμένο [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (συγχρόνως) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του φάσματος σύλληψης και της προαιρετικής φάσης φούσκας) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με το [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [GetAttribute](../../aspose.svg.dom/element/getattribute/)(*string*) | Ανακτά την τιμή ενός χαρακτηριστικού με βάση το όνομα. |
| [GetAttributeNames](../../aspose.svg.dom/element/getattributenames/)() | Επιστρέφει τα ονόματα των χαρακτηριστικών του στοιχείου ως έναν Πίνακα συμβολοσειρών. Εάν το στοιχείο δεν έχει χαρακτηριστικά, επιστρέφει έναν κενό πίνακα. |
| [GetAttributeNode](../../aspose.svg.dom/element/getattributenode/)(*string*) | Ανακτά έναν κόμβο χαρακτηριστικού με βάση το όνομα. |
| [GetAttributeNodeNS](../../aspose.svg.dom/element/getattributenodens/)(*string, string*) | Ανακτά έναν κόμβο Attr με τοπικό όνομα και URI ονοματοχώρου. |
| [GetAttributeNS](../../aspose.svg.dom/element/getattributens/)(*string, string*) | Ανακτά την τιμή ενός χαρακτηριστικού με τοπικό όνομα και URI ονοματοχώρου. |
| [GetElementsByClassName](../../aspose.svg.dom/element/getelementsbyclassname/)(*string*) | Επιστρέφει το αντικείμενο [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) που περιέχει όλα τα στοιχεία μέσα στο `element` που έχουν όλες τις κλάσεις που καθορίζονται στο όρισμα. |
| [GetElementsByTagName](../../aspose.svg.dom/element/getelementsbytagname/)(*string*) | Επιστρέφει το αντικείμενο [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) που περιέχει όλα τα `elements` με ένα συγκεκριμένο όνομα ετικέτας, με τη σειρά του εγγράφου. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/element/getelementsbytagnamens/)(*string, string*) | Επιστρέφει το αντικείμενο [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) που περιέχει όλα τα `elements` με ένα συγκεκριμένο τοπικό όνομα και συμβολοσειρά URI ονοματοχώρου, με τη σειρά του εγγράφου. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [HasAttribute](../../aspose.svg.dom/element/hasattribute/)(*string*) | Επιστρέφει true όταν ένα χαρακτηριστικό με το δοσμένο όνομα έχει οριστεί σε αυτό το στοιχείο ή έχει προεπιλεγμένη τιμή, false διαφορετικά. |
| [HasAttributeNS](../../aspose.svg.dom/element/hasattributens/)(*string, string*) | Επιστρέφει true όταν ένα χαρακτηριστικό με δοσμένο τοπικό όνομα και URI ονοματοχώρου καθορίζεται σε αυτό το στοιχείο ή έχει προεπιλεγμένη τιμή, αλλιώς false. |
| [HasAttributes](../../aspose.svg.dom/element/hasattributes/)() | Επιστρέφει αν αυτός ο κόμβος (εάν είναι στοιχείο) έχει οποιαδήποτε χαρακτηριστικά. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Επιστρέφει μια λογική τιμή που υποδεικνύει εάν ο δοσμένος [`Node`](../node/) έχει παιδικούς κόμβους ή όχι. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Εισάγει τον κόμβο πριν από τον υπάρχοντα παιδικό κόμβο child. Εάν child είναι null, εισάγει τον κόμβο στο τέλος της λίστας παιδιών. Εάν child είναι αντικείμενο DocumentFragment, όλα τα παιδιά του εισάγονται, με την ίδια σειρά, πριν από child. Εάν το παιδί βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Αυτή η μέθοδος ελέγχει εάν το καθορισμένο namespaceURI είναι ο προεπιλεγμένος χώρος ονομάτων ή όχι. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Δοκιμάζει εάν δύο κόμβοι είναι ίσοι. Αυτή η μέθοδος ελέγχει την ισότητα των κόμβων, όχι την ταυτότητα (π.χ., εάν οι δύο κόμβοι είναι αναφορές στο ίδιο αντικείμενο) η οποία μπορεί να ελεγχθεί με Node.isSameNode(). Όλοι οι κόμβοι που είναι τα ίδια θα είναι επίσης ίσοι, αν και το αντίστροφο μπορεί να μην ισχύει. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Η μέθοδος είναι ένας παλαιός ψευδώνυμος για τον τελεστή αυστηρής ισότητας ===. Δηλαδή, ελέγχει εάν δύο κόμβοι είναι τα ίδια (με άλλα λόγια, εάν αναφέρονται στο ίδιο αντικείμενο). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Αναζητήστε το URI του χώρου ονομάτων που σχετίζεται με το δοσμένο πρόθεμα, ξεκινώντας από αυτόν τον κόμβο. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Αναζητήστε το πρόθεμα που σχετίζεται με το δοσμένο URI του χώρου ονομάτων, ξεκινώντας από αυτόν τον κόμβο. Οι δηλώσεις του προεπιλεγμένου χώρου ονομάτων αγνοούνται από αυτή τη μέθοδο. Δείτε το Namespace Prefix Lookup για λεπτομέρειες σχετικά με τον αλγόριθμο που χρησιμοποιείται από αυτή τη μέθοδο. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Τοποθετεί όλους τους κόμβους Text σε πλήρη βάθος του υποδέντρου κάτω από αυτόν τον Node, συμπεριλαμβανομένων των κόμβων attribute, σε μια \"κανονική\" μορφή όπου μόνο η δομή (π.χ., στοιχεία, σχόλια, οδηγίες επεξεργασίας, ενότητες CDATA και αναφορές οντοτήτων) διαχωρίζει τους κόμβους Text, δηλαδή δεν υπάρχουν ούτε γειτονικοί κόμβοι Text ούτε κενά κόμβοι Text. Αυτό μπορεί να χρησιμοποιηθεί για να εξασφαλιστεί ότι η προβολή DOM ενός εγγράφου είναι η ίδια όπως θα ήταν αν αποθηκευτεί και ξαναφορτωθεί, και είναι χρήσιμο όταν εκτελούνται λειτουργίες (όπως αναζητήσεις XPointer [XPointer]) που εξαρτώνται από μια συγκεκριμένη δομή δέντρου εγγράφου. Εάν η παράμετρος \"normalize-characters\" του αντικειμένου DOMConfiguration που είναι συνδεδεμένο με το Node.ownerDocument είναι true, αυτή η μέθοδος θα κανονικοποιήσει επίσης πλήρως τους χαρακτήρες των κόμβων Text. |
| [QuerySelector](../../aspose.svg.dom/element/queryselector/)(*string*) | Επιστρέφει το πρώτο Element στο έγγραφο, που ταιριάζει με τον selector |
| [QuerySelectorAll](../../aspose.svg.dom/element/queryselectorall/)(*string*) | Επιστρέφει μια NodeList όλων των Elements στο έγγραφο, που ταιριάζουν με τον selector |
| [Remove](../../aspose.svg.dom/element/remove/)() | Αφαιρεί αυτήν την παρουσία. |
| [RemoveAttribute](../../aspose.svg.dom/element/removeattribute/)(*string*) | Αφαιρεί ένα χαρακτηριστικό με βάση το όνομα. |
| [RemoveAttributeNode](../../aspose.svg.dom/element/removeattributenode/)(*[Attr](../attr/)*) | Αφαιρεί τον καθορισμένο κόμβο χαρακτηριστικού. |
| [RemoveAttributeNS](../../aspose.svg.dom/element/removeattributens/)(*string, string*) | Αφαιρεί ένα χαρακτηριστικό με το τοπικό όνομα και το URI ονοματοχώρου. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Αφαιρεί έναν κόμβο-παιδί από το DOM και επιστρέφει τον αφαιρεθέντα κόμβο. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών γεγονότων από τον στόχο του γεγονότος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές γεγονότων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών γεγονότων από τον στόχο του γεγονότος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές γεγονότων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών γεγονότων από τον στόχο του γεγονότος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές γεγονότων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Αντικαθιστά τον κόμβο-παιδί oldChild με το newChild στη λίστα των παιδιών και επιστρέφει τον κόμβο oldChild. Εάν το newChild είναι αντικείμενο DocumentFragment, ο oldChild αντικαθίσταται από όλα τα παιδιά του DocumentFragment, τα οποία εισάγονται με την ίδια σειρά. Εάν το newChild βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| [SetAttribute](../../aspose.svg.dom/element/setattribute/)(*string, string*) | Προσθέτει ένα νέο χαρακτηριστικό. Εάν ένα χαρακτηριστικό με αυτό το όνομα υπάρχει ήδη στο στοιχείο, η τιμή του αλλάζει στην τιμή της παραμέτρου value. |
| [SetAttributeNode](../../aspose.svg.dom/element/setattributenode/)(*[Attr](../attr/)*) | Προσθέτει έναν νέο κόμβο χαρακτηριστικού. Εάν ένα χαρακτηριστικό με αυτό το όνομα (nodeName) υπάρχει ήδη στο στοιχείο, αντικαθίσταται με το νέο. |
| [SetAttributeNodeNS](../../aspose.svg.dom/element/setattributenodens/)(*[Attr](../attr/)*) | Προσθέτει ένα νέο χαρακτηριστικό. Εάν ένα χαρακτηριστικό με αυτό το τοπικό όνομα και το URI ονοματοχώρου υπάρχει ήδη στο στοιχείο, αντικαθίσταται με το νέο. |
| [SetAttributeNS](../../aspose.svg.dom/element/setattributens/)(*string, string, string*) | Προσθέτει ένα νέο χαρακτηριστικό. Εάν ένα χαρακτηριστικό με το ίδιο τοπικό όνομα και URI ονοματοχώρου υπάρχει ήδη στο στοιχείο, το πρόθεμά του αλλάζει στο πρόθεμα του qualifiedName, και η τιμή του αλλάζει στην τιμή της παραμέτρου value. |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/#toggleattribute)(*string*) | Εάν δεν δοθεί η παράμετρος force, «εναλλάσσει» το qualifiedName, αφαιρώντας το αν υπάρχει και προσθέτοντάς το αν δεν υπάρχει. Εάν force είναι true, προσθέτει το qualifiedName. Εάν force είναι false, αφαιρεί το qualifiedName. |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/#toggleattribute_1)(*string, bool*) | Εάν δεν δοθεί η παράμετρος force, «εναλλάσσει» το qualifiedName, αφαιρώντας το αν υπάρχει και προσθέτοντάς το αν δεν υπάρχει. Εάν force είναι true, προσθέτει το qualifiedName. Εάν force είναι false, αφαιρεί το qualifiedName. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία. |

### Δείτε επίσης

* class [Node](../node/)
* interface [IChildNode](../ichildnode/)
* interface [IParentNode](../iparentnode/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
