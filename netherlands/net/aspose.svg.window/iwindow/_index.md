---
title: "IWindow-interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Window.IWindow-interface. Het window-object vertegenwoordigt een venster dat een DOM-document bevat"
type: docs
weight: 5920
url: /nl/net/aspose.svg.window/iwindow/
---
## IWindow interface

Het window-object vertegenwoordigt een venster dat een DOM-document bevat.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | Het documentattribuut moet het nieuwste Document-object van het Window-object teruggeven. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | Het frameElement-object van een Document. |
| [LocalStorage](../../aspose.svg.window/iwindow/localstorage/) { get; } | Geeft een Storage-object terug dat u in staat stelt sleutel/waarde-paren op te slaan in de user agent. |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | Het location-attribuut van de Window-interface moet het Location-object voor het Document van dat Window-object teruggeven. |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | Het name-attribuut van het Window-object moet bij het opvragen de huidige naam van de browsing context teruggeven, en bij het instellen de naam van de browsing context op de nieuwe waarde zetten. |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | Het opener IDL-attribuut op het Window-object moet bij het opvragen het WindowProxy-object van de browsing context waaruit de huidige browsing context is gemaakt (de opener‑browsing‑context), als die bestaat, nog beschikbaar is en de huidige browsing context zijn opener niet heeft afgewezen; anders moet het null teruggeven. Bij het instellen, als de nieuwe waarde null is, moet de huidige browsing context zijn opener afwijzen; als de nieuwe waarde iets anders is, moet de user agent de interne methode [[DefineOwnProperty]] van het Window-object aanroepen, waarbij de eigenschapsnaam "opener" als sleutel wordt doorgegeven, en de Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als eigenschapsdescriptor, waarbij value de nieuwe waarde is. |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | Het parent IDL-attribuut op het Window-object van een Document in een browsing context b moet het WindowProxy-object van de bovenliggende browsing context teruggeven, als die bestaat (d.w.z. als b een child‑browsing‑context is), of anders het WindowProxy-object van de browsing context b zelf (d.w.z. als het een top‑level browsing context of een losgekoppelde geneste browsing context is). |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | Geeft het WindowProxy-object van de browsing context van het Window-object terug. |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | Het top IDL-attribuut op het Window-object van een Document in een browsing context b moet het WindowProxy-object van zijn top‑level browsing context teruggeven (wat zijn eigen WindowProxy-object zou zijn als het zelf een top‑level browsing context was), als die er één heeft, of anders zijn eigen WindowProxy-object (bijv. als het een losgekoppelde geneste browsing context was). |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | Geeft het WindowProxy-object van de browsing context van het Window-object terug. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(*string*) | Toont een modale waarschuwing met het opgegeven bericht en wacht tot de gebruiker deze sluit. |
| [Atob](../../aspose.svg.window/iwindow/atob/)(*string*) | Neemt de invoergegevens in de vorm van een Unicode‑string die base64‑gecodeerde binaire data bevat, decodeert deze en geeft een string terug die bestaat uit tekens in het bereik U+0000 tot U+00FF, elk een binair byte met waarden 0x00 tot 0xFF weergevend, overeenkomstig die binaire data. |
| [Btoa](../../aspose.svg.window/iwindow/btoa/)(*string*) | Neemt de invoergegevens, in de vorm van een Unicode‑string die alleen tekens bevat in het bereik U+0000 tot U+00FF, elk een binair byte met waarden 0x00 tot 0xFF respectievelijk, en zet deze om naar de base64‑representatie, die wordt geretourneerd. |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(*string*) | Toont een modale OK/Annuleren‑prompt met het opgegeven bericht, wacht tot de gebruiker deze sluit, en retourneert true als de gebruiker op OK klikt en false als de gebruiker op Annuleren klikt. |
| [MatchMedia](../../aspose.svg.window/iwindow/matchmedia/)(*string*) | Retourneert een nieuw MediaQueryList‑object dat vervolgens kan worden gebruikt om te bepalen of het document overeenkomt met de media‑query‑string, en om het document te monitoren om te detecteren wanneer het overeenkomt (of stopt met overeenkomen) met die media‑query. Zie de CSSOM View Module‑specificatie: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(*string, string*) | Toont een modale tekstveld‑prompt met het opgegeven bericht, wacht tot de gebruiker deze sluit, en retourneert de waarde die de gebruiker heeft ingevoerd. Als de gebruiker de prompt annuleert, wordt null geretourneerd. Als het tweede argument aanwezig is, wordt de opgegeven waarde als standaard gebruikt. |

### Zie ook

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
