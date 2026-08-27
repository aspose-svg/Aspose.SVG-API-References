---
title: "SVGBuilderExtensions.RepeatDur"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions RepeatDur मेथड। repeatDur एट्रिब्यूट सेट करता है जो एनीमेशन के दोहराने की कुल अवधि निर्दिष्ट करता है।"
type: docs
weight: 1960
url: /hi/net/aspose.svg.builder/svgbuilderextensions/repeatdur/
---
## RepeatDur<TBuilder>(*this TBuilder, TimeSpan*) {#repeatdur_1}

एनीमेशन को कितनी कुल अवधि तक दोहराना है, यह निर्दिष्ट करते हुए 'repeatDur' एट्रिब्यूट सेट करता है।

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| अवधि | एनीमेशन को दोहराने की कुल अवधि। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatDur<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatdur}

पूर्वनिर्धारित enum का उपयोग करके एनीमेशन की अनिश्चित कुल अवधि निर्दिष्ट करते हुए 'repeatDur' एट्रिब्यूट सेट करता है।

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | एनीमेशन को दोहराने के लिए पूर्वनिर्धारित अनिश्चित कुल अवधि। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
