---
title: INodeIterator
second_title: Aspose.SVG for .NET API Referansı
description: Yineleyiciler örneğin bir NodeListteki düğüm kümesi belirli bir Düğüm tarafından yönetilen belge alt ağacı bir sorgunun sonuçları veya herhangi bir başka düğüm kümesi gibi bir düğüm kümesinde adım atmak için kullanılır. Yinelenecek düğüm kümesi NodeIteratorın uygulaması tarafından belirlenir. DOM Düzey 2 bir belge alt ağacının belge sırası geçişi için tek NodeIterator uygulamasını belirtir. Bu yineleyicilerin örnekleri DocumentTraversal .createNodeIterator. çağrılarak oluşturulur.
type: docs
weight: 1250
url: /tr/net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

Yineleyiciler, örneğin bir NodeList'teki düğüm kümesi, belirli bir Düğüm tarafından yönetilen belge alt ağacı, bir sorgunun sonuçları veya herhangi bir başka düğüm kümesi gibi bir düğüm kümesinde adım atmak için kullanılır. Yinelenecek düğüm kümesi, NodeIterator'ın uygulaması tarafından belirlenir. DOM Düzey 2, bir belge alt ağacının belge sırası geçişi için tek NodeIterator uygulamasını belirtir. Bu yineleyicilerin örnekleri, DocumentTraversal .createNodeIterator(). çağrılarak oluşturulur.

Ayrıca bkz.[Belge nesnesi Modeli (DOM) Düzey 2 Geçiş ve Aralık Belirtimi](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Düzey 2

```csharp
public interface INodeIterator : ITraversal
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode) { get; } | Bu bayrağın değeri, entity referans düğümlerinin alt öğelerinin yineleyici tarafından görülüp görülmeyeceğini belirler. Yanlışsa, onlar ve torunları reddedilecektir. Bu reddetmenin whatToShow ve filtreden önce olduğunu unutmayın. Ayrıca, bunun şu anda NodeIterators'ın tek tek düğümleri atlamak yerine tam bir alt ağacı reddedebileceği tek durum olduğuna dikkat edin . Varlık referansları genişletilmiş ve varlık referans düğümünün kendisini ifşa etmeyen belgenin bir görünümünü oluşturmak için whatToShow işaretlerini kullanın node varlık referansını gizleyin ve the yineleyiciyi oluştururken expandEntityReferences öğesini true olarak ayarlayın. Varlık referansı düğümleri olan ancak varlık genişletmesi olmayan belgenin bir görünümünü oluşturmak için varlık referans düğümünü göstermek için whatToShow flags öğesini kullanın ve set ExpandEntityReferences öğesini false. olarak ayarlayın. |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode) { get; } | Geçerli başvuru düğümü. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach)() | NodeIterator'ı, üzerinde yinelediği kümesinden ayırır, tüm hesaplama kaynaklarını serbest bırakır ve yineleyici öğesini INVALID durumuna getirir. Ayırma başlatıldıktan sonra, nextNode veya öncekiNode'a çağrılar, INVALID_STATE_ERR. istisnasını yükseltir |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode)() | Kümedeki sonraki düğümü döndürür ve kümedeki yineleyicinin konumunu ilerletir. Bir NodeIterator oluşturulduktan sonra, nextNode() öğesine yapılan ilk çağrı, set. içindeki ilk düğümü döndürür. |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode)() | Kümedeki önceki düğümü döndürür ve NodeIterator konumunu kümede geriye doğru hareket ettirir. |

### Ayrıca bakınız

* interface [ITraversal](../itraversal)
* ad alanı [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal)
* toplantı [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->