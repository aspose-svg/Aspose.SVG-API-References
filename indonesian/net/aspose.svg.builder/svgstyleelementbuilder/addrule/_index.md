---
title: "SVGStyleElementBuilder.AddRule"
second_title: "Referensi API Aspose.SVG untuk .NET"
description: "Metode AddRule SVGStyleElementBuilder. Menambahkan aturan CSS ke elemen gaya."
type: docs
weight: 30
url: /id/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

Menambahkan aturan CSS ke elemen gaya.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| selector | String | Selektor CSS untuk aturan tersebut. |
| rules | String | Aturan CSS sebagai string. |

### Nilai Kembalian

Instansi SVGStyleElementBuilder untuk chaining.

### Lihat Juga

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

Menambahkan aturan CSS ke elemen gaya menggunakan RuleBuilder.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| selector | String | Selektor CSS untuk aturan tersebut. |
| configureRule | Action`1 | Delegasi untuk mengonfigurasi aturan menggunakan RuleBuilder. |

### Nilai Kembalian

Instansi SVGStyleElementBuilder untuk chaining.

### Lihat Juga

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
