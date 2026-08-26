---
title: "SVGElementInstance Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.SVGElementInstance Klasse. Das Wurzelobjekt jedes use-Element-Shadow-Baums implementiert das SVGUseElementShadowRoot-Interface. Dieses Interface definiert derzeit keine Erweiterungen der für das ShadowRoot-Interface und das DocumentOrShadowRoot-Mixin definierten Eigenschaften und Methoden. Der Baum, der an diesem Knoten wurzelt, ist jedoch aus Sicht von Autorenskripten vollständig schreibgeschützt."
type: docs
weight: 5280
url: /de/net/aspose.svg/svgelementinstance/
---
## SVGElementInstance class

Das Wurzelobjekt jedes use‑Element‑Shadow‑Baums implementiert die SVGUseElementShadowRoot‑Schnittstelle. Diese Schnittstelle definiert derzeit keine Erweiterungen zu den für die ShadowRoot‑Schnittstelle und das DocumentOrShadowRoot‑Mixin definierten Eigenschaften und Methoden. Der Baum, der an diesem Knoten wurzelt, ist jedoch aus Sicht von Autor‑Skripten vollständig schreibgeschützt.

```csharp
public class SVGElementInstance : ShadowRoot
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Gibt die absolute Basis‑URL des Dokuments zurück, das den Knoten enthält. |
| [ChildElementCount](../../aspose.svg.dom/documentfragment/childelementcount/) { get; } | Gibt die aktuelle Anzahl von Elementknoten zurück, die Kindknoten dieses Elements sind. 0, wenn dieses Element keine Kindknoten vom Knotentyp 1 hat. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Gibt eine Live‑[`NodeList`](../../aspose.svg.collections/nodelist/) der Kindknoten des angegebenen Elements zurück, wobei dem ersten Kindknoten der Index 0 zugewiesen wird. Kindknoten umfassen Elemente, Text und Kommentare. |
| [Children](../../aspose.svg.dom/documentfragment/children/) { get; } | Gibt die Kind-Elemente des aktuellen Elements zurück. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Gibt das erste Kind des Knotens im Baum zurück oder null, wenn der Knoten keine Kinder hat. |
| [FirstElementChild](../../aspose.svg.dom/documentfragment/firstelementchild/) { get; } | Gibt den ersten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kindelemente hat. |
| [Host](../../aspose.svg.dom/shadowroot/host/) { get; } | Host ist ein Element, das dieses ShadowRoot enthält. |
| [InnerHTML](../../aspose.svg.dom/documentfragment/innerhtml/) { get; set; } | Gibt ein Fragment von HTML oder XML zurück, das den Inhalt des Elements darstellt. Kann gesetzt werden, um den Inhalt des Elements durch Knoten zu ersetzen, die aus dem angegebenen String geparst wurden. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Gibt das letzte Kind des Knotens zurück. Wenn dessen übergeordnetes Element ein Element ist, ist das Kind in der Regel ein Elementknoten, ein Textknoten oder ein Kommentar­knoten. Es wird null zurückgegeben, wenn keine Kind‑Elemente vorhanden sind. |
| [LastElementChild](../../aspose.svg.dom/documentfragment/lastelementchild/) { get; } | Gibt den letzten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kindelemente hat. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten jeglichen Typs, die nicht [`ELEMENT_NODE`](../../aspose.svg.dom/node/element_node/) oder [`ATTRIBUTE_NODE`](../../aspose.svg.dom/node/attribute_node/) sind und für mit einer DOM‑Level‑1‑Methode erstellte Knoten, wie [`CreateElement`](../../aspose.svg.dom/document/createelement/), ist dies immer null. |
| [Mode](../../aspose.svg.dom/shadowroot/mode/) { get; } | Modus, in dem dieses ShadowRoot arbeitet. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Gibt die Namespace‑URI des Elements zurück oder null, wenn das Element in keinem Namespace ist. |
| [NextElementSibling](../../aspose.svg.dom/documentfragment/nextelementsibling/) { get; } | Gibt den nächsten Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine nachfolgenden Element‑Geschwisterknoten im Dokumentbaum hat. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Gibt den Knoten zurück, der dem angegebenen Knoten im [`ChildNodes`](../../aspose.svg.dom/node/childnodes/)-Array des Elternteils unmittelbar folgt, oder gibt null zurück, wenn der angegebene Knoten das letzte Kind im Elternelement ist. |
| override [NodeName](../../aspose.svg.dom/documentfragment/nodename/) { get; } | Der Name dieses Knotens, abhängig von seinem Typ. |
| override [NodeType](../../aspose.svg.dom/documentfragment/nodetype/) { get; } | Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Gibt den Wert des aktuellen Knotens zurück oder setzt ihn. |
| [OuterHTML](../../aspose.svg.dom/documentfragment/outerhtml/) { get; set; } | Gibt ein Fragment von HTML oder XML zurück, das das Element und seinen Inhalt darstellt. Kann gesetzt werden, um das Element durch Knoten zu ersetzen, die aus dem angegebenen String geparst wurden. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Gibt das Dokumentobjekt der obersten Ebene des Knotens zurück. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Gibt das übergeordnete [`Element`](../../aspose.svg.dom/element/) des DOM‑Knotens zurück, oder null, wenn der Knoten keinen Elternknoten hat oder sein Elternknoten kein DOM‑Element ist. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Gibt den Elternknoten des angegebenen Knotens im DOM‑Baum zurück. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Gibt das Namespace‑Präfix des angegebenen Elements zurück oder null, wenn kein Präfix angegeben ist. |
| [PreviousElementSibling](../../aspose.svg.dom/documentfragment/previouselementsibling/) { get; } | Gibt den vorherigen Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine vorherigen Element‑Geschwisterknoten im Dokumentbaum hat. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Gibt den Knoten zurück, der dem angegebenen Knoten in der [`ChildNodes`](../../aspose.svg.dom/node/childnodes/)-Liste des Elternteils unmittelbar vorausgeht, oder null, wenn der angegebene Knoten der erste in dieser Liste ist. |
| override [TextContent](../../aspose.svg.dom/documentfragment/textcontent/) { get; set; } | Dieses Attribut gibt den Textinhalt dieses Knotens und seiner Nachkommen zurück. Wenn es als null definiert ist, hat das Setzen keine Auswirkung. Beim Setzen werden alle möglichen Kindknoten dieses Knotens entfernt und, wenn die neue Zeichenkette nicht leer oder null ist, durch einen einzelnen Textknoten ersetzt, der die Zeichenkette enthält, auf die dieses Attribut gesetzt wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../../aspose.svg.dom/node/)*) | Fügt einem angegebenen Elternknoten am Ende der Kindliste einen Knoten hinzu. Wenn das angegebene Kind eine Referenz auf einen bereits im Dokument vorhandenen Knoten darstellt, verschiebt [`AppendChild`](../../aspose.svg.dom/node/appendchild/) ihn von seiner aktuellen Position an die neue Position (es ist nicht erforderlich, den Knoten vor dem Anhängen an einen anderen Knoten aus seinem Elternknoten zu entfernen). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Sein Parameter steuert, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Sendet ein Event an das angegebene [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListeners in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Capture‑ und optionalen Bubbling‑Phase) gelten ebenfalls für manuell mit [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Gibt einen booleschen Wert zurück, der angibt, ob der gegebene [`Node`](../../aspose.svg.dom/node/) Kindknoten hat oder nicht. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | Fügt den Knoten vor dem vorhandenen Kindknoten child ein. Wenn child null ist, wird der Knoten am Ende der Kindliste eingefügt. Wenn child ein DocumentFragment-Objekt ist, werden all seine Kinder in derselben Reihenfolge vor child eingefügt. Wenn das Kind bereits im Baum ist, wird es zuerst entfernt. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Diese Methode prüft, ob das angegebene namespaceURI der Standardsnamensraum ist oder nicht. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../../aspose.svg.dom/node/)*) | Testet, ob zwei Knoten gleich sind. Diese Methode prüft die Gleichheit von Knoten, nicht die Identität (d. h., ob die beiden Knoten Referenzen auf dasselbe Objekt sind), was mit Node.isSameNode() getestet werden kann. Alle Knoten, die identisch sind, sind auch gleich, obwohl das Gegenteil nicht unbedingt zutrifft. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../../aspose.svg.dom/node/)*) | Die Methode ist ein veralteter Alias für den strikten Gleichheitsoperator ===. Das heißt, sie prüft, ob zwei Knoten identisch sind (mit anderen Worten, ob sie auf dasselbe Objekt verweisen). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Sucht die dem angegebenen Präfix zugeordnete Namespace-URI, beginnend bei diesem Knoten. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Sucht das dem angegebenen Namespace-URI zugeordnete Präfix, beginnend bei diesem Knoten. Die Deklarationen des Standardnamensraums werden von dieser Methode ignoriert. Siehe Namespace Prefix Lookup für Details zum von dieser Methode verwendeten Algorithmus. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Setzt alle Textknoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine "normale" Form, bei der nur die Struktur (z. B. Elemente, Kommentare, Verarbeitungsanweisungen, CDATA-Abschnitte und Entity-Referenzen) Textknoten trennt, d. h. es gibt weder benachbarte Textknoten noch leere Textknoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM-Ansicht eines Dokuments dieselbe ist, als wäre sie gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen (wie XPointer [XPointer]-Nachschlagen), die von einer bestimmten Dokumentbaumstruktur abhängen, verwendet werden sollen. Wenn der Parameter "normalize-characters" des DOMConfiguration-Objekts, das an Node.ownerDocument angehängt ist, true ist, normalisiert diese Methode auch vollständig die Zeichen der Textknoten. |
| [QuerySelector](../../aspose.svg.dom/documentfragment/queryselector/)(*string*) | Gibt das erste Element im Dokument zurück, das dem Selektor entspricht |
| [QuerySelectorAll](../../aspose.svg.dom/documentfragment/queryselectorall/)(*string*) | Gibt eine NodeList aller Elemente im Dokument zurück, die dem Selektor entsprechen |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../../aspose.svg.dom/node/)*) | Entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | Ersetzt den Kindknoten oldChild durch newChild in der Kindliste und gibt den alten oldChild‑Knoten zurück. Wenn newChild ein DocumentFragment‑Objekt ist, wird oldChild durch alle Kinder des DocumentFragment ersetzt, die in derselben Reihenfolge eingefügt werden. Wenn newChild bereits im Baum ist, wird es zuerst entfernt. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [ShadowRoot](../../aspose.svg.dom/shadowroot/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
