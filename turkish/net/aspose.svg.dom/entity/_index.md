---
title: Class Entity
second_title: Aspose.SVG for .NET API Referansı
description: Aspose.Svg.Dom.Entity sınıf. Bir XML belgesinde ayrıştırılmış veya ayrıştırılmamış olarak bilinen bir varlığı temsil eder.
type: docs
weight: 850
url: /tr/net/aspose.svg.dom/entity/
---
## Entity class

Bir XML belgesinde ayrıştırılmış veya ayrıştırılmamış olarak bilinen bir varlığı temsil eder.

```csharp
public class Entity : Node
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes/) { get; } | Bu düğümün özniteliklerini (bir Öğe ise) içeren bir NamedNodeMap veya aksi halde null. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Bu düğümün mutlak temel URI'si veya uygulama mutlak bir URI elde edemediyse null. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Bu düğümün tüm alt öğelerini içeren bir NodeList. Alt öğe yoksa bu, düğüm içermeyen bir NodeList'tir.. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Bu düğümün ilk çocuğu. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| [InputEncoding](../../aspose.svg.dom/entity/inputencoding/) { get; } | Harici ayrıştırılmış bir varlık olduğunda, ayrıştırma sırasında bu varlık için kullanılan kodlamayı belirten bir öznitelik. Bu, dahili alt kümeden bir varlıksa veya bilinmiyorsa boştur. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Bu düğümün son çocuğu. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Bu düğümün nitelikli adının yerel kısmını döndürür. ELEMENT_NODE ve ATTRIBUTE_NODE dışındaki herhangi bir türdeki düğümler ve Document.createElement() gibi DOM Düzey 1 yöntemiyle oluşturulan düğümler için bu her zaman boştur. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Bu düğümün ad alanı URI'si veya belirtilmemişse boş. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Bu düğümü hemen takip eden düğüm. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| override [NodeName](../../aspose.svg.dom/entity/nodename/) { get; } | Türüne bağlı olarak bu düğümün adı. |
| override [NodeType](../../aspose.svg.dom/entity/nodetype/) { get; } | Altta yatan nesnenin türünü temsil eden bir kod. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Türüne bağlı olarak bu düğümün değeri. |
| [NotationName](../../aspose.svg.dom/entity/notationname/) { get; } | Ayrıştırılmamış varlıklar için, varlığın gösteriminin adı. Ayrıştırılmış varlıklar için bu null. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Bu düğümle ilişkili Belge nesnesi. Bu aynı zamanda yeni düğümler oluşturmak için kullanılan Belge nesnesidir. Bu düğüm, henüz herhangi bir Belge ile kullanılmayan bir Belge veya Belge Türü olduğunda, bu null. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Ebeveyni alır[`Element`](../element/) bu düğümün. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Bu düğümün ebeveyni. Attr, Document, DocumentFragment, Entity ve Notation dışındaki tüm düğümlerin bir üst öğesi olabilir. Ancak, bir düğüm yeni oluşturulmuşsa ve henüz ağaca eklenmemişse veya ağaçtan kaldırılmışsa, bu null. olur. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Bu düğümün ad alanı öneki veya belirtilmemişse boş. Boş olarak tanımlandığında, ayarının etkisi yoktur |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Bu düğümden hemen önceki düğüm. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| [PublicId](../../aspose.svg.dom/entity/publicid/) { get; } | Belirtilmişse varlıkla ilişkili genel tanımlayıcı, aksi halde boş. |
| [SystemId](../../aspose.svg.dom/entity/systemid/) { get; } | Belirtilmişse varlıkla ilişkili sistem tanımlayıcısı, aksi halde boş. Bu, mutlak bir URI olabilir veya olmayabilir. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Bu öznitelik, bu düğümün ve onun soyundan gelenlerin metin içeriğini döndürür. Null olarak tanımlandığında, ayarının hiçbir etkisi yoktur. Ayarlama sırasında, bu düğümün sahip olabileceği tüm olası alt öğeler kaldırılır ve yeni dize boş veya boş değilse, bu özniteliğin ayarlandığı dizeyi içeren tek bir Metin düğümü ile değiştirilir. |
| [XmlEncoding](../../aspose.svg.dom/entity/xmlencoding/) { get; } | Harici ayrıştırılmış bir varlık olduğunda, metin bildiriminin bir parçası olarak bu varlığın kodlamasını belirten bir öznitelik. Aksi halde bu boştur. |
| [XmlVersion](../../aspose.svg.dom/entity/xmlversion/) { get; } | Harici ayrıştırılmış bir varlık olduğunda, metin bildiriminin bir parçası olarak bu varlığın sürüm numarasını belirten bir öznitelik. Aksi halde bu boştur. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(Node) | newChild düğümünü bu düğümün çocukları listesinin sonuna ekler. newChild zaten ağaçtaysa, önce kaldırılır. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Bu düğümün bir kopyasını döndürür, yani düğümler için genel bir kopya oluşturucu görevi görür. Yinelenen düğümün üst öğesi (parentNode boştur) ve kullanıcı verisi yoktur. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(bool) | Bu düğümün bir kopyasını döndürür, yani düğümler için genel bir kopya oluşturucu görevi görür. Yinelenen düğümün üst öğesi (parentNode boştur) ve kullanıcı verisi yoktur. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(Event) | Bu yöntem, olayların uygulama olay modeline gönderilmesine izin verir. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes/)() | Bu düğümün (eğer bir öğe ise) herhangi bir özniteliği olup olmadığını döndürür |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Bu düğümün herhangi bir alt öğesi olup olmadığını döndürür. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(Node, Node) | Düğümü varolan alt düğüm alt öğesinden önce ekler. Child null ise, çocuklar listesinin sonuna düğüm ekleyin. Child bir DocumentFragment nesnesiyse, tüm alt öğeleri aynı sırayla alt öğeden önce eklenir. Çocuk zaten ağaçtaysa, önce kaldırılır. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(string) | Bu yöntem, belirtilen namespaceURI'nin varsayılan ad alanı olup olmadığını kontrol eder. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(Node) | İki düğümün eşit olup olmadığını test eder. Bu yöntem, Node.isSameNode() ile test edilebilen aynılığı (yani iki düğümün aynı nesneye referans olup olmadığını) değil, düğümlerin eşitliğini test eder. Aynı olan tüm düğümler de eşit olacaktır, ancak tersi doğru olmayabilir. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(Node) | Bu düğümün verilenle aynı düğüm olup olmadığını döndürür. Bu yöntem, uygulama tarafından döndürülen iki Düğüm başvurusunun aynı nesneye başvuruda bulunup bulunmadığını belirlemenin bir yolunu sağlar. İki Düğüm referansı aynı nesneye referans olduğunda, bir proxy üzerinden olsa bile, referanslar tamamen birbirinin yerine kullanılabilir, böylece tüm öznitelikler aynı değerlere sahip olur ve her iki referansta da aynı DOM yöntemini çağırmak her zaman tam olarak aynı etkiye sahip olur. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(string) | Bu düğümden başlayarak verilen önekle ilişkili ad alanı URI'sine bakın. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(string) | Bu düğümden başlayarak verilen ad alanı URI'si ile ilişkili öneki arayın. Varsayılan ad alanı bildirimleri bu yöntem tarafından dikkate alınmaz. Bu yöntem tarafından kullanılan algoritma hakkında ayrıntılar için Ad Alanı Öneki Arama'ya bakın. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Öznitelik düğümleri de dahil olmak üzere, bu Düğümün altındaki alt ağacın tüm derinliğindeki tüm Metin düğümlerini, Metni yalnızca yapının (örneğin, öğeler, yorumlar, işleme yönergeleri, CDATA bölümleri ve varlık referansları) ayırdığı "normal" bir forma sokar. düğümler, yani bitişik Metin düğümleri veya boş Metin düğümleri yoktur. Bu, bir belgenin DOM görünümünün, kaydedilmiş ve yeniden yüklenmiş haliyle aynı olmasını sağlamak için kullanılabilir ve belirli bir belge ağacı yapısına bağlı olan işlemler (XPointer [XPointer] aramaları gibi) kullanılmalı Node.ownerDocument'e eklenen DOMConfiguration nesnesinin "normalize-characters" parametresi doğruysa, bu yöntem Metin düğümlerinin karakterlerini de tam olarak normalleştirir. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(Node) | oldChild tarafından belirtilen alt düğümü alt öğe listesinden kaldırır ve onu döndürür. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(Node, Node) | Alt düğüm listesindeki oldChild alt düğümünü newChild ile değiştirir ve oldChild düğümünü döndürür. newChild bir DocumentFragment nesnesiyse, eskiChild aynı sırayla eklenen tüm DocumentFragment alt öğeleriyle değiştirilir. newChild zaten ağaçtaysa, önce kaldırılır. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | a döndürürString bu örneği temsil eder. |

### Ayrıca bakınız

* class [Node](../node/)
* ad alanı [Aspose.Svg.Dom](../../aspose.svg.dom/)
* toplantı [Aspose.SVG](../../)


