---
title: "IWindow.Btoa"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "IWindow Btoa method. Λαμβάνει τα δεδομένα εισόδου με τη μορφή μιας συμβολοσειράς Unicode που περιέχει μόνο χαρακτήρες στο εύρος U0000 έως U00FF, ο καθένας αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, και τα μετατρέπει στην αναπαράσταση base64 που επιστρέφει."
type: docs
weight: 130
url: /el/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

Δέχεται τα δεδομένα εισόδου, με τη μορφή μιας συμβολοσειράς Unicode που περιέχει μόνο χαρακτήρες στο εύρος U+0000 έως U+00FF, ο καθένας αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, και το μετατρέπει στην αναπαράσταση base64, την οποία επιστρέφει.

```csharp
public string Btoa(string data)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | String | Η συμβολοσειρά Unicode που περιέχει μόνο χαρακτήρες στο εύρος U+0000 έως U+00FF. |

### Τιμή Επιστροφής

Η συμβολοσειρά base64.

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Εκτοπίζει μια εξαίρεση DOMException "InvalidCharacterError" εάν η συμβολοσειρά εισόδου περιέχει οποιουσδήποτε χαρακτήρες εκτός του εύρους. |

### Δείτε επίσης

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
