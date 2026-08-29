---
title: "Document.CreateTreeWalker"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Document CreateTreeWalker‑methode. Maakt een nieuwe TreeWalker aan over de subboom die is geworteld in de opgegeven knoop."
type: docs
weight: 940
url: /nl/net/aspose.svg.dom/document/createtreewalker/
---
## CreateTreeWalker(*[Node](../../node/)*) {#createtreewalker}

Maak een nieuwe TreeWalker over de subboom die is geworteld bij de opgegeven knoop.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knoop die dient als de wortel voor de TreeWalker. De whatToShow‑vlaggen en de NodeFilter worden niet in aanmerking genomen bij het instellen van deze waarde; elk knooptype wordt geaccepteerd als wortel. De currentNode van de TreeWalker wordt op deze knoop geïnitialiseerd, ongeacht of deze zichtbaar is. De wortel fungeert als een stoppunt voor traversalmethoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De wortel mag niet null zijn. |

### Retourwaarde

De nieuw aangemaakte TreeWalker.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../node/), long*) {#createtreewalker_1}

Maak een nieuwe TreeWalker over de subboom die is geworteld bij de opgegeven knoop.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knoop die dient als de wortel voor de TreeWalker. De whatToShow‑vlaggen en de NodeFilter worden niet in aanmerking genomen bij het instellen van deze waarde; elk knooptype wordt geaccepteerd als wortel. De currentNode van de TreeWalker wordt op deze knoop geïnitialiseerd, ongeacht of deze zichtbaar is. De wortel fungeert als een stoppunt voor traversalmethoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De wortel mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooptypen kunnen verschijnen in de logische weergave van de boom die wordt gepresenteerd door de tree-walker. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |

### Retourwaarde

De nieuw aangemaakte TreeWalker.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../node/), long, [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)*) {#createtreewalker_2}

Maak een nieuwe TreeWalker over de subboom die is geworteld bij de opgegeven knoop.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knoop die dient als de wortel voor de TreeWalker. De whatToShow‑vlaggen en de NodeFilter worden niet in aanmerking genomen bij het instellen van deze waarde; elk knooptype wordt geaccepteerd als wortel. De currentNode van de TreeWalker wordt op deze knoop geïnitialiseerd, ongeacht of deze zichtbaar is. De wortel fungeert als een stoppunt voor traversalmethoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De wortel mag niet null zijn. |
| whatToShow | Int64 | vlag specificeert welke knooptypen kunnen verschijnen in de logische weergave van de boom die wordt gepresenteerd door de tree-walker. Zie de beschrijving van NodeFilter voor de set van mogelijke SHOW_-waarden. Deze vlaggen kunnen worden gecombineerd met OR. |
| filter | INodeFilter | NodeFilter die gebruikt wordt met deze TreeWalker, of null om aan te geven dat er geen filter is. |

### Retourwaarde

De nieuw aangemaakte TreeWalker.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de opgegeven root null is. |

### Zie ook

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
