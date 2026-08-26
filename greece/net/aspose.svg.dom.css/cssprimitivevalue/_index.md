---
title: "Κλάση CSSPrimitiveValue"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Κλάση Aspose.Svg.Dom.Css.CSSPrimitiveValue. Η διεπαφή CSSPrimitiveValue αντιπροσωπεύει μια μοναδική τιμή CSS. Αυτή η διεπαφή μπορεί να χρησιμοποιηθεί για να προσδιορίσει την τιμή μιας συγκεκριμένης ιδιότητας στυλ που είναι αυτή τη στιγμή ορισμένη σε ένα μπλοκ ή για να ορίσει ρητά μια συγκεκριμένη ιδιότητα στυλ μέσα στο μπλοκ. Μια παρουσία αυτής της διεπαφής μπορεί να ληφθεί από τη μέθοδο getPropertyCSSValue της διεπαφής CSSStyleDeclaration. Ένα αντικείμενο CSSPrimitiveValue εμφανίζεται μόνο σε ένα πλαίσιο ιδιότητας CSS."
type: docs
weight: 2480
url: /el/net/aspose.svg.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

Η διεπαφή CSSPrimitiveValue αντιπροσωπεύει μια μοναδική τιμή CSS. Αυτή η διεπαφή μπορεί να χρησιμοποιηθεί για τον καθορισμό της τιμής μιας συγκεκριμένης ιδιότητας στυλ που είναι αυτή τη στιγμή ορισμένη σε ένα μπλοκ ή για τον ορισμό μιας συγκεκριμένης ιδιότητας στυλ ρητά μέσα στο μπλοκ. Μια παρουσία αυτής της διεπαφής μπορεί να ληφθεί από τη μέθοδο getPropertyCSSValue της διεπαφής CSSStyleDeclaration. Ένα αντικείμενο CSSPrimitiveValue εμφανίζεται μόνο σε ένα πλαίσιο ιδιότητας CSS.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | Η ιδιότητα CSSText της διεπαφής [`CSSValue`](../cssvalue/) αντιπροσωπεύει την τρέχουσα υπολογισμένη τιμή ιδιότητας CSS. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Ένας κώδικας που ορίζει τον τύπο της τιμής. |
| [PrimitiveType](../../aspose.svg.dom.css/cssprimitivevalue/primitivetype/) { get; } | Ο τύπος της τιμής όπως ορίζεται από τις παραπάνω σταθερές. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Καθορίζει εάν το συγκεκριμένο Object είναι ίσο με αυτήν την παρουσία. |
| abstract [GetCounterValue](../../aspose.svg.dom.css/cssprimitivevalue/getcountervalue/)() | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση της τιμής Counter. Εάν αυτή η τιμή CSS δεν περιέχει τιμή counter, εγείρεται μια DOMException. Η τροποποίηση της αντίστοιχης ιδιότητας στυλ μπορεί να επιτευχθεί χρησιμοποιώντας τη διεπαφή Counter. |
| abstract [GetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/getfloatvalue/)(*ushort*) | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση μιας τιμής float σε συγκεκριμένη μονάδα. Εάν αυτή η τιμή CSS δεν περιέχει τιμή float ή δεν μπορεί να μετατραπεί στην καθορισμένη μονάδα, εγείρεται μια DOMException. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία. |
| abstract [GetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/getintvalue/)(*ushort*) | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση μιας τιμής int σε συγκεκριμένη μονάδα. Εάν αυτή η τιμή CSS δεν περιέχει τιμή int ή δεν μπορεί να μετατραπεί στην καθορισμένη μονάδα, εγείρεται μια DOMException. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου αντικειμένου ECMAScript. |
| abstract [GetRectValue](../../aspose.svg.dom.css/cssprimitivevalue/getrectvalue/)() | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση της τιμής Rect. Εάν αυτή η τιμή CSS δεν περιέχει τιμή rect, εγείρεται μια DOMException. Η τροποποίηση της αντίστοιχης ιδιότητας στυλ μπορεί να επιτευχθεί χρησιμοποιώντας τη διεπαφή Rect. |
| abstract [GetRGBColorValue](../../aspose.svg.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση του χρώματος RGB. Εάν αυτή η τιμή CSS δεν περιέχει τιμή χρώματος RGB, εγείρεται μια DOMException. Η τροποποίηση της αντίστοιχης ιδιότητας στυλ μπορεί να επιτευχθεί χρησιμοποιώντας τη διεπαφή RGBColor. |
| abstract [GetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/getstringvalue/)() | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση της τιμής string. Εάν η τιμή CSS δεν περιέχει τιμή string, εγείρεται μια DOMException. |
| abstract [SetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/setfloatvalue/)(*ushort, float*) | Μέθοδος για τον ορισμό της τιμής float με συγκεκριμένη μονάδα. Εάν η ιδιότητα που συνδέεται με αυτήν την τιμή δεν μπορεί να αποδεχτεί τη συγκεκριμένη μονάδα ή την τιμή float, η τιμή θα παραμείνει αμετάβλητη και θα εγερθεί μια DOMException. |
| abstract [SetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/setintvalue/)(*ushort, int*) | Μέθοδος για ορισμό της τιμής int με συγκεκριμένη μονάδα. Εάν η ιδιότητα που συνδέεται με αυτήν την τιμή δεν μπορεί να αποδεχθεί τη συγκεκριμένη μονάδα ή την τιμή int, η τιμή θα παραμείνει αμετάβλητη και θα προκληθεί μια DOMException. |
| abstract [SetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/setstringvalue/)(*ushort, string*) | Μέθοδος για ορισμό της τιμής string με την καθορισμένη μονάδα. Εάν η ιδιότητα που συνδέεται με αυτήν την τιμή δεν μπορεί να αποδεχθεί τη συγκεκριμένη μονάδα ή την τιμή string, η τιμή θα παραμείνει αμετάβλητη και θα προκληθεί μια DOMException. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την παρουσία. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [CSS_ATTR](../../aspose.svg.dom.css/cssprimitivevalue/css_attr/) | Η τιμή είναι μια συνάρτηση χαρακτηριστικού. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_CH](../../aspose.svg.dom.css/cssprimitivevalue/css_ch/) | Η τιμή είναι ένα μήκος (ch). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_CM](../../aspose.svg.dom.css/cssprimitivevalue/css_cm/) | Η τιμή είναι ένα μήκος (cm). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_COUNTER](../../aspose.svg.dom.css/cssprimitivevalue/css_counter/) | Η τιμή είναι μια συνάρτηση μετρητή ή μετρητών. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο GetCounterValue. |
| const [CSS_DEG](../../aspose.svg.dom.css/cssprimitivevalue/css_deg/) | Η τιμή είναι μια γωνία (deg). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_DIMENSION](../../aspose.svg.dom.css/cssprimitivevalue/css_dimension/) | Η τιμή είναι ένας αριθμός με άγνωστη διάσταση. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_DPCM](../../aspose.svg.dom.css/cssprimitivevalue/css_dpcm/) | Η τιμή είναι μια μονάδα κουκκίδων ανά εκατοστό (dpcm). |
| const [CSS_DPI](../../aspose.svg.dom.css/cssprimitivevalue/css_dpi/) | Η τιμή είναι μια μονάδα κουκκίδων ανά ίντσα (dpi). |
| const [CSS_DPPX](../../aspose.svg.dom.css/cssprimitivevalue/css_dppx/) | Η τιμή είναι μια μονάδα κουκκίδων ανά ‘px’ (dppx). |
| const [CSS_EMS](../../aspose.svg.dom.css/cssprimitivevalue/css_ems/) | Η τιμή είναι ένα μήκος (ems). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_EXS](../../aspose.svg.dom.css/cssprimitivevalue/css_exs/) | Η τιμή είναι ένα μήκος (exs). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_FR](../../aspose.svg.dom.css/cssprimitivevalue/css_fr/) | Μια ευέλικτη μονάδα μήκους ή flex είναι μια διάσταση με τη μονάδα fr, η οποία αντιπροσωπεύει ένα κλάσμα του εναπομείναντος χώρου στο grid container. |
| const [CSS_GRAD](../../aspose.svg.dom.css/cssprimitivevalue/css_grad/) | Η τιμή είναι μια γωνία (grad). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_HZ](../../aspose.svg.dom.css/cssprimitivevalue/css_hz/) | Η τιμή είναι μια συχνότητα (Hz). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_IDENT](../../aspose.svg.dom.css/cssprimitivevalue/css_ident/) | Η τιμή είναι ένας ταυτοποιητής. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_IN](../../aspose.svg.dom.css/cssprimitivevalue/css_in/) | Η τιμή είναι ένα μήκος (in). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_KHZ](../../aspose.svg.dom.css/cssprimitivevalue/css_khz/) | Η τιμή είναι μια συχνότητα (kHz). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_MM](../../aspose.svg.dom.css/cssprimitivevalue/css_mm/) | Η τιμή είναι ένα μήκος (mm). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_MS](../../aspose.svg.dom.css/cssprimitivevalue/css_ms/) | Η τιμή είναι ένας χρόνος (ms). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_NUMBER](../../aspose.svg.dom.css/cssprimitivevalue/css_number/) | Η τιμή είναι ένας απλός αριθμός. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PC](../../aspose.svg.dom.css/cssprimitivevalue/css_pc/) | Η τιμή είναι ένα μήκος (pc). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.svg.dom.css/cssprimitivevalue/css_percentage/) | Η τιμή είναι ένα ποσοστό. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PT](../../aspose.svg.dom.css/cssprimitivevalue/css_pt/) | Η τιμή είναι ένα μήκος (pt). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PX](../../aspose.svg.dom.css/cssprimitivevalue/css_px/) | Η τιμή είναι ένα μήκος (px). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_RAD](../../aspose.svg.dom.css/cssprimitivevalue/css_rad/) | Η τιμή είναι μια γωνία (rad). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_RECT](../../aspose.svg.dom.css/cssprimitivevalue/css_rect/) | Η τιμή είναι μια συνάρτηση rect. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο GetRectValue. |
| const [CSS_REM](../../aspose.svg.dom.css/cssprimitivevalue/css_rem/) | Η τιμή είναι ένα μήκος (rem). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_RGBCOLOR](../../aspose.svg.dom.css/cssprimitivevalue/css_rgbcolor/) | Η τιμή είναι ένα χρώμα RGB. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο GetRGBColorValue. |
| const [CSS_S](../../aspose.svg.dom.css/cssprimitivevalue/css_s/) | Η τιμή είναι ένας χρόνος (s). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_STRING](../../aspose.svg.dom.css/cssprimitivevalue/css_string/) | Η τιμή είναι ένα STRING. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_UNKNOWN](../../aspose.svg.dom.css/cssprimitivevalue/css_unknown/) | Η τιμή δεν είναι μια αναγνωρισμένη τιμή CSS2. Η τιμή μπορεί να ληφθεί μόνο χρησιμοποιώντας το χαρακτηριστικό cssText. |
| const [CSS_URI](../../aspose.svg.dom.css/cssprimitivevalue/css_uri/) | Η τιμή είναι ένα URI. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_VH](../../aspose.svg.dom.css/cssprimitivevalue/css_vh/) | Η τιμή είναι ένα ποσοστό του πλήρους ύψους του παραθύρου προβολής. |
| const [CSS_VMAX](../../aspose.svg.dom.css/cssprimitivevalue/css_vmax/) | Η τιμή είναι ένα ποσοστό του πλάτους ή του ύψους του παραθύρου προβολής, όποιο είναι μεγαλύτερο. |
| const [CSS_VMIN](../../aspose.svg.dom.css/cssprimitivevalue/css_vmin/) | Η τιμή είναι ένα ποσοστό του πλάτους ή του ύψους του παραθύρου προβολής, όποιο είναι μικρότερο. |
| const [CSS_VW](../../aspose.svg.dom.css/cssprimitivevalue/css_vw/) | Η τιμή είναι ένα ποσοστό του πλήρους πλάτους του παραθύρου προβολής. |
| const [CSS_X](../../aspose.svg.dom.css/cssprimitivevalue/css_x/) | Η τιμή είναι κουκκίδες ανά μονάδα ‘px’ (x). |

### Δείτε επίσης

* class [CSSValue](../cssvalue/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
