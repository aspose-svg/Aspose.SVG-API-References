---
title: "Node-klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Node class. De Node-interface is het primaire datatype voor het volledige Document-objectmodel. Het vertegenwoordigt een enkele node in de documentboom."
type: docs
weight: 3140
url: /nl/net/aspose.svg.dom/node/
---
## Node class

De Node interface is het primaire datatype voor het volledige Document Object Model. Het vertegenwoordigt een enkele knoop in de documentboom.

```csharp
public abstract class Node : EventTarget, IXPathNSResolver
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Retourneert de absolute basis-URL van het document dat de node bevat. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Retourneert een live [`NodeList`](../../aspose.svg.collections/nodelist/) van kindknooppunten van het opgegeven element waarbij het eerste kindknooppunt index 0 krijgt. Kindknooppunten omvatten elementen, tekst en commentaren. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Retourneert het eerste kind van de node in de boom, of null als de node geen kinderen heeft. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Retourneert het laatste kind van de node. Als de ouder een element is, is het kind doorgaans een elementknooppunt, een tekstknooppunt of een commentaarknooppunt. Het retourneert null als er geen kindelementen zijn. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Retourneert het lokale deel van de gekwalificeerde naam van deze node. Voor nodes van elk type behalve [`ELEMENT_NODE`](./element_node/) en [`ATTRIBUTE_NODE`](./attribute_node/) en nodes die zijn gemaakt met een DOM Level 1-methode, zoals [`CreateElement`](../document/createelement/), is dit altijd null. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Retourneert de namespace-URI van het element, of null als het element zich niet in een namespace bevindt. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Retourneert de node die direct volgt op de opgegeven node in de [`ChildNodes`](./childnodes/) van hun ouder, of retourneert null als de opgegeven node het laatste kind in het bovenliggende element is. |
| abstract [NodeName](../../aspose.svg.dom/node/nodename/) { get; } | Retourneert de naam van de huidige node als een string. |
| abstract [NodeType](../../aspose.svg.dom/node/nodetype/) { get; } | Een code die het type van het onderliggende object vertegenwoordigt. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Retourneert of stelt de waarde van het huidige knooppunt in. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Retourneert het bovenliggende documentobject van het knooppunt. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Retourneert de ouder van het DOM-knooppunt [`Element`](../element/), of null als het knooppunt geen ouder heeft, of als de ouder geen DOM-Element is. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Retourneert de ouder van het opgegeven knooppunt in de DOM-boom. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Retourneert het namespace-voorvoegsel van het opgegeven element, of null als er geen voorvoegsel is opgegeven. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Retourneert de node die direct voorafgaat aan de opgegeven node in de [`ChildNodes`](./childnodes/) lijst van zijn ouder, of null als de opgegeven node de eerste in die lijst is. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Stelt de tekstinhoud van het knooppunt en zijn afstammelingen voor. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*Node*) | Voegt een node toe aan het einde van de lijst met kinderen van een opgegeven bovenliggende node. Als het opgegeven kind een verwijzing is naar een bestaande node in het document, verplaatst [`AppendChild`](./appendchild/) deze van zijn huidige positie naar de nieuwe positie (er is geen vereiste om de node van zijn bovenliggende node te verwijderen voordat hij aan een andere node wordt toegevoegd). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/#clonenode)() | Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/#clonenode_1)(*bool*) | Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen. De parameter bepaalt of de in een knooppunt aanwezige subboom ook wordt gekloond al dan niet. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Verzendt een Event naar het opgegeven [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor eventverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Retourneert een booleaanse waarde die aangeeft of de gegeven `Node` al dan niet child nodes heeft. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*Node, Node*) | Voegt het knooppunt in vóór het bestaande kindknooppunt child. Als child null is, wordt het knooppunt aan het einde van de lijst met kinderen ingevoegd. Als child een DocumentFragment-object is, worden al zijn kinderen, in dezelfde volgorde, vóór child ingevoegd. Als het kind al in de boom aanwezig is, wordt het eerst verwijderd. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Deze methode controleert of de opgegeven namespaceURI de standaardnamespace is of niet. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*Node*) | Test of twee knooppunten gelijk zijn. Deze methode test op gelijkheid van knooppunten, niet op identiek zijn (d.w.z. of de twee knooppunten verwijzingen naar hetzelfde object zijn), wat kan worden getest met Node.isSameNode(). Alle knooppunten die identiek zijn, zijn ook gelijk, hoewel het omgekeerde niet altijd waar is. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*Node*) | Methode is een verouderde alias voor de === strikte gelijkheidsoperator. Dat wil zeggen, het test of twee knooppunten identiek zijn (met andere woorden, of ze naar hetzelfde object verwijzen). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Zoek de namespace-URI die aan het opgegeven voorvoegsel is gekoppeld, beginnend bij dit knooppunt. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Zoek het voorvoegsel dat aan de opgegeven namespace-URI is gekoppeld, beginnend bij dit knooppunt. De standaardnamespace-declaraties worden door deze methode genegeerd. Zie Namespace Prefix Lookup voor details over het algoritme dat door deze methode wordt gebruikt. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Doe alle Text-knooppunten op de volledige diepte van de subboom onder dit Node, inclusief attribuutknooppunten, in een "normale" vorm waarbij alleen de structuur (bijv. elementen, opmerkingen, verwerkingsinstructies, CDATA-secties en entiteitsreferenties) Text-knooppunten scheidt, d.w.z. er zijn geen aangrenzende Text-knooppunten noch lege Text-knooppunten. Dit kan worden gebruikt om te garanderen dat de DOM-weergave van een document hetzelfde is als wanneer het zou worden opgeslagen en opnieuw geladen, en is nuttig wanneer bewerkingen (zoals XPointer [XPointer] opzoekingen) die afhankelijk zijn van een specifieke documentboomstructuur moeten worden gebruikt. Als de parameter "normalize-characters" van het DOMConfiguration-object dat is gekoppeld aan Node.ownerDocument waar is, normaliseert deze methode ook volledig de tekens van de Text-knooppunten. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*Node*) | Verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*Node, Node*) | Vervangt het kindknooppunt oldChild door newChild in de lijst van kinderen, en retourneert het oldChild-knooppunt. Als newChild een DocumentFragment-object is, wordt oldChild vervangen door alle kinderen van de DocumentFragment, die in dezelfde volgorde worden ingevoegd. Als newChild al in de boom aanwezig is, wordt het eerst verwijderd. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [ATTRIBUTE_NODE](../../aspose.svg.dom/node/attribute_node/) | Een attribuutknooppunt |
| const [CDATA_SECTION_NODE](../../aspose.svg.dom/node/cdata_section_node/) | Een CDATA-sectieknooppunt |
| const [COMMENT_NODE](../../aspose.svg.dom/node/comment_node/) | Een commentaarknooppunt |
| const [DOCUMENT_FRAGMENT_NODE](../../aspose.svg.dom/node/document_fragment_node/) | Een documentfragmentknooppunt |
| const [DOCUMENT_NODE](../../aspose.svg.dom/node/document_node/) | Een documentknooppunt |
| const [DOCUMENT_TYPE_NODE](../../aspose.svg.dom/node/document_type_node/) | Een documenttypeknooppunt |
| const [ELEMENT_NODE](../../aspose.svg.dom/node/element_node/) | Een elementknooppunt |
| const [ENTITY_NODE](../../aspose.svg.dom/node/entity_node/) | Een entiteitsknooppunt |
| const [ENTITY_REFERENCE_NODE](../../aspose.svg.dom/node/entity_reference_node/) | Een entiteitsreferentieknooppunt |
| const [NOTATION_NODE](../../aspose.svg.dom/node/notation_node/) | Een notatieknooppunt |
| const [PROCESSING_INSTRUCTION_NODE](../../aspose.svg.dom/node/processing_instruction_node/) | Een verwerkingsinstructieknooppunt |
| const [TEXT_NODE](../../aspose.svg.dom/node/text_node/) | Een tekstknooppunt |

### Zie ook

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
