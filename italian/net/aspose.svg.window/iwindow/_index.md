---
title: Interface IWindow
second_title: Riferimento API Aspose.SVG per .NET
description: Aspose.Svg.Window.IWindow interfaccia. Loggetto finestra rappresenta una finestra contenente un documento DOM.
type: docs
weight: 3820
url: /it/net/aspose.svg.window/iwindow/
---
## IWindow interface

L'oggetto finestra rappresenta una finestra contenente un documento DOM.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | L'attributo document deve restituire l'oggetto Document più recente dell'oggetto Window. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | L'oggetto frameElement di un documento. |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | L'attributo location dell'interfaccia Window deve restituire l'oggetto Location per il documento dell'oggetto Window. |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | L'attributo name dell'oggetto Window deve, in fase di acquisizione, restituire il nome corrente del contesto di navigazione e, in fase di impostazione, impostare il nome del contesto di navigazione al nuovo valore. |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | L'attributo opener IDL sull'oggetto Window, al momento dell'ottenimento, deve restituire l'oggetto WindowProxy del contesto di navigazione da cui è stato creato il contesto di navigazione corrente (il suo contesto di navigazione opener), se presente, se è ancora disponibile e se l'attuale contesto di navigazione non ha rinnegato il suo apri; in caso contrario, deve restituire null. All'impostazione, se il nuovo valore è nullo, il contesto di navigazione corrente deve rinnegare il suo apri; se il nuovo valore è qualcos'altro, l'agente utente deve chiamare il metodo interno [[DefineOwnProperty]] dell'oggetto Window, passando il nome della proprietà "opener" come chiave della proprietà e il descrittore della proprietà { [[Value]]: valore , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } come descrittore della proprietà, dove value è il nuovo valore. |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | L'attributo parent IDL sull'oggetto Window di un Document in un contesto di navigazione b deve restituire l'oggetto WindowProxy del contesto di navigazione genitore, se presente (cioè se b è un contesto di navigazione figlio), oppure l'oggetto WindowProxy del contesto di navigazione contesto b stesso, altrimenti (ad esempio se si tratta di un contesto di navigazione di primo livello o di un contesto di navigazione annidato distaccato). |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | Restituisce l'oggetto WindowProxy del contesto di navigazione dell'oggetto Window. |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | L'attributo IDL superiore sull'oggetto Window di un documento in un contesto di navigazione b deve restituire l'oggetto WindowProxy del suo contesto di navigazione di primo livello (che sarebbe il proprio oggetto WindowProxy se fosse esso stesso un contesto di navigazione di primo livello), se ne ha uno o altrimenti il suo oggetto WindowProxy (ad esempio se si trattava di un contesto di navigazione annidato distaccato). |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | Restituisce l'oggetto WindowProxy del contesto di navigazione dell'oggetto Window. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(string) | Visualizza un avviso modale con il messaggio specificato e attende che l'utente lo elimini |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(string) | Visualizza un prompt OK/Annulla modale con il messaggio specificato, attende che l'utente lo ignori e restituisce true se l'utente fa clic su OK e false se l'utente fa clic su Annulla. |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(string, string) | Visualizza un prompt del campo di testo modale con il messaggio specificato, attende che l'utente lo elimini e restituisce il valore immesso dall'utente. Se l'utente annulla il prompt, restituisce invece null. Se è presente il secondo argomento, il valore specificato viene utilizzato come valore predefinito. |

### Guarda anche

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* spazio dei nomi [Aspose.Svg.Window](../../aspose.svg.window/)
* assemblea [Aspose.SVG](../../)


