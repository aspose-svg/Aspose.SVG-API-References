---
title: "Dokumentklasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Document-Klasse. Das Dokument stellt das gesamte HTML-, XML- oder SVG-Dokument dar. Konzeptuell ist es die Wurzel des Dokumentbaums und bietet den primären Zugriff auf die Daten des Dokuments."
type: docs
weight: 2810
url: /de/net/aspose.svg.dom/document/
---
## Document class

Das Document repräsentiert das gesamte HTML-, XML- oder SVG-Dokument. Konzeptionell ist es die Wurzel des Dokumentbaums und bietet den primären Zugriff auf die Daten des Dokuments.

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [BaseURI](../../aspose.svg.dom/document/baseuri/) { get; } | Der absolute Basis-URI dieses Knotens oder null, wenn die Implementierung keinen absoluten URI ermitteln konnte. |
| [CharacterSet](../../aspose.svg.dom/document/characterset/) { get; } | Liest die Kodierung des Dokuments. |
| [Charset](../../aspose.svg.dom/document/charset/) { get; } | Liest die Kodierung des Dokuments. |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount/) { get; } | Gibt die aktuelle Anzahl von Elementknoten zurück, die Kindknoten dieses Elements sind. 0, wenn dieses Element keine Kindknoten vom Knotentyp 1 hat. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Gibt eine Live‑[`NodeList`](../../aspose.svg.collections/nodelist/) der Kindknoten des angegebenen Elements zurück, wobei dem ersten Kindknoten der Index 0 zugewiesen wird. Kindknoten umfassen Elemente, Text und Kommentare. |
| [Children](../../aspose.svg.dom/document/children/) { get; } | Gibt die Kind-Elemente zurück. |
| [ContentType](../../aspose.svg.dom/document/contenttype/) { get; } | Liest den Inhaltstyp des Dokuments. |
| [Context](../../aspose.svg.dom/document/context/) { get; } | Liest den aktuellen Browsing-Kontext. |
| [DefaultView](../../aspose.svg.dom/document/defaultview/) { get; } | Das defaultView-IDL-Attribut der Document-Schnittstelle muss beim Abrufen das WindowProxy-Objekt des Browsing-Kontexts dieses Dokuments zurückgeben, falls dieses Dokument einen zugehörigen Browsing-Kontext hat, andernfalls null. |
| [Doctype](../../aspose.svg.dom/document/doctype/) { get; } | Die Document Type Declaration, die mit diesem Dokument verknüpft ist. |
| [DocumentElement](../../aspose.svg.dom/document/documentelement/) { get; } | Dies ist ein Komfortattribut, das direkten Zugriff auf den Kindknoten ermöglicht, der das Dokument-Element des Dokuments ist. |
| [DocumentURI](../../aspose.svg.dom/document/documenturi/) { get; } | Der Speicherort des Dokuments oder null, wenn undefiniert oder wenn das Dokument mittels DOMImplementation.createDocument erstellt wurde. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Gibt das erste Kind des Knotens im Baum zurück oder null, wenn der Knoten keine Kinder hat. |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild/) { get; } | Gibt den ersten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kindelemente hat. |
| [Implementation](../../aspose.svg.dom/document/implementation/) { get; } | Das DOMImplementation-Objekt, das dieses Dokument verarbeitet. |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding/) { get; } | Liest die Kodierung des Dokuments. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Gibt das letzte Kind des Knotens zurück. Wenn dessen übergeordnetes Element ein Element ist, ist das Kind in der Regel ein Elementknoten, ein Textknoten oder ein Kommentar­knoten. Es wird null zurückgegeben, wenn keine Kind‑Elemente vorhanden sind. |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild/) { get; } | Gibt den letzten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kindelemente hat. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten beliebigen Typs, die nicht [`ELEMENT_NODE`](../node/element_node/) oder [`ATTRIBUTE_NODE`](../node/attribute_node/) sind und für Knoten, die mit einer DOM Level 1‑Methode erstellt wurden, wie [`CreateElement`](./createelement/), ist dies immer null. |
| [Location](../../aspose.svg.dom/document/location/) { get; } | Der Speicherort des Dokuments. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Gibt die Namespace‑URI des Elements zurück oder null, wenn das Element in keinem Namespace ist. |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling/) { get; } | Gibt den nächsten Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine nachfolgenden Element‑Geschwisterknoten im Dokumentbaum hat. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Gibt den Knoten zurück, der dem angegebenen Knoten im [`ChildNodes`](../node/childnodes/)-Array des Elternknotens unmittelbar folgt, oder null, wenn der angegebene Knoten das letzte Kind im übergeordneten Element ist. |
| override [NodeName](../../aspose.svg.dom/document/nodename/) { get; } | Der Name dieses Knotens, abhängig von seinem Typ. |
| override [NodeType](../../aspose.svg.dom/document/nodetype/) { get; } | Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Gibt den Wert des aktuellen Knotens zurück oder setzt ihn. |
| [Origin](../../aspose.svg.dom/document/origin/) { get; } | Ermittelt die Herkunft des Dokuments. |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument/) { get; } | Ermittelt das Eigentümer‑Dokument. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Gibt den Eltern‑[`Element`](../element/)-Knoten des DOM‑Knotens zurück, oder null, wenn der Knoten keinen Elternteil hat oder sein Elternteil kein DOM‑Element ist. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Gibt den Elternknoten des angegebenen Knotens im DOM‑Baum zurück. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Gibt das Namespace‑Präfix des angegebenen Elements zurück oder null, wenn kein Präfix angegeben ist. |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling/) { get; } | Gibt den vorherigen Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine vorherigen Element‑Geschwisterknoten im Dokumentbaum hat. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Gibt den Knoten zurück, der dem angegebenen Knoten im [`ChildNodes`](../node/childnodes/)‑Verzeichnis seines Elternteils unmittelbar vorausgeht, oder null, wenn der angegebene Knoten der erste in dieser Liste ist. |
| [ReadyState](../../aspose.svg.dom/document/readystate/) { get; } | Gibt den Ladezustand des Dokuments zurück. "loading", während das Dokument geladen wird, "interactive", sobald das Parsen abgeschlossen ist, aber Unterressourcen noch geladen werden, und "complete", sobald es vollständig geladen ist. |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking/) { get; set; } | Ein Attribut, das angibt, ob Fehlprüfungen erzwungen werden oder nicht. Wenn es auf false gesetzt ist, kann die Implementierung auf das Testen jedes möglichen Fehlers, der normalerweise bei DOM‑Operationen definiert ist, verzichten und bei DOM‑Operationen keine DOMException auslösen oder Fehler melden, wenn Document.normalizeDocument() verwendet wird. Im Fehlerfall ist das Verhalten undefiniert. Dieses Attribut ist standardmäßig true. |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets/) { get; } | Eine Liste, die alle Stylesheets enthält, die explizit in ein Dokument verlinkt oder eingebettet sind. Für HTML‑Dokumente umfasst dies externe Stylesheets, die über das HTML‑LINK‑Element eingebunden werden, sowie inline STYLE‑Elemente. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Stellt den Textinhalt des Knotens und seiner Nachkommen dar. |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone/) { get; set; } | Ein Attribut, das im Rahmen der XML‑Deklaration angibt, ob dieses Dokument eigenständig ist. Wenn nicht angegeben, ist es false. |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion/) { get; set; } | Ein Attribut, das im Rahmen der XML‑Deklaration die Versionsnummer dieses Dokuments angibt. Gibt es keine Deklaration und unterstützt das Dokument das Feature "XML", ist der Wert "1.0". Unterstützt das Dokument das Feature "XML" nicht, ist der Wert immer null. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Fügt einen Knoten am Ende der Kindliste eines angegebenen Elternknotens hinzu. Wenn das angegebene Kind eine Referenz zu einem bereits im Dokument vorhandenen Knoten ist, verschiebt [`AppendChild`](../node/appendchild/) ihn von seiner aktuellen Position in die neue Position (es ist nicht erforderlich, den Knoten vor dem Anhängen an einen anderen Knoten aus seinem Elternknoten zu entfernen). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Sein Parameter steuert, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute/)(*string*) | Diese Methode erstellt einen neuen Attributknoten und gibt ihn zurück. Das erstellte Objekt ist ein Knoten, der die Klasse [`Attr`](../attr/) implementiert. Das DOM erzwingt nicht, welche Art von Attributen auf diese Weise zu einem bestimmten Element hinzugefügt werden können. |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens/)(*string, string*) | Diese Methode erstellt einen neuen Attributknoten und gibt ihn zurück. Das erstellte Objekt ist ein Knoten, der die Klasse [`Attr`](../attr/) implementiert. Das DOM erzwingt nicht, welche Art von Attributen auf diese Weise zu einem bestimmten Element hinzugefügt werden können. |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection/)(*string*) | Erstellt einen CDATASection‑Knoten, dessen Wert die angegebene Zeichenkette ist. |
| [CreateComment](../../aspose.svg.dom/document/createcomment/)(*string*) | Erstellt einen Comment‑Knoten mit der angegebenen Zeichenkette. |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment/)() | Erstellt ein neues leeres [`DocumentFragment`](../documentfragment/), in das DOM‑Knoten eingefügt werden können, um einen Off‑Screen‑DOM‑Baum aufzubauen. |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype/)(*string, string, string, string*) | Die Methode gibt ein [`DocumentType`](../documenttype/)-Objekt zurück, das entweder bei der Dokumenterstellung mit [`CreateDocument`](../idomimplementation/createdocument/) verwendet werden kann oder über Methoden wie [`InsertBefore`](../node/insertbefore/) oder [`ReplaceChild`](../node/replacechild/) in das Dokument eingefügt werden kann. |
| [CreateElement](../../aspose.svg.dom/document/createelement/)(*string*) | Erstellt das HTML‑Element, das durch localName angegeben ist, oder ein HTMLUnknownElement, wenn localName nicht erkannt wird. |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns/)(*string, string*) | Erstellt ein Element mit dem angegebenen qualifizierten Namen und Namespace-URI. |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference/)(*string*) | Erstellt ein EntityReference-Objekt. Zusätzlich wird, falls die referenzierte Entität bekannt ist, die Kindliste des EntityReference‑Knotens identisch zur entsprechenden Entity‑Knoten‑Kindliste gemacht. |
| [CreateEvent](../../aspose.svg.dom/document/createevent/)(*string*) | Erstellt ein [`Event`](../../aspose.svg.dom.events/event/) eines von der Implementierung unterstützten Typs. |
| [CreateExpression](../../aspose.svg.dom/document/createexpression/)(*string, [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)*) | Erstellt einen geparsten XPath‑Ausdruck mit aufgelösten Namespaces. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet wird, da es ermöglicht, die Ausdruckszeichenkette in eine effizientere interne Form zu kompilieren und alle im Ausdruck vorkommenden Namespace‑Präfixe vorab aufzulösen. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator)(*[Node](../node/)*) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_1)(*[Node](../node/), long*) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver/)(*[Node](../node/)*) | Passt jeden DOM‑Knoten an, um Namespaces aufzulösen, sodass ein XPath‑Ausdruck leicht relativ zum Kontext des Knotens, in dem er im Dokument erschien, ausgewertet werden kann. Dieser Adapter funktioniert wie die DOM‑Level‑3‑Methode `lookupNamespaceURI` bei Knoten, indem er den namespaceURI aus einem gegebenen Präfix anhand der zum Zeitpunkt des Aufrufs von lookupNamespaceURI verfügbaren Informationen in der Knotenhierarchie auflöst und dabei auch das implizite xml‑Präfix korrekt behandelt. |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction/)(*string, string*) | Erstellt einen ProcessingInstruction‑Knoten mit dem angegebenen Namen und den Daten‑Strings. |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode/)(*string*) | Erstellt einen Text‑Knoten mit der angegebenen Zeichenkette. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker)(*[Node](../node/)*) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_1)(*[Node](../node/), long*) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Sendet ein Event an das angegebene [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListeners in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Capture‑ und optionalen Bubbling‑Phase) gelten ebenfalls für manuell mit [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [Evaluate](../../aspose.svg.dom/document/evaluate/)(*string, [Node](../node/), [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/), [XPathResultType](../../aspose.svg.dom.xpath/xpathresulttype/), object*) | Wertet eine XPath‑Ausdruckszeichenkette aus und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück. |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid/)(*string*) | Diese Methode gibt ein [`Element`](../element/)‑Objekt zurück, das das Element darstellt, dessen id‑Eigenschaft mit der angegebenen Zeichenkette übereinstimmt. Da Element‑IDs, falls angegeben, eindeutig sein müssen, sind sie eine nützliche Möglichkeit, schnell auf ein bestimmtes Element zuzugreifen. |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname/)(*string*) | Diese Methode gibt ein array‑ähnliches Objekt aller Kind‑Elemente zurück, die alle angegebenen Klassennamen besitzen. |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname/)(*string*) | Diese Methode gibt eine [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) von Elementen mit dem angegebenen Tag‑Namen zurück. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens/)(*string, string*) | Gibt eine Liste von Elementen mit dem angegebenen Tag‑Namen zurück, die zum angegebenen Namespace gehören. Das gesamte Dokument wird durchsucht, einschließlich des Wurzelknotens. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Gibt einen booleschen Wert zurück, der angibt, ob der angegebene [`Node`](../node/) Kindknoten hat oder nicht. |
| [ImportNode](../../aspose.svg.dom/document/importnode/)(*[Node](../node/), bool*) | Importiert einen Knoten aus einem anderen Dokument in dieses Dokument, ohne den Quellknoten im Originaldokument zu ändern oder zu entfernen; diese Methode erstellt eine neue Kopie des Quellknotens. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Fügt den Knoten vor dem vorhandenen Kindknoten child ein. Wenn child null ist, wird der Knoten am Ende der Kindliste eingefügt. Wenn child ein DocumentFragment-Objekt ist, werden all seine Kinder in derselben Reihenfolge vor child eingefügt. Wenn das Kind bereits im Baum ist, wird es zuerst entfernt. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Diese Methode prüft, ob das angegebene namespaceURI der Standardsnamensraum ist oder nicht. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Testet, ob zwei Knoten gleich sind. Diese Methode prüft die Gleichheit von Knoten, nicht die Identität (d. h., ob die beiden Knoten Referenzen auf dasselbe Objekt sind), was mit Node.isSameNode() getestet werden kann. Alle Knoten, die identisch sind, sind auch gleich, obwohl das Gegenteil nicht unbedingt zutrifft. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Die Methode ist ein veralteter Alias für den strikten Gleichheitsoperator ===. Das heißt, sie prüft, ob zwei Knoten identisch sind (mit anderen Worten, ob sie auf dasselbe Objekt verweisen). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Sucht die dem angegebenen Präfix zugeordnete Namespace-URI, beginnend bei diesem Knoten. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Sucht das dem angegebenen Namespace-URI zugeordnete Präfix, beginnend bei diesem Knoten. Die Deklarationen des Standardnamensraums werden von dieser Methode ignoriert. Siehe Namespace Prefix Lookup für Details zum von dieser Methode verwendeten Algorithmus. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate)(*[RequestMessage](../../aspose.svg.net/requestmessage/)*) | Lädt das Dokument basierend auf dem angegebenen Anforderungsobjekt und ersetzt den vorherigen Inhalt. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_8)(*string*) | Lädt das Dokument unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_2)(*[Url](../../aspose.svg/url/)*) | Lädt das Dokument unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_1)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | Lädt das Dokument basierend auf dem angegebenen Anforderungsobjekt und ersetzt den vorherigen Inhalt. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_6)(*Stream, string*) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_4)(*Stream, [Url](../../aspose.svg/url/)*) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_13)(*string, CancellationToken*) | Lädt das Dokument unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_11)(*string, string*) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_9)(*string, [Url](../../aspose.svg/url/)*) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_3)(*[Url](../../aspose.svg/url/), CancellationToken*) | Lädt das Dokument unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_7)(*Stream, string, CancellationToken*) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_5)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_12)(*string, string, CancellationToken*) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_10)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | Lädt das Dokument asynchron basierend auf dem angegebenen Anforderungsobjekt. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_6)(*string, CancellationToken*) | Lädt das Dokument asynchron unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_1)(*[Url](../../aspose.svg/url/), CancellationToken*) | Lädt das Dokument asynchron unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_3)(*Stream, string, CancellationToken*) | Lädt das Dokument asynchron aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_2)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | Lädt das Dokument asynchron aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_5)(*string, string, CancellationToken*) | Lädt das Dokument asynchron aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_4)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | Lädt das Dokument asynchron aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Setzt alle Textknoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine "normale" Form, bei der nur die Struktur (z. B. Elemente, Kommentare, Verarbeitungsanweisungen, CDATA-Abschnitte und Entity-Referenzen) Textknoten trennt, d. h. es gibt weder benachbarte Textknoten noch leere Textknoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM-Ansicht eines Dokuments dieselbe ist, als wäre sie gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen (wie XPointer [XPointer]-Nachschlagen), die von einer bestimmten Dokumentbaumstruktur abhängen, verwendet werden sollen. Wenn der Parameter "normalize-characters" des DOMConfiguration-Objekts, das an Node.ownerDocument angehängt ist, true ist, normalisiert diese Methode auch vollständig die Zeichen der Textknoten. |
| [QuerySelector](../../aspose.svg.dom/document/queryselector/)(*string*) | Gibt das erste Element im Dokument zurück, das dem Selektor entspricht |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall/)(*string*) | Gibt eine NodeList aller Elemente im Dokument zurück, die dem Selektor entsprechen |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach ihrer Entfernung niemals aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach ihrer Entfernung niemals aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach ihrer Entfernung niemals aufgerufen werden. |
| virtual [RenderTo](../../aspose.svg.dom/document/renderto/)(*[IDevice](../../aspose.svg.rendering/idevice/)*) | Diese Methode wird verwendet, um den Inhalt des aktuellen Dokuments auf ein angegebenes grafisches Gerät zu rendern. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Ersetzt den Kindknoten oldChild durch newChild in der Kindliste und gibt den alten oldChild‑Knoten zurück. Wenn newChild ein DocumentFragment‑Objekt ist, wird oldChild durch alle Kinder des DocumentFragment ersetzt, die in derselben Reihenfolge eingefügt werden. Wenn newChild bereits im Baum ist, wird es zuerst entfernt. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |
| [Write](../../aspose.svg.dom/document/write/)(*params string[]*) | Schreibt eine Textzeichenkette in einen Dokumenten‑Stream, der mit open() geöffnet wurde. Beachten Sie, dass die Funktion ein Dokument erzeugt, das nicht unbedingt von einer DTD gesteuert wird und daher im Kontext des Dokuments ein ungültiges Ergebnis erzeugen kann. |
| [WriteLn](../../aspose.svg.dom/document/writeln/)(*params string[]*) | Schreibt eine Textzeichenkette, gefolgt von einem Zeilenumbruchzeichen, in einen Dokumenten‑Stream, der mit open() geöffnet wurde. Beachten Sie, dass die Funktion ein Dokument erzeugt, das nicht unbedingt von einer DTD gesteuert wird und daher im Kontext des Dokuments ein ungültiges Ergebnis erzeugen kann |

## Ereignisse

| Name | Beschreibung |
| --- | --- |
| event [OnAbort](../../aspose.svg.dom/document/onabort/) | Liest oder setzt den Ereignishandler für das OnAbort‑Ereignis. |
| event [OnBlur](../../aspose.svg.dom/document/onblur/) | Liest oder setzt den Ereignishandler für das OnBlur‑Ereignis. |
| event [OnCancel](../../aspose.svg.dom/document/oncancel/) | Liest oder setzt den Ereignishandler für das OnCancel‑Ereignis. |
| event [OnCanplay](../../aspose.svg.dom/document/oncanplay/) | Liest oder setzt den Ereignishandler für das OnCanplay‑Ereignis. |
| event [OnCanPlayThrough](../../aspose.svg.dom/document/oncanplaythrough/) | Liest oder setzt den Ereignishandler für das OnCanPlayThrough‑Ereignis. |
| event [OnChange](../../aspose.svg.dom/document/onchange/) | Liest oder setzt den Ereignishandler für das OnChange‑Ereignis. |
| event [OnClick](../../aspose.svg.dom/document/onclick/) | Liest oder setzt den Ereignishandler für das OnClick‑Ereignis. |
| event [OnCueChange](../../aspose.svg.dom/document/oncuechange/) | Liest oder setzt den Ereignishandler für das OnCueChange‑Ereignis. |
| event [OnDblClick](../../aspose.svg.dom/document/ondblclick/) | Liest oder setzt den Ereignishandler für das OnDblClick‑Ereignis. |
| event [OnDurationChange](../../aspose.svg.dom/document/ondurationchange/) | Liest oder setzt den Ereignishandler für das OnDurationChange‑Ereignis. |
| event [OnEmptied](../../aspose.svg.dom/document/onemptied/) | Liest oder setzt den Ereignishandler für das OnEmptied‑Ereignis. |
| event [OnEnded](../../aspose.svg.dom/document/onended/) | Liest oder setzt den Ereignishandler für das OnEnded‑Ereignis. |
| event [OnError](../../aspose.svg.dom/document/onerror/) | Liest oder setzt Ereignis-Handler für das OnError-Ereignis. |
| event [OnFocus](../../aspose.svg.dom/document/onfocus/) | Liest oder setzt Ereignis-Handler für das OnFocus-Ereignis. |
| event [OnInput](../../aspose.svg.dom/document/oninput/) | Liest oder setzt Ereignis-Handler für das OnInput-Ereignis. |
| event [OnInvalid](../../aspose.svg.dom/document/oninvalid/) | Liest oder setzt Ereignis-Handler für das OnInvalid-Ereignis. |
| event [OnKeyDown](../../aspose.svg.dom/document/onkeydown/) | Liest oder setzt Ereignis-Handler für das OnKeyDown-Ereignis. |
| event [OnKeyPress](../../aspose.svg.dom/document/onkeypress/) | Liest oder setzt Ereignis-Handler für das OnKeyPress-Ereignis. |
| event [OnKeyUp](../../aspose.svg.dom/document/onkeyup/) | Liest oder setzt Ereignis-Handler für das OnKeyUp-Ereignis. |
| event [OnLoad](../../aspose.svg.dom/document/onload/) | Liest oder setzt Ereignis-Handler für das OnLoad-Ereignis. |
| event [OnLoadedData](../../aspose.svg.dom/document/onloadeddata/) | Liest oder setzt Ereignis-Handler für das OnLoadedData-Ereignis. |
| event [OnLoadedMetadata](../../aspose.svg.dom/document/onloadedmetadata/) | Liest oder setzt Ereignis-Handler für das OnLoadedMetadata-Ereignis. |
| event [OnLoadStart](../../aspose.svg.dom/document/onloadstart/) | Liest oder setzt Ereignis-Handler für das OnLoadStart-Ereignis. |
| event [OnMouseDown](../../aspose.svg.dom/document/onmousedown/) | Liest oder setzt Ereignis-Handler für das OnMouseDown-Ereignis. |
| event [OnMouseEnter](../../aspose.svg.dom/document/onmouseenter/) | Liest oder setzt Ereignis-Handler für das OnMouseEnter-Ereignis. |
| event [OnMouseLeave](../../aspose.svg.dom/document/onmouseleave/) | Liest oder setzt Ereignis-Handler für das OnMouseLeave-Ereignis. |
| event [OnMouseMove](../../aspose.svg.dom/document/onmousemove/) | Liest oder setzt Ereignis-Handler für das OnMouseMove-Ereignis. |
| event [OnMouseOut](../../aspose.svg.dom/document/onmouseout/) | Liest oder setzt Ereignis-Handler für das OnMouseOut-Ereignis. |
| event [OnMouseOver](../../aspose.svg.dom/document/onmouseover/) | Liest oder setzt Ereignis-Handler für das OnMouseOver-Ereignis. |
| event [OnMouseUp](../../aspose.svg.dom/document/onmouseup/) | Liest oder setzt Ereignis-Handler für das OnMouseUp-Ereignis. |
| event [OnMouseWheel](../../aspose.svg.dom/document/onmousewheel/) | Liest oder setzt Ereignis-Handler für das OnMouseWheel-Ereignis. |
| event [OnPause](../../aspose.svg.dom/document/onpause/) | Liest oder setzt Ereignis-Handler für das OnPause-Ereignis. |
| event [OnPlay](../../aspose.svg.dom/document/onplay/) | Liest oder setzt Ereignis-Handler für das OnPlay-Ereignis. |
| event [OnPlaying](../../aspose.svg.dom/document/onplaying/) | Liest oder setzt Ereignis-Handler für das OnPlaying-Ereignis. |
| event [OnProgress](../../aspose.svg.dom/document/onprogress/) | Liest oder setzt Ereignis-Handler für das OnProgress-Ereignis. |
| event [OnRateChange](../../aspose.svg.dom/document/onratechange/) | Liest oder setzt Ereignis-Handler für das OnRateChange-Ereignis. |
| event [OnReadyStateChange](../../aspose.svg.dom/document/onreadystatechange/) | Liest oder setzt den Ereignishandler für das OnReadyStateChange‑Ereignis. |
| event [OnReset](../../aspose.svg.dom/document/onreset/) | Liest oder setzt Ereignis-Handler für das OnReset-Ereignis. |
| event [OnResize](../../aspose.svg.dom/document/onresize/) | Liest oder setzt den Ereignishandler für das OnResize-Ereignis. |
| event [OnScroll](../../aspose.svg.dom/document/onscroll/) | Liest oder setzt den Ereignishandler für das OnScroll-Ereignis. |
| event [OnSeeked](../../aspose.svg.dom/document/onseeked/) | Liest oder setzt den Ereignishandler für das OnSeeked-Ereignis. |
| event [OnSeeking](../../aspose.svg.dom/document/onseeking/) | Liest oder setzt den Ereignishandler für das OnSeeking-Ereignis. |
| event [OnSelect](../../aspose.svg.dom/document/onselect/) | Liest oder setzt den Ereignishandler für das OnSelect-Ereignis. |
| event [OnShow](../../aspose.svg.dom/document/onshow/) | Liest oder setzt den Ereignishandler für das OnShow-Ereignis. |
| event [OnStalled](../../aspose.svg.dom/document/onstalled/) | Liest oder setzt den Ereignishandler für das OnStalled-Ereignis. |
| event [OnSubmit](../../aspose.svg.dom/document/onsubmit/) | Liest oder setzt den Ereignishandler für das OnSubmit-Ereignis. |
| event [OnSuspend](../../aspose.svg.dom/document/onsuspend/) | Liest oder setzt den Ereignishandler für das OnSuspend-Ereignis. |
| event [OnTimeUpdate](../../aspose.svg.dom/document/ontimeupdate/) | Liest oder setzt den Ereignishandler für das OnTimeUpdate-Ereignis. |
| event [OnToggle](../../aspose.svg.dom/document/ontoggle/) | Liest oder setzt den Ereignishandler für das OnToggle-Ereignis. |
| event [OnVolumeChange](../../aspose.svg.dom/document/onvolumechange/) | Liest oder setzt den Ereignishandler für das OnVolumeChange-Ereignis. |
| event [OnWaiting](../../aspose.svg.dom/document/onwaiting/) | Liest oder setzt den Ereignishandler für das OnWaiting-Ereignis. |

### Siehe auch

* class [Node](../node/)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../aspose.svg.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../aspose.svg.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../aspose.svg.dom.xpath/ixpathevaluator/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
