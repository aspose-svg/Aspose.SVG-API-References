---
title: "SVGBuilderExtensions.Points"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions Points मेथड। डबल्स की एक एरे का उपयोग करके SVG तत्व के लिए points एट्रिब्यूट सेट करता है।"
type: docs
weight: 1910
url: /hi/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

डबल्स की एरे का उपयोग करके एक SVG तत्व के लिए 'points' एट्रिब्यूट सेट करता है।

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| points | बिंदुओं का प्रतिनिधित्व करने वाले डबल्स की एक एरे (संख्या सम होनी चाहिए)। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि बिंदुओं की संख्या विषम हो तो फेंका जाता है। |

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

PointF ऑब्जेक्ट्स की एरे का उपयोग करके एक SVG तत्व के लिए 'points' एट्रिब्यूट सेट करता है।

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| points | बिंदुओं का प्रतिनिधित्व करने वाले PointF ऑब्जेक्ट्स की एक एरे। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
