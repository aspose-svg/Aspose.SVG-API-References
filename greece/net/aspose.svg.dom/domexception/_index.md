---
title: "DOMException κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.DOMException κλάση. Η διεπαφή DOMException αντιπροσωπεύει ένα ανώμαλο γεγονός που ονομάζεται εξαίρεση, το οποίο συμβαίνει ως αποτέλεσμα κλήσης μεθόδου ή πρόσβασης σε ιδιότητα ενός web API. Αυτό είναι ουσιαστικά ο τρόπος με τον οποίο περιγράφονται οι συνθήκες σφάλματος στα web API"
type: docs
weight: 2790
url: /el/net/aspose.svg.dom/domexception/
---
## DOMException class

Η διεπαφή DOMException αντιπροσωπεύει ένα ανώμαλο γεγονός (που ονομάζεται εξαίρεση) που συμβαίνει ως αποτέλεσμα κλήσης μιας μεθόδου ή πρόσβασης σε ιδιότητα ενός web API. Αυτό είναι ουσιαστικά ο τρόπος με τον οποίο περιγράφονται οι συνθήκες σφάλματος στα web APIs.

```csharp
public class DOMException : PlatformException
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DOMException](domexception/#constructor)(*string*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `DOMException`. |
| [DOMException](domexception/#constructor_1)(*string, string*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `DOMException`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Code](../../aspose.svg.dom/domexception/code/) { get; } | Επιστρέφει μια τιμή που περιέχει μία από τις σταθερές κωδικών σφάλματος, ή 0 αν καμία δεν ταιριάζει. Αυτό το πεδίο χρησιμοποιείται για ιστορικούς λόγους. |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| override [Message](../../aspose.svg.dom/domexception/message/) { get; } | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει ένα μήνυμα ή περιγραφή που σχετίζεται με το δεδομένο όνομα σφάλματος. |
| [Name](../../aspose.svg.dom/domexception/name/) { get; } | Επιστρέφει μια συμβολοσειρά που περιέχει μία από τις συμβολοσειρές που σχετίζονται με ένα όνομα σφάλματος. |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [ABORT_ERR](../../aspose.svg.dom/domexception/abort_err/) | Η λειτουργία ματαιώθηκε. |
| const [DATA_CLONE_ERR](../../aspose.svg.dom/domexception/data_clone_err/) | Το αντικείμενο δεν μπορεί να κλωνοποιηθεί. |
| const [DOMSTRING_SIZE_ERR](../../aspose.svg.dom/domexception/domstring_size_err/) | Εάν το καθορισμένο εύρος κειμένου δεν χωράει σε ένα DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.svg.dom/domexception/hierarchy_request_err/) | Εάν οποιοδήποτε Node εισαχθεί κάπου που δεν του ανήκει. |
| const [INDEX_SIZE_ERR](../../aspose.svg.dom/domexception/index_size_err/) | Εάν το δείκτη ή το μέγεθος είναι αρνητικό, ή μεγαλύτερο από την επιτρεπόμενη τιμή. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.svg.dom/domexception/inuse_attribute_err/) | Εάν γίνει προσπάθεια προσθήκης ενός χαρακτηριστικού που χρησιμοποιείται ήδη αλλού. |
| const [INVALID_ACCESS_ERR](../../aspose.svg.dom/domexception/invalid_access_err/) | Εάν μια παράμετρος ή μια λειτουργία δεν υποστηρίζεται από το υποκείμενο αντικείμενο. |
| const [INVALID_CHARACTER_ERR](../../aspose.svg.dom/domexception/invalid_character_err/) | Εάν καθοριστεί ένας μη έγκυρος ή παράνομος χαρακτήρας, όπως σε ένα όνομα XML. |
| const [INVALID_EXPRESSION_ERR](../../aspose.svg.dom/domexception/invalid_expression_err/) | Η έκφραση έχει σφάλμα σύνταξης ή αλλιώς δεν είναι έγκυρη έκφραση σύμφωνα με τους κανόνες του συγκεκριμένου XPathEvaluator ή περιέχει εξειδικευμένες λειτουργίες επέκτασης ή μεταβλητές που δεν υποστηρίζονται από αυτήν την υλοποίηση. |
| const [INVALID_MODIFICATION_ERR](../../aspose.svg.dom/domexception/invalid_modification_err/) | Εάν γίνει προσπάθεια τροποποίησης του τύπου του υποκείμενου αντικειμένου. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.svg.dom/domexception/invalid_node_type_err/) | Ο παρεχόμενος κόμβος είναι εσφαλμένος ή έχει εσφαλμένο πρόγονο για αυτήν τη λειτουργία. |
| const [INVALID_STATE_ERR](../../aspose.svg.dom/domexception/invalid_state_err/) | Εάν γίνει προσπάθεια χρήσης ενός αντικείμενου που δεν είναι, ή δεν είναι πλέον, χρησιμοποιήσιμο. |
| const [NAMESPACE_ERR](../../aspose.svg.dom/domexception/namespace_err/) | Εάν γίνει προσπάθεια δημιουργίας ή αλλαγής ενός αντικειμένου με τρόπο που είναι λανθασμένος ως προς τα namespaces. |
| const [NETWORK_ERR](../../aspose.svg.dom/domexception/network_err/) | Παρουσιάστηκε σφάλμα δικτύου. |
| const [NOT_FOUND_ERR](../../aspose.svg.dom/domexception/not_found_err/) | Εάν γίνει προσπάθεια αναφοράς σε ένα Node σε ένα πλαίσιο όπου δεν υπάρχει. |
| const [NOT_SUPPORTED_ERR](../../aspose.svg.dom/domexception/not_supported_err/) | Εάν η υλοποίηση δεν υποστηρίζει τον ζητούμενο τύπο αντικειμένου ή λειτουργίας. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_data_allowed_err/) | Εάν καθοριστούν δεδομένα για ένα Node που δεν υποστηρίζει δεδομένα. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_modification_allowed_err/) | Εάν γίνει προσπάθεια τροποποίησης ενός αντικειμένου όπου οι τροποποιήσεις δεν επιτρέπονται. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.svg.dom/domexception/quota_exceeded_err/) | Το όριο έχει ξεπεραστεί. |
| const [SECURITY_ERR](../../aspose.svg.dom/domexception/security_err/) | Η λειτουργία δεν είναι ασφαλής. |
| const [SYNTAX_ERR](../../aspose.svg.dom/domexception/syntax_err/) | Εάν έχει καθοριστεί μια μη έγκυρη ή παράνομη συμβολοσειρά. |
| const [TIMEOUT_ERR](../../aspose.svg.dom/domexception/timeout_err/) | Η λειτουργία έληξε το χρονικό όριο. |
| const [TYPE_ERR](../../aspose.svg.dom/domexception/type_err/) | Η έκφραση δεν μπορεί να μετατραπεί ώστε να επιστρέψει τον καθορισμένο τύπο. |
| const [TYPE_MISMATCH_ERR](../../aspose.svg.dom/domexception/type_mismatch_err/) | Εάν ο τύπος ενός αντικειμένου είναι ασύμβατος με τον αναμενόμενο τύπο της παραμέτρου που σχετίζεται με το αντικείμενο. |
| const [URL_MISMATCH_ERR](../../aspose.svg.dom/domexception/url_mismatch_err/) | Το δοσμένο URL δεν ταιριάζει με άλλο URL. |
| const [VALIDATION_ERR](../../aspose.svg.dom/domexception/validation_err/) | Εάν μια κλήση σε μέθοδο όπως insertBefore ή removeChild καθιστούσε το Node μη έγκυρο σε σχέση με την «μερική εγκυρότητα», αυτή η εξαίρεση θα εγερθεί και η λειτουργία δεν θα εκτελεστεί. Αυτός ο κώδικας χρησιμοποιείται στο [DOM Level 3 Validation]. Ανατρέξτε σε αυτήν την προδιαγραφή για περισσότερες πληροφορίες. |
| const [WRONG_DOCUMENT_ERR](../../aspose.svg.dom/domexception/wrong_document_err/) | Εάν ένα Node χρησιμοποιείται σε διαφορετικό έγγραφο από αυτό που το δημιούργησε (που δεν το υποστηρίζει). |

### Δείτε επίσης

* class [PlatformException](../../aspose.svg/platformexception/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
