---
title: "Interface IStorage"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Interface Aspose.Svg.Dom.IStorage. Cette interface de l’API Web Storage fournit un accès à la session ou au stockage local d’un domaine particulier. Voir la spécification Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /fr/net/aspose.svg.dom/istorage/
---
## IStorage interface

Cette interface de l’API Web Storage fournit un accès à la session ou au stockage local d’un domaine particulier. Voir la spécification Web Storage : [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | Renvoie le nombre de paires clé/valeur. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | Supprime toutes les paires clé/valeur, s’il y en a. |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | Renvoie la valeur actuelle associée à la clé donnée, ou null si la clé donnée n’existe pas. |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | Renvoie le nom de la nième clé, ou null si n est supérieur ou égal au nombre de paires clé/valeur. |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | Supprime la paire clé/valeur avec la clé donnée, si une paire avec cette clé existe. |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | Définit la valeur de la paire identifiée par la clé à la valeur, créant une nouvelle paire clé/valeur si aucune n’existait auparavant pour cette clé. |

### Voir aussi

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
