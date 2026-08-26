---
title: "Aspose.Svg.Dom.Events"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Το namespace Aspose.Svg.Dom.Events παρέχει αντικείμενα για τυχόν γεγονότα που σχετίζονται με την ενημέρωση του DOM. Περιλαμβάνει συνδρομή σε συγκεκριμένες παρατηρήσεις συμφραζομένων που σχετίζονται με το γεγονός, καθώς και δημιουργία προσαρμοσμένων γεγονότων."
type: docs
weight: 100
url: /el/net/aspose.svg.dom.events/
---
Ο χώρος ονομάτων **Aspose.Svg.Dom.Events** παρέχει αντικείμενα για οποιαδήποτε γεγονότα σχετιζόμενα με την ενημέρωση του DOM. Περιλαμβάνει συνδρομή σε συγκεκριμένη παρατήρηση συμφραζομένων που σχετίζονται με το γεγονός, καθώς και δημιουργία προσαρμοσμένων γεγονότων.

## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [CustomEvent](./customevent/) | Γεγονότα που χρησιμοποιούν τη διεπαφή CustomEvent μπορούν να χρησιμοποιηθούν για τη μεταφορά προσαρμοσμένων δεδομένων. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | Το [`DocumentLoadErrorEvent`](../aspose.svg.dom.events/documentloaderrorevent/) εμφανίζεται όταν ο ζητούμενος πόρος δεν είναι διαθέσιμος. |
| [DOMEventHandler](./domeventhandler/) | Αντιπροσωπεύει την κλήση επιστροφής για τη διαχείριση γεγονότων. |
| [ErrorEvent](./errorevent/) | Το [`ErrorEvent`](../aspose.svg.dom.events/errorevent/) παρέχει πληροφορίες συμφραζομένων σχετικά με σφάλματα που συνέβησαν κατά την εκτέλεση. |
| [Event](./event/) | Το [`Event`](../aspose.svg.dom.events/event/) χρησιμοποιείται για την παροχή πληροφοριών συμφραζομένων σχετικά με ένα γεγονός στον επεξεργαστή που επεξεργάζεται το γεγονός. |
| [FocusEvent](./focusevent/) | Η διεπαφή FocusEvent παρέχει συγκεκριμένες πληροφορίες συμφραζομένων που σχετίζονται με γεγονότα εστίασης. |
| [InputEvent](./inputevent/) | Τα γεγονότα εισόδου αποστέλλονται ως ειδοποιήσεις όποτε ενημερώνεται το DOM. |
| [KeyboardEvent](./keyboardevent/) | Η διεπαφή KeyboardEvent παρέχει συγκεκριμένες πληροφορίες συμφραζομένων που σχετίζονται με συσκευές πληκτρολογίου. Κάθε γεγονός πληκτρολογίου αναφέρεται σε ένα πλήκτρο χρησιμοποιώντας μια τιμή. Τα γεγονότα πληκτρολογίου συνήθως κατευθύνονται προς το στοιχείο που έχει την εστίαση. |
| [MouseEvent](./mouseevent/) | Η διεπαφή MouseEvent παρέχει συγκεκριμένες πληροφορίες συμφραζομένων που σχετίζονται με γεγονότα ποντικιού. |
| [UIEvent](./uievent/) | Η διεπαφή UIEvent παρέχει συγκεκριμένες πληροφορίες συμφραζομένων που σχετίζονται με γεγονότα διεπαφής χρήστη. |
| [WheelEvent](./wheelevent/) | Η διεπαφή WheelEvent παρέχει συγκεκριμένες πληροφορίες συμφραζομένων που σχετίζονται με γεγονότα τροχού. Για να δημιουργήσετε μια παρουσία της διεπαφής WheelEvent, χρησιμοποιήστε τον κατασκευαστή WheelEvent, περνώντας ένα προαιρετικό λεξικό WheelEventInit. |
## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | Η διεπαφή [`IDocumentEvent`](../aspose.svg.dom.events/idocumentevent/) παρέχει έναν μηχανισμό με τον οποίο ο χρήστης μπορεί να δημιουργήσει ένα [`Event`](../aspose.svg.dom.events/event/) τύπου που υποστηρίζεται από την υλοποίηση. |
| [IEventListener](./ieventlistener/) | Το [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) διασύνδεση είναι η κύρια μέθοδος για τη διαχείριση συμβάντων. Οι χρήστες υλοποιούν το [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) διασύνδεση και καταχωρούν τον ακροατή τους σε ένα [`EventTarget`](../aspose.svg.dom/eventtarget/) χρησιμοποιώντας τη μέθοδο [`AddEventListener`](../aspose.svg.dom/eventtarget/addeventlistener/). Οι χρήστες θα πρέπει επίσης να αφαιρέσουν το [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) από το [`EventTarget`](../aspose.svg.dom/eventtarget/) μετά την ολοκλήρωση της χρήσης του ακροατή. |
| [IEventTarget](./ieventtarget/) | Το [`EventTarget`](../aspose.svg.dom/eventtarget/) διασύνδεση υλοποιείται από όλους τους Κόμβους σε μια υλοποίηση που υποστηρίζει το μοντέλο συμβάντων DOM. Συνεπώς, αυτή η διασύνδεση μπορεί να ληφθεί χρησιμοποιώντας μεθόδους μετατροπής ειδικές για το binding σε μια παρουσία του διασύνδεσης Node. Η διασύνδεση επιτρέπει την εγγραφή και αφαίρεση ακροατών συμβάντων σε ένα [`EventTarget`](../aspose.svg.dom/eventtarget/) και την αποστολή συμβάντων σε αυτό το [`IEventTarget`](../aspose.svg.dom.events/ieventtarget/). |
