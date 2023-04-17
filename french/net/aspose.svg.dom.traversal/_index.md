---
title: Aspose.Svg.Dom.Traversal
second_title: Référence de l'API Aspose.SVG pour .NET
description: Le Aspose.Svg.Dom.Traversallespace de noms contient des méthodes qui créent des itérateurs et des arborescences pour naviguer entre les éléments et traversent un nœud et ses enfants dans lordre du document.
type: docs
weight: 100
url: /fr/net/aspose.svg.dom.traversal/
---
Le **Aspose.Svg.Dom.Traversal**l'espace de noms contient des méthodes qui créent des itérateurs et des arborescences pour naviguer entre les éléments et traversent un nœud et ses enfants dans l'ordre du document.

## Interfaces

| Interface | La description |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal contient des méthodes qui créent des itérateurs et des tree-walkers pour parcourir un nœud et ses enfants dans l'ordre du document (profondeur en premier, parcours de pré-ordre, qui équivaut à l'ordre dans lequel les balises de début apparaissent dans la représentation textuelle de le document). Dans les DOM qui prennent en charge la fonction Traversal, DocumentTraversal sera implémenté par les mêmes objets qui implémentent l'interface Document. |
| [IElementTraversal](./ielementtraversal/) | L'interface ElementTraversal est un ensemble d'attributs en lecture seule qui permettent à un auteur de naviguer facilement entre les éléments d'un document. Dans les implémentations conformes d'Element Traversal, tous les objets qui implémentent Element doivent également implémenter l'interface ElementTraversal. |
| [INodeFilter](./inodefilter/) | Les filtres sont des objets qui savent comment "filtrer" les nœuds. Si un NodeIterator ou TreeWalker reçoit un NodeFilter, il applique le filtre avant de renvoyer le nœud suivant. Si le filtre dit d'accepter le nœud, la logique de traversée le renvoie ; sinon, la traversée recherche le nœud suivant et prétend que le nœud qui a été rejeté n'était pas là. |
| [INodeIterator](./inodeiterator/) | Les itérateurs sont utilisés pour parcourir un ensemble de nœuds, par exemple l'ensemble de nœuds dans une NodeList, le sous-arbre de documents régi par un nœud particulier, les résultats d'une requête ou tout autre ensemble de nœuds. L'ensemble de nœuds à itérer est déterminé par l'implémentation de NodeIterator. DOM niveau 2 spécifie une implémentation unique de NodeIterator pour la traversée de l'ordre des documents d'une sous-arborescence de documents. Les instances de ces itérateurs sont créées en appelant DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Les itérateurs sont utilisés pour parcourir un ensemble de nœuds, par exemple l'ensemble de nœuds dans une NodeList, le sous-arbre de documents régi par un nœud particulier, les résultats d'une requête ou tout autre ensemble de nœuds. L'ensemble de nœuds à itérer est déterminé par l'implémentation de NodeIterator. DOM niveau 2 spécifie une implémentation unique de NodeIterator pour la traversée de l'ordre des documents d'une sous-arborescence de documents. Les instances de ces itérateurs sont créées en appelant DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | Les objets TreeWalker sont utilisés pour naviguer dans une arborescence de documents ou une sous-arborescence en utilisant la vue du document définie par leurs drapeaux whatToShow et leur filtre (le cas échéant). Toute fonction qui effectue la navigation à l'aide d'un TreeWalker prendra automatiquement en charge toute vue définie par un TreeWalker. |


