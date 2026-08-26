---
title: "Document.Navigate"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Document Navigate. Φορτώνει το έγγραφο στη συγκεκριμένη διεύθυνση Uniform Resource Locator URL στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο"
type: docs
weight: 1010
url: /el/net/aspose.svg.dom/document/navigate/
---
## Navigate(*string*) {#navigate_8}

Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(string address)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| address | String | Η διεύθυνση του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |

### Δείτε επίσης

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/)*) {#navigate_2}

Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(Url url)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Το URL του εγγράφου. |

### Δείτε επίσης

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string*) {#navigate_11}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(string content, string baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | String | Το περιεχόμενο του εγγράφου. |
| baseUri | String | Η βασική διεύθυνση URI για την επίλυση σχετικών πόρων. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει ένα απόλυτο URL. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/)*) {#navigate_9}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(string content, Url baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | String | Το περιεχόμενο του εγγράφου. |
| baseUri | Url | Η βασική διεύθυνση URI για την επίλυση σχετικών πόρων. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string*) {#navigate_6}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από τη τρέχουσα θέση στη ροή.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | Stream | Το περιεχόμενο του εγγράφου. |
| baseUri | String | Η βασική διεύθυνση URI για την επίλυση σχετικών πόρων. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει ένα απόλυτο URL. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/)*) {#navigate_4}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από τη τρέχουσα θέση στη ροή.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | Stream | Το περιεχόμενο του εγγράφου. |
| baseUri | Url | Η βασική διεύθυνση URI για την επίλυση σχετικών πόρων. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/)*) {#navigate}

Φορτώνει το έγγραφο βάσει του καθορισμένου αντικειμένου αίτησης, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(RequestMessage request)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| request | RequestMessage | Το αντικείμενο αίτησης που χρησιμοποιείται για τη φόρτωση του περιεχομένου του εγγράφου. |

### Δείτε επίσης

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, CancellationToken*) {#navigate_13}

Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(string address, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| address | String | Η διεύθυνση του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| cancellationToken | CancellationToken | Το token ακύρωσης. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| OperationCanceledException | Η λειτουργία ακυρώθηκε. |

### Δείτε επίσης

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_3}

Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(Url url, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Το URL του εγγράφου. |
| cancellationToken | CancellationToken | Το token ακύρωσης. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| OperationCanceledException | Η λειτουργία ακυρώθηκε. |

### Δείτε επίσης

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string, CancellationToken*) {#navigate_12}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(string content, string baseUri, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | String | Το περιεχόμενο του εγγράφου. |
| baseUri | String | Η βασική διεύθυνση URI για την επίλυση σχετικών πόρων. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει ένα απόλυτο URL. |
| cancellationToken | CancellationToken | Το token ακύρωσης. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| OperationCanceledException | Η λειτουργία ακυρώθηκε. |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_10}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(string content, Url baseUri, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | String | Το περιεχόμενο του εγγράφου. |
| baseUri | Url | Η βασική διεύθυνση URI για την επίλυση σχετικών πόρων. |
| cancellationToken | CancellationToken | Το token ακύρωσης. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| OperationCanceledException | Η λειτουργία ακυρώθηκε. |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string, CancellationToken*) {#navigate_7}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από τη τρέχουσα θέση στη ροή.

```csharp
public void Navigate(Stream content, string baseUri, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | Stream | Το περιεχόμενο του εγγράφου. |
| baseUri | String | Η βασική διεύθυνση URI για την επίλυση σχετικών πόρων. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει ένα απόλυτο URL. |
| cancellationToken | CancellationToken | Το token ακύρωσης. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| OperationCanceledException | Η λειτουργία ακυρώθηκε. |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_5}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από τη τρέχουσα θέση στη ροή.

```csharp
public void Navigate(Stream content, Url baseUri, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | Stream | Το περιεχόμενο του εγγράφου. |
| baseUri | Url | Η βασική διεύθυνση URI για την επίλυση σχετικών πόρων. |
| cancellationToken | CancellationToken | Το token ακύρωσης. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| OperationCanceledException | Η λειτουργία ακυρώθηκε. |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/), CancellationToken*) {#navigate_1}

Φορτώνει το έγγραφο βάσει του καθορισμένου αντικειμένου αίτησης, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(RequestMessage request, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| request | RequestMessage | Το αντικείμενο αίτησης που χρησιμοποιείται για τη φόρτωση του περιεχομένου του εγγράφου. |
| cancellationToken | CancellationToken | Το token ακύρωσης. |

### Exceptions

| εξαίρεση | condition |
| --- | --- |
| OperationCanceledException | Η λειτουργία ακυρώθηκε. |

### Δείτε επίσης

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
