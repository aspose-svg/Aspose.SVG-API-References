---
title: "SVGBuilderExtensions.In"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions In मेथड। SVG फ़िल्टर प्रिमिटिव के लिए in एट्रिब्यूट सेट करता है"
type: docs
weight: 1040
url: /hi/net/aspose.svg.builder/svgbuilderextensions/in/
---
## In<TBuilder>(*this TBuilder, string*) {#in_1}

SVG फ़िल्टर प्रिमिटिव के लिए 'in' एट्रिब्यूट सेट करता है।

```csharp
public static TBuilder In<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveInAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| value | इनपुट के रूप में उपयोग करने के लिए स्रोत ग्राफ़िक या फ़िल्टर प्रिमिटिव परिणाम। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../../ifilterprimitiveinattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## In<TBuilder>(*this TBuilder, [FilterInput](../../filterinput/)*) {#in}

SVG फ़िल्टर प्रिमिटिव के लिए 'in' एट्रिब्यूट को एक पूर्वनिर्धारित इनपुट स्रोत का उपयोग करके सेट करता है।

```csharp
public static TBuilder In<TBuilder>(this TBuilder builder, FilterInput input)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveInAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| इनपुट | पूर्वनिर्धारित इनपुट स्रोत (जैसे, SourceGraphic, SourceAlpha)। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [FilterInput](../../filterinput/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../../ifilterprimitiveinattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
