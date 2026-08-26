---
title: "CSSValueList Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Css.CSSValueList κλάση. Η διεπαφή CSSValueList παρέχει την αφαίρεση μιας διατεταγμένης συλλογής τιμών CSS."
type: docs
weight: 2500
url: /el/net/aspose.svg.dom.css/cssvaluelist/
---
## CSSValueList class

Η διεπαφή CSSValueList παρέχει την αφαιρετική αναπαράσταση μιας διατεταγμένης συλλογής τιμών CSS.

```csharp
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `CSSValueList`. |
| [CSSValueList](cssvaluelist/#constructor_1)(*params CSSValue[]*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `CSSValueList`. |
| [CSSValueList](cssvaluelist/#constructor_2)(*IEnumerable&lt;CSSValue&gt;*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `CSSValueList`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| override [CSSText](../../aspose.svg.dom.css/cssvaluelist/csstext/) { get; set; } | Η ιδιότητα CSSText της διεπαφής [`CSSValue`](../cssvalue/) αντιπροσωπεύει την τρέχουσα υπολογισμένη τιμή ιδιότητας CSS. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Ένας κώδικας που ορίζει τον τύπο της τιμής. |
| [Item](../../aspose.svg.dom.css/cssvaluelist/item/) { get; } | Λαμβάνει το [`CSSValue`](../cssvalue/) στον καθορισμένο δείκτη. |
| [Length](../../aspose.svg.dom.css/cssvaluelist/length/) { get; } | Η ιδιότητα length μόνο για ανάγνωση της διεπαφής CSSValueList αντιπροσωπεύει τον αριθμό των CSSValues στη λίστα. Το εύρος των έγκυρων τιμών των δεικτών είναι από 0 έως length-1, συμπεριλαμβανομένου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Καθορίζει εάν το συγκεκριμένο Object είναι ίσο με αυτήν την παρουσία. |
| [GetEnumerator](../../aspose.svg.dom.css/cssvaluelist/getenumerator/)() | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvaluelist/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου αντικειμένου ECMAScript. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία. |

### Δείτε επίσης

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
