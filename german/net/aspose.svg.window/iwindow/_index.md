---
title: "IWindow‑Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Window.IWindow-Schnittstelle. Das Fensterobjekt stellt ein Fenster dar, das ein DOM-Dokument enthält"
type: docs
weight: 5920
url: /de/net/aspose.svg.window/iwindow/
---
## IWindow interface

Das window‑Objekt stellt ein Fenster dar, das ein DOM‑Dokument enthält.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | Das document-Attribut muss das neueste Document-Objekt des Window-Objekts zurückgeben. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | Das frameElement-Objekt eines Dokuments. |
| [LocalStorage](../../aspose.svg.window/iwindow/localstorage/) { get; } | Gibt ein Storage-Objekt zurück, das es ermöglicht, Schlüssel/Wert-Paare im User-Agent zu speichern. |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | Das location-Attribut der Window-Schnittstelle muss das Location-Objekt für das Document dieses Window-Objekts zurückgeben. |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | Das name-Attribut des Window-Objekts muss beim Auslesen den aktuellen Namen des Browsing‑Kontexts zurückgeben und beim Setzen den Namen des Browsing‑Kontexts auf den neuen Wert setzen. |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | Das opener-IDL-Attribut des Window-Objekts muss beim Auslesen das WindowProxy-Objekt des Browsing‑Kontexts zurückgeben, aus dem der aktuelle Browsing‑Kontext erstellt wurde (sein opener‑Browsing‑Kontext), falls ein solcher existiert, noch verfügbar ist und der aktuelle Browsing‑Kontext seinen opener nicht aufgegeben hat; andernfalls muss es null zurückgeben. Beim Setzen, wenn der neue Wert null ist, muss der aktuelle Browsing‑Kontext seinen opener aufgeben; ist der neue Wert ein anderer Wert, muss der User‑Agent die interne Methode [[DefineOwnProperty]] des Window-Objekts aufrufen, wobei der Property‑Name "opener" als Schlüssel übergeben wird und der Property‑Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als Descriptor verwendet wird, wobei value der neue Wert ist. |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | Das parent-IDL-Attribut des Window-Objekts eines Dokuments in einem Browsing‑Kontext b muss das WindowProxy-Objekt des übergeordneten Browsing‑Kontexts zurückgeben, falls ein solcher existiert (d. h. wenn b ein Kind‑Browsing‑Kontext ist), andernfalls das WindowProxy-Objekt des Browsing‑Kontexts b selbst (d. h. wenn es ein Top‑Level‑Browsing‑Kontext oder ein losgelöster verschachtelter Browsing‑Kontext ist). |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | Gibt das WindowProxy-Objekt des Browsing‑Kontexts des Window-Objekts zurück. |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | Das top-IDL-Attribut des Window-Objekts eines Dokuments in einem Browsing‑Kontext b muss das WindowProxy-Objekt seines Top‑Level‑Browsing‑Kontexts zurückgeben (was sein eigenes WindowProxy-Objekt wäre, wenn es selbst ein Top‑Level‑Browsing‑Kontext wäre), falls ein solches existiert, sonst sein eigenes WindowProxy-Objekt (z. B. wenn es ein losgelöster verschachtelter Browsing‑Kontext war). |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | Gibt das WindowProxy-Objekt des Browsing‑Kontexts des Window-Objekts zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(*string*) | Zeigt einen modalen Alarm mit der angegebenen Meldung an und wartet, bis der Benutzer ihn schließt. |
| [Atob](../../aspose.svg.window/iwindow/atob/)(*string*) | Nimmt die Eingabedaten in Form eines Unicode‑Strings, der base64‑kodierte Binärdaten enthält, dekodiert sie und gibt einen String zurück, der aus Zeichen im Bereich U+0000 bis U+00FF besteht, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF darstellt, entsprechend den Binärdaten. |
| [Btoa](../../aspose.svg.window/iwindow/btoa/)(*string*) | Nimmt die Eingabedaten in Form eines Unicode‑Strings, der nur Zeichen im Bereich U+0000 bis U+00FF enthält, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF darstellt, und wandelt ihn in seine base64‑Darstellung um, die zurückgegeben wird. |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(*string*) | Zeigt eine modale OK/Cancel‑Eingabeaufforderung mit der angegebenen Meldung an, wartet, bis der Benutzer sie schließt, und gibt true zurück, wenn der Benutzer OK klickt, und false, wenn er Abbrechen klickt. |
| [MatchMedia](../../aspose.svg.window/iwindow/matchmedia/)(*string*) | Gibt ein neues MediaQueryList-Objekt zurück, das dann verwendet werden kann, um zu bestimmen, ob das Dokument dem Media‑Query‑String entspricht, sowie um das Dokument zu überwachen, um zu erkennen, wann es dem Media‑Query entspricht (oder nicht mehr entspricht). Siehe CSSOM View Module‑Spezifikation: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(*string, string*) | Zeigt eine modale Texteingabeaufforderung mit der angegebenen Meldung an, wartet, bis der Benutzer sie schließt, und gibt den vom Benutzer eingegebenen Wert zurück. Wenn der Benutzer die Eingabe abbricht, wird stattdessen null zurückgegeben. Wenn das zweite Argument vorhanden ist, wird der angegebene Wert als Standard verwendet. |

### Siehe auch

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
