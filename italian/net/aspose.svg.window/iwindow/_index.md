---
title: IWindow
second_title: Riferimento API Aspose.SVG per .NET
description: Loggetto window rappresenta una finestra contenente un documento DOM.
type: docs
weight: 3740
url: /it/net/aspose.svg.window/iwindow/
---
## IWindow interface

L'oggetto window rappresenta una finestra contenente un documento DOM.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document) { get; } | L'attributo document deve restituire l'oggetto Document più recente dell'oggetto Window. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement) { get; } | L'oggetto frameElement di un documento. |
| [Location](../../aspose.svg.window/iwindow/location) { get; } | L'attributo location dell'interfaccia Window deve restituire l'oggetto Location per il documento di quell'oggetto Window. |
| [Name](../../aspose.svg.window/iwindow/name) { get; set; } | L'attributo name dell'oggetto Window deve, all'ottenimento, restituire il nome corrente del contesto di navigazione e, al momento dell'impostazione, impostare il nome del contesto di navigazione sul nuovo valore. |
| [Opener](../../aspose.svg.window/iwindow/opener) { get; } | L'attributo IDL di apertura sull'oggetto Window, al momento della ricezione, deve restituire l'oggetto WindowProxy del contesto di navigazione da cui è stato creato il contesto di navigazione corrente (il suo contesto di navigazione di apertura), se presente, se è ancora disponibile e se l'attuale contesto di navigazione non ha rinnegato il suo apri; in caso contrario, deve restituire null. Al momento dell'impostazione, se il nuovo valore è nullo, il contesto di navigazione corrente deve negare il suo apri; se il nuovo valore è qualcos'altro, lo user agent deve chiamare il metodo interno [[DefineOwnProperty]] dell'oggetto Window, passando il nome della proprietà "opener" come chiave della proprietà, e il Property Descriptor { [[Value]]: value , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } come descrittore di proprietà, dove value è il nuovo valore. |
| [Parent](../../aspose.svg.window/iwindow/parent) { get; } | L'attributo IDL padre sull'oggetto Window di un Documento in un contesto di navigazione b deve restituire l'oggetto WindowProxy del contesto di navigazione padre, se presente (ad esempio se b è un contesto di navigazione figlio), oppure l'oggetto WindowProxy della navigazione contesto b stesso, altrimenti (ad esempio se si tratta di un contesto di navigazione di primo livello o di un contesto di navigazione nidificato distaccato). |
| [Self](../../aspose.svg.window/iwindow/self) { get; } | Restituisce l'oggetto WindowProxy del contesto di navigazione dell'oggetto Window. |
| [Top](../../aspose.svg.window/iwindow/top) { get; } | L'attributo IDL superiore sull'oggetto Window di un Documento in un contesto di navigazione b deve restituire l'oggetto WindowProxy del suo contesto di navigazione di primo livello (che sarebbe il proprio oggetto WindowProxy se fosse esso stesso un contesto di navigazione di primo livello), se ne ha uno, o il proprio oggetto WindowProxy in caso contrario (ad esempio se fosse un contesto di navigazione nidificato distaccato). |
| [Window](../../aspose.svg.window/iwindow/window) { get; } | Restituisce l'oggetto WindowProxy del contesto di navigazione dell'oggetto Window. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert)(string) | Visualizza un avviso modale con il messaggio specificato e attende che l'utente lo concluda |
| [Confirm](../../aspose.svg.window/iwindow/confirm)(string) | Visualizza un prompt modale OK/Annulla con il messaggio specificato, attende che l'utente lo concluda e restituisce true se l'utente fa clic su OK e false se l'utente fa clic su Annulla. |
| [Prompt](../../aspose.svg.window/iwindow/prompt)(string, string) | Visualizza un prompt di campo di testo modale con il messaggio specificato, attende che l'utente lo concluda e restituisce il valore immesso dall'utente. Se l'utente annulla il prompt, restituisce invece null. Se è presente il secondo argomento, il valore specificato viene utilizzato come predefinito. |

### Guarda anche

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers)
* interface [IWindowEventHandlers](../iwindoweventhandlers)
* interface [IWindowTimers](../iwindowtimers)
* spazio dei nomi [Aspose.Svg.Window](../../aspose.svg.window)
* assemblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->