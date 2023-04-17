---
title: Document.CreateNodeIterator
second_title: Référence de l'API Aspose.SVG pour .NET
description: Document méthode. Créer un nouveau NodeIterator sur la sousarborescence enracinée au nœud spécifié.
type: docs
weight: 900
url: /fr/net/aspose.svg.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Créer un nouveau NodeIterator sur la sous-arborescence enracinée au nœud spécifié.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| root | Node | nœud qui sera itéré avec ses enfants. L'itérateur est initialement positionné juste avant ce nœud. Les drapeaux whatToShow et le filtre, le cas échéant, ne sont pas pris en compte lors de la définition de cette position. La racine ne doit pas être null. |

### Return_Value

Le NodeIterator nouvellement créé.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR : déclenché si la racine spécifiée est null. |

### Voir également

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* espace de noms [Aspose.Svg.Dom](../../document/)
* Assemblée [Aspose.SVG](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Créer un nouveau NodeIterator sur la sous-arborescence enracinée au nœud spécifié.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| root | Node | nœud qui sera itéré avec ses enfants. L'itérateur est initialement positionné juste avant ce nœud. Les drapeaux whatToShow et le filtre, le cas échéant, ne sont pas pris en compte lors de la définition de cette position. La racine ne doit pas être null. |
| whatToShow | Int64 | flag spécifie quels types de nœuds peuvent apparaître dans la vue logique de l'arborescence présentée par l'itérateur. Voir la description de NodeFilter pour l'ensemble de valeurs SHOW_ possibles. Ces drapeaux peuvent être combinés en utilisant OR. |

### Return_Value

Le NodeIterator nouvellement créé.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR : déclenché si la racine spécifiée est null. |

### Voir également

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* espace de noms [Aspose.Svg.Dom](../../document/)
* Assemblée [Aspose.SVG](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Créer un nouveau NodeIterator sur la sous-arborescence enracinée au nœud spécifié.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| root | Node | nœud qui sera itéré avec ses enfants. L'itérateur est initialement positionné juste avant ce nœud. Les drapeaux whatToShow et le filtre, le cas échéant, ne sont pas pris en compte lors de la définition de cette position. La racine ne doit pas être null. |
| whatToShow | Int64 | flag spécifie quels types de nœuds peuvent apparaître dans la vue logique de l'arborescence présentée par l'itérateur. Voir la description de NodeFilter pour l'ensemble de valeurs SHOW_ possibles. Ces drapeaux peuvent être combinés en utilisant OR. |
| filter | INodeFilter | NodeFilter à utiliser avec this TreeWalker, ou null pour indiquer aucun filtre. |

### Return_Value

Le NodeIterator nouvellement créé.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR : déclenché si la racine spécifiée est null. |

### Voir également

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* espace de noms [Aspose.Svg.Dom](../../document/)
* Assemblée [Aspose.SVG](../../../)


