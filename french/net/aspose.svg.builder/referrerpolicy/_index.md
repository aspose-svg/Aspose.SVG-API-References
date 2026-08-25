---
title: "Énumération ReferrerPolicy"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Aspose.Svg.Builder.ReferrerPolicy enum. Spécifie la politique de référent à utiliser lors de la récupération des ressources"
type: docs
weight: 1020
url: /fr/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

Spécifie la politique de référent à utiliser lors de la récupération des ressources.

```csharp
public enum ReferrerPolicy
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Aucune politique de référent n'est définie. |
| NoReferrer | `1` | L'en-tête Referer ne sera pas envoyé. |
| NoReferrerWhenDowngrade | `2` | L'en-tête Referer ne sera pas envoyé aux origines avec moins de sécurité (HTTPS -&gt; HTTP). |
| SameOrigin | `3` | L'en-tête Referer sera envoyé uniquement pour les requêtes de même origine. |
| Origin | `4` | Seule l'origine du document sera envoyée comme en-tête Referer. |
| StrictOrigin | `5` | Seule l'origine du document sera envoyée comme en-tête Referer pour les contextes sécurisés. |
| OriginWhenCrossOrigin | `6` | L'URL complète sera envoyée comme en-tête Referer pour les requêtes de même origine, mais seule l'origine pour les requêtes cross-origin. |
| StrictOriginWhenCrossOrigin | `7` | Seule l'origine du document sera envoyée comme en-tête Referer pour les requêtes de même origine, mais aucun en-tête pour les requêtes cross-origin dans les contextes non sécurisés. |
| UnsafeUrl | `8` | L'URL complète, incluant le chemin et la chaîne de requête, sera toujours envoyée comme en-tête Referer. |

### Voir aussi

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
