---
title: IXPathResult.SnapshotItem
second_title: Référence de l'API Aspose.SVG pour .NET
description: IXPathResult méthode. Renvoie leindice ème élément de la collection dinstantanés. Siindiceest supérieur à ou égal au nombre de nœuds de la liste cette méthode renvoienul . Contrairement au résultat de litérateur  linstantané ne devient pas invalide mais peut ne pas correspondre au document actuel sil est muté.
type: docs
weight: 90
url: /fr/net/aspose.svg.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Renvoie le`indice` ème élément de la collection d'instantanés. Si`indice`est supérieur à ou égal au nombre de nœuds de la liste, cette méthode renvoie`nul` . Contrairement au résultat de l'itérateur , l'instantané ne devient pas invalide, mais peut ne pas correspondre au document actuel s'il est muté.

```csharp
public Node SnapshotItem(int index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Index dans la collection d'instantanés. |

### Return_Value

Le nœud au`indice` ème position dans le`Liste de nœuds` , ou`nul` si ce n'est pas un index valide.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR : déclenché si`type de résultat` n'est pas `UnorderedNodeSnapshotUnorderedNodeSnapshot` taper ou`OrderedNodeSnapshot` taper. |

### Voir également

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* espace de noms [Aspose.Svg.Dom.XPath](../../ixpathresult/)
* Assemblée [Aspose.SVG](../../../)


