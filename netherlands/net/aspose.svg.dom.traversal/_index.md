---
title: "Aspose.Svg.Dom.Traversal"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "De Aspose.Svg.Dom.Traversal‑namespace bevat methoden die iterators en tree‑walkers maken om tussen elementen te navigeren en een knoop en zijn kinderen in documentvolgorde te doorlopen."
type: docs
weight: 120
url: /nl/net/aspose.svg.dom.traversal/
---
De **Aspose.Svg.Dom.Traversal** naamruimte bevat methoden die iterators en boom‑walkers creëren om tussen elementen te navigeren en een knooppunt en zijn kinderen in documentvolgorde te doorlopen.

## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal bevat methoden die iterators en tree‑walkers maken om een knoop en zijn kinderen in documentvolgorde te doorlopen (diepte‑eerste, pre‑order traversie, wat overeenkomt met de volgorde waarin de start‑tags voorkomen in de tekstrepresentatie van het document). In DOM’s die de Traversal‑functie ondersteunen, wordt DocumentTraversal geïmplementeerd door dezelfde objecten die de Document‑interface implementeren. |
| [IElementTraversal](./ielementtraversal/) | De ElementTraversal‑interface is een set van alleen‑lees‑attributen die een auteur in staat stelt gemakkelijk tussen elementen in een document te navigeren. In conforme implementaties van Element Traversal moeten alle objecten die Element implementeren ook de ElementTraversal‑interface implementeren. |
| [INodeFilter](./inodefilter/) | Filters zijn objecten die weten hoe ze knopen moeten \"filteren\". Als een NodeIterator of TreeWalker een NodeFilter krijgt, past hij het filter toe voordat hij de volgende knoop retourneert. Als het filter aangeeft de knoop te accepteren, retourneert de traversielogica deze; anders zoekt de traversie naar de volgende knoop en doet alsof de afgewezen knoop niet bestond. |
| [INodeIterator](./inodeiterator/) | Iterators worden gebruikt om door een verzameling knopen te stappen, bijvoorbeeld de verzameling knopen in een NodeList, de document‑subboom die wordt beheerd door een specifieke Node, de resultaten van een query, of elke andere verzameling knopen. De te itereren verzameling knopen wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert één NodeIterator‑implementatie voor document‑volgorde traversie van een document‑subboom. Exemplaren van deze iterators worden gecreëerd door DocumentTraversal .createNodeIterator() aan te roepen. |
| [ITraversal](./itraversal/) | Iterators worden gebruikt om door een verzameling knopen te stappen, bijvoorbeeld de verzameling knopen in een NodeList, de document‑subboom die wordt beheerd door een specifieke Node, de resultaten van een query, of elke andere verzameling knopen. De te itereren verzameling knopen wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert één NodeIterator‑implementatie voor document‑volgorde traversie van een document‑subboom. Exemplaren van deze iterators worden gecreëerd door DocumentTraversal .createNodeIterator() aan te roepen. |
| [ITreeWalker](./itreewalker/) | TreeWalker‑objecten worden gebruikt om een documentboom of subboom te navigeren met behulp van de weergave van het document die wordt gedefinieerd door hun whatToShow‑vlaggen en filter (indien aanwezig). Elke functie die navigatie uitvoert met een TreeWalker ondersteunt automatisch elke weergave die door een TreeWalker is gedefinieerd. |
