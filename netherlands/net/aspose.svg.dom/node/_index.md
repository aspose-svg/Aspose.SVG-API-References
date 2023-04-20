---
title: Class Node
second_title: Aspose.SVG voor .NET API-referentie
description: Aspose.Svg.Dom.Node klas. De Nodeinterface is het primaire datatype voor het gehele documentobjectmodel. Het vertegenwoordigt een enkel knooppunt in de documentstructuur.
type: docs
weight: 1150
url: /nl/net/aspose.svg.dom/node/
---
## Node class

De Node-interface is het primaire datatype voor het gehele documentobjectmodel. Het vertegenwoordigt een enkel knooppunt in de documentstructuur.

```csharp
public abstract class Node : EventTarget, IXPathNSResolver
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes/) { get; } | Een NamedNodeMap met de attributen van dit knooppunt (als het een Element is) of anders nul. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | De absolute basis-URI van dit knooppunt of null als de implementatie geen absolute URI kon verkrijgen. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Een NodeList die alle kinderen van deze node bevat. Als er geen kinderen zijn, is dit een NodeList die geen nodes bevat.. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Het eerste kind van dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Het laatste kind van dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Retourneert het lokale deel van de gekwalificeerde naam van dit knooppunt. Voor knooppunten van een ander type dan ELEMENT_NODE en ATTRIBUTE_NODE en knooppunten gemaakt met een DOM Level 1-methode, zoals Document.createElement(), is dit altijd null. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | De naamruimte-URI van dit knooppunt, of null als deze niet is gespecificeerd. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Het knooppunt dat onmiddellijk volgt op dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| abstract [NodeName](../../aspose.svg.dom/node/nodename/) { get; } | De naam van dit knooppunt, afhankelijk van het type. |
| abstract [NodeType](../../aspose.svg.dom/node/nodetype/) { get; } | Een code die het type van het onderliggende object vertegenwoordigt. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | De waarde van dit knooppunt, afhankelijk van het type. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Het documentobject dat aan dit knooppunt is gekoppeld. Dit is ook het documentobject dat wordt gebruikt om nieuwe knooppunten te maken. Als dit knooppunt een document is of een documenttype dat nog niet met een document wordt gebruikt, is dit null. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Haalt de ouder op[`Element`](../element/) van dit knooppunt. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | De ouder van dit knooppunt. Alle knooppunten, behalve Attr, Document, DocumentFragment, Entity en Notation kunnen een ouder hebben. Als een knooppunt echter net is gemaakt en nog niet aan de boom is toegevoegd, of als het uit de boom is verwijderd, is dit null. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Het naamruimtevoorvoegsel van dit knooppunt, of null als het niet is gespecificeerd. Als het is gedefinieerd als null, heeft het instellen ervan geen effect |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Het knooppunt dat onmiddellijk aan dit knooppunt voorafgaat. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Dit attribuut retourneert de tekstinhoud van dit knooppunt en zijn afstammelingen. Als het is gedefinieerd als null, heeft het instellen ervan geen effect. Bij het instellen worden alle mogelijke kinderen die dit knooppunt heeft verwijderd en, als de nieuwe tekenreeks niet leeg of null is, vervangen door een enkel tekstknooppunt dat de tekenreeks bevat waarop dit kenmerk is ingesteld. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(Node) | Voegt het knooppunt newChild toe aan het einde van de lijst met kinderen van dit knooppunt. Als de newChild al in de stamboom staat, wordt deze eerst verwijderd. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/#clonenode)() | Retourneert een duplicaat van dit knooppunt, dwz dient als generieke kopieerconstructor voor knooppunten. Het gedupliceerde knooppunt heeft geen ouder (parentNode is null) en geen gebruikersgegevens. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/#clonenode_1)(bool) | Retourneert een duplicaat van dit knooppunt, dwz dient als generieke kopieerconstructor voor knooppunten. Het gedupliceerde knooppunt heeft geen ouder (parentNode is null) en geen gebruikersgegevens. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(Event) | Met deze methode kunnen gebeurtenissen worden verzonden naar het gebeurtenismodel van de implementatie. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijmaken, vrijgeven of resetten van onbeheerde bronnen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes/)() | Geeft terug of dit knooppunt (als het een element is) attributen heeft |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Geeft terug of dit knooppunt kinderen heeft. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(Node, Node) | Voegt het knooppunt in vóór het bestaande onderliggende knooppunt. Als kind null is, voegt u een knooppunt in aan het einde van de lijst met kinderen. Als kind een DocumentFragment-object is, worden alle kinderen in dezelfde volgorde ingevoegd vóór kind. Als het kind al in de boom zit, wordt het eerst verwijderd. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(string) | Deze methode controleert of de opgegeven naamruimte-URI de standaard naamruimte is of niet. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(Node) | Test of twee knooppunten gelijk zijn. Deze methode test op gelijkheid van knooppunten, niet gelijkheid (dwz of de twee knooppunten verwijzingen naar hetzelfde object zijn), wat kan worden getest met Node.isSameNode(). Alle knooppunten die hetzelfde zijn, zullen ook gelijk zijn, hoewel het omgekeerde misschien niet waar is. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(Node) | Geeft terug of dit knooppunt hetzelfde knooppunt is als het opgegeven knooppunt. Deze methode biedt een manier om te bepalen of twee Node-referenties die door de implementatie worden geretourneerd, naar hetzelfde object verwijzen. Wanneer twee Node-referenties verwijzingen zijn naar hetzelfde object, zelfs via een proxy, kunnen de referenties volledig onderling uitwisselbaar worden gebruikt, zodat alle attributen dezelfde waarden hebben en het aanroepen van dezelfde DOM-methode voor beide referenties altijd exact hetzelfde effect heeft. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(string) | Zoek de naamruimte-URI op die is gekoppeld aan het opgegeven voorvoegsel, beginnend vanaf dit knooppunt. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(string) | Zoek het voorvoegsel op dat is gekoppeld aan de opgegeven naamruimte-URI, beginnend bij dit knooppunt. De standaard naamruimtedeclaraties worden door deze methode genegeerd. Zie Namespace Prefix Lookup voor meer informatie over het algoritme dat door deze methode wordt gebruikt. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Zet alle tekstknooppunten in de volledige diepte van de subboom onder dit knooppunt, inclusief attribuutknooppunten, in een "normale" vorm waar alleen structuur (bijv. elementen, opmerkingen, verwerkingsinstructies, CDATA-secties en entiteitsreferenties) tekst scheidt knooppunten, dwz er zijn geen aangrenzende tekstknooppunten of lege tekstknooppunten. Dit kan worden gebruikt om ervoor te zorgen dat de DOM-weergave van een document hetzelfde is alsof het is opgeslagen en opnieuw geladen, en is handig wanneer bewerkingen (zoals XPointer [XPointer]-lookups) die afhankelijk zijn van een bepaalde documentboomstructuur, moeten worden uitgevoerd. worden gebruikt. Als de parameter "normalize-characters" van het DOMConfiguration-object dat aan het Node.ownerDocument is gekoppeld, waar is, zal deze methode ook de tekens van de tekstknooppunten volledig normaliseren. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(Node) | Verwijdert het onderliggende knooppunt aangegeven door oldChild uit de lijst met onderliggende items en retourneert het. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(Node, Node) | Vervangt het onderliggende knooppunt oldChild door newChild in de lijst met onderliggende items en retourneert het oldChild-knooppunt. Als newChild een DocumentFragment-object is, wordt oldChild vervangen door alle DocumentFragment-kinderen, die in dezelfde volgorde worden ingevoegd. Als de newChild al in de stamboom staat, wordt deze eerst verwijderd. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [ATTRIBUTE_NODE](../../aspose.svg.dom/node/attribute_node/) | Een attribuut node |
| const [CDATA_SECTION_NODE](../../aspose.svg.dom/node/cdata_section_node/) | Een cdata sectie node |
| const [COMMENT_NODE](../../aspose.svg.dom/node/comment_node/) | Een commentaar node |
| const [DOCUMENT_FRAGMENT_NODE](../../aspose.svg.dom/node/document_fragment_node/) | Een documentfragment node |
| const [DOCUMENT_NODE](../../aspose.svg.dom/node/document_node/) | Een documentknooppunt |
| const [DOCUMENT_TYPE_NODE](../../aspose.svg.dom/node/document_type_node/) | Een documenttype node |
| const [ELEMENT_NODE](../../aspose.svg.dom/node/element_node/) | Een element node |
| const [ENTITY_NODE](../../aspose.svg.dom/node/entity_node/) | Een entiteitsknooppunt |
| const [ENTITY_REFERENCE_NODE](../../aspose.svg.dom/node/entity_reference_node/) | Een entiteitsreferentieknooppunt |
| const [NOTATION_NODE](../../aspose.svg.dom/node/notation_node/) | Een notatie node |
| const [PROCESSING_INSTRUCTION_NODE](../../aspose.svg.dom/node/processing_instruction_node/) | Een verwerkingsinstructie node |
| const [TEXT_NODE](../../aspose.svg.dom/node/text_node/) | Een tekstknooppunt |

### Zie ook

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)
* naamruimte [Aspose.Svg.Dom](../../aspose.svg.dom/)
* montage [Aspose.SVG](../../)


