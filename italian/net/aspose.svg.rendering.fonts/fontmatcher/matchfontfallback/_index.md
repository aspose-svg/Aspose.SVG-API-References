---
title: MatchFontFallback
second_title: Riferimento API Aspose.SVG per .NET
description: Questo metodo viene chiamato se non è stato trovato alcun carattere appropriato nelle cartelle di ricerca dei caratteri. Dovrebbe restituire un carattere di tipo vero in base alfontMatchingProperties che può renderecharCode  onullo se tale carattere non è disponibile.
type: docs
weight: 10
url: /it/net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Questo metodo viene chiamato se non è stato trovato alcun carattere appropriato nelle cartelle di ricerca dei caratteri. Dovrebbe restituire un carattere di tipo vero in base al*fontMatchingProperties* che può rendere*charCode* , o`nullo` se tale carattere non è disponibile.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Proprietà del carattere abbinato. |
| charCode | UInt32 | Codice del carattere che verrà reso utilizzando il font abbinato. |

### Valore di ritorno

Una matrice di byte contenente i dati dei caratteri o`nullo`.

### Guarda anche

* class [FontMatchingProperties](../../fontmatchingproperties)
* class [FontMatcher](../../fontmatcher)
* spazio dei nomi [Aspose.Svg.Rendering.Fonts](../../fontmatcher)
* assemblea [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->