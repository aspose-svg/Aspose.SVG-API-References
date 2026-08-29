---
title: "Elementklasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Element class. De Element‑interface vertegenwoordigt een element in een HTML‑ of XML‑document."
type: docs
weight: 2840
url: /nl/net/aspose.svg.dom/element/
---
## Element class

De Element interface vertegenwoordigt een element in een HTML- of XML-document.

```csharp
public class Element : Node, IChildNode, IParentNode
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Element](element/)(*[QualifiedName](../qualifiedname/), [Document](../document/)*) | Initialiseert een nieuw exemplaar van de `Element`‑klasse. Roep deze constructor niet direct aan, gebruik [`CreateElement`](../document/createelement/) of [`CreateElementNS`](../document/createelementns/). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Attributes](../../aspose.svg.dom/element/attributes/) { get; } | Een NamedNodeMap die de attributen van dit knooppunt bevat (als het een Element is) of anders null. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Retourneert de absolute basis-URL van het document dat de node bevat. |
| [ChildElementCount](../../aspose.svg.dom/element/childelementcount/) { get; } | Geeft het huidige aantal elementknooppunten terug die kinderen zijn van dit element. 0 als dit element geen kindknooppunten heeft van nodeType 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Retourneert een live [`NodeList`](../../aspose.svg.collections/nodelist/) van kindknooppunten van het opgegeven element waarbij het eerste kindknooppunt index 0 krijgt. Kindknooppunten omvatten elementen, tekst en commentaren. |
| [Children](../../aspose.svg.dom/element/children/) { get; } | Retourneert de kindelementen van het huidige element. |
| [ClassList](../../aspose.svg.dom/element/classlist/) { get; } | Retourneert een live DOMTokenList die tokens bevat die zijn verkregen door het parseren van het "class"‑attribuut. |
| [ClassName](../../aspose.svg.dom/element/classname/) { get; set; } | Het class‑attribuut van het element. Dit attribuut is hernoemd vanwege conflicten met het "class"‑trefwoord dat door veel talen wordt blootgesteld. Zie de definitie van het class‑attribuut in HTML 4.01. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Retourneert het eerste kind van de node in de boom, of null als de node geen kinderen heeft. |
| [FirstElementChild](../../aspose.svg.dom/element/firstelementchild/) { get; } | Geeft het eerste kind‑elementknooppunt van dit element terug. null als dit element geen kind‑elementen heeft. |
| [Id](../../aspose.svg.dom/element/id/) { get; set; } | De identifier van het element. Zie de definitie van het id‑attribuut in HTML 4.01. |
| [InnerHTML](../../aspose.svg.dom/element/innerhtml/) { get; set; } | Retourneert een fragment van HTML of XML dat de inhoud van het element weergeeft. Kan worden ingesteld om de inhoud van het element te vervangen door knooppunten die uit de opgegeven tekenreeks zijn geparseerd. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Retourneert het laatste kind van de node. Als de ouder een element is, is het kind doorgaans een elementknooppunt, een tekstknooppunt of een commentaarknooppunt. Het retourneert null als er geen kindelementen zijn. |
| [LastElementChild](../../aspose.svg.dom/element/lastelementchild/) { get; } | Retourneert het laatste kind-elementknooppunt van dit element. null als dit element geen kindelementen heeft. |
| override [LocalName](../../aspose.svg.dom/element/localname/) { get; } | Retourneert het lokale deel van de gekwalificeerde naam van deze node. Voor knooppunten van elk type anders dan ELEMENT_NODE en ATTRIBUTE_NODE en knooppunten die zijn gemaakt met een DOM Level 1-methode, zoals Document.createElement(), is dit altijd null. |
| override [NamespaceURI](../../aspose.svg.dom/element/namespaceuri/) { get; } | De namespace-URI van deze node, of null als deze niet is gespecificeerd. |
| [NextElementSibling](../../aspose.svg.dom/element/nextelementsibling/) { get; } | Retourneert het volgende sibling‑elementknooppunt van dit element. null als dit element geen element‑sibling‑knooppunten heeft die na dit knooppunt in de documentboom komen. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Retourneert het knooppunt dat direct volgt op het opgegeven knooppunt in de ouder's [`ChildNodes`](../node/childnodes/), of retourneert null als het opgegeven knooppunt het laatste kind is in het bovenliggende element. |
| override [NodeName](../../aspose.svg.dom/element/nodename/) { get; } | De naam van dit knooppunt, afhankelijk van het type. |
| override [NodeType](../../aspose.svg.dom/element/nodetype/) { get; } | Een code die het type van het onderliggende object vertegenwoordigt. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Retourneert of stelt de waarde van het huidige knooppunt in. |
| [OuterHTML](../../aspose.svg.dom/element/outerhtml/) { get; set; } | Retourneert een fragment van HTML of XML dat het element en de inhoud ervan weergeeft. Kan worden ingesteld om het element te vervangen door knooppunten die uit de opgegeven tekenreeks zijn geparseerd. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Retourneert het bovenliggende documentobject van het knooppunt. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Retourneert de bovenliggende `Element` van het DOM‑knooppunt, of null als het knooppunt geen bovenliggend element heeft, of als de bovenliggende geen DOM‑Element is. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Retourneert de ouder van het opgegeven knooppunt in de DOM-boom. |
| override [Prefix](../../aspose.svg.dom/element/prefix/) { get; } | Het namespace-voorvoegsel van dit knooppunt, of null als het niet is gespecificeerd. Wanneer het is gedefinieerd als null, heeft het instellen ervan geen effect |
| [PreviousElementSibling](../../aspose.svg.dom/element/previouselementsibling/) { get; } | Retourneert het vorige sibling‑elementknooppunt van dit element. null als dit element geen element‑sibling‑knooppunten heeft die vóór dit knooppunt in de documentboom komen. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Retourneert het knooppunt dat direct voorafgaat aan het opgegeven knooppunt in de [`ChildNodes`](../node/childnodes/) lijst van de ouder, of null als het opgegeven knooppunt het eerste in die lijst is. |
| [ShadowRoot](../../aspose.svg.dom/element/shadowroot/) { get; } | Retourneert de shadowRoot die op dit element is opgeslagen, of null als deze gesloten is. |
| [TagName](../../aspose.svg.dom/element/tagname/) { get; } | De naam van het element. |
| override [TextContent](../../aspose.svg.dom/element/textcontent/) { get; set; } | Dit attribuut retourneert de tekstinhoud van dit knooppunt en zijn afstammelingen. Wanneer het is gedefinieerd als null, heeft het instellen ervan geen effect. Bij het instellen worden eventuele kinderen die dit knooppunt kan hebben verwijderd en, als de nieuwe tekenreeks niet leeg of null is, vervangen door één enkel Text-knooppunt dat de tekenreeks bevat waar dit attribuut op wordt gezet. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Voegt een knooppunt toe aan het einde van de lijst met kinderen van een opgegeven ouderknooppunt. Als het opgegeven kind een verwijzing is naar een bestaand knooppunt in het document, verplaatst [`AppendChild`](../node/appendchild/) het van zijn huidige positie naar de nieuwe positie (er is geen vereiste om het knooppunt uit zijn ouderknooppunt te verwijderen voordat het aan een ander knooppunt wordt toegevoegd). |
| [AttachShadow](../../aspose.svg.dom/element/attachshadow/)(*[ShadowRootMode](../shadowrootmode/)*) | Maakt een shadow root aan en koppelt deze aan het huidige element. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen. De parameter bepaalt of de in een knooppunt aanwezige subboom ook wordt gekloond al dan niet. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Verzendt een Event naar het opgegeven [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor eventverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| [GetAttribute](../../aspose.svg.dom/element/getattribute/)(*string*) | Haalt een attribuutwaarde op op basis van de naam. |
| [GetAttributeNames](../../aspose.svg.dom/element/getattributenames/)() | Retourneert de attribuutnamen van het element als een array van strings. Als het element geen attributen heeft, wordt een lege array geretourneerd. |
| [GetAttributeNode](../../aspose.svg.dom/element/getattributenode/)(*string*) | Haalt een attribuutknooppunt op op basis van de naam. |
| [GetAttributeNodeNS](../../aspose.svg.dom/element/getattributenodens/)(*string, string*) | Haalt een Attr‑knooppunt op op basis van de lokale naam en namespace‑URI. |
| [GetAttributeNS](../../aspose.svg.dom/element/getattributens/)(*string, string*) | Haalt een attribuutwaarde op op basis van de lokale naam en namespace‑URI. |
| [GetElementsByClassName](../../aspose.svg.dom/element/getelementsbyclassname/)(*string*) | Retourneert een [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/)‑object dat alle elementen binnen `element` bevat die alle in het argument opgegeven klassen hebben. |
| [GetElementsByTagName](../../aspose.svg.dom/element/getelementsbytagname/)(*string*) | Retourneert een [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/)‑object dat alle `elements` met een opgegeven tag‑naam bevat, in documentvolgorde. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/element/getelementsbytagnamens/)(*string, string*) | Retourneert een [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/)‑object dat alle `elements` met een opgegeven lokale naam en namespace‑URI‑string bevat, in documentvolgorde. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [HasAttribute](../../aspose.svg.dom/element/hasattribute/)(*string*) | Retourneert true wanneer een attribuut met een opgegeven naam op dit element is gespecificeerd of een standaardwaarde heeft, anders false. |
| [HasAttributeNS](../../aspose.svg.dom/element/hasattributens/)(*string, string*) | Retourneert true wanneer een attribuut met een opgegeven lokale naam en namespace-URI is gespecificeerd op dit element of een standaardwaarde heeft, anders false. |
| [HasAttributes](../../aspose.svg.dom/element/hasattributes/)() | Retourneert of dit knooppunt (indien het een element is) attributen heeft. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Retourneert een booleaanse waarde die aangeeft of het gegeven [`Node`](../node/) kindknooppunten heeft of niet. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Voegt het knooppunt in vóór het bestaande kindknooppunt child. Als child null is, wordt het knooppunt aan het einde van de lijst met kinderen ingevoegd. Als child een DocumentFragment-object is, worden al zijn kinderen, in dezelfde volgorde, vóór child ingevoegd. Als het kind al in de boom aanwezig is, wordt het eerst verwijderd. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Deze methode controleert of de opgegeven namespaceURI de standaardnamespace is of niet. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Test of twee knooppunten gelijk zijn. Deze methode test op gelijkheid van knooppunten, niet op identiek zijn (d.w.z. of de twee knooppunten verwijzingen naar hetzelfde object zijn), wat kan worden getest met Node.isSameNode(). Alle knooppunten die identiek zijn, zijn ook gelijk, hoewel het omgekeerde niet altijd waar is. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Methode is een verouderde alias voor de === strikte gelijkheidsoperator. Dat wil zeggen, het test of twee knooppunten identiek zijn (met andere woorden, of ze naar hetzelfde object verwijzen). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Zoek de namespace-URI die aan het opgegeven voorvoegsel is gekoppeld, beginnend bij dit knooppunt. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Zoek het voorvoegsel dat aan de opgegeven namespace-URI is gekoppeld, beginnend bij dit knooppunt. De standaardnamespace-declaraties worden door deze methode genegeerd. Zie Namespace Prefix Lookup voor details over het algoritme dat door deze methode wordt gebruikt. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Doe alle Text-knooppunten op de volledige diepte van de subboom onder dit Node, inclusief attribuutknooppunten, in een "normale" vorm waarbij alleen de structuur (bijv. elementen, opmerkingen, verwerkingsinstructies, CDATA-secties en entiteitsreferenties) Text-knooppunten scheidt, d.w.z. er zijn geen aangrenzende Text-knooppunten noch lege Text-knooppunten. Dit kan worden gebruikt om te garanderen dat de DOM-weergave van een document hetzelfde is als wanneer het zou worden opgeslagen en opnieuw geladen, en is nuttig wanneer bewerkingen (zoals XPointer [XPointer] opzoekingen) die afhankelijk zijn van een specifieke documentboomstructuur moeten worden gebruikt. Als de parameter "normalize-characters" van het DOMConfiguration-object dat is gekoppeld aan Node.ownerDocument waar is, normaliseert deze methode ook volledig de tekens van de Text-knooppunten. |
| [QuerySelector](../../aspose.svg.dom/element/queryselector/)(*string*) | Retourneert het eerste Element in het document dat aan de selector voldoet |
| [QuerySelectorAll](../../aspose.svg.dom/element/queryselectorall/)(*string*) | Retourneert een NodeList van alle Elements in het document die aan de selector voldoen |
| [Remove](../../aspose.svg.dom/element/remove/)() | Verwijdert deze instantie. |
| [RemoveAttribute](../../aspose.svg.dom/element/removeattribute/)(*string*) | Verwijdert een attribuut op naam. |
| [RemoveAttributeNode](../../aspose.svg.dom/element/removeattributenode/)(*[Attr](../attr/)*) | Verwijdert het opgegeven attribuutknooppunt. |
| [RemoveAttributeNS](../../aspose.svg.dom/element/removeattributens/)(*string, string*) | Verwijdert een attribuut op lokale naam en namespace-URI. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Vervangt het kindknooppunt oldChild door newChild in de lijst van kinderen, en retourneert het oldChild-knooppunt. Als newChild een DocumentFragment-object is, wordt oldChild vervangen door alle kinderen van de DocumentFragment, die in dezelfde volgorde worden ingevoegd. Als newChild al in de boom aanwezig is, wordt het eerst verwijderd. |
| [SetAttribute](../../aspose.svg.dom/element/setattribute/)(*string, string*) | Voegt een nieuw attribuut toe. Als een attribuut met die naam al aanwezig is in het element, wordt de waarde gewijzigd in de waarde van de parameter. |
| [SetAttributeNode](../../aspose.svg.dom/element/setattributenode/)(*[Attr](../attr/)*) | Voegt een nieuw attribuutknooppunt toe. Als een attribuut met die naam (nodeName) al aanwezig is in het element, wordt het vervangen door het nieuwe. |
| [SetAttributeNodeNS](../../aspose.svg.dom/element/setattributenodens/)(*[Attr](../attr/)*) | Voegt een nieuw attribuut toe. Als een attribuut met die lokale naam en die namespace-URI al aanwezig is in het element, wordt het vervangen door het nieuwe. |
| [SetAttributeNS](../../aspose.svg.dom/element/setattributens/)(*string, string, string*) | Voegt een nieuw attribuut toe. Als een attribuut met dezelfde lokale naam en namespace-URI al aanwezig is op het element, wordt het voorvoegsel gewijzigd naar het voorvoegsel van de qualifiedName, en wordt de waarde gewijzigd naar de waardeparameter. |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/#toggleattribute)(*string*) | Als force niet is opgegeven, "schakelt" qualifiedName, verwijdert het als het aanwezig is en voegt het toe als het niet aanwezig is. Als force true is, wordt qualifiedName toegevoegd. Als force false is, wordt qualifiedName verwijderd. |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/#toggleattribute_1)(*string, bool*) | Als force niet is opgegeven, "schakelt" qualifiedName, verwijdert het als het aanwezig is en voegt het toe als het niet aanwezig is. Als force true is, wordt qualifiedName toegevoegd. Als force false is, wordt qualifiedName verwijderd. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

### Zie ook

* class [Node](../node/)
* interface [IChildNode](../ichildnode/)
* interface [IParentNode](../iparentnode/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
