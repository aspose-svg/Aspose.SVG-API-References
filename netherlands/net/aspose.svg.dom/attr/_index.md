---
title: "Attr Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Attr klasse. De Attr interface vertegenwoordigt een attribuut in een Element-object. Typisch worden de toegestane waarden voor het attribuut gedefinieerd in een schema dat aan het document is gekoppeld"
type: docs
weight: 2350
url: /nl/net/aspose.svg.dom/attr/
---
## Attr class

De Attr interface vertegenwoordigt een attribuut in een Element-object. Typisch worden de toegestane waarden voor het attribuut gedefinieerd in een schema dat aan het document is gekoppeld.

```csharp
public sealed class Attr : Node
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Retourneert de absolute basis-URL van het document dat de node bevat. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Retourneert een live [`NodeList`](../../aspose.svg.collections/nodelist/) van kindknooppunten van het opgegeven element waarbij het eerste kindknooppunt index 0 krijgt. Kindknooppunten omvatten elementen, tekst en commentaren. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Retourneert het eerste kind van de node in de boom, of null als de node geen kinderen heeft. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Retourneert het laatste kind van de node. Als de ouder een element is, is het kind doorgaans een elementknooppunt, een tekstknooppunt of een commentaarknooppunt. Het retourneert null als er geen kindelementen zijn. |
| override [LocalName](../../aspose.svg.dom/attr/localname/) { get; } | Retourneert het lokale deel van de gekwalificeerde naam van deze node. Voor knooppunten van elk type anders dan ELEMENT_NODE en ATTRIBUTE_NODE en knooppunten die zijn gemaakt met een DOM Level 1-methode, zoals Document.createElement(), is dit altijd null. |
| [Name](../../aspose.svg.dom/attr/name/) { get; } | Retourneert de naam van dit attribuut. |
| override [NamespaceURI](../../aspose.svg.dom/attr/namespaceuri/) { get; } | De namespace-URI van deze node, of null als deze niet is gespecificeerd. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Retourneert het knooppunt dat direct volgt op het opgegeven knooppunt in de ouder's [`ChildNodes`](../node/childnodes/), of retourneert null als het opgegeven knooppunt het laatste kind is in het bovenliggende element. |
| override [NodeName](../../aspose.svg.dom/attr/nodename/) { get; } | De naam van dit knooppunt, afhankelijk van het type. |
| override [NodeType](../../aspose.svg.dom/attr/nodetype/) { get; } | Een code die het type van het onderliggende object vertegenwoordigt. |
| override [NodeValue](../../aspose.svg.dom/attr/nodevalue/) { get; set; } | De waarde van dit knooppunt, afhankelijk van het type. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Retourneert het bovenliggende documentobject van het knooppunt. |
| [OwnerElement](../../aspose.svg.dom/attr/ownerelement/) { get; } | Het Element-knooppunt waaraan dit attribuut is gekoppeld of null als dit attribuut niet in gebruik is. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Retourneert de ouder van het DOM-knooppunt [`Element`](../element/), of null als het knooppunt geen ouder heeft, of als de ouder geen DOM-Element is. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Retourneert de ouder van het opgegeven knooppunt in de DOM-boom. |
| override [Prefix](../../aspose.svg.dom/attr/prefix/) { get; } | Het namespace-voorvoegsel van dit knooppunt, of null als het niet is gespecificeerd. Wanneer het is gedefinieerd als null, heeft het instellen ervan geen effect |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Retourneert het knooppunt dat direct voorafgaat aan het opgegeven knooppunt in de [`ChildNodes`](../node/childnodes/) lijst van de ouder, of null als het opgegeven knooppunt het eerste in die lijst is. |
| [Specified](../../aspose.svg.dom/attr/specified/) { get; } | Waar als dit attribuut expliciet een waarde kreeg in het instantiedocument, onwaar anders. |
| override [TextContent](../../aspose.svg.dom/attr/textcontent/) { get; set; } | Dit attribuut retourneert de tekstinhoud van dit knooppunt en zijn afstammelingen. Wanneer het is gedefinieerd als null, heeft het instellen ervan geen effect. Bij het instellen worden eventuele kinderen die dit knooppunt kan hebben verwijderd en, als de nieuwe tekenreeks niet leeg of null is, vervangen door één enkel Text-knooppunt dat de tekenreeks bevat waar dit attribuut op wordt gezet. |
| [Value](../../aspose.svg.dom/attr/value/) { get; set; } | Bij het ophalen wordt de waarde van het attribuut geretourneerd als een tekenreeks. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Voegt een knooppunt toe aan het einde van de lijst met kinderen van een opgegeven ouderknooppunt. Als het opgegeven kind een verwijzing is naar een bestaand knooppunt in het document, verplaatst [`AppendChild`](../node/appendchild/) het van zijn huidige positie naar de nieuwe positie (er is geen vereiste om het knooppunt uit zijn ouderknooppunt te verwijderen voordat het aan een ander knooppunt wordt toegevoegd). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen. De parameter bepaalt of de in een knooppunt aanwezige subboom ook wordt gekloond al dan niet. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Verzendt een Event naar het opgegeven [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor eventverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Retourneert een booleaanse waarde die aangeeft of het gegeven [`Node`](../node/) kindknooppunten heeft of niet. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Voegt het knooppunt in vóór het bestaande kindknooppunt child. Als child null is, wordt het knooppunt aan het einde van de lijst met kinderen ingevoegd. Als child een DocumentFragment-object is, worden al zijn kinderen, in dezelfde volgorde, vóór child ingevoegd. Als het kind al in de boom aanwezig is, wordt het eerst verwijderd. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Deze methode controleert of de opgegeven namespaceURI de standaardnamespace is of niet. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Test of twee knooppunten gelijk zijn. Deze methode test op gelijkheid van knooppunten, niet op identiek zijn (d.w.z. of de twee knooppunten verwijzingen naar hetzelfde object zijn), wat kan worden getest met Node.isSameNode(). Alle knooppunten die identiek zijn, zijn ook gelijk, hoewel het omgekeerde niet altijd waar is. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Methode is een verouderde alias voor de === strikte gelijkheidsoperator. Dat wil zeggen, het test of twee knooppunten identiek zijn (met andere woorden, of ze naar hetzelfde object verwijzen). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Zoek de namespace-URI die aan het opgegeven voorvoegsel is gekoppeld, beginnend bij dit knooppunt. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Zoek het voorvoegsel dat aan de opgegeven namespace-URI is gekoppeld, beginnend bij dit knooppunt. De standaardnamespace-declaraties worden door deze methode genegeerd. Zie Namespace Prefix Lookup voor details over het algoritme dat door deze methode wordt gebruikt. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Doe alle Text-knooppunten op de volledige diepte van de subboom onder dit Node, inclusief attribuutknooppunten, in een "normale" vorm waarbij alleen de structuur (bijv. elementen, opmerkingen, verwerkingsinstructies, CDATA-secties en entiteitsreferenties) Text-knooppunten scheidt, d.w.z. er zijn geen aangrenzende Text-knooppunten noch lege Text-knooppunten. Dit kan worden gebruikt om te garanderen dat de DOM-weergave van een document hetzelfde is als wanneer het zou worden opgeslagen en opnieuw geladen, en is nuttig wanneer bewerkingen (zoals XPointer [XPointer] opzoekingen) die afhankelijk zijn van een specifieke documentboomstructuur moeten worden gebruikt. Als de parameter "normalize-characters" van het DOMConfiguration-object dat is gekoppeld aan Node.ownerDocument waar is, normaliseert deze methode ook volledig de tekens van de Text-knooppunten. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Vervangt het kindknooppunt oldChild door newChild in de lijst van kinderen, en retourneert het oldChild-knooppunt. Als newChild een DocumentFragment-object is, wordt oldChild vervangen door alle kinderen van de DocumentFragment, die in dezelfde volgorde worden ingevoegd. Als newChild al in de boom aanwezig is, wordt het eerst verwijderd. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

### Zie ook

* class [Node](../node/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
