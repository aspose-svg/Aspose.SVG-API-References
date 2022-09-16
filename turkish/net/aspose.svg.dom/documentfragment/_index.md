---
title: DocumentFragment
second_title: Aspose.SVG for .NET API Referansı
description: DocumentFragment hafif veya minimal bir Document nesnesidir. Bir belgenin ağacının bir kısmını çıkarabilmeyi veya belgenin yeni bir parçasını oluşturabilmeyi istemek çok yaygındır.
type: docs
weight: 820
url: /tr/net/aspose.svg.dom/documentfragment/
---
## DocumentFragment class

DocumentFragment, "hafif" veya "minimal" bir Document nesnesidir. Bir belgenin ağacının bir kısmını çıkarabilmeyi veya belgenin yeni bir parçasını oluşturabilmeyi istemek çok yaygındır.

```csharp
public class DocumentFragment : Node, IParentNode
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes) { get; } | Bu düğümün (bir Öğe ise) özniteliklerini içeren bir NamedNodeMap, aksi takdirde null. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri) { get; } | Bu düğümün mutlak temel URI'si veya uygulama mutlak bir URI alamadıysa null. |
| [ChildElementCount](../../aspose.svg.dom/documentfragment/childelementcount) { get; } | Bu öğenin alt öğeleri olan geçerli öğe düğümlerinin sayısını döndürür. 0, bu öğenin nodeType 1. olan alt düğümleri yoksa |
| [ChildNodes](../../aspose.svg.dom/node/childnodes) { get; } | Bu düğümün tüm alt öğelerini içeren bir Düğüm Listesi. Alt öğe yoksa, bu düğüm içermeyen bir NodeList'tir.. |
| [Children](../../aspose.svg.dom/documentfragment/children) { get; } | Geçerli öğenin alt öğelerini döndürür. |
| [FirstChild](../../aspose.svg.dom/node/firstchild) { get; } | Bu düğümün ilk çocuğu. Böyle bir düğüm yoksa, bu null. değerini döndürür. |
| [FirstElementChild](../../aspose.svg.dom/documentfragment/firstelementchild) { get; } | Bu öğenin ilk alt öğe düğümünü döndürür. bu öğenin alt öğesi yoksa null. |
| [InnerHTML](../../aspose.svg.dom/documentfragment/innerhtml) { get; set; } | Öğenin içeriğini temsil eden bir HTML veya XML parçası döndürür. Öğenin içeriğini verilen dizeden ayrıştırılan düğümlerle değiştirmek için ayarlanabilir. |
| [LastChild](../../aspose.svg.dom/node/lastchild) { get; } | Bu düğümün son çocuğu. Böyle bir düğüm yoksa, bu null. değerini döndürür. |
| [LastElementChild](../../aspose.svg.dom/documentfragment/lastelementchild) { get; } | Bu öğenin son alt öğe düğümünü döndürür. bu öğenin alt öğesi yoksa null. |
| virtual [LocalName](../../aspose.svg.dom/node/localname) { get; } | Bu düğümün nitelikli adının yerel bölümünü döndürür. ELEMENT_NODE ve ATTRIBUTE_NODE dışındaki herhangi bir türdeki düğümler ve Document.createElement() gibi bir DOM Düzey 1 yöntemiyle oluşturulan düğümler için bu her zaman null. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri) { get; } | Bu düğümün ad alanı URI'si veya belirtilmemişse null. |
| [NextElementSibling](../../aspose.svg.dom/documentfragment/nextelementsibling) { get; } | Bu öğenin sonraki kardeş öğe düğümünü döndürür. bu öğenin belge ağacında bundan sonra gelen öğe kardeş düğümleri yoksa null. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling) { get; } | Bu düğümden hemen sonraki düğüm. Böyle bir düğüm yoksa, bu null. değerini döndürür. |
| override [NodeName](../../aspose.svg.dom/documentfragment/nodename) { get; } | Türüne bağlı olarak bu düğümün adı. |
| override [NodeType](../../aspose.svg.dom/documentfragment/nodetype) { get; } | Temel alınan nesnenin türünü temsil eden bir kod. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue) { get; set; } | Türüne bağlı olarak bu düğümün değeri. |
| [OuterHTML](../../aspose.svg.dom/documentfragment/outerhtml) { get; set; } | Öğeyi ve içeriğini temsil eden bir HTML veya XML parçası döndürür. Öğeyi verilen dizeden ayrıştırılan düğümlerle değiştirmek için ayarlanabilir. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument) { get; } | Bu düğümle ilişkili Document nesnesi. Bu aynı zamanda yeni düğümler oluşturmak için kullanılan Document nesnesidir. Bu düğüm bir Document veya henüz herhangi bir Document ile kullanılmayan bir DocumentType olduğunda, bu null. |
| [ParentElement](../../aspose.svg.dom/node/parentelement) { get; } | Üst öğeyi alır[`Element`](../element) bu düğümün. |
| [ParentNode](../../aspose.svg.dom/node/parentnode) { get; } | Bu düğümün ebeveyni. Attr, Document, DocumentFragment, Entity ve Notation dışındaki tüm düğümlerin bir üst öğesi olabilir. Ancak, bir düğüm yeni oluşturulmuşsa ve henüz ağaca eklenmemişse veya ağaçtan kaldırılmışsa, bu null. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix) { get; set; } | Bu düğümün ad alanı öneki veya belirtilmemişse null. Null olarak tanımlandığında, ayarın hiçbir etkisi yoktur |
| [PreviousElementSibling](../../aspose.svg.dom/documentfragment/previouselementsibling) { get; } | Bu öğenin önceki kardeş öğe düğümünü döndürür. bu öğenin belge ağacında bundan önce gelen öğe kardeş düğümleri yoksa null. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling) { get; } | Bu düğümden hemen önceki düğüm. Böyle bir düğüm yoksa, bu null. değerini döndürür. |
| override [TextContent](../../aspose.svg.dom/documentfragment/textcontent) { get; set; } | Bu öznitelik, bu düğümün ve onun soyundan gelenlerin metin içeriğini döndürür. Null olarak tanımlandığında, ayarlamanın bir etkisi olmaz. Ayar sırasında, bu düğümün sahip olabileceği olası tüm alt öğeler kaldırılır ve yeni dize boş veya boş değilse, bu özniteliğin ayarlandığı dizeyi içeren tek bir Metin düğümü ile değiştirilir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine olanak tanır. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine olanak tanır. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine olanak tanır. |
| [AppendChild](../../aspose.svg.dom/node/appendchild)(Node) | newChild düğümünü bu düğümün alt öğeleri listesinin sonuna ekler. newChild zaten ağaçtaysa, önce kaldırılır. |
| [CloneNode](../../aspose.svg.dom/node/clonenode)() | Bu düğümün bir kopyasını döndürür, yani düğümler için genel bir kopya oluşturucu görevi görür. Yinelenen düğümün üst öğesi yok (parentNode null) ve kullanıcı verisi yok. |
| [CloneNode](../../aspose.svg.dom/node/clonenode)(bool) | Bu düğümün bir kopyasını döndürür, yani düğümler için genel bir kopya oluşturucu görevi görür. Yinelenen düğümün üst öğesi yok (parentNode null) ve kullanıcı verisi yok. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent)(Event) | Bu yöntem, olayların uygulama olay modeline gönderilmesine olanak tanır. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Bu yöntem, ECMAScript nesnesini almak için kullanılırType . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes)() | Bu düğümün (bir öğeyse) herhangi bir niteliği olup olmadığını döndürür |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes)() | Bu düğümün alt öğesi olup olmadığını döndürür. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore)(Node, Node) | Düğümü, mevcut alt düğüm alt öğesinden önce ekler. Alt öğe null ise, alt öğe listesinin sonuna düğüm ekleyin. Alt öğe bir DocumentFragment nesnesiyse, alt öğelerin tümü alt öğeden önce aynı sırayla eklenir. Alt öğe zaten ağaçtaysa, önce kaldırılır. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace)(string) | Bu yöntem, belirtilen ad alanıURI'sinin varsayılan ad alanı olup olmadığını kontrol eder. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode)(Node) | İki düğümün eşit olup olmadığını test eder. Bu yöntem, Node.isSameNode() ile test edilebilen aynılığı değil (yani, iki düğümün aynı nesneye referans olup olmadığını) değil düğümlerin eşitliğini test eder. Aynı olan tüm düğümler de eşit olacaktır, ancak bunun tersi doğru olmayabilir. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode)(Node) | Bu düğümün verilen düğümle aynı düğüm olup olmadığını döndürür. Bu yöntem, uygulama tarafından döndürülen iki Düğüm başvurusunun aynı nesneye başvurup göndermediğini belirlemenin bir yolunu sağlar. İki Node referansı aynı nesneye referans olduğunda, bir proxy aracılığıyla bile olsa referanslar tamamen birbirinin yerine kullanılabilir, öyle ki tüm nitelikler aynı değerlere sahiptir ve her iki referansta da aynı DOM yöntemini çağırmak her zaman tam olarak aynı etkiye sahiptir. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri)(string) | Bu düğümden başlayarak, verilen önekle ilişkili ad alanı URI'sini arayın. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix)(string) | Bu düğümden başlayarak, verilen ad alanı URI'si ile ilişkili öneki arayın. Varsayılan ad alanı bildirimleri bu yöntem tarafından yok sayılır. Bu yöntem tarafından kullanılan algoritmayla ilgili ayrıntılar için bkz. Ad Alanı Önek Araması. |
| [Normalize](../../aspose.svg.dom/node/normalize)() | Öznitelik düğümleri de dahil olmak üzere, bu Düğümün altındaki alt ağacın tam derinliğindeki tüm Metin düğümlerini, yalnızca yapının (örneğin, öğeler, yorumlar, işleme talimatları, CDATA bölümleri ve varlık referansları) Metin'i ayırdığı "normal" bir forma koyar düğümler, yani ne bitişik Metin düğümleri ne de boş Metin düğümleri vardır. Bu, bir belgenin DOM görünümünün, sanki kaydedilmiş ve yeniden yüklenmiş gibi aynı olmasını sağlamak için kullanılabilir ve belirli bir belge ağacı yapısına bağlı işlemler (XPointer [XPointer] aramaları gibi) gerektiğinde yararlıdır. kullanılabilir. Node.ownerDocument öğesine eklenen DOMConfiguration nesnesinin "normalize-characters" parametresi doğruysa, bu yöntem Metin düğümlerinin karakterlerini de tamamen normalleştirir. |
| [QuerySelector](../../aspose.svg.dom/documentfragment/queryselector)(string) | Belgedeki seçici ile eşleşen ilk Öğeyi döndürür |
| [QuerySelectorAll](../../aspose.svg.dom/documentfragment/queryselectorall)(string) | Selector ile eşleşen, belgedeki tüm Öğelerin Düğüm Listesini döndürür |
| [RemoveChild](../../aspose.svg.dom/node/removechild)(Node) | oldChild tarafından belirtilen alt düğümü alt öğeler listesinden kaldırır ve döndürür. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener) birinden kaldırılır[`EventTarget`](../eventtarget) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyicileri, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener) birinden kaldırılır[`EventTarget`](../eventtarget) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyicileri, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener) birinden kaldırılır[`EventTarget`](../eventtarget) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyicileri, kaldırıldıktan sonra asla çağrılamaz. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild)(Node, Node) | Çocuklar listesinde oldChild alt düğümünü newChild ile değiştirir ve oldChild düğümünü döndürür. newChild bir DocumentFragment nesnesiyse, oldChild, aynı sırayla eklenen tüm DocumentFragment alt öğeleriyle değiştirilir. newChild zaten ağaçtaysa, önce kaldırılır. |
| override [ToString](../../aspose.svg.dom/node/tostring)() | Bir döndürürString bu, bu örneği temsil eder. |

### Ayrıca bakınız

* class [Node](../node)
* interface [IParentNode](../iparentnode)
* ad alanı [Aspose.Svg.Dom](../../aspose.svg.dom)
* toplantı [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->