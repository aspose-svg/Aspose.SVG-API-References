---
title: "SVGGeometryElement Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.SVGGeometryElement Klasse. Das Interface SVGGeometryElement repräsentiert SVG‑Elemente, deren Darstellung durch Geometrie mit einem äquivalenten Pfad definiert ist und die gefüllt und konturiert werden können. Dies schließt Pfade und die Grundformen ein."
type: docs
weight: 5340
url: /de/net/aspose.svg/svggeometryelement/
---
## SVGGeometryElement class

Die Schnittstelle SVGGeometryElement repräsentiert SVG‑Elemente, deren Darstellung durch Geometrie mit einem äquivalenten Pfad definiert ist und die gefüllt und konturiert werden können. Dazu gehören Pfade und die Grundformen.

```csharp
public class SVGGeometryElement : SVGGraphicsElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Attributes](../../aspose.svg.dom/element/attributes/) { get; } | Eine NamedNodeMap, die die Attribute dieses Knotens enthält (falls es ein Element ist) oder andernfalls null. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Gibt die absolute Basis‑URL des Dokuments zurück, das den Knoten enthält. |
| [ChildElementCount](../../aspose.svg.dom/element/childelementcount/) { get; } | Gibt die aktuelle Anzahl von Elementknoten zurück, die Kindknoten dieses Elements sind. 0, wenn dieses Element keine Kindknoten vom Knotentyp 1 hat. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Gibt eine Live‑[`NodeList`](../../aspose.svg.collections/nodelist/) der Kindknoten des angegebenen Elements zurück, wobei dem ersten Kindknoten der Index 0 zugewiesen wird. Kindknoten umfassen Elemente, Text und Kommentare. |
| [Children](../../aspose.svg.dom/element/children/) { get; } | Gibt die Kind-Elemente des aktuellen Elements zurück. |
| [ClassList](../../aspose.svg.dom/element/classlist/) { get; } | Gibt eine Live-DOMTokenList zurück, die Token enthält, die beim Parsen des "class"-Attributs erhalten wurden. |
| [ClassName](../../aspose.svg/svgelement/classname/) { get; } | Entspricht dem Attribut ‘class’ des angegebenen Elements. |
| [ClassName](../../aspose.svg.dom/element/classname/) { get; set; } | Das class-Attribut des Elements. Dieses Attribut wurde umbenannt, weil es mit dem Schlüsselwort "class" vieler Sprachen kollidiert. Siehe die Definition des class-Attributs in HTML 4.01. |
| [FarthestViewportElement](../../aspose.svg/svggraphicselement/farthestviewportelement/) { get; } | Das am weitesten entfernte übergeordnete ‘svg’-Element. Null, wenn das aktuelle Element das äußerste svg‑Element ist. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Gibt das erste Kind des Knotens im Baum zurück oder null, wenn der Knoten keine Kinder hat. |
| [FirstElementChild](../../aspose.svg.dom/element/firstelementchild/) { get; } | Gibt den ersten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kindelemente hat. |
| [Id](../../aspose.svg/svgelement/id/) { get; set; } | Der Wert des ‘id’-Attributs des angegebenen Elements oder die leere Zeichenkette, wenn ‘id’ nicht vorhanden ist. |
| [InnerHTML](../../aspose.svg.dom/element/innerhtml/) { get; set; } | Gibt ein Fragment von HTML oder XML zurück, das den Inhalt des Elements darstellt. Kann gesetzt werden, um den Inhalt des Elements durch Knoten zu ersetzen, die aus dem angegebenen String geparst wurden. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Gibt das letzte Kind des Knotens zurück. Wenn dessen übergeordnetes Element ein Element ist, ist das Kind in der Regel ein Elementknoten, ein Textknoten oder ein Kommentar­knoten. Es wird null zurückgegeben, wenn keine Kind‑Elemente vorhanden sind. |
| [LastElementChild](../../aspose.svg.dom/element/lastelementchild/) { get; } | Gibt den letzten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kindelemente hat. |
| override [LocalName](../../aspose.svg.dom/element/localname/) { get; } | Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten jeglichen Typs außer ELEMENT_NODE und ATTRIBUTE_NODE sowie für mit einer DOM‑Level‑1‑Methode erstellte Knoten, wie Document.createElement(), ist dies stets null. |
| override [NamespaceURI](../../aspose.svg.dom/element/namespaceuri/) { get; } | Der Namespace‑URI dieses Knotens oder null, wenn er nicht angegeben ist. |
| [NearestViewportElement](../../aspose.svg/svggraphicselement/nearestviewportelement/) { get; } | Das Element, das den aktuellen Ansichtsbereich festgelegt hat. Oft das nächstgelegene übergeordnete ‘svg’-Element. Null, wenn das aktuelle Element das äußerste svg‑Element ist. |
| [NextElementSibling](../../aspose.svg.dom/element/nextelementsibling/) { get; } | Gibt den nächsten Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine nachfolgenden Element‑Geschwisterknoten im Dokumentbaum hat. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Gibt den Knoten zurück, der dem angegebenen Knoten im [`ChildNodes`](../../aspose.svg.dom/node/childnodes/)-Array des Elternteils unmittelbar folgt, oder gibt null zurück, wenn der angegebene Knoten das letzte Kind im Elternelement ist. |
| override [NodeName](../../aspose.svg.dom/element/nodename/) { get; } | Der Name dieses Knotens, abhängig von seinem Typ. |
| override [NodeType](../../aspose.svg.dom/element/nodetype/) { get; } | Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Gibt den Wert des aktuellen Knotens zurück oder setzt ihn. |
| [OuterHTML](../../aspose.svg.dom/element/outerhtml/) { get; set; } | Gibt ein Fragment von HTML oder XML zurück, das das Element und seinen Inhalt darstellt. Kann gesetzt werden, um das Element durch Knoten zu ersetzen, die aus dem angegebenen String geparst wurden. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Gibt das Dokumentobjekt der obersten Ebene des Knotens zurück. |
| [OwnerSVGElement](../../aspose.svg/svgelement/ownersvgelement/) { get; } | Das nächstgelegene übergeordnete ‘svg’-Element. Null, wenn das angegebene Element das äußerste svg-Element ist. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Gibt das übergeordnete [`Element`](../../aspose.svg.dom/element/) des DOM‑Knotens zurück, oder null, wenn der Knoten keinen Elternknoten hat oder sein Elternknoten kein DOM‑Element ist. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Gibt den Elternknoten des angegebenen Knotens im DOM‑Baum zurück. |
| [PathLength](../../aspose.svg/svggeometryelement/pathlength/) { get; } | Entspricht dem Attribut pathLength des angegebenen Elements. |
| override [Prefix](../../aspose.svg.dom/element/prefix/) { get; } | Der Namensraum‑Präfix dieses Knotens, oder null, wenn er nicht angegeben ist. Wenn er als null definiert ist, hat das Setzen keine Auswirkung. |
| [PreviousElementSibling](../../aspose.svg.dom/element/previouselementsibling/) { get; } | Gibt den vorherigen Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine vorherigen Element‑Geschwisterknoten im Dokumentbaum hat. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Gibt den Knoten zurück, der dem angegebenen Knoten in der [`ChildNodes`](../../aspose.svg.dom/node/childnodes/)-Liste des Elternteils unmittelbar vorausgeht, oder null, wenn der angegebene Knoten der erste in dieser Liste ist. |
| [RequiredExtensions](../../aspose.svg/svggraphicselement/requiredextensions/) { get; } | Entspricht dem Attribut ‘requiredExtensions’ des angegebenen Elements. |
| [RequiredFeatures](../../aspose.svg/svggraphicselement/requiredfeatures/) { get; } | Entspricht dem Attribut ‘requiredFeatures’ des angegebenen Elements. |
| [ShadowRoot](../../aspose.svg.dom/element/shadowroot/) { get; } | Gibt das auf diesem Element gespeicherte shadowRoot zurück oder null, wenn es geschlossen ist. |
| [Style](../../aspose.svg/svgelement/style/) { get; } | Entspricht dem Attribut ‘style’ des angegebenen Elements. Wenn der User‑Agent keine CSS‑Stilgebung unterstützt, muss dieses Attribut stets den Wert null haben. |
| [SystemLanguage](../../aspose.svg/svggraphicselement/systemlanguage/) { get; } | Entspricht dem Attribut ‘systemLanguage’ des angegebenen Elements. |
| [TagName](../../aspose.svg.dom/element/tagname/) { get; } | Der Name des Elements. |
| override [TextContent](../../aspose.svg.dom/element/textcontent/) { get; set; } | Dieses Attribut gibt den Textinhalt dieses Knotens und seiner Nachkommen zurück. Wenn es als null definiert ist, hat das Setzen keine Auswirkung. Beim Setzen werden alle möglichen Kindknoten dieses Knotens entfernt und, wenn die neue Zeichenkette nicht leer oder null ist, durch einen einzelnen Textknoten ersetzt, der die Zeichenkette enthält, auf die dieses Attribut gesetzt wird. |
| [Transform](../../aspose.svg/svggraphicselement/transform/) { get; } | Entspricht dem Attribut ‘transform’ des angegebenen Elements. |
| [ViewportElement](../../aspose.svg/svgelement/viewportelement/) { get; } | Das Element, das den aktuellen Ansichtsbereich festgelegt hat. Oft das nächstgelegene übergeordnete ‘svg’-Element. Null, wenn das angegebene Element das äußerste svg-Element ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../../aspose.svg.dom/node/)*) | Fügt einem angegebenen Elternknoten am Ende der Kindliste einen Knoten hinzu. Wenn das angegebene Kind eine Referenz auf einen bereits im Dokument vorhandenen Knoten darstellt, verschiebt [`AppendChild`](../../aspose.svg.dom/node/appendchild/) ihn von seiner aktuellen Position an die neue Position (es ist nicht erforderlich, den Knoten vor dem Anhängen an einen anderen Knoten aus seinem Elternknoten zu entfernen). |
| [AttachShadow](../../aspose.svg.dom/element/attachshadow/)(*[ShadowRootMode](../../aspose.svg.dom/shadowrootmode/)*) | Erstellt ein shadowRoot und fügt es dem aktuellen Element hinzu. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Sein Parameter steuert, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [Combine](../../aspose.svg/svggeometryelement/combine/)(*SVGGeometryElement, [BooleanPathOp](../../aspose.svg.rendering/booleanpathop/)*) | Kombiniert diese Geometrie mit einer anderen SVG‑Geometrie mittels einer booleschen Operation und gibt ein neues `<path>`‑Element zurück, das das Ergebnis enthält. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Sendet ein Event an das angegebene [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListeners in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Capture‑ und optionalen Bubbling‑Phase) gelten ebenfalls für manuell mit [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [GetAttribute](../../aspose.svg.dom/element/getattribute/)(*string*) | Ruft einen Attributwert anhand des Namens ab. |
| [GetAttributeNames](../../aspose.svg.dom/element/getattributenames/)() | Gibt die Attributnamen des Elements als Array von Zeichenketten zurück. Hat das Element keine Attribute, wird ein leeres Array zurückgegeben. |
| [GetAttributeNode](../../aspose.svg.dom/element/getattributenode/)(*string*) | Ruft einen Attributknoten anhand des Namens ab. |
| [GetAttributeNodeNS](../../aspose.svg.dom/element/getattributenodens/)(*string, string*) | Ruft einen Attr-Knoten anhand des lokalen Namens und des Namespace-URI ab. |
| [GetAttributeNS](../../aspose.svg.dom/element/getattributens/)(*string, string*) | Ruft einen Attributwert anhand des lokalen Namens und des Namespace-URI ab. |
| [GetBBox](../../aspose.svg/svggraphicselement/getbbox/)() | Gibt die enge Begrenzungsbox im aktuellen Benutzerraum (d. h. nach Anwendung des Attributs ‘transform’, falls vorhanden) für die Geometrie aller enthaltenen Grafikelemente zurück, ohne Strichführung, Clipping, Maskierung und Filtereffekte. Hinweis: getBBox muss zum Zeitpunkt des Aufrufs die tatsächliche Begrenzungsbox zurückgeben, selbst wenn das Element noch nicht gerendert wurde. |
| [GetCTM](../../aspose.svg/svggraphicselement/getctm/)() | Gibt die Transformationsmatrix von den aktuellen Benutzereinheiten (d. h. nach Anwendung des Attributs ‘transform’, falls vorhanden) zum Koordinatensystem des Ansichtsbereichs für das nearestViewportElement zurück. |
| [GetElementsByClassName](../../aspose.svg.dom/element/getelementsbyclassname/)(*string*) | Gibt ein [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/)‑Objekt zurück, das alle Elemente innerhalb von [`element`](../../aspose.svg.dom/element/) enthält, die alle im Argument angegebenen Klassen besitzen. |
| [GetElementsByTagName](../../aspose.svg.dom/element/getelementsbytagname/)(*string*) | Gibt ein [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/)‑Objekt zurück, das alle [`elements`](../../aspose.svg.dom/element/) mit einem angegebenen Tag‑Namen in Dokumentreihenfolge enthält. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/element/getelementsbytagnamens/)(*string, string*) | Gibt ein [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/)‑Objekt zurück, das alle [`elements`](../../aspose.svg.dom/element/) mit einem angegebenen lokalen Namen und Namespace‑URI‑String in Dokumentreihenfolge enthält. |
| [GetEquivalentPath](../../aspose.svg/svggeometryelement/getequivalentpath/)() | Gibt eine neue Instanz von [`SVGPathSegList`](../../aspose.svg.paths/svgpathseglist/) zurück, die `SVGGeometryElement` als Pfadsegmente darstellt. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [GetPointAtLength](../../aspose.svg/svggeometryelement/getpointatlength/)(*float*) | Gibt die (x,y)-Koordinate im Benutzerraum zurück, die in Distanz‑Einheiten entlang des Pfads liegt und den distance‑along‑a‑path‑Algorithmus des User‑Agents verwendet. |
| [GetScreenCTM](../../aspose.svg/svggraphicselement/getscreenctm/)() | Gibt die Transformationsmatrix von den aktuellen Benutzereinheiten (d. h. nach Anwendung des Attributs ‘transform’, falls vorhanden) zur Wahrnehmung eines "Pixel" durch den übergeordneten User‑Agent zurück. Für Anzeigegeräte entspricht dies idealerweise einem physischen Bildschirm‑Pixel. Für andere Geräte oder Umgebungen, in denen die physischen Pixelgrößen nicht bekannt sind, kann stattdessen ein Algorithmus verwendet werden, der der CSS2‑Definition eines "Pixels" ähnelt. Hinweis: Es wird null zurückgegeben, wenn dieses Element nicht im Dokumentbaum verankert ist. Diese Methode hätte besser getClientCTM heißen können, aber der Name getScreenCTM wird aus historischen Gründen beibehalten. |
| [GetTotalLength](../../aspose.svg/svggeometryelement/gettotallength/)() | Gibt den vom User‑Agent berechneten Wert für die Gesamtlänge des Pfads zurück, wobei der distance‑along‑a‑path‑Algorithmus des User‑Agents verwendet wird, als Distanz im aktuellen Benutzerkoordinatensystem. |
| [HasAttribute](../../aspose.svg.dom/element/hasattribute/)(*string*) | Gibt true zurück, wenn ein Attribut mit dem angegebenen Namen an diesem Element festgelegt ist oder einen Standardwert hat, andernfalls false. |
| [HasAttributeNS](../../aspose.svg.dom/element/hasattributens/)(*string, string*) | Gibt true zurück, wenn ein Attribut mit dem angegebenen lokalen Namen und Namespace‑URI an diesem Element festgelegt ist oder einen Standardwert hat, andernfalls false. |
| [HasAttributes](../../aspose.svg.dom/element/hasattributes/)() | Gibt zurück, ob dieser Knoten (falls er ein Element ist) Attribute besitzt |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Gibt einen booleschen Wert zurück, der angibt, ob der gegebene [`Node`](../../aspose.svg.dom/node/) Kindknoten hat oder nicht. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | Fügt den Knoten vor dem vorhandenen Kindknoten child ein. Wenn child null ist, wird der Knoten am Ende der Kindliste eingefügt. Wenn child ein DocumentFragment-Objekt ist, werden all seine Kinder in derselben Reihenfolge vor child eingefügt. Wenn das Kind bereits im Baum ist, wird es zuerst entfernt. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Diese Methode prüft, ob das angegebene namespaceURI der Standardsnamensraum ist oder nicht. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../../aspose.svg.dom/node/)*) | Testet, ob zwei Knoten gleich sind. Diese Methode prüft die Gleichheit von Knoten, nicht die Identität (d. h., ob die beiden Knoten Referenzen auf dasselbe Objekt sind), was mit Node.isSameNode() getestet werden kann. Alle Knoten, die identisch sind, sind auch gleich, obwohl das Gegenteil nicht unbedingt zutrifft. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../../aspose.svg.dom/node/)*) | Die Methode ist ein veralteter Alias für den strikten Gleichheitsoperator ===. Das heißt, sie prüft, ob zwei Knoten identisch sind (mit anderen Worten, ob sie auf dasselbe Objekt verweisen). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Sucht die dem angegebenen Präfix zugeordnete Namespace-URI, beginnend bei diesem Knoten. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Sucht das dem angegebenen Namespace-URI zugeordnete Präfix, beginnend bei diesem Knoten. Die Deklarationen des Standardnamensraums werden von dieser Methode ignoriert. Siehe Namespace Prefix Lookup für Details zum von dieser Methode verwendeten Algorithmus. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Setzt alle Textknoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine "normale" Form, bei der nur die Struktur (z. B. Elemente, Kommentare, Verarbeitungsanweisungen, CDATA-Abschnitte und Entity-Referenzen) Textknoten trennt, d. h. es gibt weder benachbarte Textknoten noch leere Textknoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM-Ansicht eines Dokuments dieselbe ist, als wäre sie gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen (wie XPointer [XPointer]-Nachschlagen), die von einer bestimmten Dokumentbaumstruktur abhängen, verwendet werden sollen. Wenn der Parameter "normalize-characters" des DOMConfiguration-Objekts, das an Node.ownerDocument angehängt ist, true ist, normalisiert diese Methode auch vollständig die Zeichen der Textknoten. |
| [QuerySelector](../../aspose.svg.dom/element/queryselector/)(*string*) | Gibt das erste Element im Dokument zurück, das dem Selektor entspricht |
| [QuerySelectorAll](../../aspose.svg.dom/element/queryselectorall/)(*string*) | Gibt eine NodeList aller Elemente im Dokument zurück, die dem Selektor entsprechen |
| [Remove](../../aspose.svg.dom/element/remove/)() | Entfernt diese Instanz. |
| [RemoveAttribute](../../aspose.svg.dom/element/removeattribute/)(*string*) | Entfernt ein Attribut nach Namen. |
| [RemoveAttributeNode](../../aspose.svg.dom/element/removeattributenode/)(*[Attr](../../aspose.svg.dom/attr/)*) | Entfernt den angegebenen Attributknoten. |
| [RemoveAttributeNS](../../aspose.svg.dom/element/removeattributens/)(*string, string*) | Entfernt ein Attribut nach lokalem Namen und Namespace‑URI. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../../aspose.svg.dom/node/)*) | Entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Diese Methode ermöglicht das Entfernen von Event‑Listenern vom Event‑Ziel. Wenn ein [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Event‑Listener können nach ihrer Entfernung niemals mehr aufgerufen werden. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | Ersetzt den Kindknoten oldChild durch newChild in der Kindliste und gibt den alten oldChild‑Knoten zurück. Wenn newChild ein DocumentFragment‑Objekt ist, wird oldChild durch alle Kinder des DocumentFragment ersetzt, die in derselben Reihenfolge eingefügt werden. Wenn newChild bereits im Baum ist, wird es zuerst entfernt. |
| [SetAttribute](../../aspose.svg.dom/element/setattribute/)(*string, string*) | Fügt ein neues Attribut hinzu. Wenn bereits ein Attribut mit diesem Namen im Element vorhanden ist, wird sein Wert auf den des value‑Parameters geändert. |
| [SetAttributeNode](../../aspose.svg.dom/element/setattributenode/)(*[Attr](../../aspose.svg.dom/attr/)*) | Fügt einen neuen Attributknoten hinzu. Wenn bereits ein Attribut mit diesem Namen (nodeName) im Element vorhanden ist, wird es durch das neue ersetzt. |
| [SetAttributeNodeNS](../../aspose.svg.dom/element/setattributenodens/)(*[Attr](../../aspose.svg.dom/attr/)*) | Fügt ein neues Attribut hinzu. Wenn bereits ein Attribut mit diesem lokalen Namen und diesem Namespace‑URI im Element vorhanden ist, wird es durch das neue ersetzt. |
| [SetAttributeNS](../../aspose.svg.dom/element/setattributens/)(*string, string, string*) | Fügt ein neues Attribut hinzu. Wenn bereits ein Attribut mit demselben lokalen Namen und Namespace‑URI im Element vorhanden ist, wird sein Präfix auf den Präfixteil des qualifiedName geändert und sein Wert auf den value‑Parameter gesetzt. |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/)(*string*) | Wenn force nicht angegeben ist, wird qualifiedName „gewechselt“, d.h. entfernt, falls es vorhanden ist, und hinzugefügt, falls es nicht vorhanden ist. Ist force true, wird qualifiedName hinzugefügt. Ist force false, wird qualifiedName entfernt. |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/)(*string, bool*) | Wenn force nicht angegeben ist, wird qualifiedName „gewechselt“, d.h. entfernt, falls es vorhanden ist, und hinzugefügt, falls es nicht vorhanden ist. Ist force true, wird qualifiedName hinzugefügt. Ist force false, wird qualifiedName entfernt. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [SVGGraphicsElement](../svggraphicselement/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
