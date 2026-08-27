---
title: "SVGBuilderExtensions.Style"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions Style मेथड। CSS शैलियों को परिभाषित करने के लिए एक नियम बिल्डर का उपयोग करके style एट्रिब्यूट सेट करता है"
type: docs
weight: 2160
url: /hi/net/aspose.svg.builder/svgbuilderextensions/style/
---
## Style<TBuilder>(*this TBuilder, Action&lt;RuleBuilder&gt;*) {#style}

एक नियम बिल्डर का उपयोग करके 'style' विशेषता निर्धारित करता है, जिससे CSS शैलियों को परिभाषित किया जाता है।

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, Action<RuleBuilder> configureRule)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| configureRule | CSS नियम को कॉन्फ़िगर करने के लिए कार्रवाई। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [RuleBuilder](../../rulebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Style<TBuilder>(*this TBuilder, string*) {#style_1}

SVG तत्व के लिए इनलाइन CSS शैलियों को परिभाषित करते हुए 'style' विशेषता निर्धारित करता है।

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, string rules)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| नियम | CSS नियम एक स्ट्रिंग के रूप में। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
