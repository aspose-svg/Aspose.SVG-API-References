---
title: "IStorage Διεπαφή"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.IStorage διεπαφή. Αυτή η διεπαφή του Web Storage API παρέχει πρόσβαση στη συνεδρία ή στην τοπική αποθήκευση ενός συγκεκριμένου τομέα. Δείτε την προδιαγραφή Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /el/net/aspose.svg.dom/istorage/
---
## IStorage interface

Αυτή η διεπαφή του Web Storage API παρέχει πρόσβαση στην αποθήκευση συνεδρίας ή τοπική αποθήκευση ενός συγκεκριμένου τομέα. Δείτε την προδιαγραφή Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | Επιστρέφει τον αριθμό των ζευγών κλειδί/τιμή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | Αφαιρεί όλα τα ζευγάρια κλειδί/τιμή, εάν υπάρχουν. |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | Επιστρέφει την τρέχουσα τιμή που συσχετίζεται με το δοσμένο κλειδί, ή null εάν το δοσμένο κλειδί δεν υπάρχει. |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | Επιστρέφει το όνομα του n‑ου κλειδιού, ή null εάν το n είναι μεγαλύτερο ή ίσο με τον αριθμό των ζευγών κλειδί/τιμή. |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | Αφαιρεί το ζεύγος κλειδί/τιμή με το δοσμένο κλειδί, εάν υπάρχει ζεύγος κλειδί/τιμή με το δοσμένο κλειδί. |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | Ορίζει την τιμή του ζεύγους που προσδιορίζεται από το κλειδί σε value, δημιουργώντας ένα νέο ζεύγος κλειδί/τιμή εάν δεν υπήρχε προηγουμένως για το κλειδί. |

### Δείτε επίσης

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
