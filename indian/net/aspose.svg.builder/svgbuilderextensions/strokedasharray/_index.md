---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions StrokeDashArray मेथड। SVG तत्व के लिए stroke-dasharray एट्रिब्यूट सेट करता है, जो स्ट्रोक को पेंट करने के लिए डैश और गैप के पैटर्न को परिभाषित करता है।"
type: docs
weight: 2090
url: /hi/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

SVG तत्व के लिए 'stroke-dasharray' विशेषता निर्धारित करता है, जो स्ट्रोक को पेंट करने के लिए उपयोग किए जाने वाले डैश और गैप के पैटर्न को परिभाषित करता है।

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| dashArray | डैश लंबाइयों की एरे। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

पूर्वनिर्धारित डैश पैटर्न का उपयोग करके SVG तत्व के लिए 'stroke-dasharray' विशेषता निर्धारित करता है।

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| value | सेट करने के लिए डैश पैटर्न। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
