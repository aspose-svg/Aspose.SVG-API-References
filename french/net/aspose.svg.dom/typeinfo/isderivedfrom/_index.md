---
title: TypeInfo.IsDerivedFrom
second_title: Référence de l'API Aspose.SVG pour .NET
description: TypeInfo méthode. Cette méthode renvoie sil existe une dérivation entre la définition du type de référence cestàdire le TypeInfo sur lequel la méthode est appelée et lautre définition de type cestàdire celle passée en paramètre.
type: docs
weight: 30
url: /fr/net/aspose.svg.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Cette méthode renvoie s'il existe une dérivation entre la définition du type de référence, c'est-à-dire le TypeInfo sur lequel la méthode est appelée, et l'autre définition de type, c'est-à-dire celle passée en paramètre.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| typeNamespaceArg | String | l'espace de noms de l'autre définition de type |
| typeNameArg | String | le nom de l'autre définition de type. |
| derivationMethod | UInt64 | le type de dérivation et les conditions appliquées entre deux types, comme décrit dans la liste des constantes fournies dans cette interface. |

### Return_Value

Si le schéma du document est une DTD ou si aucun schéma n'est associé au document, cette méthode retournera toujours false. Si le schéma du document est un schéma XML, la méthode sera vraie si la définition du type de référence est dérivée de l'autre définition de type selon le paramètre de dérivation. Si la valeur du paramètre est 0 (aucun bit n'est défini sur 1 pour le paramètre derivationMethod), la méthode renverra true si l'autre définition de type peut être atteinte en récursant toute combinaison de {base type definition}, {item type definition} , ou {définitions de type de membre} à partir de la définition de type de référence.

### Voir également

* class [TypeInfo](../)
* espace de noms [Aspose.Svg.Dom](../../typeinfo/)
* Assemblée [Aspose.SVG](../../../)


