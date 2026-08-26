---
title: "Node.TextContent"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Ιδιότητα Node TextContent. Αντιπροσωπεύει το περιεχόμενο κειμένου του κόμβου και των απογόνων του"
type: docs
weight: 160
url: /el/net/aspose.svg.dom/node/textcontent/
---
## Node.TextContent property

Αναπαριστά το κείμενο περιεχομένου του κόμβου και των απογόνων του.

```csharp
public virtual string TextContent { get; set; }
```

### Property Value

Μια συμβολοσειρά ή null. Η τιμή του εξαρτάται από την κατάσταση:

Εάν ο κόμβος είναι ένα έγγραφο ή ένα doctype, το `TextContent` επιστρέφει null. Σημείωση: Για να λάβετε όλο το κείμενο και τα δεδομένα CDATA για ολόκληρο το έγγραφο, χρησιμοποιήστε

```csharp
document.DocumentElement.TextContent
```

.Εάν ο κόμβος είναι μια ενότητα CDATA, ένα σχόλιο, μια οδηγία επεξεργασίας ή ένας κόμβος κειμένου, το `TextContent` επιστρέφει ή ορίζει το κείμενο μέσα στον κόμβο, δηλαδή το [`NodeValue`](../nodevalue/). Για άλλους τύπους κόμβων, το `TextContent` επιστρέφει τη συνένωση του `TextContent` κάθε παιδικού κόμβου, εξαιρώντας τα σχόλια και τις οδηγίες επεξεργασίας.

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-textcontent).

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
