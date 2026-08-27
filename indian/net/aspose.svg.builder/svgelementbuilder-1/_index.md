---
title: "SVGElementBuilderT क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGElementBuilder1T क्लास। T प्रकार के SVG तत्वों को बनाने के लिए एक बेस क्लास का प्रतिनिधित्व करता है।"
type: docs
weight: 1160
url: /hi/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

*T* प्रकार के SVG तत्व बनाने के लिए एक बेस क्लास का प्रतिनिधित्व करता है।

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| पैरामीटर | विवरण |
| --- | --- |
| T | इस बिल्डर की जिम्मेदारी वाला SVG तत्व का प्रकार। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | SVG तत्व पर लागू किए जाने वाले कॉन्फ़िगरेशन की सूची प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | SVG तत्व में एक विशेषता कॉन्फ़िगरेशन जोड़ता है। |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | SVG तत्व बनाता है और सभी कॉन्फ़िगरेशन उसे लागू करता है। |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | मौजूदा SVG तत्व पर कॉन्फ़िगरेशन लागू करता है। |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | SVG तत्व को एक सामान्य SVGElement के रूप में बनाता है। |

### संबंधित देखें

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
