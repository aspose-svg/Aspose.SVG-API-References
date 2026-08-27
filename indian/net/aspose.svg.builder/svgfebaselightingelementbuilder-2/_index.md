---
title: "SVGFEBaseLightingElementBuilderTElementTBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGFEBaseLightingElementBuilder2TElementTBuilder क्लास। SVG फ़िल्टर इफ़ेक्ट लाइटिंग तत्वों के बिल्डरों के लिए सारभूत बेस क्लास"
type: docs
weight: 1180
url: /hi/net/aspose.svg.builder/svgfebaselightingelementbuilder-2/
---
## SVGFEBaseLightingElementBuilder<TElement,TBuilder> class

SVG फ़िल्टर प्रभाव लाइटिंग तत्वों के बिल्डर्स के लिए एब्स्ट्रैक्ट बेस क्लास।

```csharp
public abstract class SVGFEBaseLightingElementBuilder<TElement, TBuilder> : 
    SVGElementBuilder<TElement>, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
    where TElement : SVGElement
    where TBuilder : SVGFEBaseLightingElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TElement | निर्मित किए जा रहे SVG तत्व का प्रकार। |
| TBuilder | बिल्डर स्वयं का प्रकार। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | तत्व में एक स्क्रिप्ट कॉन्फ़िगरेशन जोड़ता है। |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | SVG तत्व को बनाता है, यदि निर्दिष्ट हो तो लाइट सोर्स कॉन्फ़िगरेशन लागू करता है। |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*TElement*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) | फ़िल्टर प्रभाव के लिए एक दूरस्थ प्रकाश स्रोत को कॉन्फ़िगर करता है। |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) | फ़िल्टर प्रभाव के लिए एक बिंदु प्रकाश स्रोत को कॉन्फ़िगर करता है। |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) | फ़िल्टर प्रभाव के लिए एक स्पॉट प्रकाश स्रोत को कॉन्फ़िगर करता है। |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
