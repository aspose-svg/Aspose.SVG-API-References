---
title: "Notation-Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Notation-Klasse. Stellt eine in der DTD deklarierte Notation dar"
type: docs
weight: 3150
url: /de/net/aspose.svg.dom/notation/
---
## Notation class

Stellt eine im DTD deklarierte Notation dar.

```csharp
public class Notation : Node
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Gibt die absolute Basis‑URL des Dokuments zurück, das den Knoten enthält. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Gibt eine Live‑[`NodeList`](../../aspose.svg.collections/nodelist/) der Kindknoten des angegebenen Elements zurück, wobei dem ersten Kindknoten der Index 0 zugewiesen wird. Kindknoten umfassen Elemente, Text und Kommentare. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Gibt das erste Kind des Knotens im Baum zurück oder null, wenn der Knoten keine Kinder hat. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Gibt das letzte Kind des Knotens zurück. Wenn dessen übergeordnetes Element ein Element ist, ist das Kind in der Regel ein Elementknoten, ein Textknoten oder ein Kommentar­knoten. Es wird null zurückgegeben, wenn keine Kind‑Elemente vorhanden sind. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten jeglichen Typs außer [`ELEMENT_NODE`](../node/element_node/) und [`ATTRIBUTE_NODE`](../node/attribute_node/) sowie für mit einer DOM Level 1‑Methode erstellte Knoten, wie [`CreateElement`](../document/createelement/), ist dieser immer null. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Gibt die Namespace‑URI des Elements zurück oder null, wenn das Element in keinem Namespace ist. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Gibt den Knoten zurück, der dem angegebenen Knoten im [`ChildNodes`](../node/childnodes/)-Array des Elternknotens unmittelbar folgt, oder null, wenn der angegebene Knoten das letzte Kind im übergeordneten Element ist. |
| override [NodeName](../../aspose.svg.dom/notation/nodename/) { get; } | Der Name dieses Knotens, abhängig von seinem Typ. |
| override [NodeType](../../aspose.svg.dom/notation/nodetype/) { get; } | Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Gibt den Wert des aktuellen Knotens zurück oder setzt ihn. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Gibt das Dokumentobjekt der obersten Ebene des Knotens zurück. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Gibt den Eltern‑[`Element`](../element/)-Knoten des DOM‑Knotens zurück, oder null, wenn der Knoten keinen Elternteil hat oder sein Elternteil kein DOM‑Element ist. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Gibt den Elternknoten des angegebenen Knotens im DOM‑Baum zurück. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Gibt das Namespace‑Präfix des angegebenen Elements zurück oder null, wenn kein Präfix angegeben ist. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Gibt den Knoten zurück, der dem angegebenen Knoten im [`ChildNodes`](../node/childnodes/)‑Verzeichnis seines Elternteils unmittelbar vorausgeht, oder null, wenn der angegebene Knoten der erste in dieser Liste ist. |
| [PublicId](../../aspose.svg.dom/notation/publicid/) { get; } | Der öffentliche Bezeichner dieser Notation. Wenn der öffentliche Bezeichner nicht angegeben wurde, ist er null. |
| [SystemId](../../aspose.svg.dom/notation/systemid/) { get; } | Der Systembezeichner dieser Notation. Wenn der Systembezeichner nicht angegeben wurde, ist er null. Dies kann ein absoluter URI sein oder nicht. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Stellt den Textinhalt des Knotens und seiner Nachkommen dar. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Fügt einen Knoten am Ende der Kindliste eines angegebenen Elternknotens hinzu. Wenn das angegebene Kind eine Referenz zu einem bereits im Dokument vorhandenen Knoten ist, verschiebt [`AppendChild`](../node/appendchild/) ihn von seiner aktuellen Position in die neue Position (es ist nicht erforderlich, den Knoten vor dem Anhängen an einen anderen Knoten aus seinem Elternknoten zu entfernen). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Sein Parameter steuert, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Sendet ein Event an das angegebene [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListeners in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Capture‑ und optionalen Bubbling‑Phase) gelten ebenfalls für manuell mit [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Gibt einen booleschen Wert zurück, der angibt, ob der angegebene [`Node`](../node/) Kindknoten hat oder nicht. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Fügt den Knoten vor dem vorhandenen Kindknoten child ein. Wenn child null ist, wird der Knoten am Ende der Kindliste eingefügt. Wenn child ein DocumentFragment-Objekt ist, werden all seine Kinder in derselben Reihenfolge vor child eingefügt. Wenn das Kind bereits im Baum ist, wird es zuerst entfernt. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Diese Methode prüft, ob das angegebene namespaceURI der Standardsnamensraum ist oder nicht. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Testet, ob zwei Knoten gleich sind. Diese Methode prüft die Gleichheit von Knoten, nicht die Identität (d. h., ob die beiden Knoten Referenzen auf dasselbe Objekt sind), was mit Node.isSameNode() getestet werden kann. Alle Knoten, die identisch sind, sind auch gleich, obwohl das Gegenteil nicht unbedingt zutrifft. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Die Methode ist ein veralteter Alias für den strikten Gleichheitsoperator ===. Das heißt, sie prüft, ob zwei Knoten identisch sind (mit anderen Worten, ob sie auf dasselbe Objekt verweisen). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Sucht die dem angegebenen Präfix zugeordnete Namespace-URI, beginnend bei diesem Knoten. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Sucht das dem angegebenen Namespace-URI zugeordnete Präfix, beginnend bei diesem Knoten. Die Deklarationen des Standardnamensraums werden von dieser Methode ignoriert. Siehe Namespace Prefix Lookup für Details zum von dieser Methode verwendeten Algorithmus. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Setzt alle Textknoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine "normale" Form, bei der nur die Struktur (z. B. Elemente, Kommentare, Verarbeitungsanweisungen, CDATA-Abschnitte und Entity-Referenzen) Textknoten trennt, d. h. es gibt weder benachbarte Textknoten noch leere Textknoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM-Ansicht eines Dokuments dieselbe ist, als wäre sie gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen (wie XPointer [XPointer]-Nachschlagen), die von einer bestimmten Dokumentbaumstruktur abhängen, verwendet werden sollen. Wenn der Parameter "normalize-characters" des DOMConfiguration-Objekts, das an Node.ownerDocument angehängt ist, true ist, normalisiert diese Methode auch vollständig die Zeichen der Textknoten. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach ihrer Entfernung niemals aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach ihrer Entfernung niemals aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach ihrer Entfernung niemals aufgerufen werden. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Ersetzt den Kindknoten oldChild durch newChild in der Kindliste und gibt den alten oldChild‑Knoten zurück. Wenn newChild ein DocumentFragment‑Objekt ist, wird oldChild durch alle Kinder des DocumentFragment ersetzt, die in derselben Reihenfolge eingefügt werden. Wenn newChild bereits im Baum ist, wird es zuerst entfernt. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [Node](../node/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
