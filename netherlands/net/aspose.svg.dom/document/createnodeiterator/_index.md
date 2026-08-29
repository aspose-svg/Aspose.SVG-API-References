---
title: "Document.CreateNodeIterator"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Document CreateNodeIterator‑methode. Maak een nieuwe NodeIterator over de subboom die is geworteld in de opgegeven node"
type: docs
weight: 900
url: /nl/net/aspose.svg.dom/document/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../node/)*) {#createnodeiterator}

Maak een nieuwe NodeIterator aan over de subboom die is geworteld in het opgegeven knooppunt.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | node die samen met zijn kinderen wordt doorlopen. De iterator wordt aanvankelijk gepositioneerd direct vóór deze node. De whatToShow‑vlaggen en het filter, indien aanwezig, worden niet in aanmerking genomen bij het instellen van deze positie. De root mag niet null zijn. |

### Retourwaarde

De nieuw aangemaakte NodeIterator.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long*) {#createnodeiterator_1}

Maak een nieuwe NodeIterator aan over de subboom die is geworteld in het opgegeven knooppunt.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | node die samen met zijn kinderen wordt doorlopen. De iterator wordt aanvankelijk gepositioneerd direct vóór deze node. De whatToShow‑vlaggen en het filter, indien aanwezig, worden niet in aanmerking genomen bij het instellen van deze positie. De root mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooptypen kunnen verschijnen in de logische weergave van de boom die door de iterator wordt gepresenteerd. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_ waarden. Deze vlaggen kunnen worden gecombineerd met OR. |

### Retourwaarde

De nieuw aangemaakte NodeIterator.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long, [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)*) {#createnodeiterator_2}

Maak een nieuwe NodeIterator aan over de subboom die is geworteld in het opgegeven knooppunt.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | node die samen met zijn kinderen wordt doorlopen. De iterator wordt aanvankelijk gepositioneerd direct vóór deze node. De whatToShow‑vlaggen en het filter, indien aanwezig, worden niet in aanmerking genomen bij het instellen van deze positie. De root mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooptypen kunnen verschijnen in de logische weergave van de boom die door de iterator wordt gepresenteerd. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_ waarden. Deze vlaggen kunnen worden gecombineerd met OR. |
| filter | INodeFilter | NodeFilter die gebruikt wordt met deze TreeWalker, of null om aan te geven dat er geen filter is. |

### Retourwaarde

De nieuw aangemaakte NodeIterator.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
