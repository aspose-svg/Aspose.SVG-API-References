---
title: Interface IWindow
second_title: Aspose.SVG voor .NET API-referentie
description: Aspose.Svg.Window.IWindow koppel. Het vensterobject stelt een venster voor dat een DOMdocument bevat.
type: docs
weight: 3820
url: /nl/net/aspose.svg.window/iwindow/
---
## IWindow interface

Het vensterobject stelt een venster voor dat een DOM-document bevat.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | Het documentattribuut moet het nieuwste documentobject van het Window-object retourneren. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | Het frameElement-object van een document. |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | Het location attribuut van de Window-interface moet het Location-object retourneren voor het Document van dat Window-object. |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | Het naamattribuut van het Window-object moet bij het ophalen de huidige naam van de browsercontext retourneren en bij het instellen de naam van de browsecontext op de nieuwe waarde instellen. |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | Het opener IDL-attribuut op het Window-object moet bij het ophalen het WindowProxy-object retourneren van de browsecontext van waaruit de huidige browsecontext is gemaakt (de opener browsingcontext), als er een is, als deze nog beschikbaar is en als de huidige browsercontext heeft zijn opener niet verloochend; anders moet het null retourneren. Als bij het instellen de nieuwe waarde null is, moet de huidige browsercontext de opener verloochenen; als de nieuwe waarde iets anders is, moet de user-agent de [[DefineOwnProperty]] interne methode van het Window-object aanroepen, waarbij de eigenschapsnaam "opener" wordt doorgegeven als de eigenschapssleutel, en de eigenschapsbeschrijving { [[Value]]: waarde , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als eigenschapsdescriptor, waarbij waarde de nieuwe waarde is. |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | Het bovenliggende IDL-attribuut op het Window-object van een document in een browsercontext b moet het WindowProxy-object van de bovenliggende browsecontext retourneren, als die er is (dwz als b een onderliggende browsercontext is), of het WindowProxy-object van de browsecontext context b zelf, anders (dwz als het een browsercontext op het hoogste niveau is of een vrijstaande geneste browsecontext). |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | Retourneert het WindowProxy-object van de browsercontext van het Window-object. |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | Het top IDL-attribuut op het Window-object van een document in een browsercontext b moet het WindowProxy-object van zijn browsercontext op het hoogste niveau retourneren (wat zijn eigen WindowProxy-object zou zijn als het zelf een browsecontext op het hoogste niveau was), als het heeft er één of anders zijn eigen WindowProxy-object (bijvoorbeeld als het een losgekoppelde geneste browsecontext was). |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | Retourneert het WindowProxy-object van de browsercontext van het Window-object. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(string) | Geeft een modale waarschuwing weer met het gegeven bericht en wacht tot de gebruiker het verwerpt |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(string) | Toont een modale OK/Annuleren-prompt met het gegeven bericht, wacht tot de gebruiker het negeert en retourneert true als de gebruiker op OK klikt en false als de gebruiker op Annuleren klikt. |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(string, string) | Geeft een modale tekstveldprompt weer met het gegeven bericht, wacht tot de gebruiker het negeert en retourneert de waarde die de gebruiker heeft ingevoerd. Als de gebruiker de prompt annuleert, retourneert hij in plaats daarvan null. Als het tweede argument aanwezig is, wordt de opgegeven waarde als standaard gebruikt. |

### Zie ook

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* naamruimte [Aspose.Svg.Window](../../aspose.svg.window/)
* montage [Aspose.SVG](../../)


