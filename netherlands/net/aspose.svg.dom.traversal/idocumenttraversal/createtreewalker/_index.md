---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IDocumentTraversal CreateTreeWalker-methode. Maak een nieuwe TreeWalker over de subboom die is geworteld bij de opgegeven node"
type: docs
weight: 20
url: /nl/net/aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/)*) {#createtreewalker}

Maak een nieuwe TreeWalker over de subboom die is geworteld bij de opgegeven knoop.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| root | Node | knoop die dient als de wortel voor de TreeWalker. De whatToShow‑vlaggen en de NodeFilter worden niet in aanmerking genomen bij het instellen van deze waarde; elk knooptype wordt geaccepteerd als wortel. De currentNode van de TreeWalker wordt op deze knoop geïnitialiseerd, ongeacht of deze zichtbaar is. De wortel fungeert als een stoppunt voor traversalmethoden die omhoog kijken in de documentstructuur, zoals parentNode en nextNode. De wortel mag niet null zijn. |

### Retourwaarde

De nieuw aangemaakte TreeWalker.

### Zie ook

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long*) {#createtreewalker_1}

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

### Zie ook

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createtreewalker_2}

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

### Zie ook

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
