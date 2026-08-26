---
title: "SVGDocument.Save"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Save του SVGDocument. Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από το url. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε διπλανό φάκελο του οποίου το όνομα θα δημιουργηθεί ως output_file_name _files. Εάν το καθορισμένο url τελειώνει με .svgz, το έγγραφο θα αποθηκευτεί ως συμπιεσμένο αρχείο SVGZ"
type: docs
weight: 90
url: /el/net/aspose.svg/svgdocument/save/
---
## Save(*[Url](../../url/)*) {#save_4}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από το `url`. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε γειτονικό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files". Εάν το καθορισμένο `url` λήγει σε ".svgz", το έγγραφο θα αποθηκευτεί ως συμπιεσμένο αρχείο SVGZ.

```csharp
public void Save(Url url)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπικό URL για το αρχείο εξόδου. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentException | Εγείρεται εάν το καθορισμένο `url` δεν είναι έγκυρο τοπικό URL αρχείου. |

### Δείτε επίσης

* class [Url](../../url/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string*) {#save_8}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από το `path`. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε γειτονικό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files". Εάν το καθορισμένο `url` λήγει σε ".svgz", το έγγραφο θα αποθηκευτεί ως συμπιεσμένο αρχείο SVGZ.

```csharp
public void Save(string path)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Τοπική διαδρομή για το αρχείο εξόδου. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentException | Εγείρεται εάν η καθορισμένη `path` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)*) {#save}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους πόρους χρησιμοποιώντας τον [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |

### Δείτε επίσης

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_9}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από `path`. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Τοπική διαδρομή για το αρχείο εξόδου. |
| saveFormat | SVGSaveFormat | Μορφή στην οποία αποθηκεύεται το έγγραφο. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentException | Εγείρεται εάν η καθορισμένη `path` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |
| ArgumentOutOfRangeException | Εγείρεται όταν η καθορισμένη τιμή *saveFormat* δεν αναγνωρίζεται από την τρέχουσα υλοποίηση. |

### Δείτε επίσης

* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_1}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους πόρους χρησιμοποιώντας τον [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | Μορφή στην οποία αποθηκεύεται το έγγραφο. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentOutOfRangeException | Εγείρεται όταν η καθορισμένη τιμή *saveFormat* δεν αναγνωρίζεται από την τρέχουσα υλοποίηση. |

### Δείτε επίσης

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_10}

Αποθηκεύει το έγγραφο ως αρχείο `.svg` στη τοπική διαδρομή που καθορίζεται από *path*. Όλοι οι εξωτερικοί πόροι γράφονται σε έναν αδελφό φάκελο με όνομα `{output_file_name}_files`.

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Απόλυτη ή σχετική διαδρομή του στόχου αρχείου `.svg`. |
| saveOptions | SVGSaveOptions | Επιλογές που ελέγχουν τη σειριοποίηση plain‑SVG. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentException | Εκτοξεύεται εάν το *path* δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_2}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους πόρους χρησιμοποιώντας τον [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | Επιλογές αποθήκευσης SVG. |

### Δείτε επίσης

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_5}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από `url`. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπικό URL για το αρχείο εξόδου. |
| saveFormat | SVGSaveFormat | Μορφή στην οποία αποθηκεύεται το έγγραφο. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentException | Εκτοξεύεται όταν το *url* δεν αντιπροσωπεύει έγκυρη τοπική θέση αρχείου (π.χ., είναι null, σχετικό ή δείχνει σε μη‑αρχείο σχήμα). |
| ArgumentOutOfRangeException | Εκτοξεύεται όταν η παρεχόμενη τιμή *saveFormat* δεν αναγνωρίζεται από την τρέχουσα υλοποίηση. |

### Δείτε επίσης

* class [Url](../../url/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_6}

Αποθηκεύει το έγγραφο ως αρχείο `.svg` στο *url*. Όλοι οι εξωτερικοί πόροι τοποθετούνται σε έναν αδελφό φάκελο με όνομα `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική διαδρομή του στόχου αρχείου `.svg`. |
| saveOptions | SVGSaveOptions | Επιλογές που ελέγχουν τη σειριοποίηση plain‑SVG. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentException | Εκτοξεύεται εάν το *url* δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [Url](../../url/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_7}

Αποθηκεύει το έγγραφο ως συμπιεσμένο αρχείο `.svgz` στο *url*. Όλοι οι εξωτερικοί πόροι τοποθετούνται σε έναν αδελφό φάκελο με όνομα `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGZSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική διαδρομή του στόχου αρχείου `.svgz`. |
| saveOptions | SVGZSaveOptions | Επιλογές που ελέγχουν τη σειριοποίηση SVGZ. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentException | Εκτοξεύεται εάν το *url* δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [Url](../../url/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_3}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους σχετικούς πόρους χρησιμοποιώντας τον καθορισμένο [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGZSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων για τη διαχείριση των πόρων του εγγράφου, όπως το σύστημα αρχείων ή η αποθήκευση στη μνήμη. |
| saveOptions | SVGZSaveOptions | Επιλογές που καθορίζουν πρόσθετες παραμέτρους αποθήκευσης, όπως προτιμήσεις διανυσματοποίησης. |

### Δείτε επίσης

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_11}

Αποθηκεύει το έγγραφο ως συμπιεσμένο αρχείο `.svgz` στη τοπική διαδρομή που καθορίζεται από *path*. Όλοι οι εξωτερικοί πόροι γράφονται σε έναν αδελφό φάκελο με όνομα `{output_file_name}_files`.

```csharp
public void Save(string path, SVGZSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Απόλυτη ή σχετική διαδρομή του στόχου αρχείου `.svgz`. |
| saveOptions | SVGZSaveOptions | Επιλογές που ελέγχουν τη σειριοποίηση SVGZ. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentException | Εκτοξεύεται εάν το *path* δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
