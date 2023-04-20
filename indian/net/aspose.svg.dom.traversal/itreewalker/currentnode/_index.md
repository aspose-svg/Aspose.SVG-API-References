---
title: ITreeWalker.CurrentNode
second_title: .NET API संदर्भ के लिए Aspose.SVG
description: ITreeWalker संपत्त. वह नड जस पर ट्रवकर वर्तमन में स्थत है DOM ट्र में बदलव के करण वर्तमन नड अब क ट्रवकर के संबंधत फ़ल्टर द्वर स्वकर नहं कय ज सकत है करेंटनड क स्पष्ट रूप से कस भ नड पर सेट कय ज सकत है चहे वह ह य न ह the रूट नड द्वर नर्दष्ट सबट्र के भतर य फ़ल्टर और whatToShow फ़्लैग द्वर स्वकर कय जएग आगे ट्रैवर्सल currentNode के सपेक्ष हत है भले ह यह वर्तमन दृश्य क हस्स न ह अनुरधत दश में फ़ल्टर लगू करके यद कई ट्रैवर्सल संभव नहं है त वर्तमन नड नहं बदल गय है
type: docs
weight: 10
url: /hi/net/aspose.svg.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

वह नोड जिस पर ट्रीवॉकर वर्तमान में स्थित है। DOM ट्री में बदलाव के कारण वर्तमान नोड अब को ट्रीवॉकर के संबंधित फ़िल्टर द्वारा स्वीकार नहीं किया जा सकता है। करेंटनोड को स्पष्ट रूप से किसी भी नोड पर सेट किया जा सकता है, चाहे वह हो या न हो the रूट नोड द्वारा निर्दिष्ट सबट्री के भीतर या फ़िल्टर और whatToShow फ़्लैग द्वारा स्वीकार किया जाएगा। आगे ट्रैवर्सल currentNode के सापेक्ष होता है भले ही यह वर्तमान दृश्य का हिस्सा न हो, अनुरोधित दिशा में फ़िल्टर लागू करके; यदि कोई ट्रैवर्सल संभव नहीं है, तो वर्तमान नोड नहीं बदला गया है।

```csharp
public Node CurrentNode { get; set; }
```

### संपत्ति मूल्य

वर्तमान नोड.

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: अगर set currentNode को शून्य करने का प्रयास किया जाता है तो उठाया जाता है। |

### यह सभी देखें

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* नाम स्थान [Aspose.Svg.Dom.Traversal](../../itreewalker/)
* सभा [Aspose.SVG](../../../)

