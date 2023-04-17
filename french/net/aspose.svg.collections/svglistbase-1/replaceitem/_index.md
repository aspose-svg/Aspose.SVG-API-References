---
title: SVGListBase1.ReplaceItem
second_title: Référence de l'API Aspose.SVG pour .NET
description: SVGListBase méthode. Remplace un élément existant dans la liste par un nouvel élément.
type: docs
weight: 110
url: /fr/net/aspose.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Remplace un élément existant dans la liste par un nouvel élément.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newItem | T | L'élément qui doit être inséré dans la liste. |
| index | UInt64 | Index de l'élément à remplacer. Le premier élément est le numéro 0. |

### Return_Value

L'élément inséré.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Levé lorsque la liste ne peut pas être modifiée. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code[`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Déclenché si le numéro d'index est supérieur ou égal à numberOfItems. |

### Voir également

* class [SVGListBase&lt;T&gt;](../)
* espace de noms [Aspose.Svg.Collections](../../svglistbase-1/)
* Assemblée [Aspose.SVG](../../../)


