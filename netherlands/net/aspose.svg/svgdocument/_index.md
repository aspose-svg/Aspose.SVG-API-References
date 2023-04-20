---
title: Class SVGDocument
second_title: Aspose.SVG voor .NET API-referentie
description: Aspose.Svg.SVGDocument klas. EenSVGDocumentis de hoofdmap van de SVGhiërarchie en bevat de volledige inhoud. Naast het bieden van toegang tot de hiërarchie biedt het ook een aantal handige methoden om toegang te krijgen tot bepaalde sets informatie uit het document. Wanneer een svgelement inline is ingesloten als onderdeel van een document uit een andere naamruimte zoals wanneer een svgelement element inline is ingesloten in een XHTMLdocument XHTML dan bestaat er geen SVGDocumentobject in plaats daarvan zal het rootobject in de documentobjecthiërarchie een Documentobject van een ander type zijn zoals een HTMLDocumentobject. Er zal echter wel een SVGDocumentobject bestaan wanneer het rootelement van de XMLdocumenthiërarchie een svgelement is  zoals bij het bekijken van een zelfstandig SVGbestand dwz een bestand met MIMEtype image/svgxml. In dit geval is het SVGDocumentobject het hoofdobject van de hiërarchie van het documentobjectmodel.
type: docs
weight: 3190
url: /nl/net/aspose.svg/svgdocument/
---
## SVGDocument class

Een`SVGDocument`is de hoofdmap van de SVG-hiërarchie en bevat de volledige inhoud. Naast het bieden van toegang tot de hiërarchie, biedt het ook een aantal handige methoden om toegang te krijgen tot bepaalde sets informatie uit het document. Wanneer een 'svg'-element inline is ingesloten als onderdeel van een document uit een andere naamruimte, zoals wanneer een 'svg'-element element inline is ingesloten in een XHTML-document [XHTML], dan bestaat er geen SVGDocument-object; in plaats daarvan zal het root-object in de documentobjecthiërarchie een Document-object van een ander type zijn, zoals een HTMLDocument-object. Er zal echter wel een SVGDocument-object bestaan wanneer het root-element van de XML-documenthiërarchie een 'svg'-element is , zoals bij het bekijken van een zelfstandig SVG-bestand (dwz een bestand met MIME-type "image/svg+xml"). In dit geval is het SVGDocument-object het hoofdobject van de hiërarchie van het documentobjectmodel.

```csharp
public class SVGDocument : Document, IDocumentCSS
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | Initialiseert een nieuw exemplaar van het`SVGDocument` klasse. |
| [SVGDocument](svgdocument/#constructor_1)(Configuration) | Initialiseert een nieuw exemplaar van het`SVGDocument` klasse. |
| [SVGDocument](svgdocument/#constructor_2)(RequestMessage) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_10)(string) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_4)(Url) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_3)(RequestMessage, Configuration) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_8)(Stream, string) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . Het laden van documenten begint vanaf de huidige positie in de stream. |
| [SVGDocument](svgdocument/#constructor_6)(Stream, Url) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . Het laden van documenten begint vanaf de huidige positie in de stream. |
| [SVGDocument](svgdocument/#constructor_11)(string, Configuration) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_14)(string, string) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_12)(string, Url) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_5)(Url, Configuration) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_9)(Stream, string, Configuration) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . Het laden van documenten begint vanaf de huidige positie in de stream. |
| [SVGDocument](svgdocument/#constructor_7)(Stream, Url, Configuration) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . Het laden van documenten begint vanaf de huidige positie in de stream. |
| [SVGDocument](svgdocument/#constructor_15)(string, string, Configuration) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_13)(string, Url, Configuration) | Initialiseert een nieuw exemplaar van het`SVGDocument`klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.svg.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) . |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes/) { get; } | Een NamedNodeMap met de attributen van dit knooppunt (als het een Element is) of anders nul. |
| override [BaseURI](../../aspose.svg.dom/document/baseuri/) { get; } | De absolute basis-URI van dit knooppunt of null als de implementatie geen absolute URI kon verkrijgen. |
| [CharacterSet](../../aspose.svg.dom/document/characterset/) { get; } | Haalt de codering van het document op. |
| [Charset](../../aspose.svg.dom/document/charset/) { get; } | Haalt de codering van het document op. |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount/) { get; } | Retourneert het huidige aantal elementknooppunten dat kinderen zijn van dit element. 0 als dit element geen onderliggende knooppunten heeft die van nodeType 1. zijn |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Een NodeList die alle kinderen van deze node bevat. Als er geen kinderen zijn, is dit een NodeList die geen nodes bevat.. |
| [Children](../../aspose.svg.dom/document/children/) { get; } | Geeft de onderliggende elementen terug. |
| [ContentType](../../aspose.svg.dom/document/contenttype/) { get; } | Haalt het inhoudstype van het document op. |
| [Context](../../aspose.svg.dom/document/context/) { get; } | Haalt de huidige browsercontext op. |
| [DefaultView](../../aspose.svg.dom/document/defaultview/) { get; } | Het defaultView IDL-attribuut van de documentinterface, bij ophalen, moet het WindowProxy-object van de browsercontext van dit document retourneren, als dit document een bijbehorende browsecontext heeft, of anders null. |
| [Doctype](../../aspose.svg.dom/document/doctype/) { get; } | De documenttypeverklaring die aan dit document is gekoppeld. |
| [DocumentElement](../../aspose.svg.dom/document/documentelement/) { get; } | Dit is een handig attribuut dat directe toegang geeft tot het onderliggende knooppunt dat het documentelement van het document is. |
| [DocumentURI](../../aspose.svg.dom/document/documenturi/) { get; } | De locatie van het document of null indien niet gedefinieerd of als het document is gemaakt met DOMImplementation.createDocument. |
| [Domain](../../aspose.svg/svgdocument/domain/) { get; } | De domeinnaam van de server die het document heeft geleverd, of een null-tekenreeks als de server niet kan worden geïdentificeerd door een domeinnaam. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Het eerste kind van dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild/) { get; } | Retourneert het eerste onderliggende elementknooppunt van dit element. null als dit element geen onderliggende elementen heeft. |
| [Implementation](../../aspose.svg.dom/document/implementation/) { get; } | Het DOMImplementatieobject dat dit document afhandelt. |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding/) { get; } | Haalt de codering van het document op. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Het laatste kind van dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild/) { get; } | Geeft het laatste onderliggende elementknooppunt van dit element terug. null als dit element geen onderliggende elementen heeft. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Retourneert het lokale deel van de gekwalificeerde naam van dit knooppunt. Voor knooppunten van een ander type dan ELEMENT_NODE en ATTRIBUTE_NODE en knooppunten gemaakt met een DOM Level 1-methode, zoals Document.createElement(), is dit altijd null. |
| [Location](../../aspose.svg.dom/document/location/) { get; } | De locatie van het document. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | De naamruimte-URI van dit knooppunt, of null als deze niet is gespecificeerd. |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling/) { get; } | Retourneert het volgende elementknooppunt van dit element. null als dit element geen element-zusterknooppunten heeft die na dit element in de documentstructuur komen. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Het knooppunt dat onmiddellijk volgt op dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| override [NodeName](../../aspose.svg.dom/document/nodename/) { get; } | De naam van dit knooppunt, afhankelijk van het type. |
| override [NodeType](../../aspose.svg.dom/document/nodetype/) { get; } | Een code die het type van het onderliggende object vertegenwoordigt. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | De waarde van dit knooppunt, afhankelijk van het type. |
| [Origin](../../aspose.svg.dom/document/origin/) { get; } | Haalt de oorsprong van het document op. |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument/) { get; } | Haalt het eigenaarsdocument op. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Haalt de ouder op[`Element`](../../aspose.svg.dom/element/) van dit knooppunt. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | De ouder van dit knooppunt. Alle knooppunten, behalve Attr, Document, DocumentFragment, Entity en Notation kunnen een ouder hebben. Als een knooppunt echter net is gemaakt en nog niet aan de boom is toegevoegd, of als het uit de boom is verwijderd, is dit null. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Het naamruimtevoorvoegsel van dit knooppunt, of null als het niet is gespecificeerd. Als het is gedefinieerd als null, heeft het instellen ervan geen effect |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling/) { get; } | Retourneert het vorige elementknooppunt van dit element. null als dit element geen element-zusterknooppunten heeft die vóór dit element in de documentstructuur komen. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Het knooppunt dat onmiddellijk aan dit knooppunt voorafgaat. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| [ReadyState](../../aspose.svg.dom/document/readystate/) { get; } | Retourneert de gereedheid van het document. Het "laden" terwijl het document wordt geladen, "interactief" zodra het klaar is met parseren maar nog steeds subbronnen laadt, en "voltooid" zodra het is geladen. |
| [Referrer](../../aspose.svg/svgdocument/referrer/) { get; } | Retourneert de URI van de pagina die naar deze pagina heeft gelinkt. De waarde is een lege string als de gebruiker rechtstreeks naar de pagina is genavigeerd (niet via een link, maar bijvoorbeeld via een bladwijzer). |
| [RootElement](../../aspose.svg/svgdocument/rootelement/) { get; } | De root 'svg' in de documenthiërarchie. |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking/) { get; set; } | Een attribuut dat specificeert of foutcontrole wordt afgedwongen of niet. Indien ingesteld op false, is de implementatie vrij om niet elk mogelijk foutgeval te testen dat normaal is gedefinieerd voor DOM-bewerkingen, en geen DOMException op te roepen voor DOM-bewerkingen of fouten te rapporteren tijdens het gebruik van Document.normalizeDocument(). In geval van een fout is het gedrag ongedefinieerd. Dit kenmerk is standaard waar. |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets/) { get; } | Een lijst met alle stijlbladen die expliciet zijn gekoppeld aan of ingebed in een document. Voor HTML-documenten omvat dit externe stijlbladen, opgenomen via het HTML LINK-element, en inline STYLE-elementen. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Dit attribuut retourneert de tekstinhoud van dit knooppunt en zijn afstammelingen. Als het is gedefinieerd als null, heeft het instellen ervan geen effect. Bij het instellen worden alle mogelijke kinderen die dit knooppunt heeft verwijderd en, als de nieuwe tekenreeks niet leeg of null is, vervangen door een enkel tekstknooppunt dat de tekenreeks bevat waarop dit kenmerk is ingesteld. |
| [Title](../../aspose.svg/svgdocument/title/) { get; } | De titel van een document zoals gespecificeerd door het 'title' subelement van het 'svg' root element (dwz,Hier is de titel... ) |
| [URL](../../aspose.svg/svgdocument/url/) { get; } | De volledige URI van het document. |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone/) { get; set; } | Een attribuut dat specificeert, als onderdeel van de XML-declaratie, of dit document op zichzelf staat. Dit is niet waar wanneer niet gespecificeerd. |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion/) { get; set; } | Een attribuut dat, als onderdeel van de XML-declaratie, het versienummer van dit document specificeert. Als er geen declaratie is en als dit document de functie "XML" ondersteunt, is de waarde "1.0". Als dit document de "XML"-functie niet ondersteunt, is de waarde altijd null. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(Node) | Voegt het knooppunt newChild toe aan het einde van de lijst met kinderen van dit knooppunt. Als de newChild al in de stamboom staat, wordt deze eerst verwijderd. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Retourneert een duplicaat van dit knooppunt, dwz dient als generieke kopieerconstructor voor knooppunten. Het gedupliceerde knooppunt heeft geen ouder (parentNode is null) en geen gebruikersgegevens. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(bool) | Retourneert een duplicaat van dit knooppunt, dwz dient als generieke kopieerconstructor voor knooppunten. Het gedupliceerde knooppunt heeft geen ouder (parentNode is null) en geen gebruikersgegevens. |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute/)(string) | Creëert een Attr van de opgegeven naam. |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens/)(string, string) | Maakt een kenmerk van de gegeven gekwalificeerde naam en naamruimte-URI. |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection/)(string) | Maakt een CDATASection-knooppunt waarvan de waarde de opgegeven tekenreeks is. |
| [CreateComment](../../aspose.svg.dom/document/createcomment/)(string) | Creëert een commentaarknooppunt op basis van de opgegeven tekenreeks. |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment/)() | Maakt een leeg DocumentFragment-object aan. |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype/)(string, string, string, string) | Creëert een DocumentType-knooppunt. |
| [CreateElement](../../aspose.svg.dom/document/createelement/)(string) | Creëert een element van het gespecificeerde type. Merk op dat de geretourneerde instantie de Element-interface implementeert, dus attributen kunnen rechtstreeks op het geretourneerde object worden gespecificeerd. |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns/)(string, string) | Maakt een element van de opgegeven gekwalificeerde naam en naamruimte-URI. |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference/)(string) | Maakt een EntityReference-object. Bovendien, als de entiteit waarnaar wordt verwezen bekend is, wordt de onderliggende lijst van het EntityReference-knooppunt hetzelfde gemaakt als die van het corresponderende Entity-knooppunt. |
| [CreateEvent](../../aspose.svg.dom/document/createevent/)(string) | Creëert een[`Event`](../../aspose.svg.dom.events/event/) van een type dat wordt ondersteund door de implementatie. |
| [CreateExpression](../../aspose.svg.dom/document/createexpression/)(string, IXPathNSResolver) | Maakt een geparseerde XPath-expressie met opgeloste naamruimten. Dit is handig wanneer een expressie opnieuw wordt gebruikt in een toepassing, aangezien het mogelijk maakt om de uitdrukkingsreeks in een efficiëntere interne vorm te compileren en alle naamruimtevoorvoegsels die binnen de uitdrukking voorkomen vooraf op te lossen. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/)(Node) | Maak een nieuwe NodeIterator over de substructuur die is geworteld in het gespecificeerde knooppunt. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/)(Node, long) | Maak een nieuwe NodeIterator over de substructuur die is geworteld in het gespecificeerde knooppunt. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Maak een nieuwe NodeIterator over de substructuur die is geworteld in het gespecificeerde knooppunt. |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver/)(Node) | Past elk DOM-knooppunt aan om naamruimten op te lossen, zodat een XPath-expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waar het in het document verscheen. Deze adapter werkt zoals de DOM Level 3-methode`opzoekenNaamruimteURI` op knooppunten bij het oplossen van de namespaceURI van een bepaald voorvoegsel met behulp van de huidige informatie die beschikbaar is in de hiërarchie van het knooppunt op het moment dat lookupNamespaceURI wordt aangeroepen, waarbij ook het impliciete xml-voorvoegsel correct wordt opgelost. |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction/)(string, string) | Maakt een ProcessingInstruction-knooppunt met de opgegeven naam en gegevensreeksen. |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode/)(string) | Maakt een tekstknooppunt op basis van de opgegeven tekenreeks. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/)(Node) | Maak een nieuwe TreeWalker over de subboom die is geroot op het gespecificeerde knooppunt. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/)(Node, long) | Maak een nieuwe TreeWalker over de subboom die is geroot op het gespecificeerde knooppunt. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/)(Node, long, INodeFilter) | Maak een nieuwe TreeWalker over de subboom die is geroot op het gespecificeerde knooppunt. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(Event) | Met deze methode kunnen gebeurtenissen worden verzonden naar het gebeurtenismodel van de implementatie. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijmaken, vrijgeven of resetten van onbeheerde bronnen. |
| [Evaluate](../../aspose.svg.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Evalueert een XPath-expressietekenreeks en retourneert indien mogelijk een resultaat van het opgegeven type. |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid/)(string) | Geeft het element terug dat een ID-attribuut heeft met de gegeven waarde. Als een dergelijk element niet bestaat, wordt null geretourneerd. Als meer dan één element een ID-attribuut met die waarde heeft, is wat wordt geretourneerd ongedefinieerd. |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname/)(string) | Retourneert een live NodeList-object met alle elementen in het document waarvan alle klassen zijn opgegeven in argument. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname/)(string) | Retourneert een NodeList van alle Elementen in documentvolgorde met een gegeven tagnaam en zijn opgenomen in het document. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens/)(string, string) | Retourneert een NodeList van alle elementen met een gegeven lokale naam en naamruimte-URI in documentvolgorde. |
| [GetOverrideStyle](../../aspose.svg/svgdocument/getoverridestyle/)(Element, string) | Deze methode wordt gebruikt om de override-stijldeclaratie op te halen voor een gespecificeerd element en een gespecificeerd pseudo-element. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes/)() | Geeft terug of dit knooppunt (als het een element is) attributen heeft |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Geeft terug of dit knooppunt kinderen heeft. |
| [ImportNode](../../aspose.svg.dom/document/importnode/)(Node, bool) | Importeert een knooppunt uit een ander document naar dit document, zonder het bronknooppunt uit het originele document te wijzigen of te verwijderen; deze methode maakt een nieuwe kopie van het bronknooppunt. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(Node, Node) | Voegt het knooppunt in vóór het bestaande onderliggende knooppunt. Als kind null is, voegt u een knooppunt in aan het einde van de lijst met kinderen. Als kind een DocumentFragment-object is, worden alle kinderen in dezelfde volgorde ingevoegd vóór kind. Als het kind al in de boom zit, wordt het eerst verwijderd. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(string) | Deze methode controleert of de opgegeven naamruimte-URI de standaard naamruimte is of niet. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(Node) | Test of twee knooppunten gelijk zijn. Deze methode test op gelijkheid van knooppunten, niet gelijkheid (dwz of de twee knooppunten verwijzingen naar hetzelfde object zijn), wat kan worden getest met Node.isSameNode(). Alle knooppunten die hetzelfde zijn, zullen ook gelijk zijn, hoewel het omgekeerde misschien niet waar is. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(Node) | Geeft terug of dit knooppunt hetzelfde knooppunt is als het opgegeven knooppunt. Deze methode biedt een manier om te bepalen of twee Node-referenties die door de implementatie worden geretourneerd, naar hetzelfde object verwijzen. Wanneer twee Node-referenties verwijzingen zijn naar hetzelfde object, zelfs via een proxy, kunnen de referenties volledig onderling uitwisselbaar worden gebruikt, zodat alle attributen dezelfde waarden hebben en het aanroepen van dezelfde DOM-methode voor beide referenties altijd exact hetzelfde effect heeft. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(string) | Zoek de naamruimte-URI op die is gekoppeld aan het opgegeven voorvoegsel, beginnend vanaf dit knooppunt. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(string) | Zoek het voorvoegsel op dat is gekoppeld aan de opgegeven naamruimte-URI, beginnend bij dit knooppunt. De standaard naamruimtedeclaraties worden door deze methode genegeerd. Zie Namespace Prefix Lookup voor meer informatie over het algoritme dat door deze methode wordt gebruikt. |
| [Navigate](../../aspose.svg.dom/document/navigate/)(RequestMessage) | Laadt het document op basis van het opgegeven verzoekobject en vervangt de vorige inhoud. |
| [Navigate](../../aspose.svg.dom/document/navigate/)(string) | Laadt het document op de gespecificeerde Uniform Resource Locator (URL) in de huidige instantie en vervangt de vorige inhoud. |
| [Navigate](../../aspose.svg.dom/document/navigate/)(Url) | Laadt het document op de gespecificeerde Uniform Resource Locator (URL) in de huidige instantie en vervangt de vorige inhoud. |
| [Navigate](../../aspose.svg.dom/document/navigate/)(Stream, string) | Laadt het document vanuit gespecificeerde inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van documenten begint vanaf de huidige positie in de stroom. |
| [Navigate](../../aspose.svg.dom/document/navigate/)(Stream, Url) | Laadt het document vanuit gespecificeerde inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van documenten begint vanaf de huidige positie in de stroom. |
| [Navigate](../../aspose.svg.dom/document/navigate/)(string, string) | Laadt het document vanuit gespecificeerde inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. |
| [Navigate](../../aspose.svg.dom/document/navigate/)(string, Url) | Laadt het document vanuit gespecificeerde inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Zet alle tekstknooppunten in de volledige diepte van de subboom onder dit knooppunt, inclusief attribuutknooppunten, in een "normale" vorm waar alleen structuur (bijv. elementen, opmerkingen, verwerkingsinstructies, CDATA-secties en entiteitsreferenties) tekst scheidt knooppunten, dwz er zijn geen aangrenzende tekstknooppunten of lege tekstknooppunten. Dit kan worden gebruikt om ervoor te zorgen dat de DOM-weergave van een document hetzelfde is alsof het is opgeslagen en opnieuw geladen, en is handig wanneer bewerkingen (zoals XPointer [XPointer]-lookups) die afhankelijk zijn van een bepaalde documentboomstructuur, moeten worden uitgevoerd. worden gebruikt. Als de parameter "normalize-characters" van het DOMConfiguration-object dat aan het Node.ownerDocument is gekoppeld, waar is, zal deze methode ook de tekens van de tekstknooppunten volledig normaliseren. |
| [QuerySelector](../../aspose.svg.dom/document/queryselector/)(string) | Retourneert het eerste element in het document dat overeenkomt met selector |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall/)(string) | Retourneert een NodeList van alle elementen in het document, die overeenkomen met selector |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(Node) | Verwijdert het onderliggende knooppunt aangegeven door oldChild uit de lijst met onderliggende items en retourneert het. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../aspose.svg.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../aspose.svg.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../aspose.svg.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| override [RenderTo](../../aspose.svg/svgdocument/renderto/)(IDevice) | Deze methode wordt gebruikt om de inhoud van het huidige document naar het opgegeven apparaat af te drukken. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(Node, Node) | Vervangt het onderliggende knooppunt oldChild door newChild in de lijst met onderliggende items en retourneert het oldChild-knooppunt. Als newChild een DocumentFragment-object is, wordt oldChild vervangen door alle DocumentFragment-kinderen, die in dezelfde volgorde worden ingevoegd. Als de newChild al in de stamboom staat, wordt deze eerst verwijderd. |
| [Save](../../aspose.svg/svgdocument/save/#save)(IOutputStorage) | Slaat de documentinhoud en bronnen op in de uitvoeropslag. |
| [Save](../../aspose.svg/svgdocument/save/#save_6)(string) | Slaat het document op in een lokaal bestand gespecificeerd door`pad` . Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.svg/svgdocument/save/#save_3)(Url) | Slaat het document op in een lokaal bestand gespecificeerd door`url` . Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.svg/svgdocument/save/#save_1)(IOutputStorage, SVGSaveFormat) | Slaat de documentinhoud en bronnen op in de uitvoeropslag. |
| [Save](../../aspose.svg/svgdocument/save/#save_2)(IOutputStorage, SVGSaveOptions) | Slaat de documentinhoud en bronnen op in de uitvoeropslag. |
| [Save](../../aspose.svg/svgdocument/save/#save_7)(string, SVGSaveFormat) | Slaat het document op in een lokaal bestand gespecificeerd door`pad` . Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.svg/svgdocument/save/#save_8)(string, SVGSaveOptions) | Slaat het document op in een lokaal bestand gespecificeerd door`pad` . Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.svg/svgdocument/save/#save_4)(Url, SVGSaveFormat) | Slaat het document op in een lokaal bestand gespecificeerd door`url` . Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.svg/svgdocument/save/#save_5)(Url, SVGSaveOptions) | Slaat het document op in een lokaal bestand gespecificeerd door`url` . Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |
| [Write](../../aspose.svg.dom/document/write/)(params string[]) | Schrijf een tekstreeks naar een documentstroom geopend door open(). Merk op dat de functie een document zal produceren dat niet noodzakelijkerwijs wordt aangestuurd door een DTD en daarom kan zijn een ongeldig resultaat opleveren in de context van het document. |
| [WriteLn](../../aspose.svg.dom/document/writeln/)(params string[]) | Schrijf een tekstreeks gevolgd door een teken voor een nieuwe regel naar een document stroom geopend door open(). Merk op dat de functie will een document produceert dat niet noodzakelijkerwijs wordt aangestuurd door een DTD en kan daarom een ongeldig resultaat opleveren in de context van the document |

## Evenementen

| Naam | Beschrijving |
| --- | --- |
| event [OnAbort](../../aspose.svg.dom/document/onabort/) | Haalt of stelt gebeurtenishandler in voor OnAbort-gebeurtenis. |
| event [OnBlur](../../aspose.svg.dom/document/onblur/) | Haalt of stelt gebeurtenishandler in voor OnBlur-gebeurtenis. |
| event [OnCancel](../../aspose.svg.dom/document/oncancel/) | Haalt of stelt gebeurtenishandler in voor OnCancel-gebeurtenis. |
| event [OnCanplay](../../aspose.svg.dom/document/oncanplay/) | Haalt of stelt gebeurtenishandler in voor OnCanplay-gebeurtenis. |
| event [OnCanPlayThrough](../../aspose.svg.dom/document/oncanplaythrough/) | Haalt of stelt gebeurtenishandler in voor OnCanPlayThrough-gebeurtenis. |
| event [OnChange](../../aspose.svg.dom/document/onchange/) | Haalt of stelt gebeurtenishandler in voor OnChange-gebeurtenis. |
| event [OnClick](../../aspose.svg.dom/document/onclick/) | Haalt of stelt gebeurtenishandler in voor OnClick-gebeurtenis. |
| event [OnCueChange](../../aspose.svg.dom/document/oncuechange/) | Haalt of stelt gebeurtenishandler in voor OnCueChange-gebeurtenis. |
| event [OnDblClick](../../aspose.svg.dom/document/ondblclick/) | Haalt of stelt gebeurtenishandler in voor OnDblClick-gebeurtenis. |
| event [OnDurationChange](../../aspose.svg.dom/document/ondurationchange/) | Haalt of stelt gebeurtenishandler in voor OnDurationChange-gebeurtenis. |
| event [OnEmptied](../../aspose.svg.dom/document/onemptied/) | Haalt of stelt gebeurtenishandler in voor OnEmptied-gebeurtenis. |
| event [OnEnded](../../aspose.svg.dom/document/onended/) | Haalt of stelt gebeurtenishandler in voor OnEnded-gebeurtenis. |
| event [OnError](../../aspose.svg.dom/document/onerror/) | Haalt of stelt gebeurtenishandler in voor OnError-gebeurtenis. |
| event [OnFocus](../../aspose.svg.dom/document/onfocus/) | Krijgt of stelt gebeurtenishandler in voor OnFocus-gebeurtenis. |
| event [OnInput](../../aspose.svg.dom/document/oninput/) | Haalt of stelt gebeurtenishandler in voor OnInput-gebeurtenis. |
| event [OnInvalid](../../aspose.svg.dom/document/oninvalid/) | Haalt of stelt gebeurtenishandler in voor OnInvalid-gebeurtenis. |
| event [OnKeyDown](../../aspose.svg.dom/document/onkeydown/) | Haalt of stelt gebeurtenishandler in voor OnKeyDown-gebeurtenis. |
| event [OnKeyPress](../../aspose.svg.dom/document/onkeypress/) | Krijgt of stelt gebeurtenishandler in voor OnKeyPress-gebeurtenis. |
| event [OnKeyUp](../../aspose.svg.dom/document/onkeyup/) | Haalt of stelt gebeurtenishandler in voor OnKeyUp-gebeurtenis. |
| event [OnLoad](../../aspose.svg.dom/document/onload/) | Haalt of stelt gebeurtenishandler in voor OnLoad-gebeurtenis. |
| event [OnLoadedData](../../aspose.svg.dom/document/onloadeddata/) | Haalt of stelt gebeurtenishandler in voor OnLoadedData-gebeurtenis. |
| event [OnLoadedMetadata](../../aspose.svg.dom/document/onloadedmetadata/) | Haalt of stelt gebeurtenishandler in voor OnLoadedMetadata-gebeurtenis. |
| event [OnLoadStart](../../aspose.svg.dom/document/onloadstart/) | Haalt of stelt gebeurtenishandler in voor OnLoadStart-gebeurtenis. |
| event [OnMouseDown](../../aspose.svg.dom/document/onmousedown/) | Haalt of stelt gebeurtenishandler in voor OnMouseDown-gebeurtenis. |
| event [OnMouseEnter](../../aspose.svg.dom/document/onmouseenter/) | Haalt gebeurtenishandler op of stelt deze in voor OnMouseEnter-gebeurtenis. |
| event [OnMouseLeave](../../aspose.svg.dom/document/onmouseleave/) | Haalt of stelt gebeurtenishandler in voor OnMouseLeave-gebeurtenis. |
| event [OnMouseMove](../../aspose.svg.dom/document/onmousemove/) | Haalt of stelt gebeurtenishandler in voor OnMouseMove-gebeurtenis. |
| event [OnMouseOut](../../aspose.svg.dom/document/onmouseout/) | Haalt of stelt gebeurtenishandler in voor OnMouseOut-gebeurtenis. |
| event [OnMouseOver](../../aspose.svg.dom/document/onmouseover/) | Haalt of stelt gebeurtenishandler in voor OnMouseOver-gebeurtenis. |
| event [OnMouseUp](../../aspose.svg.dom/document/onmouseup/) | Haalt of stelt gebeurtenishandler in voor OnMouseUp-gebeurtenis. |
| event [OnMouseWheel](../../aspose.svg.dom/document/onmousewheel/) | Haalt of stelt gebeurtenishandler in voor OnMouseWheel-gebeurtenis. |
| event [OnPause](../../aspose.svg.dom/document/onpause/) | Haalt of stelt gebeurtenishandler in voor OnPause-gebeurtenis. |
| event [OnPlay](../../aspose.svg.dom/document/onplay/) | Krijgt of stelt gebeurtenishandler in voor OnPlay-gebeurtenis. |
| event [OnPlaying](../../aspose.svg.dom/document/onplaying/) | Haalt of stelt gebeurtenishandler in voor OnPlaying-gebeurtenis. |
| event [OnProgress](../../aspose.svg.dom/document/onprogress/) | Haalt of stelt gebeurtenishandler in voor OnProgress-gebeurtenis. |
| event [OnRateChange](../../aspose.svg.dom/document/onratechange/) | Haalt of stelt gebeurtenishandler in voor OnRateChange-gebeurtenis. |
| event [OnReadyStateChange](../../aspose.svg.dom/document/onreadystatechange/) | Haalt of stelt gebeurtenishandler in voor OnReadyStateChange-gebeurtenis. |
| event [OnReset](../../aspose.svg.dom/document/onreset/) | Haalt of stelt gebeurtenishandler in voor OnReset-gebeurtenis. |
| event [OnResize](../../aspose.svg.dom/document/onresize/) | Haalt of stelt gebeurtenishandler in voor OnResize-gebeurtenis. |
| event [OnScroll](../../aspose.svg.dom/document/onscroll/) | Haalt of stelt gebeurtenishandler in voor OnScroll-gebeurtenis. |
| event [OnSeeked](../../aspose.svg.dom/document/onseeked/) | Haalt of stelt gebeurtenishandler in voor OnSeeked-gebeurtenis. |
| event [OnSeeking](../../aspose.svg.dom/document/onseeking/) | Haalt of stelt gebeurtenishandler in voor OnSeeking-gebeurtenis. |
| event [OnSelect](../../aspose.svg.dom/document/onselect/) | Haalt of stelt gebeurtenishandler in voor OnSelect-gebeurtenis. |
| event [OnShow](../../aspose.svg.dom/document/onshow/) | Haalt of stelt gebeurtenishandler in voor OnShow-gebeurtenis. |
| event [OnStalled](../../aspose.svg.dom/document/onstalled/) | Krijgt of stelt gebeurtenishandler in voor OnStalled-gebeurtenis. |
| event [OnSubmit](../../aspose.svg.dom/document/onsubmit/) | Haalt of stelt gebeurtenishandler in voor OnSubmit-gebeurtenis. |
| event [OnSuspend](../../aspose.svg.dom/document/onsuspend/) | Haalt gebeurtenishandler op of stelt deze in voor OnSuspend-gebeurtenis. |
| event [OnTimeUpdate](../../aspose.svg.dom/document/ontimeupdate/) | Haalt of stelt gebeurtenishandler in voor OnTimeUpdate-gebeurtenis. |
| event [OnToggle](../../aspose.svg.dom/document/ontoggle/) | Haalt of stelt gebeurtenishandler in voor OnToggle-gebeurtenis. |
| event [OnVolumeChange](../../aspose.svg.dom/document/onvolumechange/) | Haalt of stelt gebeurtenishandler in voor OnVolumeChange-gebeurtenis. |
| event [OnWaiting](../../aspose.svg.dom/document/onwaiting/) | Haalt of stelt gebeurtenishandler in voor OnWaiting-gebeurtenis. |

### Zie ook

* class [Document](../../aspose.svg.dom/document/)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../aspose.svg.dom.css/idocumentcss/)
* naamruimte [Aspose.Svg](../../aspose.svg/)
* montage [Aspose.SVG](../../)


