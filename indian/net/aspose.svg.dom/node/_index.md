---
title: Class Node
second_title: .NET API संदर्भ के लिए Aspose.SVG
description: Aspose.Svg.Dom.Node कक्ष. नड इंटरफ़ेस संपूर्ण दस्तवेज़ ऑब्जेक्ट मडल के लए प्रथमक डेट प्रकर है यह दस्तवेज़ ट्र में एकल नड क प्रतनधत्व करत है.
type: docs
weight: 1150
url: /hi/net/aspose.svg.dom/node/
---
## Node class

नोड इंटरफ़ेस संपूर्ण दस्तावेज़ ऑब्जेक्ट मॉडल के लिए प्राथमिक डेटा प्रकार है। यह दस्तावेज़ ट्री में एकल नोड का प्रतिनिधित्व करता है.

```csharp
public abstract class Node : EventTarget, IXPathNSResolver
```

## गुण

| नाम | विवरण |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes/) { get; } | एक NamedNodeMap जिसमें इस नोड की विशेषताएँ हैं (यदि यह एक तत्व है) या अशक्त अन्यथा। |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | इस नोड का पूर्ण आधार यूआरआई या शून्य यदि कार्यान्वयन पूर्ण यूआरआई प्राप्त करने में सक्षम नहीं था। |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | एक नोडलिस्ट जिसमें इस नोड के सभी बच्चे शामिल हैं। यदि कोई बच्चे नहीं हैं, तो यह एक नोडलिस्ट है जिसमें कोई नोड नहीं है.. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | इस नोड का पहला चाइल्ड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | इस नोड का अंतिम बच्चा। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | इस नोड के योग्य नाम का स्थानीय भाग लौटाता है। ELEMENT_NODE और ATTRIBUTE_NODE के अलावा किसी भी प्रकार के नोड्स और DOM स्तर 1 विधि के साथ बनाए गए नोड्स के लिए, जैसे कि Document.createElement (), यह हमेशा शून्य होता है। |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | इस नोड का नामस्थान यूआरआई, या अनिर्दिष्ट होने पर शून्य। |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | इस नोड के तुरंत बाद का नोड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| abstract [NodeName](../../aspose.svg.dom/node/nodename/) { get; } | इस नोड का नाम, इसके प्रकार पर निर्भर करता है। |
| abstract [NodeType](../../aspose.svg.dom/node/nodetype/) { get; } | अंतर्निहित वस्तु के प्रकार का प्रतिनिधित्व करने वाला एक कोड। |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | इस नोड का मान, इसके प्रकार पर निर्भर करता है। |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | इस नोड से जुड़ा दस्तावेज़ ऑब्जेक्ट। यह नए नोड बनाने के लिए उपयोग की जाने वाली दस्तावेज़ वस्तु भी है। जब यह नोड एक दस्तावेज़ या एक दस्तावेज़ प्रकार है जिसका अभी तक किसी दस्तावेज़ के साथ उपयोग नहीं किया गया है, तो यह शून्य है। |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | माता-पिता को प्राप्त करता है[`Element`](../element/) इस नोड का. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | इस नोड का जनक। Attr, Document, DocumentFragment, Entity, और Notation को छोड़कर सभी नोड्स में माता-पिता हो सकते हैं। हालाँकि, यदि कोई नोड अभी बनाया गया है और अभी तक ट्री में नहीं जोड़ा गया है, या यदि इसे ट्री से हटा दिया गया है, तो यह शून्य है। |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | इस नोड का नामस्थान उपसर्ग, या अनिर्दिष्ट होने पर अशक्त। जब इसे शून्य के रूप में परिभाषित किया जाता है, तो इसे सेट करने से कोई प्रभाव नहीं पड़ता |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | इस नोड के ठीक पहले वाला नोड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | यह विशेषता इस नोड और उसके वंश की पाठ्य सामग्री लौटाती है। जब इसे शून्य के रूप में परिभाषित किया जाता है, तो इसे सेट करने का कोई प्रभाव नहीं पड़ता है। सेट करने पर, इस नोड के किसी भी संभावित बच्चे को हटा दिया जा सकता है और, यदि यह नया स्ट्रिंग खाली या शून्य नहीं है, तो इस विशेषता को सेट करने वाले स्ट्रिंग वाले एकल टेक्स्ट नोड द्वारा प्रतिस्थापित किया जाता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(Node) | इस नोड के चिल्ड्रन की सूची के अंत में नोड न्यूचाइल्ड जोड़ता है। यदि नया बच्चा पहले से ही पेड़ में है, तो इसे पहले हटा दिया जाता है। |
| [CloneNode](../../aspose.svg.dom/node/clonenode/#clonenode)() | इस नोड का एक डुप्लिकेट लौटाता है, अर्थात, नोड्स के लिए एक सामान्य कॉपी कंस्ट्रक्टर के रूप में कार्य करता है। डुप्लिकेट नोड का कोई पैरेंट नहीं है (parentNode खाली है) और कोई उपयोगकर्ता डेटा नहीं है। |
| [CloneNode](../../aspose.svg.dom/node/clonenode/#clonenode_1)(bool) | इस नोड का एक डुप्लिकेट लौटाता है, अर्थात, नोड्स के लिए एक सामान्य कॉपी कंस्ट्रक्टर के रूप में कार्य करता है। डुप्लिकेट नोड का कोई पैरेंट नहीं है (parentNode खाली है) और कोई उपयोगकर्ता डेटा नहीं है। |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(Event) | यह विधि इवेंट को कार्यान्वयन इवेंट मॉडल में भेजने की अनुमति देती है. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | अप्रबंधित संसाधनों को मुक्त करने, जारी करने या रीसेट करने से संबंधित एप्लिकेशन-परिभाषित कार्य करता है। |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes/)() | रिटर्न करता है कि क्या इस नोड (यदि यह एक तत्व है) में कोई विशेषता है |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | लौटाता है कि क्या इस नोड के कोई बच्चे हैं। |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(Node, Node) | मौजूदा चाइल्ड नोड चाइल्ड से पहले नोड डालें। यदि बच्चा शून्य है, तो बच्चों की सूची के अंत में नोड डालें। यदि बच्चा पहले से ही पेड़ में है, तो उसे पहले हटा दिया जाता है। |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(string) | यह विधि जांचती है कि निर्दिष्ट नामस्थान यूआरआई डिफ़ॉल्ट नामस्थान है या नहीं। |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(Node) | परीक्षण करता है कि क्या दो नोड समान हैं। यह विधि नोड्स की समानता के लिए परीक्षण करती है, समरूपता के लिए नहीं (अर्थात, क्या दो नोड एक ही वस्तु के संदर्भ हैं) जिसे Node.isSameNode() के साथ परीक्षण किया जा सकता है। सभी नोड जो समान हैं, वे भी बराबर होंगे, हालांकि रिवर्स सत्य नहीं हो सकता है। |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(Node) | रिटर्न देता है कि क्या यह नोड दिए गए नोड के समान नोड है। यह विधि यह निर्धारित करने का एक तरीका प्रदान करती है कि कार्यान्वयन द्वारा लौटाए गए दो नोड संदर्भ एक ही वस्तु को संदर्भित करते हैं या नहीं। जब दो नोड संदर्भ एक ही वस्तु के संदर्भ होते हैं, भले ही एक प्रॉक्सी के माध्यम से, संदर्भों को पूरी तरह से एक दूसरे के स्थान पर उपयोग किया जा सकता है, जैसे कि सभी विशेषताओं में समान मान होते हैं और समान DOM विधि को किसी भी संदर्भ पर कॉल करने का हमेशा एक ही प्रभाव होता है। |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(string) | इस नोड से शुरू करते हुए, दिए गए उपसर्ग से जुड़े नामस्थान यूआरआई को देखें। |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(string) | इस नोड से शुरू करते हुए दिए गए नेमस्पेस यूआरआई से जुड़े उपसर्ग को देखें। इस विधि द्वारा डिफ़ॉल्ट नामस्थान घोषणाओं को अनदेखा किया जाता है। इस विधि द्वारा उपयोग किए गए एल्गोरिदम पर विवरण के लिए नामस्थान उपसर्ग लुकअप देखें। |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | सभी टेक्स्ट नोड्स को इस नोड के नीचे सब-ट्री की पूरी गहराई में रखता है, विशेषता नोड्स सहित, एक "सामान्य" रूप में जहां केवल संरचना (जैसे, तत्व, टिप्पणियां, प्रसंस्करण निर्देश, सीडीएटीए अनुभाग और इकाई संदर्भ) टेक्स्ट को अलग करती है। नोड्स, यानी, न तो सन्निकट टेक्स्ट नोड्स हैं और न ही खाली टेक्स्ट नोड्स। इसका उपयोग यह सुनिश्चित करने के लिए किया जा सकता है कि किसी दस्तावेज़ का DOM दृश्य वैसा ही है जैसे कि उसे सहेजा गया था और पुनः लोड किया गया था, और जब संचालन (जैसे XPointer [XPointer] लुकअप) जो किसी विशेष दस्तावेज़ ट्री संरचना पर निर्भर करता है, तब उपयोगी होता है इस्तेमाल किया गया। यदि Node.ownerDocument से जुड़ी DOMConfiguration ऑब्जेक्ट का पैरामीटर "सामान्यीकृत-अक्षर" सत्य है, तो यह विधि टेक्स्ट नोड्स के वर्णों को भी पूरी तरह से सामान्य कर देगी। |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(Node) | ओल्डचाइल्ड द्वारा बच्चों की सूची से संकेतित चाइल्ड नोड को हटाता है, और इसे वापस करता है। |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener) | यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../eventtarget/) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है। |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../eventtarget/) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है। |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../eventtarget/) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है। |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(Node, Node) | बच्चों की सूची में चाइल्ड नोड ओल्डचाइल्ड को न्यूचाइल्ड से बदल देता है, और ओल्डचाइल्ड नोड लौटाता है। यदि न्यूचाइल्ड एक डॉक्यूमेंटफ्रैगमेंट ऑब्जेक्ट है, तो ओल्डचाइल्ड को सभी डॉक्यूमेंटफ्रैगमेंट चिल्ड्रेन से बदल दिया जाता है, जो उसी क्रम में डाले जाते हैं। यदि नया बच्चा पहले से ही पेड़ में है, तो इसे पहले हटा दिया जाता है। |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [ATTRIBUTE_NODE](../../aspose.svg.dom/node/attribute_node/) | एक विशेषता नोड |
| const [CDATA_SECTION_NODE](../../aspose.svg.dom/node/cdata_section_node/) | एक cdata अनुभाग नोड |
| const [COMMENT_NODE](../../aspose.svg.dom/node/comment_node/) | एक टिप्पणी नोड |
| const [DOCUMENT_FRAGMENT_NODE](../../aspose.svg.dom/node/document_fragment_node/) | एक दस्तावेज़ खंड नोड |
| const [DOCUMENT_NODE](../../aspose.svg.dom/node/document_node/) | एक दस्तावेज़ नोड |
| const [DOCUMENT_TYPE_NODE](../../aspose.svg.dom/node/document_type_node/) | एक दस्तावेज़ प्रकार नोड |
| const [ELEMENT_NODE](../../aspose.svg.dom/node/element_node/) | एक तत्व नोड |
| const [ENTITY_NODE](../../aspose.svg.dom/node/entity_node/) | एक इकाई नोड |
| const [ENTITY_REFERENCE_NODE](../../aspose.svg.dom/node/entity_reference_node/) | एक इकाई संदर्भ नोड |
| const [NOTATION_NODE](../../aspose.svg.dom/node/notation_node/) | एक संकेतन नोड |
| const [PROCESSING_INSTRUCTION_NODE](../../aspose.svg.dom/node/processing_instruction_node/) | एक प्रोसेसिंग निर्देश नोड |
| const [TEXT_NODE](../../aspose.svg.dom/node/text_node/) | एक टेक्स्ट नोड |

### यह सभी देखें

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)
* नाम स्थान [Aspose.Svg.Dom](../../aspose.svg.dom/)
* सभा [Aspose.SVG](../../)


