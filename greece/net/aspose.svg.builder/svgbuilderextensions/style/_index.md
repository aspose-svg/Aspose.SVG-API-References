---
title: "SVGBuilderExtensions.Style"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions Style. Ορίζει το χαρακτηριστικό style χρησιμοποιώντας έναν δημιουργό κανόνων για τον ορισμό στυλ CSS."
type: docs
weight: 2160
url: /el/net/aspose.svg.builder/svgbuilderextensions/style/
---
## Style<TBuilder>(*this TBuilder, Action&lt;RuleBuilder&gt;*) {#style}

Ορίζει το χαρακτηριστικό 'style' χρησιμοποιώντας έναν δημιουργό κανόνων για τον ορισμό των στυλ CSS.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, Action<RuleBuilder> configureRule)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| configureRule | Η ενέργεια για τη διαμόρφωση του κανόνα CSS. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [RuleBuilder](../../rulebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Style<TBuilder>(*this TBuilder, string*) {#style_1}

Ορίζει το χαρακτηριστικό 'style', ορίζοντας ενσωματωμένα στυλ CSS για το στοιχείο SVG.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, string rules)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| rules | Οι κανόνες CSS ως συμβολοσειρά. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
