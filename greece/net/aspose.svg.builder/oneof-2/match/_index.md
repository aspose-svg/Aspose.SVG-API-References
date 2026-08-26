---
title: "OneOf-2.Match"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος OneOf Match. Εκτελεί μία από τις παρεχόμενες συναρτήσεις βάσει του υποκείμενου τύπου της τιμής"
type: docs
weight: 20
url: /el/net/aspose.svg.builder/oneof-2/match/
---
## OneOf<T1,T2>.Match<TResult> method

Εκτελεί μία από τις παρεχόμενες συναρτήσεις με βάση τον υποκείμενο τύπο της τιμής.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2)
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TResult | Ο τύπος επιστροφής των συναρτήσεων. |
| func1 | Η συνάρτηση που θα εκτελεστεί εάν η τιμή είναι τύπου T1. |
| func2 | Η συνάρτηση που θα εκτελεστεί εάν η τιμή είναι τύπου T2. |

### Τιμή Επιστροφής

Το αποτέλεσμα της εκτελεσθείσας συνάρτησης.

### Δείτε επίσης

* class [OneOf&lt;T1,T2&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
