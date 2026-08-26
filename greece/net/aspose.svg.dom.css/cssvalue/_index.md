---
title: "CSSValue Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Css.CSSValue κλάση. Αντιπροσωπεύει μια απλή ή σύνθετη τιμή. Ένα αντικείμενο CSSValue εμφανίζεται μόνο σε ένα πλαίσιο ιδιότητας CSS."
type: docs
weight: 2490
url: /el/net/aspose.svg.dom.css/cssvalue/
---
## CSSValue class

Αντιπροσωπεύει μια απλή ή σύνθετη τιμή. Ένα αντικείμενο CSSValue εμφανίζεται μόνο σε ένα πλαίσιο ιδιότητας CSS.

```csharp
public abstract class CSSValue : DOMObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | Η ιδιότητα CSSText της διεπαφής `CSSValue` αντιπροσωπεύει την τρέχουσα υπολογισμένη τιμή ιδιότητας CSS. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Ένας κώδικας που ορίζει τον τύπο της τιμής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Καθορίζει εάν το συγκεκριμένο Object είναι ίσο με αυτήν την παρουσία. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου αντικειμένου ECMAScript. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία. |
| [operator ==](../../aspose.svg.dom.css/cssvalue/op_equality/) | Υλοποιεί τον τελεστή ==. |
| [operator !=](../../aspose.svg.dom.css/cssvalue/op_inequality/) | Υλοποιεί τον τελεστή !=. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.svg.dom.css/cssvalue/css_custom/) | Η τιμή είναι προσαρμοσμένη τιμή. |
| const [CSS_INHERIT](../../aspose.svg.dom.css/cssvalue/css_inherit/) | Η τιμή κληρονομείται και το cssText περιέχει \"inherit\". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.svg.dom.css/cssvalue/css_primitive_value/) | Η τιμή είναι μια πρωτόγονη τιμή και μια παρουσία της διεπαφής CSSPrimitiveValue μπορεί να ληφθεί χρησιμοποιώντας μεθόδους μετατροπής ειδικές για το binding σε αυτήν την παρουσία της διεπαφής CSSValue. |
| const [CSS_VALUE_LIST](../../aspose.svg.dom.css/cssvalue/css_value_list/) | Η τιμή είναι μια λίστα CSSValue και μια παρουσία της διεπαφής CSSValueList μπορεί να ληφθεί χρησιμοποιώντας μεθόδους μετατροπής ειδικές για τη σύνδεση σε αυτήν την παρουσία της διεπαφής CSSValue. |

### Δείτε επίσης

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
