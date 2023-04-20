---
title: Class CSSPrimitiveValue
second_title: Aspose.SVG για Αναφορά API .NET
description: Aspose.Svg.Dom.Css.CSSPrimitiveValue τάξη. Η διεπαφή CSSPrimitiveValue αντιπροσωπεύει μια μεμονωμένη τιμή CSS. Αυτή η διεπαφή μπορεί να χρησιμοποιηθεί για τον προσδιορισμό της τιμής μιας συγκεκριμένης ιδιότητας στυλ που έχει οριστεί αυτήν τη στιγμή σε ένα μπλοκ ή για τον ορισμό μιας συγκεκριμένης ιδιότητας στυλ ρητά εντός του μπλοκ. Μια παρουσία αυτής της διεπαφής μπορεί να ληφθεί από τη μέθοδο getPropertyCSSValue της διεπαφής CSSStyleDeclaration. Ένα αντικείμενο CSSPrimitiveValue εμφανίζεται μόνο σε ένα περιβάλλον μιας ιδιότητας CSS.
type: docs
weight: 480
url: /el/net/aspose.svg.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

Η διεπαφή CSSPrimitiveValue αντιπροσωπεύει μια μεμονωμένη τιμή CSS. Αυτή η διεπαφή μπορεί να χρησιμοποιηθεί για τον προσδιορισμό της τιμής μιας συγκεκριμένης ιδιότητας στυλ που έχει οριστεί αυτήν τη στιγμή σε ένα μπλοκ ή για τον ορισμό μιας συγκεκριμένης ιδιότητας στυλ ρητά εντός του μπλοκ. Μια παρουσία αυτής της διεπαφής μπορεί να ληφθεί από τη μέθοδο getPropertyCSSValue της διεπαφής CSSStyleDeclaration. Ένα αντικείμενο CSSPrimitiveValue εμφανίζεται μόνο σε ένα περιβάλλον μιας ιδιότητας CSS.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | Αναπαράσταση συμβολοσειράς της τρέχουσας τιμής. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Ένας κωδικός που καθορίζει τον τύπο της τιμής. |
| [PrimitiveType](../../aspose.svg.dom.css/cssprimitivevalue/primitivetype/) { get; } | Ο τύπος της τιμής όπως ορίζεται από τις σταθερές που καθορίζονται παραπάνω. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(object) | Καθορίζει εάν το καθορισμένοObject ισούται με αυτήν την περίπτωση. |
| abstract [GetCounterValue](../../aspose.svg.dom.css/cssprimitivevalue/getcountervalue/)() | Αυτή η μέθοδος χρησιμοποιείται για τη λήψη της τιμής Counter. Εάν αυτή η τιμή CSS δεν περιέχει μια τιμή μετρητή, δημιουργείται μια εξαίρεση DOME. Η τροποποίηση της αντίστοιχης ιδιότητας στυλ μπορεί να επιτευχθεί χρησιμοποιώντας τη διεπαφή Counter. |
| abstract [GetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Αυτή η μέθοδος χρησιμοποιείται για να ληφθεί μια τιμή float σε μια καθορισμένη μονάδα. Εάν αυτή η τιμή CSS δεν περιέχει μια κινητή τιμή ή δεν μπορεί να μετατραπεί στην καθορισμένη μονάδα, δημιουργείται μια εξαίρεση DOME. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την εμφάνιση. |
| abstract [GetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Αυτή η μέθοδος χρησιμοποιείται για τη λήψη μιας τιμής int σε μια καθορισμένη μονάδα. Εάν αυτή η τιμή CSS δεν περιέχει τιμή int ή δεν μπορεί να μετατραπεί στην καθορισμένη μονάδα, δημιουργείται μια εξαίρεση DOME. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση αντικειμένου ECMAScriptType . |
| abstract [GetRectValue](../../aspose.svg.dom.css/cssprimitivevalue/getrectvalue/)() | Αυτή η μέθοδος χρησιμοποιείται για τη λήψη της τιμής Rect. Εάν αυτή η τιμή CSS δεν περιέχει μια ορθή τιμή, δημιουργείται μια εξαίρεση DOME. Η τροποποίηση της αντίστοιχης ιδιότητας στυλ μπορεί να επιτευχθεί χρησιμοποιώντας τη διεπαφή Rect. |
| abstract [GetRGBColorValue](../../aspose.svg.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Αυτή η μέθοδος χρησιμοποιείται για τη λήψη του χρώματος RGB. Εάν αυτή η τιμή CSS δεν περιέχει μια τιμή χρώματος RGB, δημιουργείται μια εξαίρεση DOME. Η τροποποίηση της αντίστοιχης ιδιότητας στυλ μπορεί να επιτευχθεί χρησιμοποιώντας τη διεπαφή RGBColor. |
| abstract [GetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/getstringvalue/)() | Αυτή η μέθοδος χρησιμοποιείται για τη λήψη της τιμής συμβολοσειράς. Εάν η τιμή CSS δεν περιέχει τιμή συμβολοσειράς, δημιουργείται μια εξαίρεση DOME. |
| abstract [SetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Μια μέθοδος για τον ορισμό της τιμής float με μια καθορισμένη μονάδα. Εάν η ιδιότητα που επισυνάπτεται με αυτήν την τιμή δεν μπορεί να δεχτεί την καθορισμένη μονάδα ή την τιμή float, η τιμή θα παραμείνει αμετάβλητη και θα αυξηθεί μια εξαίρεση DOME. |
| abstract [SetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Μια μέθοδος για τον ορισμό της τιμής int με μια καθορισμένη μονάδα. Εάν η ιδιότητα που συνδέεται με αυτήν την τιμή δεν μπορεί να δεχτεί την καθορισμένη μονάδα ή την τιμή int, η τιμή θα παραμείνει αμετάβλητη και θα αυξηθεί μια εξαίρεση DOME. |
| abstract [SetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/setstringvalue/)(ushort, string) | Μια μέθοδος για τον ορισμό της τιμής συμβολοσειράς με την καθορισμένη μονάδα. Εάν η ιδιότητα που συνδέεται με αυτήν την τιμή δεν μπορεί να δεχτεί την καθορισμένη μονάδα ή την τιμή συμβολοσειράς, η τιμή θα παραμείνει αμετάβλητη και θα αυξηθεί μια εξαίρεση DOME. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [CSS_ATTR](../../aspose.svg.dom.css/cssprimitivevalue/css_attr/) | Η τιμή είναι συνάρτηση χαρακτηριστικού. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_CH](../../aspose.svg.dom.css/cssprimitivevalue/css_ch/) | Η τιμή είναι ένα μήκος (ch). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_CM](../../aspose.svg.dom.css/cssprimitivevalue/css_cm/) | Η τιμή είναι ένα μήκος (cm). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_COUNTER](../../aspose.svg.dom.css/cssprimitivevalue/css_counter/) | Η τιμή είναι συνάρτηση μετρητή ή μετρητών. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο GetCounterValue. |
| const [CSS_DEG](../../aspose.svg.dom.css/cssprimitivevalue/css_deg/) | Η τιμή είναι γωνία (deg). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_DIMENSION](../../aspose.svg.dom.css/cssprimitivevalue/css_dimension/) | Η τιμή είναι ένας αριθμός με άγνωστη διάσταση. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_DPCM](../../aspose.svg.dom.css/cssprimitivevalue/css_dpcm/) | Η τιμή είναι κουκκίδες ανά εκατοστό (dpcm). |
| const [CSS_DPI](../../aspose.svg.dom.css/cssprimitivevalue/css_dpi/) | Η τιμή είναι κουκκίδες ανά ίντσα (dpi). |
| const [CSS_DPPX](../../aspose.svg.dom.css/cssprimitivevalue/css_dppx/) | Η τιμή είναι κουκκίδες ανά μονάδα 'px' (dppx). |
| const [CSS_EMS](../../aspose.svg.dom.css/cssprimitivevalue/css_ems/) | Η τιμή είναι ένα μήκος (ems). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_EXS](../../aspose.svg.dom.css/cssprimitivevalue/css_exs/) | Η τιμή είναι ένα μήκος (exs). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_GRAD](../../aspose.svg.dom.css/cssprimitivevalue/css_grad/) | Η τιμή είναι γωνία (βαθμίδα). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_HZ](../../aspose.svg.dom.css/cssprimitivevalue/css_hz/) | Η τιμή είναι μια συχνότητα (Hz). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_IDENT](../../aspose.svg.dom.css/cssprimitivevalue/css_ident/) | Η τιμή είναι ένα αναγνωριστικό. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_IN](../../aspose.svg.dom.css/cssprimitivevalue/css_in/) | Η τιμή είναι ένα μήκος (in). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_KHZ](../../aspose.svg.dom.css/cssprimitivevalue/css_khz/) | Η τιμή είναι μια συχνότητα (kHz). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_MM](../../aspose.svg.dom.css/cssprimitivevalue/css_mm/) | Η τιμή είναι ένα μήκος (mm). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_MS](../../aspose.svg.dom.css/cssprimitivevalue/css_ms/) | Η τιμή είναι χρόνος (ms). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_NUMBER](../../aspose.svg.dom.css/cssprimitivevalue/css_number/) | Η τιμή είναι ένας απλός αριθμός. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PC](../../aspose.svg.dom.css/cssprimitivevalue/css_pc/) | Η τιμή είναι ένα μήκος (pc). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.svg.dom.css/cssprimitivevalue/css_percentage/) | Η τιμή είναι ποσοστό. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PT](../../aspose.svg.dom.css/cssprimitivevalue/css_pt/) | Η τιμή είναι ένα μήκος (pt). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PX](../../aspose.svg.dom.css/cssprimitivevalue/css_px/) | Η τιμή είναι ένα μήκος (px). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_RAD](../../aspose.svg.dom.css/cssprimitivevalue/css_rad/) | Η τιμή είναι γωνία (rad). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_RECT](../../aspose.svg.dom.css/cssprimitivevalue/css_rect/) | Η τιμή είναι μια ορθή συνάρτηση. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο GetRectValue. |
| const [CSS_REM](../../aspose.svg.dom.css/cssprimitivevalue/css_rem/) | Η τιμή είναι ένα μήκος (rem). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_RGBCOLOR](../../aspose.svg.dom.css/cssprimitivevalue/css_rgbcolor/) | Η τιμή είναι ένα χρώμα RGB. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο GetRGBColorValue. |
| const [CSS_S](../../aspose.svg.dom.css/cssprimitivevalue/css_s/) | Η τιμή είναι ένας χρόνος (s). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_STRING](../../aspose.svg.dom.css/cssprimitivevalue/css_string/) | Η τιμή είναι STRING. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_UNKNOWN](../../aspose.svg.dom.css/cssprimitivevalue/css_unknown/) | Η τιμή δεν είναι αναγνωρισμένη τιμή CSS2. Η τιμή μπορεί να ληφθεί μόνο χρησιμοποιώντας το χαρακτηριστικό cssText. |
| const [CSS_URI](../../aspose.svg.dom.css/cssprimitivevalue/css_uri/) | Η τιμή είναι ένα URI. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_VH](../../aspose.svg.dom.css/cssprimitivevalue/css_vh/) | Η τιμή είναι ένα ποσοστό του πλήρους ύψους της θύρας προβολής. |
| const [CSS_VMAX](../../aspose.svg.dom.css/cssprimitivevalue/css_vmax/) | Η τιμή είναι ένα ποσοστό του πλάτους ή του ύψους της θύρας προβολής, όποιο είναι μεγαλύτερο. |
| const [CSS_VMIN](../../aspose.svg.dom.css/cssprimitivevalue/css_vmin/) | Η τιμή είναι ένα ποσοστό του πλάτους ή του ύψους της θύρας προβολής, όποιο είναι μικρότερο. |
| const [CSS_VW](../../aspose.svg.dom.css/cssprimitivevalue/css_vw/) | Η τιμή είναι ένα ποσοστό του πλήρους πλάτους της θύρας προβολής. |

### Δείτε επίσης

* class [CSSValue](../cssvalue/)
* χώρος ονομάτων [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* συνέλευση [Aspose.SVG](../../)


