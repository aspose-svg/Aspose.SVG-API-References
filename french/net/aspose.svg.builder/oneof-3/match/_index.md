---
title: "OneOf-3.Match"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode Match de OneOf. Exécute l'une des fonctions fournies en fonction du type sous-jacent de la valeur."
type: docs
weight: 20
url: /fr/net/aspose.svg.builder/oneof-3/match/
---
## OneOf<T1,T2,T3>.Match<TResult> method

Exécute l'une des fonctions fournies en fonction du type sous-jacent de la valeur.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2, 
    Func<T3, TResult> func3)
```

| Paramètre | Description |
| --- | --- |
| TResult | Le type de retour des fonctions. |
| func1 | La fonction à exécuter si la valeur est de type T1. |
| func2 | La fonction à exécuter si la valeur est de type T2. |
| func3 | La fonction à exécuter si la valeur est de type T3. |

### Valeur de retour

Le résultat de la fonction exécutée.

### Voir aussi

* class [OneOf&lt;T1,T2,T3&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
