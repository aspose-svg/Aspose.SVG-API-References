---
title: "IWindow.Atob"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Méthode IWindow Atob. Prend les données d'entrée sous la forme d'une chaîne Unicode contenant des données binaires encodées en base64, les décode et renvoie une chaîne composée de caractères dans la plage U0000 à U00FF, chaque caractère représentant un octet binaire avec des valeurs 0x00 à 0xFF correspondant respectivement à ces données binaires."
type: docs
weight: 120
url: /fr/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

Prend les données d'entrée, sous la forme d'une chaîne Unicode contenant des données binaires encodées en base64, les décode et renvoie une chaîne composée de caractères dans la plage U+0000 à U+00FF, chaque caractère représentant un octet binaire avec des valeurs 0x00 à 0xFF respectivement, correspondant à ces données binaires.

```csharp
public string Atob(string data)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| données | String | La chaîne Unicode contenant des données binaires encodées en base64 |

### Valeur de retour

La chaîne composée de caractères dans la plage U+0000 à U+00FF

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Lève une exception DOMException "InvalidCharacterError" si la chaîne d'entrée n'est pas des données base64 valides. |

### Voir aussi

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
