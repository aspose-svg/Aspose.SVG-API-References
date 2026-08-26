---
title: "ICSSKeyframesRule Interface"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Dom.Css.ICSSKeyframesRule interface. Η διεπαφή CSSKeyframesRule αντιπροσωπεύει ένα πλήρες σύνολο καρέ-κλειδιών για μία ενιαία κίνηση"
type: docs
weight: 2580
url: /el/net/aspose.svg.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

Η διεπαφή CSSKeyframesRule αντιπροσωπεύει ένα πλήρες σύνολο keyframes για μια μεμονωμένη κίνηση

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icsskeyframesrule/cssrules/) { get; } | Αυτό το χαρακτηριστικό παρέχει πρόσβαση στα keyframes στη λίστα |
| [Name](../../aspose.svg.dom.css/icsskeyframesrule/name/) { get; } | Αυτό το χαρακτηριστικό είναι το όνομα των keyframes, που χρησιμοποιείται από την ιδιότητα ‘animation-name’. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AppendRule](../../aspose.svg.dom.css/icsskeyframesrule/appendrule/)(*string*) | Η μέθοδος appendRule προσθέτει το δοσμένο CSSKeyframeRule στη λίστα στο δοσμένο κλειδί |
| [DeleteRule](../../aspose.svg.dom.css/icsskeyframesrule/deleterule/)(*string*) | Η μέθοδος deleteRule διαγράφει το CSSKeyframeRule με το δοσμένο κλειδί. Εάν δεν υπάρχει κανένας κανόνας με αυτό το κλειδί, η μέθοδος δεν κάνει τίποτα |
| [FindRule](../../aspose.svg.dom.css/icsskeyframesrule/findrule/)(*string*) | Η μέθοδος findRule επιστρέφει τον κανόνα με κλειδί που ταιριάζει στο δοσμένο κλειδί. Εάν δεν υπάρχει τέτοιος κανόνας, επιστρέφεται τιμή null |

### Δείτε επίσης

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
