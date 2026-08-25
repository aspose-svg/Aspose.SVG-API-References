---
title: "IWindow.Btoa"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode IWindow Btoa. Prend les données d'entrée sous la forme d'une chaîne Unicode contenant uniquement des caractères dans la plage U0000 à U00FF, chaque caractère représentant un octet binaire avec des valeurs de 0x00 à 0xFF respectivement, et la convertit en sa représentation base64 qu'elle renvoie."
type: docs
weight: 130
url: /fr/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

Prend les données d'entrée, sous la forme d'une chaîne Unicode contenant uniquement des caractères dans la plage U+0000 à U+00FF, chaque caractère représentant un octet binaire avec des valeurs de 0x00 à 0xFF respectivement, et la convertit en sa représentation base64, qu'elle renvoie.

```csharp
public string Btoa(string data)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| données | String | La chaîne Unicode contenant uniquement des caractères dans la plage U+0000 à U+00FF. |

### Valeur de retour

La chaîne base64.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Lève une exception DOMException "InvalidCharacterError" si la chaîne d'entrée contient des caractères hors limites. |

### Voir aussi

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
