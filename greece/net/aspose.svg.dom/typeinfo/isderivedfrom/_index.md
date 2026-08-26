---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος TypeInfo IsDerivedFrom. Αυτή η μέθοδος επιστρέφει εάν υπάρχει παράγωγος μεταξύ του ορισμού τύπου αναφοράς, δηλαδή του TypeInfo στο οποίο καλείται η μέθοδος, και του άλλου ορισμού τύπου, δηλαδή του ορισμού που περνιέται ως παράμετρος"
type: docs
weight: 30
url: /el/net/aspose.svg.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Αυτή η μέθοδος επιστρέφει εάν υπάρχει παράγωγος μεταξύ του ορισμού τύπου αναφοράς, δηλαδή του TypeInfo στο οποίο καλείται η μέθοδος, και του άλλου ορισμού τύπου, δηλαδή αυτού που περνιέται ως παράμετρος.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| typeNamespaceArg | String | το namespace του άλλου ορισμού τύπου |
| typeNameArg | String | το όνομα του άλλου ορισμού τύπου. |
| derivationMethod | UInt64 | ο τύπος κληρονομικότητας και οι συνθήκες που εφαρμόζονται μεταξύ δύο τύπων, όπως περιγράφεται στη λίστα των σταθερών που παρέχονται σε αυτή τη διεπαφή. |

### Τιμή Επιστροφής

Εάν το σχήμα του εγγράφου είναι DTD ή δεν υπάρχει σχήμα συσχετισμένο με το έγγραφο, αυτή η μέθοδος θα επιστρέφει πάντα false. Εάν το σχήμα του εγγράφου είναι XML Schema, η μέθοδος θα επιστρέφει true εάν ο ορισμός τύπου αναφοράς προέρχεται από τον άλλο ορισμό τύπου σύμφωνα με την παράμετρο κληρονομικότητας. Εάν η τιμή της παραμέτρου είναι 0 (κανένα bit δεν είναι ορισμένο σε 1 για την παράμετρο derivationMethod), η μέθοδος θα επιστρέφει true εάν ο άλλος ορισμός τύπου μπορεί να προσεγγιστεί επαναλαμβάνοντας οποιονδήποτε συνδυασμό των {base type definition}, {item type definition} ή {member type definitions} από τον ορισμό τύπου αναφοράς.

### Δείτε επίσης

* class [TypeInfo](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
