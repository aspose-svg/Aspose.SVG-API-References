---
title: Class CDATASection
second_title: .NET API संदर्भ के लिए Aspose.SVG
description: Aspose.Svg.Dom.CDATASection कक्ष. सडएटए अनुभगं क उपयग अक्षरं वले टेक्स्ट के ब्लक से बचने के लए कय जत है जसे अन्यथ मर्कअप के रूप में मन जएग
type: docs
weight: 440
url: /hi/net/aspose.svg.dom/cdatasection/
---
## CDATASection class

सीडीएटीए अनुभागों का उपयोग अक्षरों वाले टेक्स्ट के ब्लॉक से बचने के लिए किया जाता है जिसे अन्यथा मार्कअप के रूप में माना जाएगा।

```csharp
public class CDATASection : Text
```

## गुण

| नाम | विवरण |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes/) { get; } | एक NamedNodeMap जिसमें इस नोड की विशेषताएँ हैं (यदि यह एक तत्व है) या अशक्त अन्यथा। |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | इस नोड का पूर्ण आधार यूआरआई या शून्य यदि कार्यान्वयन पूर्ण यूआरआई प्राप्त करने में सक्षम नहीं था। |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | एक नोडलिस्ट जिसमें इस नोड के सभी बच्चे शामिल हैं। यदि कोई बच्चे नहीं हैं, तो यह एक नोडलिस्ट है जिसमें कोई नोड नहीं है.. |
| virtual [Data](../../aspose.svg.dom/characterdata/data/) { get; set; } | इस इंटरफ़ेस को लागू करने वाले नोड का वर्ण डेटा। |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | इस नोड का पहला चाइल्ड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| [IsElementContentWhitespace](../../aspose.svg.dom/text/iselementcontentwhitespace/) { get; } | लौटाता है कि क्या इस टेक्स्ट नोड में एलिमेंट कंटेंट व्हाइटस्पेस है, जिसे अक्सर अपमानजनक रूप से "इग्नोरेबल व्हाइटस्पेस" कहा जाता है। |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | इस नोड का अंतिम बच्चा। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| [Length](../../aspose.svg.dom/characterdata/length/) { get; } | 16-बिट इकाइयों की संख्या जो डेटा और सबस्ट्रिंगडेटा विधि के माध्यम से उपलब्ध हैं। इसका मान शून्य हो सकता है, अर्थात, कैरेक्टरडेटा नोड खाली हो सकता है। |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | इस नोड के योग्य नाम का स्थानीय भाग लौटाता है। ELEMENT_NODE और ATTRIBUTE_NODE के अलावा किसी भी प्रकार के नोड्स और DOM स्तर 1 विधि के साथ बनाए गए नोड्स के लिए, जैसे कि Document.createElement (), यह हमेशा शून्य होता है। |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | इस नोड का नामस्थान यूआरआई, या अनिर्दिष्ट होने पर शून्य। |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | इस नोड के तुरंत बाद का नोड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| override [NodeName](../../aspose.svg.dom/cdatasection/nodename/) { get; } | इस नोड का नाम, इसके प्रकार पर निर्भर करता है। |
| override [NodeType](../../aspose.svg.dom/cdatasection/nodetype/) { get; } | अंतर्निहित वस्तु के प्रकार का प्रतिनिधित्व करने वाला एक कोड। |
| override [NodeValue](../../aspose.svg.dom/text/nodevalue/) { get; set; } | इस नोड का मान, इसके प्रकार पर निर्भर करता है। |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | इस नोड से जुड़ा दस्तावेज़ ऑब्जेक्ट। यह नए नोड बनाने के लिए उपयोग की जाने वाली दस्तावेज़ वस्तु भी है। जब यह नोड एक दस्तावेज़ या एक दस्तावेज़ प्रकार है जिसका अभी तक किसी दस्तावेज़ के साथ उपयोग नहीं किया गया है, तो यह शून्य है। |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | माता-पिता को प्राप्त करता है[`Element`](../element/) इस नोड का. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | इस नोड का जनक। Attr, Document, DocumentFragment, Entity, और Notation को छोड़कर सभी नोड्स में माता-पिता हो सकते हैं। हालाँकि, यदि कोई नोड अभी बनाया गया है और अभी तक ट्री में नहीं जोड़ा गया है, या यदि इसे ट्री से हटा दिया गया है, तो यह शून्य है। |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | इस नोड का नामस्थान उपसर्ग, या अनिर्दिष्ट होने पर अशक्त। जब इसे शून्य के रूप में परिभाषित किया जाता है, तो इसे सेट करने से कोई प्रभाव नहीं पड़ता |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | इस नोड के ठीक पहले वाला नोड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| override [TextContent](../../aspose.svg.dom/text/textcontent/) { get; set; } | यह विशेषता इस नोड और उसके वंश की पाठ्य सामग्री लौटाती है। जब इसे शून्य के रूप में परिभाषित किया जाता है, तो इसे सेट करने का कोई प्रभाव नहीं पड़ता है। सेट करने पर, इस नोड के किसी भी संभावित बच्चे को हटा दिया जा सकता है और, यदि यह नया स्ट्रिंग खाली या शून्य नहीं है, तो इस विशेषता को सेट करने वाले स्ट्रिंग वाले एकल टेक्स्ट नोड द्वारा प्रतिस्थापित किया जाता है। |
| [WholeText](../../aspose.svg.dom/text/wholetext/) { get; } | टेक्स्ट नोड्स के सभी टेक्स्ट को तार्किक रूप से आसन्न टेक्स्ट नोड्स को इस नोड में लौटाता है, जो दस्तावेज़ क्रम में जुड़ा हुआ है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(Node) | इस नोड के चिल्ड्रन की सूची के अंत में नोड न्यूचाइल्ड जोड़ता है। यदि नया बच्चा पहले से ही पेड़ में है, तो इसे पहले हटा दिया जाता है। |
| virtual [AppendData](../../aspose.svg.dom/characterdata/appenddata/)(string) | नोड के वर्ण डेटा के अंत में स्ट्रिंग जोड़ें। |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | इस नोड का एक डुप्लिकेट लौटाता है, अर्थात, नोड्स के लिए एक सामान्य कॉपी कंस्ट्रक्टर के रूप में कार्य करता है। डुप्लिकेट नोड का कोई पैरेंट नहीं है (parentNode खाली है) और कोई उपयोगकर्ता डेटा नहीं है। |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(bool) | इस नोड का एक डुप्लिकेट लौटाता है, अर्थात, नोड्स के लिए एक सामान्य कॉपी कंस्ट्रक्टर के रूप में कार्य करता है। डुप्लिकेट नोड का कोई पैरेंट नहीं है (parentNode खाली है) और कोई उपयोगकर्ता डेटा नहीं है। |
| virtual [DeleteData](../../aspose.svg.dom/characterdata/deletedata/)(int, int) | नोड से 16-बिट इकाइयों की श्रेणी निकालें। |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(Event) | यह विधि इवेंट को कार्यान्वयन इवेंट मॉडल में भेजने की अनुमति देती है. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | अप्रबंधित संसाधनों को मुक्त करने, जारी करने या रीसेट करने से संबंधित एप्लिकेशन-परिभाषित कार्य करता है। |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes/)() | रिटर्न करता है कि क्या इस नोड (यदि यह एक तत्व है) में कोई विशेषता है |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | लौटाता है कि क्या इस नोड के कोई बच्चे हैं। |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(Node, Node) | मौजूदा चाइल्ड नोड चाइल्ड से पहले नोड डालें। यदि बच्चा शून्य है, तो बच्चों की सूची के अंत में नोड डालें। यदि बच्चा पहले से ही पेड़ में है, तो उसे पहले हटा दिया जाता है। |
| virtual [InsertData](../../aspose.svg.dom/characterdata/insertdata/)(int, string) | निर्दिष्ट 16-बिट इकाई ऑफ़सेट पर एक स्ट्रिंग डालें. |
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
| virtual [ReplaceData](../../aspose.svg.dom/characterdata/replacedata/)(int, int, string) | निर्दिष्ट स्ट्रिंग के साथ निर्दिष्ट 16-बिट इकाई ऑफ़सेट पर शुरू होने वाले वर्णों को बदलें। |
| [ReplaceWholeText](../../aspose.svg.dom/text/replacewholetext/)(string) | निर्दिष्ट पाठ के साथ वर्तमान नोड और सभी तार्किक रूप से आसन्न पाठ नोड्स के पाठ को प्रतिस्थापित करता है। सभी तार्किक रूप से आसन्न पाठ नोड्स को वर्तमान नोड सहित हटा दिया जाता है जब तक कि यह प्रतिस्थापन पाठ का प्राप्तकर्ता नहीं था। |
| [SplitText](../../aspose.svg.dom/text/splittext/)(int) | निर्दिष्ट ऑफसेट पर इस नोड को दो नोड्स में तोड़ता है, दोनों को पेड़ में भाई-बहन के रूप में रखता है। |
| virtual [SubstringData](../../aspose.svg.dom/characterdata/substringdata/)(int, int) | नोड से डेटा की एक श्रेणी निकालता है। |
| override [ToString](../../aspose.svg.dom/characterdata/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

### यह सभी देखें

* class [Text](../text/)
* नाम स्थान [Aspose.Svg.Dom](../../aspose.svg.dom/)
* सभा [Aspose.SVG](../../)


