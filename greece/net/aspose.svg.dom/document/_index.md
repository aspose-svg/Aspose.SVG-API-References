---
title: "Κλάση Document"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Document class. Το Document αντιπροσωπεύει ολόκληρο το έγγραφο HTML, XML ή SVG. Συγκεκριμένα, είναι η ρίζα του δέντρου του εγγράφου και παρέχει την κύρια πρόσβαση στα δεδομένα του εγγράφου."
type: docs
weight: 2810
url: /el/net/aspose.svg.dom/document/
---
## Document class

Το Document αντιπροσωπεύει ολόκληρο το έγγραφο HTML, XML ή SVG. Συγκεκριμένα, είναι η ρίζα του δέντρου του εγγράφου και παρέχει την κύρια πρόσβαση στα δεδομένα του εγγράφου.

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| override [BaseURI](../../aspose.svg.dom/document/baseuri/) { get; } | Το απόλυτο βασικό URI αυτού του κόμβου ή null εάν η υλοποίηση δεν μπόρεσε να αποκτήσει ένα απόλυτο URI. |
| [CharacterSet](../../aspose.svg.dom/document/characterset/) { get; } | Λαμβάνει την κωδικοποίηση του εγγράφου. |
| [Charset](../../aspose.svg.dom/document/charset/) { get; } | Λαμβάνει την κωδικοποίηση του εγγράφου. |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount/) { get; } | Επιστρέφει τον τρέχοντα αριθμό κόμβων στοιχείων που είναι παιδιά αυτού του στοιχείου. 0 εάν αυτό το στοιχείο δεν έχει κόμβους παιδία που είναι τύπου nodeType 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Επιστρέφει μια ζωντανή λίστα [`NodeList`](../../aspose.svg.collections/nodelist/) των παιδικών κόμβων του δεδομένου στοιχείου, όπου ο πρώτος παιδικός κόμβος έχει δείκτη 0. Οι παιδικοί κόμβοι περιλαμβάνουν στοιχεία, κείμενο και σχόλια. |
| [Children](../../aspose.svg.dom/document/children/) { get; } | Επιστρέφει τα παιδικά στοιχεία. |
| [ContentType](../../aspose.svg.dom/document/contenttype/) { get; } | Λαμβάνει τον τύπο περιεχομένου του εγγράφου. |
| [Context](../../aspose.svg.dom/document/context/) { get; } | Λαμβάνει το τρέχον πλαίσιο περιήγησης. |
| [DefaultView](../../aspose.svg.dom/document/defaultview/) { get; } | Το χαρακτηριστικό defaultView IDL της διεπαφής Document, κατά την ανάκτηση, πρέπει να επιστρέφει το αντικείμενο WindowProxy του πλαισίου περιήγησης του Document, εάν αυτό το Document έχει συσχετισμένο πλαίσιο περιήγησης, ή null διαφορετικά. |
| [Doctype](../../aspose.svg.dom/document/doctype/) { get; } | Η Document Type Declaration που σχετίζεται με αυτό το έγγραφο. |
| [DocumentElement](../../aspose.svg.dom/document/documentelement/) { get; } | Αυτό είναι ένα χαρακτηριστικό ευκολίας που επιτρέπει άμεση πρόσβαση στον κόμβο παιδί που είναι το στοιχείο εγγράφου του εγγράφου. |
| [DocumentURI](../../aspose.svg.dom/document/documenturi/) { get; } | Η θέση του εγγράφου ή null εάν είναι ακαθόριστη ή εάν το Document δημιουργήθηκε χρησιμοποιώντας τη μέθοδο DOMImplementation.createDocument. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Επιστρέφει το πρώτο παιδί του κόμβου στο δέντρο, ή null εάν ο κόμβος δεν έχει παιδιά. |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild/) { get; } | Επιστρέφει τον πρώτο κόμβο παιδικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδικά στοιχεία. |
| [Implementation](../../aspose.svg.dom/document/implementation/) { get; } | Το αντικείμενο DOMImplementation που διαχειρίζεται αυτό το έγγραφο. |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding/) { get; } | Λαμβάνει την κωδικοποίηση του εγγράφου. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Επιστρέφει το τελευταίο παιδί του κόμβου. Εάν ο γονέας του είναι ένα στοιχείο, τότε το παιδί είναι γενικά ένας κόμβος στοιχείου, ένας κόμβος κειμένου ή ένας κόμβος σχολίου. Επιστρέφει null εάν δεν υπάρχουν παιδικά στοιχεία. |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild/) { get; } | Επιστρέφει τον τελευταίο κόμβο στοιχείου παιδί αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδιά στοιχεία. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Επιστρέφει το τοπικό μέρος του πλήρους ονόματος αυτού του κόμβου. Για κόμβους οποιουδήποτε τύπου εκτός από [`ELEMENT_NODE`](../node/element_node/) και [`ATTRIBUTE_NODE`](../node/attribute_node/) και κόμβους που δημιουργήθηκαν με μέθοδο DOM Level 1, όπως το [`CreateElement`](./createelement/), αυτό είναι πάντα null. |
| [Location](../../aspose.svg.dom/document/location/) { get; } | Η τοποθεσία του εγγράφου. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Επιστρέφει το URI του ονοματοχώρου του στοιχείου, ή null εάν το στοιχείο δεν βρίσκεται σε ονοματοχώρο. |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling/) { get; } | Επιστρέφει τον επόμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς κόμβους στοιχείου που έρχονται μετά από αυτό στο δέντρο του εγγράφου. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Επιστρέφει τον κόμβο που ακολουθεί αμέσως τον καθορισμένο στο γονέα τους [`ChildNodes`](../node/childnodes/), ή επιστρέφει null εάν ο καθορισμένος κόμβος είναι το τελευταίο παιδί στο γονικό στοιχείο. |
| override [NodeName](../../aspose.svg.dom/document/nodename/) { get; } | Το όνομα αυτού του κόμβου, ανάλογα με τον τύπο του. |
| override [NodeType](../../aspose.svg.dom/document/nodetype/) { get; } | Ένας κώδικας που αντιπροσωπεύει τον τύπο του υποκείμενου αντικειμένου. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Επιστρέφει ή ορίζει την τιμή του τρέχοντος κόμβου. |
| [Origin](../../aspose.svg.dom/document/origin/) { get; } | Λαμβάνει την προέλευση του εγγράφου. |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument/) { get; } | Λαμβάνει το έγγραφο ιδιοκτήτη. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Επιστρέφει τον γονέα του κόμβου DOM [`Element`](../element/), ή null εάν ο κόμβος δεν έχει γονέα ή ο γονέας του δεν είναι στοιχείο DOM. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Επιστρέφει το πρόθεμα ονοματοχώρου του συγκεκριμένου στοιχείου, ή null εάν δεν έχει καθοριστεί πρόθεμα. |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling/) { get; } | Επιστρέφει τον προηγούμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς κόμβους στοιχείου που έρχονται πριν από αυτό στο δέντρο του εγγράφου. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Επιστρέφει τον κόμβο που προηγείται αμέσως του καθορισμένου στη λίστα [`ChildNodes`](../node/childnodes/) του γονέα του, ή null εάν ο καθορισμένος κόμβος είναι ο πρώτος σε αυτή τη λίστα. |
| [ReadyState](../../aspose.svg.dom/document/readystate/) { get; } | Επιστρέφει την ετοιμότητα του εγγράφου. Το "loading" ενώ το Έγγραφο φορτώνεται, το "interactive" όταν έχει ολοκληρωθεί η ανάλυση αλλά εξακολουθούν να φορτώνονται υπο-πόροι, και το "complete" όταν έχει φορτωθεί πλήρως. |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking/) { get; set; } | Ένα χαρακτηριστικό που καθορίζει εάν η έλεγχος σφαλμάτων επιβάλλεται ή όχι. Όταν οριστεί σε false, η υλοποίηση είναι ελεύθερη να μην ελέγχει κάθε πιθανή περίπτωση σφάλματος που ορίζεται κανονικά στις λειτουργίες DOM, και να μην εγείρει κανένα DOMException στις λειτουργίες DOM ή να αναφέρει σφάλματα κατά τη χρήση του Document.normalizeDocument(). Σε περίπτωση σφάλματος, η συμπεριφορά είναι ακαθόριστη. Αυτό το χαρακτηριστικό είναι true εξ ορισμού. |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets/) { get; } | Μια λίστα που περιέχει όλα τα φύλλα στυλ που συνδέονται ρητά ή ενσωματώνονται σε ένα έγγραφο. Για έγγραφα HTML, αυτό περιλαμβάνει εξωτερικά φύλλα στυλ, που περιλαμβάνονται μέσω του στοιχείου HTML LINK, και ενσωματωμένα στοιχεία STYLE. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Αναπαριστά το κείμενο περιεχομένου του κόμβου και των απογόνων του. |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone/) { get; set; } | Ένα χαρακτηριστικό που καθορίζει, ως μέρος της δήλωσης XML, εάν αυτό το έγγραφο είναι αυτόνομο. Αυτό είναι false όταν δεν έχει καθοριστεί. |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion/) { get; set; } | Ένα χαρακτηριστικό που καθορίζει, ως μέρος της δήλωσης XML, τον αριθμό έκδοσης αυτού του εγγράφου. Εάν δεν υπάρχει δήλωση και το έγγραφο υποστηρίζει τη δυνατότητα "XML", η τιμή είναι "1.0". Εάν το έγγραφο δεν υποστηρίζει τη δυνατότητα "XML", η τιμή είναι πάντα null. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Προσθέτει έναν κόμβο στο τέλος της λίστας παιδιών ενός καθορισμένου γονικού κόμβου. Εάν το δοσμένο παιδί είναι αναφορά σε έναν υπάρχοντα κόμβο στο έγγραφο, [`AppendChild`](../node/appendchild/) τον μετακινεί από την τρέχουσα θέση του στη νέα θέση (δεν απαιτείται να αφαιρεθεί ο κόμβος από τον γονέα του πριν προστεθεί σε κάποιο άλλο κόμβο). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρος του ελέγχει εάν το υποδέντρο που περιέχεται σε έναν κόμβο κλωνοποιείται επίσης ή όχι. |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute/)(*string*) | Αυτή η μέθοδος δημιουργεί έναν νέο κόμβο χαρακτηριστικού και τον επιστρέφει. Το αντικείμενο που δημιουργείται είναι ένας κόμβος που υλοποιεί την κλάση [`Attr`](../attr/). Το DOM δεν επιβάλλει τι είδους χαρακτηριστικά μπορούν να προστεθούν σε ένα συγκεκριμένο στοιχείο με αυτόν τον τρόπο. |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens/)(*string, string*) | Αυτή η μέθοδος δημιουργεί έναν νέο κόμβο χαρακτηριστικού και τον επιστρέφει. Το αντικείμενο που δημιουργείται είναι ένας κόμβος που υλοποιεί την κλάση [`Attr`](../attr/). Το DOM δεν επιβάλλει τι είδους χαρακτηριστικά μπορούν να προστεθούν σε ένα συγκεκριμένο στοιχείο με αυτόν τον τρόπο. |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection/)(*string*) | Δημιουργεί έναν κόμβο CDATASection του οποίου η τιμή είναι η καθορισμένη συμβολοσειρά. |
| [CreateComment](../../aspose.svg.dom/document/createcomment/)(*string*) | Δημιουργεί έναν κόμβο Comment με την καθορισμένη συμβολοσειρά. |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment/)() | Δημιουργεί ένα νέο κενό [`DocumentFragment`](../documentfragment/) στο οποίο μπορούν να προστεθούν κόμβοι DOM για την κατασκευή ενός εκτός οθόνης δέντρου DOM. |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype/)(*string, string, string, string*) | Η μέθοδος επιστρέφει ένα αντικείμενο [`DocumentType`](../documenttype/) το οποίο μπορεί είτε να χρησιμοποιηθεί με το [`CreateDocument`](../idomimplementation/createdocument/) κατά τη δημιουργία του εγγράφου είτε να τοποθετηθεί στο έγγραφο μέσω μεθόδων όπως το [`InsertBefore`](../node/insertbefore/) ή το [`ReplaceChild`](../node/replacechild/). |
| [CreateElement](../../aspose.svg.dom/document/createelement/)(*string*) | Δημιουργεί το στοιχείο HTML που καθορίζεται από το localName, ή ένα HTMLUnknownElement εάν το localName δεν αναγνωρίζεται. |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns/)(*string, string*) | Δημιουργεί ένα στοιχείο με το δοσμένο πλήρες όνομα και το URI του ονόματος χώρου. |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference/)(*string*) | Δημιουργεί ένα αντικείμενο EntityReference. Επιπλέον, εάν η αναφερόμενη οντότητα είναι γνωστή, η λίστα παιδιών του κόμβου EntityReference γίνεται ίδια με αυτή του αντίστοιχου κόμβου Entity. |
| [CreateEvent](../../aspose.svg.dom/document/createevent/)(*string*) | Δημιουργεί ένα [`Event`](../../aspose.svg.dom.events/event/) τύπου που υποστηρίζεται από την υλοποίηση. |
| [CreateExpression](../../aspose.svg.dom/document/createexpression/)(*string, [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)*) | Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένα ονόματα χώρων. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατό το μεταγλωττισμό της συμβολοσειράς έκφρασης σε μια πιο αποδοτική εσωτερική μορφή και την προεπίλυση όλων των προθεμάτων ονομάτων χώρων που εμφανίζονται στην έκφραση. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator)(*[Node](../node/)*) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_1)(*[Node](../node/), long*) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver/)(*[Node](../node/)*) | Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση ονομάτων χώρων ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 `lookupNamespaceURI` στους κόμβους για την επίλυση του namespaceURI από ένα δεδομένο πρόθεμα, χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου τη στιγμή που καλείται η lookupNamespaceURI, καθώς και επιλύοντας σωστά το έμμεσο πρόθεμα xml. |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction/)(*string, string*) | Δημιουργεί έναν κόμβο ProcessingInstruction με το καθορισμένο όνομα και τις συμβολοσειρές δεδομένων. |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode/)(*string*) | Δημιουργεί έναν κόμβο Text με την καθορισμένη συμβολοσειρά. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker)(*[Node](../node/)*) | Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_1)(*[Node](../node/), long*) | Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που ρίζεται στον καθορισμένο κόμβο. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Αποστέλλει ένα Event στον καθορισμένο [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (συγχρόνως) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του φάσματος σύλληψης και της προαιρετικής φάσης φούσκας) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με το [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [Evaluate](../../aspose.svg.dom/document/evaluate/)(*string, [Node](../node/), [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/), [XPathResultType](../../aspose.svg.dom.xpath/xpathresulttype/), object*) | Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου, εφόσον είναι δυνατόν. |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid/)(*string*) | Αυτή η μέθοδος επιστρέφει ένα αντικείμενο [`Element`](../element/) που αντιπροσωπεύει το στοιχείο του οποίου η ιδιότητα id ταιριάζει με το καθορισμένο κείμενο. Δεδομένου ότι τα IDs των στοιχείων πρέπει να είναι μοναδικά εάν καθοριστούν, αποτελούν έναν χρήσιμο τρόπο γρήγορης πρόσβασης σε ένα συγκεκριμένο στοιχείο. |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname/)(*string*) | Αυτή η μέθοδος επιστρέφει ένα αντικείμενο παρόμοιο με πίνακα όλων των θυγατρικών στοιχείων που έχουν όλα τα δοσμένα ονόματα κλάσης. |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname/)(*string*) | Αυτή η μέθοδος επιστρέφει ένα [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) στοιχείων με το δοσμένο όνομα ετικέτας. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens/)(*string, string*) | Επιστρέφει μια λίστα στοιχείων με το δοσμένο όνομα ετικέτας που ανήκουν στο δοσμένο χώρο ονομάτων. Αναζητείται ολόκληρο το έγγραφο, συμπεριλαμβανομένου του ριζικού κόμβου. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου του αντικειμένου ECMAScript. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Επιστρέφει μια λογική τιμή που υποδεικνύει εάν ο δοσμένος [`Node`](../node/) έχει παιδικούς κόμβους ή όχι. |
| [ImportNode](../../aspose.svg.dom/document/importnode/)(*[Node](../node/), bool*) | Εισάγει έναν κόμβο από άλλο έγγραφο σε αυτό το έγγραφο, χωρίς να τροποποιήσει ή να αφαιρέσει τον κόμβο προέλευσης από το αρχικό έγγραφο· αυτή η μέθοδος δημιουργεί ένα νέο αντίγραφο του κόμβου προέλευσης. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Εισάγει τον κόμβο πριν από τον υπάρχοντα παιδικό κόμβο child. Εάν child είναι null, εισάγει τον κόμβο στο τέλος της λίστας παιδιών. Εάν child είναι αντικείμενο DocumentFragment, όλα τα παιδιά του εισάγονται, με την ίδια σειρά, πριν από child. Εάν το παιδί βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Αυτή η μέθοδος ελέγχει εάν το καθορισμένο namespaceURI είναι ο προεπιλεγμένος χώρος ονομάτων ή όχι. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Δοκιμάζει εάν δύο κόμβοι είναι ίσοι. Αυτή η μέθοδος ελέγχει την ισότητα των κόμβων, όχι την ταυτότητα (π.χ., εάν οι δύο κόμβοι είναι αναφορές στο ίδιο αντικείμενο) η οποία μπορεί να ελεγχθεί με Node.isSameNode(). Όλοι οι κόμβοι που είναι τα ίδια θα είναι επίσης ίσοι, αν και το αντίστροφο μπορεί να μην ισχύει. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Η μέθοδος είναι ένας παλαιός ψευδώνυμος για τον τελεστή αυστηρής ισότητας ===. Δηλαδή, ελέγχει εάν δύο κόμβοι είναι τα ίδια (με άλλα λόγια, εάν αναφέρονται στο ίδιο αντικείμενο). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Αναζητήστε το URI του χώρου ονομάτων που σχετίζεται με το δοσμένο πρόθεμα, ξεκινώντας από αυτόν τον κόμβο. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Αναζητήστε το πρόθεμα που σχετίζεται με το δοσμένο URI του χώρου ονομάτων, ξεκινώντας από αυτόν τον κόμβο. Οι δηλώσεις του προεπιλεγμένου χώρου ονομάτων αγνοούνται από αυτή τη μέθοδο. Δείτε το Namespace Prefix Lookup για λεπτομέρειες σχετικά με τον αλγόριθμο που χρησιμοποιείται από αυτή τη μέθοδο. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate)(*[RequestMessage](../../aspose.svg.net/requestmessage/)*) | Φορτώνει το έγγραφο βάσει του καθορισμένου αντικειμένου αίτησης, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_8)(*string*) | Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_2)(*[Url](../../aspose.svg/url/)*) | Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_1)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | Φορτώνει το έγγραφο βάσει του καθορισμένου αντικειμένου αίτησης, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_6)(*Stream, string*) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από τη τρέχουσα θέση στη ροή. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_4)(*Stream, [Url](../../aspose.svg/url/)*) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από τη τρέχουσα θέση στη ροή. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_13)(*string, CancellationToken*) | Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_11)(*string, string*) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_9)(*string, [Url](../../aspose.svg/url/)*) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_3)(*[Url](../../aspose.svg/url/), CancellationToken*) | Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_7)(*Stream, string, CancellationToken*) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από τη τρέχουσα θέση στη ροή. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_5)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από τη τρέχουσα θέση στη ροή. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_12)(*string, string, CancellationToken*) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_10)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | Φορτώνει ασύγχρονα το έγγραφο βάσει του καθορισμένου αντικειμένου αίτησης. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_6)(*string, CancellationToken*) | Φορτώνει ασύγχρονα το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_1)(*[Url](../../aspose.svg/url/), CancellationToken*) | Φορτώνει ασύγχρονα το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_3)(*Stream, string, CancellationToken*) | Φορτώνει ασύγχρονα το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_2)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | Φορτώνει ασύγχρονα το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_5)(*string, string, CancellationToken*) | Φορτώνει ασύγχρονα το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_4)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | Φορτώνει ασύγχρονα το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Τοποθετεί όλους τους κόμβους Text σε πλήρη βάθος του υποδέντρου κάτω από αυτόν τον Node, συμπεριλαμβανομένων των κόμβων attribute, σε μια \"κανονική\" μορφή όπου μόνο η δομή (π.χ., στοιχεία, σχόλια, οδηγίες επεξεργασίας, ενότητες CDATA και αναφορές οντοτήτων) διαχωρίζει τους κόμβους Text, δηλαδή δεν υπάρχουν ούτε γειτονικοί κόμβοι Text ούτε κενά κόμβοι Text. Αυτό μπορεί να χρησιμοποιηθεί για να εξασφαλιστεί ότι η προβολή DOM ενός εγγράφου είναι η ίδια όπως θα ήταν αν αποθηκευτεί και ξαναφορτωθεί, και είναι χρήσιμο όταν εκτελούνται λειτουργίες (όπως αναζητήσεις XPointer [XPointer]) που εξαρτώνται από μια συγκεκριμένη δομή δέντρου εγγράφου. Εάν η παράμετρος \"normalize-characters\" του αντικειμένου DOMConfiguration που είναι συνδεδεμένο με το Node.ownerDocument είναι true, αυτή η μέθοδος θα κανονικοποιήσει επίσης πλήρως τους χαρακτήρες των κόμβων Text. |
| [QuerySelector](../../aspose.svg.dom/document/queryselector/)(*string*) | Επιστρέφει το πρώτο Element στο έγγραφο, που ταιριάζει με τον selector |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall/)(*string*) | Επιστρέφει μια NodeList όλων των Elements στο έγγραφο, που ταιριάζουν με τον selector |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Αφαιρεί έναν κόμβο-παιδί από το DOM και επιστρέφει τον αφαιρεθέντα κόμβο. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών γεγονότων από τον στόχο του γεγονότος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές γεγονότων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών γεγονότων από τον στόχο του γεγονότος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές γεγονότων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών γεγονότων από τον στόχο του γεγονότος. Εάν ένας [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) αφαιρεθεί από ένα [`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές γεγονότων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| virtual [RenderTo](../../aspose.svg.dom/document/renderto/)(*[IDevice](../../aspose.svg.rendering/idevice/)*) | Αυτή η μέθοδος χρησιμοποιείται για την απόδοση των περιεχομένων του τρέχοντος εγγράφου σε μια καθορισμένη γραφική συσκευή. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Αντικαθιστά τον κόμβο-παιδί oldChild με το newChild στη λίστα των παιδιών και επιστρέφει τον κόμβο oldChild. Εάν το newChild είναι αντικείμενο DocumentFragment, ο oldChild αντικαθίσταται από όλα τα παιδιά του DocumentFragment, τα οποία εισάγονται με την ίδια σειρά. Εάν το newChild βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία. |
| [Write](../../aspose.svg.dom/document/write/)(*params string[]*) | Γράψτε μια συμβολοσειρά κειμένου σε μια ροή εγγράφου που ανοίχτηκε με την open(). Σημειώστε ότι η λειτουργία θα δημιουργήσει ένα έγγραφο που δεν είναι απαραίτητα καθοδηγούμενο από DTD και επομένως μπορεί να παραγάγει ένα μη έγκυρο αποτέλεσμα στο πλαίσιο του εγγράφου. |
| [WriteLn](../../aspose.svg.dom/document/writeln/)(*params string[]*) | Γράψτε μια συμβολοσειρά κειμένου ακολουθούμενη από χαρακτήρα νέας γραμμής σε μια ροή εγγράφου που ανοίχτηκε με την open(). Σημειώστε ότι η λειτουργία θα δημιουργήσει ένα έγγραφο που δεν είναι απαραίτητα καθοδηγούμενο από DTD και επομένως μπορεί να παραγάγει ένα μη έγκυρο αποτέλεσμα στο πλαίσιο του εγγράφου. |

## Συμβάντα

| Όνομα | Περιγραφή |
| --- | --- |
| event [OnAbort](../../aspose.svg.dom/document/onabort/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnAbort. |
| event [OnBlur](../../aspose.svg.dom/document/onblur/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnBlur. |
| event [OnCancel](../../aspose.svg.dom/document/oncancel/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnCancel. |
| event [OnCanplay](../../aspose.svg.dom/document/oncanplay/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnCanplay. |
| event [OnCanPlayThrough](../../aspose.svg.dom/document/oncanplaythrough/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnCanPlayThrough. |
| event [OnChange](../../aspose.svg.dom/document/onchange/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnChange. |
| event [OnClick](../../aspose.svg.dom/document/onclick/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnClick. |
| event [OnCueChange](../../aspose.svg.dom/document/oncuechange/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnCueChange. |
| event [OnDblClick](../../aspose.svg.dom/document/ondblclick/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnDblClick. |
| event [OnDurationChange](../../aspose.svg.dom/document/ondurationchange/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnDurationChange. |
| event [OnEmptied](../../aspose.svg.dom/document/onemptied/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnEmptied. |
| event [OnEnded](../../aspose.svg.dom/document/onended/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnEnded. |
| event [OnError](../../aspose.svg.dom/document/onerror/) | Αποκτά ή ορίζει τον χειριστή γεγονότος για το γεγονός OnError. |
| event [OnFocus](../../aspose.svg.dom/document/onfocus/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnFocus συμβάν. |
| event [OnInput](../../aspose.svg.dom/document/oninput/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnInput συμβάν. |
| event [OnInvalid](../../aspose.svg.dom/document/oninvalid/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnInvalid συμβάν. |
| event [OnKeyDown](../../aspose.svg.dom/document/onkeydown/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnKeyDown συμβάν. |
| event [OnKeyPress](../../aspose.svg.dom/document/onkeypress/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnKeyPress συμβάν. |
| event [OnKeyUp](../../aspose.svg.dom/document/onkeyup/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnKeyUp συμβάν. |
| event [OnLoad](../../aspose.svg.dom/document/onload/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnLoad συμβάν. |
| event [OnLoadedData](../../aspose.svg.dom/document/onloadeddata/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnLoadedData συμβάν. |
| event [OnLoadedMetadata](../../aspose.svg.dom/document/onloadedmetadata/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnLoadedMetadata συμβάν. |
| event [OnLoadStart](../../aspose.svg.dom/document/onloadstart/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnLoadStart συμβάν. |
| event [OnMouseDown](../../aspose.svg.dom/document/onmousedown/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnMouseDown συμβάν. |
| event [OnMouseEnter](../../aspose.svg.dom/document/onmouseenter/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnMouseEnter συμβάν. |
| event [OnMouseLeave](../../aspose.svg.dom/document/onmouseleave/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnMouseLeave συμβάν. |
| event [OnMouseMove](../../aspose.svg.dom/document/onmousemove/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnMouseMove συμβάν. |
| event [OnMouseOut](../../aspose.svg.dom/document/onmouseout/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnMouseOut συμβάν. |
| event [OnMouseOver](../../aspose.svg.dom/document/onmouseover/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnMouseOver συμβάν. |
| event [OnMouseUp](../../aspose.svg.dom/document/onmouseup/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnMouseUp συμβάν. |
| event [OnMouseWheel](../../aspose.svg.dom/document/onmousewheel/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnMouseWheel συμβάν. |
| event [OnPause](../../aspose.svg.dom/document/onpause/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnPause συμβάν. |
| event [OnPlay](../../aspose.svg.dom/document/onplay/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnPlay συμβάν. |
| event [OnPlaying](../../aspose.svg.dom/document/onplaying/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnPlaying συμβάν. |
| event [OnProgress](../../aspose.svg.dom/document/onprogress/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnProgress συμβάν. |
| event [OnRateChange](../../aspose.svg.dom/document/onratechange/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnRateChange συμβάν. |
| event [OnReadyStateChange](../../aspose.svg.dom/document/onreadystatechange/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnReadyStateChange. |
| event [OnReset](../../aspose.svg.dom/document/onreset/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnReset συμβάν. |
| event [OnResize](../../aspose.svg.dom/document/onresize/) | Λαμβάνει ή ορίζει το χειριστή συμβάντος για OnResize συμβάν. |
| event [OnScroll](../../aspose.svg.dom/document/onscroll/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnScroll. |
| event [OnSeeked](../../aspose.svg.dom/document/onseeked/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnSeeked. |
| event [OnSeeking](../../aspose.svg.dom/document/onseeking/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnSeeking. |
| event [OnSelect](../../aspose.svg.dom/document/onselect/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnSelect. |
| event [OnShow](../../aspose.svg.dom/document/onshow/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnShow. |
| event [OnStalled](../../aspose.svg.dom/document/onstalled/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnStalled. |
| event [OnSubmit](../../aspose.svg.dom/document/onsubmit/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnSubmit. |
| event [OnSuspend](../../aspose.svg.dom/document/onsuspend/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnSuspend. |
| event [OnTimeUpdate](../../aspose.svg.dom/document/ontimeupdate/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnTimeUpdate. |
| event [OnToggle](../../aspose.svg.dom/document/ontoggle/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnToggle. |
| event [OnVolumeChange](../../aspose.svg.dom/document/onvolumechange/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnVolumeChange. |
| event [OnWaiting](../../aspose.svg.dom/document/onwaiting/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnWaiting. |

### Δείτε επίσης

* class [Node](../node/)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../aspose.svg.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../aspose.svg.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../aspose.svg.dom.xpath/ixpathevaluator/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
