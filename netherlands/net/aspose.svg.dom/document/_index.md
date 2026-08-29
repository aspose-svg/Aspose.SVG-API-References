---
title: "Documentklasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Document class. Het Document vertegenwoordigt het volledige HTML‑, XML‑ of SVG‑document. Conceptueel is het de wortel van de documentboom en biedt het primaire toegang tot de gegevens van het document."
type: docs
weight: 2810
url: /nl/net/aspose.svg.dom/document/
---
## Document class

De Document vertegenwoordigt het volledige HTML-, XML- of SVG-document. Conceptueel is het de wortel van de documentboom en biedt het primaire toegang tot de gegevens van het document.

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [BaseURI](../../aspose.svg.dom/document/baseuri/) { get; } | De absolute basis‑URI van dit knooppunt of null als de implementatie geen absolute URI kon verkrijgen. |
| [CharacterSet](../../aspose.svg.dom/document/characterset/) { get; } | Haalt de codering van het document op. |
| [Charset](../../aspose.svg.dom/document/charset/) { get; } | Haalt de codering van het document op. |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount/) { get; } | Geeft het huidige aantal elementknooppunten terug die kinderen zijn van dit element. 0 als dit element geen kindknooppunten heeft van nodeType 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Retourneert een live [`NodeList`](../../aspose.svg.collections/nodelist/) van kindknooppunten van het opgegeven element waarbij het eerste kindknooppunt index 0 krijgt. Kindknooppunten omvatten elementen, tekst en commentaren. |
| [Children](../../aspose.svg.dom/document/children/) { get; } | Geeft de onderliggende elementen terug. |
| [ContentType](../../aspose.svg.dom/document/contenttype/) { get; } | Haalt het inhoudstype van het document op. |
| [Context](../../aspose.svg.dom/document/context/) { get; } | Haalt de huidige browse‑context op. |
| [DefaultView](../../aspose.svg.dom/document/defaultview/) { get; } | Het defaultView‑IDL‑attribuut van de Document‑interface moet bij opvragen dit Document‑browse‑context‑WindowProxy‑object retourneren, als dit Document een gekoppelde browse‑context heeft, anders null. |
| [Doctype](../../aspose.svg.dom/document/doctype/) { get; } | De Document Type Declaration die aan dit document is gekoppeld. |
| [DocumentElement](../../aspose.svg.dom/document/documentelement/) { get; } | Dit is een gebruiksgemak‑attribuut dat directe toegang biedt tot het kindknooppunt dat het document‑element van het document is. |
| [DocumentURI](../../aspose.svg.dom/document/documenturi/) { get; } | De locatie van het document of null als ongedefinieerd of als het Document is gemaakt met DOMImplementation.createDocument. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Retourneert het eerste kind van de node in de boom, of null als de node geen kinderen heeft. |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild/) { get; } | Geeft het eerste kind‑elementknooppunt van dit element terug. null als dit element geen kind‑elementen heeft. |
| [Implementation](../../aspose.svg.dom/document/implementation/) { get; } | Het DOMImplementation-object dat dit document verwerkt. |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding/) { get; } | Haalt de codering van het document op. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Retourneert het laatste kind van de node. Als de ouder een element is, is het kind doorgaans een elementknooppunt, een tekstknooppunt of een commentaarknooppunt. Het retourneert null als er geen kindelementen zijn. |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild/) { get; } | Retourneert het laatste kind-elementknooppunt van dit element. null als dit element geen kindelementen heeft. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Retourneert het lokale deel van de gekwalificeerde naam van dit knooppunt. Voor knooppunten van elk type behalve [`ELEMENT_NODE`](../node/element_node/) en [`ATTRIBUTE_NODE`](../node/attribute_node/) en knooppunten die zijn gemaakt met een DOM Level 1-methode, zoals [`CreateElement`](./createelement/), is dit altijd null. |
| [Location](../../aspose.svg.dom/document/location/) { get; } | De locatie van het document. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Retourneert de namespace-URI van het element, of null als het element zich niet in een namespace bevindt. |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling/) { get; } | Retourneert het volgende sibling‑elementknooppunt van dit element. null als dit element geen element‑sibling‑knooppunten heeft die na dit knooppunt in de documentboom komen. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Retourneert het knooppunt dat direct volgt op het opgegeven knooppunt in de ouder's [`ChildNodes`](../node/childnodes/), of retourneert null als het opgegeven knooppunt het laatste kind is in het bovenliggende element. |
| override [NodeName](../../aspose.svg.dom/document/nodename/) { get; } | De naam van dit knooppunt, afhankelijk van het type. |
| override [NodeType](../../aspose.svg.dom/document/nodetype/) { get; } | Een code die het type van het onderliggende object vertegenwoordigt. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Retourneert of stelt de waarde van het huidige knooppunt in. |
| [Origin](../../aspose.svg.dom/document/origin/) { get; } | Haalt de oorsprong van het document op. |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument/) { get; } | Haalt het eigenaar‑document op. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Retourneert de ouder van het DOM-knooppunt [`Element`](../element/), of null als het knooppunt geen ouder heeft, of als de ouder geen DOM-Element is. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Retourneert de ouder van het opgegeven knooppunt in de DOM-boom. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Retourneert het namespace-voorvoegsel van het opgegeven element, of null als er geen voorvoegsel is opgegeven. |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling/) { get; } | Retourneert het vorige sibling‑elementknooppunt van dit element. null als dit element geen element‑sibling‑knooppunten heeft die vóór dit knooppunt in de documentboom komen. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Retourneert het knooppunt dat direct voorafgaat aan het opgegeven knooppunt in de [`ChildNodes`](../node/childnodes/) lijst van de ouder, of null als het opgegeven knooppunt het eerste in die lijst is. |
| [ReadyState](../../aspose.svg.dom/document/readystate/) { get; } | Retourneert de gereedheid van het document. "loading" terwijl het Document laadt, "interactive" zodra het klaar is met parseren maar nog sub‑resources laadt, en "complete" zodra het volledig is geladen. |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking/) { get; set; } | Een attribuut dat aangeeft of foutcontrole wordt afgedwongen of niet. Wanneer ingesteld op false, mag de implementatie elke mogelijke fout niet testen die normaal gedefinieerd is voor DOM‑operaties, en geen DOMException werpen bij DOM‑operaties of fouten melden tijdens het gebruik van Document.normalizeDocument(). In geval van een fout is het gedrag ongedefinieerd. Dit attribuut is standaard true. |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets/) { get; } | Een lijst met alle stijlbladen die expliciet zijn gekoppeld aan of ingebed in een document. Voor HTML‑documenten omvat dit externe stijlbladen, opgenomen via het HTML‑LINK‑element, en inline STYLE‑elementen. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Stelt de tekstinhoud van het knooppunt en zijn afstammelingen voor. |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone/) { get; set; } | Een attribuut dat, als onderdeel van de XML‑declaratie, aangeeft of dit document zelfstandig is. Dit is false wanneer niet gespecificeerd. |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion/) { get; set; } | Een attribuut dat, als onderdeel van de XML‑declaratie, het versienummer van dit document aangeeft. Als er geen declaratie is en dit document de "XML"‑functie ondersteunt, is de waarde "1.0". Als dit document de "XML"‑functie niet ondersteunt, is de waarde altijd null. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Voegt een knooppunt toe aan het einde van de lijst met kinderen van een opgegeven ouderknooppunt. Als het opgegeven kind een verwijzing is naar een bestaand knooppunt in het document, verplaatst [`AppendChild`](../node/appendchild/) het van zijn huidige positie naar de nieuwe positie (er is geen vereiste om het knooppunt uit zijn ouderknooppunt te verwijderen voordat het aan een ander knooppunt wordt toegevoegd). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Retourneert een duplicaat van het knooppunt waarop deze methode werd aangeroepen. De parameter bepaalt of de in een knooppunt aanwezige subboom ook wordt gekloond al dan niet. |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute/)(*string*) | Deze methode maakt een nieuw attribuutknooppunt aan en retourneert het. Het gemaakte object is een knooppunt dat de [`Attr`](../attr/)‑klasse implementeert. De DOM dwingt niet af welk type attributen op deze manier aan een bepaald element kan worden toegevoegd. |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens/)(*string, string*) | Deze methode maakt een nieuw attribuutknooppunt aan en retourneert het. Het gemaakte object is een knooppunt dat de [`Attr`](../attr/)‑klasse implementeert. De DOM dwingt niet af welk type attributen op deze manier aan een bepaald element kan worden toegevoegd. |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection/)(*string*) | Maakt een CDATASection‑knooppunt waarvan de waarde de opgegeven tekenreeks is. |
| [CreateComment](../../aspose.svg.dom/document/createcomment/)(*string*) | Maakt een Comment‑knooppunt aan met de opgegeven tekenreeks. |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment/)() | Maakt een nieuw leeg [`DocumentFragment`](../documentfragment/) aan waarin DOM‑knooppunten kunnen worden toegevoegd om een off‑screen DOM‑boom op te bouwen. |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype/)(*string, string, string, string*) | De methode retourneert een [`DocumentType`](../documenttype/)‑object dat ofwel kan worden gebruikt met [`CreateDocument`](../idomimplementation/createdocument/) bij het aanmaken van een document, of in het document kan worden geplaatst via methoden zoals [`InsertBefore`](../node/insertbefore/) of [`ReplaceChild`](../node/replacechild/). |
| [CreateElement](../../aspose.svg.dom/document/createelement/)(*string*) | Maakt het HTML‑element aan dat wordt gespecificeerd door localName, of een HTMLUnknownElement als localName niet wordt herkend. |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns/)(*string, string*) | Maakt een element aan met de opgegeven gekwalificeerde naam en namespace‑URI. |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference/)(*string*) | Maakt een EntityReference‑object aan. Bovendien, als de verwezen entiteit bekend is, wordt de kindlijst van het EntityReference‑knooppunt gelijkgesteld aan die van het overeenkomstige Entity‑knooppunt. |
| [CreateEvent](../../aspose.svg.dom/document/createevent/)(*string*) | Maakt een [`Event`](../../aspose.svg.dom.events/event/) aan van een type dat door de implementatie wordt ondersteund. |
| [CreateExpression](../../aspose.svg.dom/document/createexpression/)(*string, [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)*) | Maakt een geparseerde XPath-expressie met opgeloste namespaces. Dit is nuttig wanneer een expressie opnieuw zal worden gebruikt in een toepassing, omdat het mogelijk maakt de expressiestring te compileren naar een efficiëntere interne vorm en alle namespace‑prefixen die in de expressie voorkomen vooraf op te lossen. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator)(*[Node](../node/)*) | Maak een nieuwe NodeIterator aan over de subboom die is geworteld in het opgegeven knooppunt. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_1)(*[Node](../node/), long*) | Maak een nieuwe NodeIterator aan over de subboom die is geworteld in het opgegeven knooppunt. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | Maak een nieuwe NodeIterator aan over de subboom die is geworteld in het opgegeven knooppunt. |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver/)(*[Node](../node/)*) | Past elke DOM‑knoop aan om namespaces op te lossen zodat een XPath-expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van de knoop waarin deze in het document verscheen. Deze adapter werkt zoals de DOM Level 3‑methode `lookupNamespaceURI` op knopen bij het oplossen van de namespaceURI van een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de hiërarchie van de knoop op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook de impliciete xml‑prefix correct op. |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction/)(*string, string*) | Maakt een ProcessingInstruction‑knooppunt aan met de opgegeven naam‑ en gegevens‑strings. |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode/)(*string*) | Maakt een Text‑knooppunt aan met de opgegeven tekenreeks. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker)(*[Node](../node/)*) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij de opgegeven knoop. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_1)(*[Node](../node/), long*) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij de opgegeven knoop. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij de opgegeven knoop. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Verzendt een Event naar het opgegeven [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor eventverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| [Evaluate](../../aspose.svg.dom/document/evaluate/)(*string, [Node](../node/), [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/), [XPathResultType](../../aspose.svg.dom.xpath/xpathresulttype/), object*) | Evalueert een XPath-expressiestring en retourneert een resultaat van het opgegeven type indien mogelijk. |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid/)(*string*) | Deze methode retourneert een [`Element`](../element/) object dat het element vertegenwoordigt waarvan de id‑eigenschap overeenkomt met de opgegeven tekenreeks. Aangezien element‑ID's uniek moeten zijn indien opgegeven, zijn ze een handige manier om snel toegang te krijgen tot een specifiek element. |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname/)(*string*) | Deze methode retourneert een array‑achtig object van alle kindelementen die alle opgegeven klassenaam(en) hebben. |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname/)(*string*) | Deze methode retourneert een [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) van elementen met de opgegeven tagnaam. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens/)(*string, string*) | Retourneert een lijst van elementen met de opgegeven tagnaam die tot de opgegeven namespace behoren. Het volledige document wordt doorzocht, inclusief de root‑knoop. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Retourneert een booleaanse waarde die aangeeft of het gegeven [`Node`](../node/) kindknooppunten heeft of niet. |
| [ImportNode](../../aspose.svg.dom/document/importnode/)(*[Node](../node/), bool*) | Importeert een knoop van een ander document naar dit document, zonder de bronknoop uit het oorspronkelijke document te wijzigen of te verwijderen; deze methode maakt een nieuwe kopie van de bronknoop. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Voegt het knooppunt in vóór het bestaande kindknooppunt child. Als child null is, wordt het knooppunt aan het einde van de lijst met kinderen ingevoegd. Als child een DocumentFragment-object is, worden al zijn kinderen, in dezelfde volgorde, vóór child ingevoegd. Als het kind al in de boom aanwezig is, wordt het eerst verwijderd. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Deze methode controleert of de opgegeven namespaceURI de standaardnamespace is of niet. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Test of twee knooppunten gelijk zijn. Deze methode test op gelijkheid van knooppunten, niet op identiek zijn (d.w.z. of de twee knooppunten verwijzingen naar hetzelfde object zijn), wat kan worden getest met Node.isSameNode(). Alle knooppunten die identiek zijn, zijn ook gelijk, hoewel het omgekeerde niet altijd waar is. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Methode is een verouderde alias voor de === strikte gelijkheidsoperator. Dat wil zeggen, het test of twee knooppunten identiek zijn (met andere woorden, of ze naar hetzelfde object verwijzen). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Zoek de namespace-URI die aan het opgegeven voorvoegsel is gekoppeld, beginnend bij dit knooppunt. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Zoek het voorvoegsel dat aan de opgegeven namespace-URI is gekoppeld, beginnend bij dit knooppunt. De standaardnamespace-declaraties worden door deze methode genegeerd. Zie Namespace Prefix Lookup voor details over het algoritme dat door deze methode wordt gebruikt. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate)(*[RequestMessage](../../aspose.svg.net/requestmessage/)*) | Laadt het document op basis van het opgegeven request‑object, waarbij de vorige inhoud wordt vervangen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_8)(*string*) | Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_2)(*[Url](../../aspose.svg/url/)*) | Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_1)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | Laadt het document op basis van het opgegeven request‑object, waarbij de vorige inhoud wordt vervangen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_6)(*Stream, string*) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document start vanaf de huidige positie in de stream. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_4)(*Stream, [Url](../../aspose.svg/url/)*) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document start vanaf de huidige positie in de stream. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_13)(*string, CancellationToken*) | Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_11)(*string, string*) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_9)(*string, [Url](../../aspose.svg/url/)*) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_3)(*[Url](../../aspose.svg/url/), CancellationToken*) | Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_7)(*Stream, string, CancellationToken*) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document start vanaf de huidige positie in de stream. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_5)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document start vanaf de huidige positie in de stream. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_12)(*string, string, CancellationToken*) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_10)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | Laadt het document asynchroon op basis van het opgegeven request‑object. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_6)(*string, CancellationToken*) | Laadt het document asynchroon op de opgegeven Uniform Resource Locator (URL) in de huidige instantie. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_1)(*[Url](../../aspose.svg/url/), CancellationToken*) | Laadt het document asynchroon op de opgegeven Uniform Resource Locator (URL) in de huidige instantie. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_3)(*Stream, string, CancellationToken*) | Laadt het document asynchroon vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_2)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | Laadt het document asynchroon vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_5)(*string, string, CancellationToken*) | Laadt het document asynchroon vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_4)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | Laadt het document asynchroon vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Doe alle Text-knooppunten op de volledige diepte van de subboom onder dit Node, inclusief attribuutknooppunten, in een "normale" vorm waarbij alleen de structuur (bijv. elementen, opmerkingen, verwerkingsinstructies, CDATA-secties en entiteitsreferenties) Text-knooppunten scheidt, d.w.z. er zijn geen aangrenzende Text-knooppunten noch lege Text-knooppunten. Dit kan worden gebruikt om te garanderen dat de DOM-weergave van een document hetzelfde is als wanneer het zou worden opgeslagen en opnieuw geladen, en is nuttig wanneer bewerkingen (zoals XPointer [XPointer] opzoekingen) die afhankelijk zijn van een specifieke documentboomstructuur moeten worden gebruikt. Als de parameter "normalize-characters" van het DOMConfiguration-object dat is gekoppeld aan Node.ownerDocument waar is, normaliseert deze methode ook volledig de tekens van de Text-knooppunten. |
| [QuerySelector](../../aspose.svg.dom/document/queryselector/)(*string*) | Retourneert het eerste Element in het document dat aan de selector voldoet |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall/)(*string*) | Retourneert een NodeList van alle Elements in het document die aan de selector voldoen |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../eventtarget/) terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| virtual [RenderTo](../../aspose.svg.dom/document/renderto/)(*[IDevice](../../aspose.svg.rendering/idevice/)*) | Deze methode wordt gebruikt om de inhoud van het huidige document te renderen naar een opgegeven grafisch apparaat. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Vervangt het kindknooppunt oldChild door newChild in de lijst van kinderen, en retourneert het oldChild-knooppunt. Als newChild een DocumentFragment-object is, wordt oldChild vervangen door alle kinderen van de DocumentFragment, die in dezelfde volgorde worden ingevoegd. Als newChild al in de boom aanwezig is, wordt het eerst verwijderd. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |
| [Write](../../aspose.svg.dom/document/write/)(*params string[]*) | Schrijf een tekenreeks tekst naar een documentstroom die is geopend met open(). Merk op dat de functie een document kan produceren dat niet noodzakelijkerwijs wordt aangestuurd door een DTD en daarom een ongeldig resultaat kan opleveren in de context van het document. |
| [WriteLn](../../aspose.svg.dom/document/writeln/)(*params string[]*) | Schrijf een tekenreeks tekst, gevolgd door een regeleinde‑teken, naar een documentstroom die is geopend met open(). Merk op dat de functie een document kan produceren dat niet noodzakelijkerwijs wordt aangestuurd door een DTD en daarom een ongeldig resultaat kan opleveren in de context van het document. |

## Evenementen

| Naam | Beschrijving |
| --- | --- |
| event [OnAbort](../../aspose.svg.dom/document/onabort/) | Haalt op of stelt de event‑handler in voor het OnAbort‑event. |
| event [OnBlur](../../aspose.svg.dom/document/onblur/) | Haalt op of stelt de event‑handler in voor het OnBlur‑event. |
| event [OnCancel](../../aspose.svg.dom/document/oncancel/) | Haalt op of stelt de event‑handler in voor het OnCancel‑event. |
| event [OnCanplay](../../aspose.svg.dom/document/oncanplay/) | Haalt op of stelt de event‑handler in voor het OnCanplay‑event. |
| event [OnCanPlayThrough](../../aspose.svg.dom/document/oncanplaythrough/) | Haalt op of stelt de event‑handler in voor het OnCanPlayThrough‑event. |
| event [OnChange](../../aspose.svg.dom/document/onchange/) | Haalt op of stelt de event‑handler in voor het OnChange‑event. |
| event [OnClick](../../aspose.svg.dom/document/onclick/) | Haalt op of stelt de event‑handler in voor het OnClick‑event. |
| event [OnCueChange](../../aspose.svg.dom/document/oncuechange/) | Haalt op of stelt de event‑handler in voor het OnCueChange‑event. |
| event [OnDblClick](../../aspose.svg.dom/document/ondblclick/) | Haalt op of stelt de event‑handler in voor het OnDblClick‑event. |
| event [OnDurationChange](../../aspose.svg.dom/document/ondurationchange/) | Haalt op of stelt de event‑handler in voor het OnDurationChange‑event. |
| event [OnEmptied](../../aspose.svg.dom/document/onemptied/) | Haalt op of stelt de event‑handler in voor het OnEmptied‑event. |
| event [OnEnded](../../aspose.svg.dom/document/onended/) | Haalt op of stelt de event‑handler in voor het OnEnded‑event. |
| event [OnError](../../aspose.svg.dom/document/onerror/) | Haalt op of stelt de event‑handler in voor het OnError‑event. |
| event [OnFocus](../../aspose.svg.dom/document/onfocus/) | Haalt op of stelt de eventhandler in voor het OnFocus event. |
| event [OnInput](../../aspose.svg.dom/document/oninput/) | Haalt op of stelt de eventhandler in voor het OnInput event. |
| event [OnInvalid](../../aspose.svg.dom/document/oninvalid/) | Haalt op of stelt de eventhandler in voor het OnInvalid event. |
| event [OnKeyDown](../../aspose.svg.dom/document/onkeydown/) | Haalt op of stelt de eventhandler in voor het OnKeyDown event. |
| event [OnKeyPress](../../aspose.svg.dom/document/onkeypress/) | Haalt op of stelt de eventhandler in voor het OnKeyPress event. |
| event [OnKeyUp](../../aspose.svg.dom/document/onkeyup/) | Haalt op of stelt de eventhandler in voor het OnKeyUp event. |
| event [OnLoad](../../aspose.svg.dom/document/onload/) | Haalt op of stelt de eventhandler in voor het OnLoad event. |
| event [OnLoadedData](../../aspose.svg.dom/document/onloadeddata/) | Haalt op of stelt de eventhandler in voor het OnLoadedData event. |
| event [OnLoadedMetadata](../../aspose.svg.dom/document/onloadedmetadata/) | Haalt op of stelt de eventhandler in voor het OnLoadedMetadata event. |
| event [OnLoadStart](../../aspose.svg.dom/document/onloadstart/) | Haalt op of stelt de eventhandler in voor het OnLoadStart event. |
| event [OnMouseDown](../../aspose.svg.dom/document/onmousedown/) | Haalt op of stelt de eventhandler in voor het OnMouseDown event. |
| event [OnMouseEnter](../../aspose.svg.dom/document/onmouseenter/) | Haalt op of stelt de eventhandler in voor het OnMouseEnter event. |
| event [OnMouseLeave](../../aspose.svg.dom/document/onmouseleave/) | Haalt op of stelt de eventhandler in voor het OnMouseLeave event. |
| event [OnMouseMove](../../aspose.svg.dom/document/onmousemove/) | Haalt op of stelt de eventhandler in voor het OnMouseMove event. |
| event [OnMouseOut](../../aspose.svg.dom/document/onmouseout/) | Haalt op of stelt de eventhandler in voor het OnMouseOut event. |
| event [OnMouseOver](../../aspose.svg.dom/document/onmouseover/) | Haalt op of stelt de eventhandler in voor het OnMouseOver event. |
| event [OnMouseUp](../../aspose.svg.dom/document/onmouseup/) | Haalt op of stelt de eventhandler in voor het OnMouseUp event. |
| event [OnMouseWheel](../../aspose.svg.dom/document/onmousewheel/) | Haalt op of stelt de eventhandler in voor het OnMouseWheel event. |
| event [OnPause](../../aspose.svg.dom/document/onpause/) | Haalt op of stelt de eventhandler in voor het OnPause event. |
| event [OnPlay](../../aspose.svg.dom/document/onplay/) | Haalt op of stelt de eventhandler in voor het OnPlay event. |
| event [OnPlaying](../../aspose.svg.dom/document/onplaying/) | Haalt op of stelt de eventhandler in voor het OnPlaying event. |
| event [OnProgress](../../aspose.svg.dom/document/onprogress/) | Haalt op of stelt de eventhandler in voor het OnProgress event. |
| event [OnRateChange](../../aspose.svg.dom/document/onratechange/) | Haalt op of stelt de eventhandler in voor het OnRateChange event. |
| event [OnReadyStateChange](../../aspose.svg.dom/document/onreadystatechange/) | Haalt of stelt de event‑handler in voor het OnReadyStateChange‑event. |
| event [OnReset](../../aspose.svg.dom/document/onreset/) | Haalt op of stelt de eventhandler in voor het OnReset event. |
| event [OnResize](../../aspose.svg.dom/document/onresize/) | Haalt op of stelt de eventhandler in voor het OnResize event. |
| event [OnScroll](../../aspose.svg.dom/document/onscroll/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnScroll‑evenement. |
| event [OnSeeked](../../aspose.svg.dom/document/onseeked/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnSeeked‑evenement. |
| event [OnSeeking](../../aspose.svg.dom/document/onseeking/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnSeeking‑evenement. |
| event [OnSelect](../../aspose.svg.dom/document/onselect/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnSelect‑evenement. |
| event [OnShow](../../aspose.svg.dom/document/onshow/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnShow‑evenement. |
| event [OnStalled](../../aspose.svg.dom/document/onstalled/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnStalled‑evenement. |
| event [OnSubmit](../../aspose.svg.dom/document/onsubmit/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnSubmit‑evenement. |
| event [OnSuspend](../../aspose.svg.dom/document/onsuspend/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnSuspend‑evenement. |
| event [OnTimeUpdate](../../aspose.svg.dom/document/ontimeupdate/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnTimeUpdate‑evenement. |
| event [OnToggle](../../aspose.svg.dom/document/ontoggle/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnToggle‑evenement. |
| event [OnVolumeChange](../../aspose.svg.dom/document/onvolumechange/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnVolumeChange‑evenement. |
| event [OnWaiting](../../aspose.svg.dom/document/onwaiting/) | Haalt op of stelt de gebeurtenisafhandelaar in voor het OnWaiting‑evenement. |

### Zie ook

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
