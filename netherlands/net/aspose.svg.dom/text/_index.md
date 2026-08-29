---
title: "Tekstklasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Text klasse. De Text-interface erft van CharacterData en vertegenwoordigt de tekstuele inhoud, aangeduid als character data, in XML van een Element of Attr."
type: docs
weight: 3200
url: /nl/net/aspose.svg.dom/text/
---
## Text class

De Text‑interface erft van CharacterData en stelt de tekstuele inhoud (in XML aangeduid als character data) van een Element of Attr voor.

```csharp
public class Text : CharacterData
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Retourneert de absolute basis-URL van het document dat de node bevat. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Retourneert een live [`NodeList`](../../aspose.svg.collections/nodelist/) van kindknooppunten van het opgegeven element waarbij het eerste kindknooppunt index 0 krijgt. Kindknooppunten omvatten elementen, tekst en commentaren. |
| virtual [Data](../../aspose.svg.dom/characterdata/data/) { get; set; } | De character data van het knooppunt dat deze interface implementeert. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Retourneert het eerste kind van de node in de boom, of null als de node geen kinderen heeft. |
| [IsElementContentWhitespace](../../aspose.svg.dom/text/iselementcontentwhitespace/) { get; } | Retourneert of dit tekstknooppunt witruimte bevat die tot elementinhoud behoort, vaak abusief "ignorable whitespace" genoemd. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Retourneert het laatste kind van de node. Als de ouder een element is, is het kind doorgaans een elementknooppunt, een tekstknooppunt of een commentaarknooppunt. Het retourneert null als er geen kindelementen zijn. |
| [Length](../../aspose.svg.dom/characterdata/length/) { get; } | Het aantal 16-bit eenheden dat beschikbaar is via data en de onderstaande substringData-methode. Dit kan de waarde nul hebben, d.w.z. CharacterData-knooppunten kunnen leeg zijn. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Retourneert het lokale deel van de gekwalificeerde naam van dit knooppunt. Voor knooppunten van elk type behalve [`ELEMENT_NODE`](../node/element_node/) en [`ATTRIBUTE_NODE`](../node/attribute_node/) en knooppunten die zijn gemaakt met een DOM Level 1-methode, zoals [`CreateElement`](../document/createelement/), is dit altijd null. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Retourneert de namespace-URI van het element, of null als het element zich niet in een namespace bevindt. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Retourneert het knooppunt dat direct volgt op het opgegeven knooppunt in de ouder's [`ChildNodes`](../node/childnodes/), of retourneert null als het opgegeven knooppunt het laatste kind is in het bovenliggende element. |
| override [NodeName](../../aspose.svg.dom/text/nodename/) { get; } | De naam van dit knooppunt, afhankelijk van het type. |
| override [NodeType](../../aspose.svg.dom/text/nodetype/) { get; } | Een code die het type van het onderliggende object vertegenwoordigt. |
| override [NodeValue](../../aspose.svg.dom/text/nodevalue/) { get; set; } | De waarde van dit knooppunt, afhankelijk van het type. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Retourneert het bovenliggende documentobject van het knooppunt. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Retourneert de ouder van het DOM-knooppunt [`Element`](../element/), of null als het knooppunt geen ouder heeft, of als de ouder geen DOM-Element is. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Retourneert de ouder van het opgegeven knooppunt in de DOM-boom. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Retourneert het namespace-voorvoegsel van het opgegeven element, of null als er geen voorvoegsel is opgegeven. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Retourneert het knooppunt dat direct voorafgaat aan het opgegeven knooppunt in de [`ChildNodes`](../node/childnodes/) lijst van de ouder, of null als het opgegeven knooppunt het eerste in die lijst is. |
| override [TextContent](../../aspose.svg.dom/text/textcontent/) { get; set; } | Dit attribuut retourneert de tekstinhoud van dit knooppunt en zijn afstammelingen. Wanneer het is gedefinieerd als null, heeft het instellen ervan geen effect. Bij het instellen worden eventuele kinderen die dit knooppunt kan hebben verwijderd en, als de nieuwe tekenreeks niet leeg of null is, vervangen door één enkel Text-knooppunt dat de tekenreeks bevat waar dit attribuut op wordt gezet. |
| [WholeText](../../aspose.svg.dom/text/wholetext/) { get; } | Retourneert alle tekst van Text-knooppunten die logisch aangrenzend zijn aan dit knooppunt, aaneengeschakeld in documentvolgorde. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Voegt een knooppunt toe aan het einde van de lijst met kinderen van een opgegeven ouderknooppunt. Als het opgegeven kind een verwijzing is naar een bestaand knooppunt in het document, verplaatst [`AppendChild`](../node/appendchild/) het van zijn huidige positie naar de nieuwe positie (er is geen vereiste om het knooppunt uit zijn ouderknooppunt te verwijderen voordat het aan een ander knooppunt wordt toegevoegd). |
| virtual [AppendData](../../aspose.svg.dom/characterdata/appenddata/)(*string*) | Voeg de tekenreeks toe aan het einde van de character data van het knooppunt. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen. De parameter bepaalt of de in een knooppunt aanwezige subboom ook wordt gekloond al dan niet. |
| virtual [DeleteData](../../aspose.svg.dom/characterdata/deletedata/)(*int, int*) | Verwijder een bereik van 16-bit eenheden van het knooppunt. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Verzendt een Event naar het opgegeven [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor eventverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Retourneert een booleaanse waarde die aangeeft of het gegeven [`Node`](../node/) kindknooppunten heeft of niet. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Voegt het knooppunt in vóór het bestaande kindknooppunt child. Als child null is, wordt het knooppunt aan het einde van de lijst met kinderen ingevoegd. Als child een DocumentFragment-object is, worden al zijn kinderen, in dezelfde volgorde, vóór child ingevoegd. Als het kind al in de boom aanwezig is, wordt het eerst verwijderd. |
| virtual [InsertData](../../aspose.svg.dom/characterdata/insertdata/)(*int, string*) | Voeg een tekenreeks in op de opgegeven 16-bit eenheidsoffset. |
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
| virtual [ReplaceData](../../aspose.svg.dom/characterdata/replacedata/)(*int, int, string*) | Vervang de tekens beginnend op de opgegeven 16-bit eenheidsoffset door de opgegeven tekenreeks. |
| [ReplaceWholeText](../../aspose.svg.dom/text/replacewholetext/)(*string*) | Vervangt de tekst van het huidige knooppunt en alle logisch aangrenzende tekstknooppunten door de opgegeven tekst. Alle logisch aangrenzende tekstknooppunten worden verwijderd, inclusief het huidige knooppunt, tenzij het de ontvanger van de vervangende tekst was. |
| [SplitText](../../aspose.svg.dom/text/splittext/)(*int*) | Splitst dit knooppunt in twee knooppunten op de opgegeven offset, waarbij beide als broers in de boom blijven. |
| virtual [SubstringData](../../aspose.svg.dom/characterdata/substringdata/)(*int, int*) | Extraheert een bereik aan gegevens uit het knooppunt. |
| override [ToString](../../aspose.svg.dom/characterdata/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

### Zie ook

* class [CharacterData](../characterdata/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
