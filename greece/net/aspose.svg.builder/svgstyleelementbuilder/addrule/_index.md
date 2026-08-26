---
title: "SVGStyleElementBuilder.AddRule"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGStyleElementBuilder AddRule μέθοδος. Προσθέτει έναν κανόνα CSS στο στοιχείο στυλ"
type: docs
weight: 30
url: /el/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

Προσθέτει έναν κανόνα CSS στο στοιχείο στυλ.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| selector | String | Ο CSS selector για τον κανόνα. |
| rules | String | Οι κανόνες CSS ως συμβολοσειρά. |

### Τιμή Επιστροφής

Το αντικείμενο SVGStyleElementBuilder για αλυσίδωση.

### Δείτε επίσης

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

Προσθέτει έναν κανόνα CSS στο στοιχείο στυλ χρησιμοποιώντας ένα RuleBuilder.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| selector | String | Ο CSS selector για τον κανόνα. |
| configureRule | Action`1 | Ένας delegate για τη διαμόρφωση του κανόνα χρησιμοποιώντας ένα RuleBuilder. |

### Τιμή Επιστροφής

Το αντικείμενο SVGStyleElementBuilder για αλυσίδωση.

### Δείτε επίσης

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
