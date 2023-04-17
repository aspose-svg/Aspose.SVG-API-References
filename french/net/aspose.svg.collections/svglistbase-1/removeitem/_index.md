---
title: SVGListBase1.RemoveItem
second_title: Référence de l'API Aspose.SVG pour .NET
description: SVGListBase méthode. Supprime un élément existant de la liste.
type: docs
weight: 100
url: /fr/net/aspose.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Supprime un élément existant de la liste.

```csharp
public T RemoveItem(ulong index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | UInt64 | Index de l'élément à supprimer. Le premier élément est le numéro 0. |

### Return_Value

L'élément supprimé.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Levé lorsque la liste ne peut pas être modifiée. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code[`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Déclenché si le numéro d'index est supérieur ou égal à numberOfItems. |

### Voir également

* class [SVGListBase&lt;T&gt;](../)
* espace de noms [Aspose.Svg.Collections](../../svglistbase-1/)
* Assemblée [Aspose.SVG](../../../)


