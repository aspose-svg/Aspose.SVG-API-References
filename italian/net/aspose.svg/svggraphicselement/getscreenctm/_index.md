---
title: SVGGraphicsElement.GetScreenCTM
second_title: Riferimento API Aspose.SVG per .NET
description: SVGGraphicsElement metodo. Restituisce la matrice di trasformazione dalle unità dellutente corrente cioè dopo lapplicazione dellattributo transform se presente allavviso dellagente utente genitore di un pixel. Per i dispositivi di visualizzazione idealmente questo rappresenta un pixel dello schermo fisico. Per altri dispositivi o ambienti in cui le dimensioni fisiche dei pixel non sono note è possibile utilizzare invece un algoritmo simile alla definizione CSS2 di pixel. Si noti che viene restituito null se questo elemento non è collegato allalbero del documento. Questo metodo sarebbe stato chiamato più appropriatamente come getClientCTM ma il nome getScreenCTM viene mantenuto per motivi storici.
type: docs
weight: 90
url: /it/net/aspose.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Restituisce la matrice di trasformazione dalle unità dell'utente corrente (cioè, dopo l'applicazione dell'attributo 'transform', se presente) all'avviso dell'agente utente genitore di un "pixel". Per i dispositivi di visualizzazione, idealmente questo rappresenta un pixel dello schermo fisico. Per altri dispositivi o ambienti in cui le dimensioni fisiche dei pixel non sono note, è possibile utilizzare invece un algoritmo simile alla definizione CSS2 di "pixel". Si noti che viene restituito null se questo elemento non è collegato all'albero del documento. Questo metodo sarebbe stato chiamato più appropriatamente come getClientCTM, ma il nome getScreenCTM viene mantenuto per motivi storici.

```csharp
public SVGMatrix GetScreenCTM()
```

### Valore di ritorno

Un oggetto SVGMatrix che definisce la matrice di trasformazione data.

### Guarda anche

* class [SVGMatrix](../../../aspose.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* spazio dei nomi [Aspose.Svg](../../svggraphicselement/)
* assemblea [Aspose.SVG](../../../)


