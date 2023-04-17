---
title: Enum Sandbox
second_title: Référence de l'API Aspose.SVG pour .NET
description: Aspose.Svg.Sandbox énumération. Un ensemble dindicateurs de sandboxing est un ensemble de zéro ou plusieurs des indicateurs suivants qui sont utilisés pour restreindre les capacités des ressources potentiellement non fiables.
type: docs
weight: 3610
url: /fr/net/aspose.svg/sandbox/
---
## Sandbox enumeration

Un ensemble d'indicateurs de sandboxing est un ensemble de zéro ou plusieurs des indicateurs suivants, qui sont utilisés pour restreindre les capacités des ressources potentiellement non fiables.

```csharp
[Flags]
public enum Sandbox
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| None | `0` | Aucun indicateur n'est défini, chaque fonctionnalité de bac à sable est acceptée |
| Navigation | `1` | Cet indicateur empêche le contenu de naviguer dans des contextes de navigation autres que le contexte de navigation en bac à sable lui-même (ou les contextes de navigation imbriqués à l'intérieur de celui-ci), les contextes de navigation auxiliaires (qui sont protégés par l'indicateur de contexte de navigation de navigation auxiliaire en bac à sable défini ci-après) et le niveau supérieur contexte de navigation (qui est protégé par l'indicateur de contexte de navigation de navigation de niveau supérieur en bac à sable défini ci-dessous). Si l'indicateur de contexte de navigation de navigation auxiliaire en bac à sable n'est pas défini, dans certains cas, les restrictions autorisent néanmoins l'ouverture de popups (nouveaux contextes de navigation de niveau supérieur). Ces contextes de navigation ont toujours un navigateur en bac à sable autorisé, défini lors de la création du contexte de navigation, qui permet au contexte de navigation qui les a créés de les parcourir réellement. (Sinon, l'indicateur de contexte de navigation de navigation en bac à sable empêcherait leur navigation même s'ils étaient ouverts. |
| AuxiliaryNavigation | `2` | Cet indicateur empêche le contenu de créer de nouveaux contextes de navigation auxiliaires, par exemple en utilisant l'attribut target ou la méthode window.open(). |
| TopLevelNavigation | `4` | Cet indicateur empêche le contenu de naviguer dans son contexte de navigation de niveau supérieur et empêche le contenu de fermer son contexte de navigation de niveau supérieur. Lorsque l'indicateur de contexte de navigation de navigation de niveau supérieur en bac à sable n'est pas défini, le contenu peut naviguer dans son contexte de navigation de niveau supérieur, mais les autres contextes de navigation sont toujours protégés par l'indicateur de contexte de navigation de navigation en bac à sable et éventuellement l'indicateur de contexte de navigation auxiliaire en bac à sable. |
| Plugins | `8` | Cet indicateur empêche le contenu d'instancier des plugins, que ce soit en utilisant l'élément embed, l'élément object, l'élément applet, ou via la navigation d'un contexte de navigation imbriqué, à moins que ces plugins puissent être sécurisés. |
| Origin | `10` | Cet indicateur force le contenu dans une origine unique, l'empêchant ainsi d'accéder à d'autres contenus de la même origine. |
| Forms | `20` | Ce drapeau bloque la soumission du formulaire. |
| PointerLock | `40` | Cet indicateur désactive l'API Pointer Lock. |
| Scripts | `80` | Cet indicateur bloque l'exécution du script. |
| AutomaticFeatures | `100` | Cet indicateur bloque les fonctionnalités qui se déclenchent automatiquement, telles que la lecture automatique d'une vidéo ou la mise au point automatique d'un contrôle de formulaire. |
| Fullscreen | `200` | Cet indicateur empêche le contenu d'utiliser la méthode requestFullscreen(). |
| DocumentDomain | `400` | Cet indicateur empêche le contenu d'utiliser la fonctionnalité document.domain pour modifier l'origine effective du script. |
| Images | `800` | Ce drapeau désactive le chargement de l'image. |

### Voir également

* espace de noms [Aspose.Svg](../../aspose.svg/)
* Assemblée [Aspose.SVG](../../)


