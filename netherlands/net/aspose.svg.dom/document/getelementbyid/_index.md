---
title: "Document.GetElementById"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Document GetElementById methode. Deze methode retourneert een Element‑object dat het element vertegenwoordigt waarvan de id‑eigenschap overeenkomt met de opgegeven tekenreeks. Aangezien element‑ID's, indien gespecificeerd, uniek moeten zijn, zijn ze een handige manier om snel toegang te krijgen tot een specifiek element."
type: docs
weight: 960
url: /nl/net/aspose.svg.dom/document/getelementbyid/
---
## Document.GetElementById method

Deze methode retourneert een [`Element`](../../element/) object dat het element vertegenwoordigt waarvan de id‑eigenschap overeenkomt met de opgegeven tekenreeks. Aangezien element‑ID's, indien gespecificeerd, uniek moeten zijn, zijn ze een handige manier om snel toegang te krijgen tot een specifiek element.

Als je toegang moet krijgen tot een element dat geen ID heeft, kun je [`QuerySelector`](../queryselector/) gebruiken om het element te vinden met behulp van een willekeurige selector.

```csharp
public Element GetElementById(string elementId)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| elementId | String | De ID van het te vinden element. De ID is een hoofdlettergevoelige tekenreeks die uniek is binnen het document; slechts één element mag een bepaalde ID hebben. |

### Retourwaarde

Een [`Element`](../../element/) object dat het DOM‑element beschrijft dat overeenkomt met de opgegeven ID, of null als er geen overeenkomend element in het document werd gevonden.

## Opmerkingen

Zie de officiële [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid).

### Zie ook

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
