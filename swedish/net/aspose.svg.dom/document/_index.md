---
title: "Dokumentklass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Document-klass. Dokumentet representerar hela HTML‑, XML‑ eller SVG‑dokumentet. Konceptuellt är det roten i dokumentträdet och ger primär åtkomst till dokumentets data."
type: docs
weight: 2810
url: /sv/net/aspose.svg.dom/document/
---
## Document class

Document representerar hela HTML‑, XML‑ eller SVG‑dokumentet. Konceptuellt är det roten i dokumentträdet och ger primär åtkomst till dokumentets data.

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [BaseURI](../../aspose.svg.dom/document/baseuri/) { get; } | Den absoluta bas‑URI:n för den här noden eller null om implementationen inte kunde erhålla en absolut URI. |
| [CharacterSet](../../aspose.svg.dom/document/characterset/) { get; } | Hämtar dokumentets kodning. |
| [Charset](../../aspose.svg.dom/document/charset/) { get; } | Hämtar dokumentets kodning. |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount/) { get; } | Returnerar det aktuella antalet elementnoder som är barn till detta element. 0 om detta element inte har några barnnoder av nodtyp 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Returnerar en levande [`NodeList`](../../aspose.svg.collections/nodelist/) av barnnoder för det angivna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer. |
| [Children](../../aspose.svg.dom/document/children/) { get; } | Returnerar barn‑elementen. |
| [ContentType](../../aspose.svg.dom/document/contenttype/) { get; } | Hämtar dokumentets innehållstyp. |
| [Context](../../aspose.svg.dom/document/context/) { get; } | Hämtar det aktuella bläddringskontextet. |
| [DefaultView](../../aspose.svg.dom/document/defaultview/) { get; } | defaultView‑IDL‑attributet för Document‑gränssnittet ska, vid läsning, returnera detta dokuments bläddringskontexts WindowProxy‑objekt, om detta dokument har ett associerat bläddringskontext, annars null. |
| [Doctype](../../aspose.svg.dom/document/doctype/) { get; } | Dokumenttypdeklarationen som är associerad med detta dokument. |
| [DocumentElement](../../aspose.svg.dom/document/documentelement/) { get; } | Detta är ett bekvämlighetsattribut som möjliggör direkt åtkomst till barnnoden som är dokumentelementet i dokumentet. |
| [DocumentURI](../../aspose.svg.dom/document/documenturi/) { get; } | Platsen för dokumentet eller null om den är odefinierad eller om dokumentet skapades med DOMImplementation.createDocument. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Returnerar nodens första barn i trädet, eller null om noden saknar barn. |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild/) { get; } | Returnerar den första barn‑elementnoden för detta element. Null om detta element inte har några barn‑element. |
| [Implementation](../../aspose.svg.dom/document/implementation/) { get; } | DOMImplementation‑objektet som hanterar detta dokument. |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding/) { get; } | Hämtar dokumentets kodning. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Returnerar nodens sista barn. Om dess förälder är ett element är barnet vanligtvis ett elementnod, ett textnod eller ett kommentarnod. Den returnerar null om det inte finns några barn-element. |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild/) { get; } | Returnerar det sista barn-elementnodet för detta element. null om detta element inte har några barn-element. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Returnerar den lokala delen av det kvalificerade namnet för denna nod. För noder av någon annan typ än [`ELEMENT_NODE`](../node/element_node/) och [`ATTRIBUTE_NODE`](../node/attribute_node/) samt noder skapade med en DOM Level 1-metod, såsom [`CreateElement`](./createelement/), är detta alltid null. |
| [Location](../../aspose.svg.dom/document/location/) { get; } | Dokumentets plats. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Returnerar elementets namnrymd‑URI, eller null om elementet inte är i en namnrymd. |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling/) { get; } | Returnerar nästa syskon-elementnod för detta element. null om detta element inte har några element-syskon som kommer efter detta i dokumentträdet. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Returnerar noden som omedelbart följer den angivna i deras förälders [`ChildNodes`](../node/childnodes/), eller returnerar null om den angivna noden är det sista barnet i förälderelementet. |
| override [NodeName](../../aspose.svg.dom/document/nodename/) { get; } | Namnet på denna nod, beroende på dess typ. |
| override [NodeType](../../aspose.svg.dom/document/nodetype/) { get; } | En kod som representerar typen av det underliggande objektet. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Returnerar eller anger värdet för den aktuella noden. |
| [Origin](../../aspose.svg.dom/document/origin/) { get; } | Hämtar dokumentets ursprung. |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument/) { get; } | Hämtar ägardokumentet. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Returnerar DOM-nodens förälder [`Element`](../element/), eller null om noden antingen saknar förälder eller om dess förälder inte är ett DOM-element. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Returnerar föräldern till den angivna noden i DOM-trädet. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Returnerar namnrymdsprefixet för det angivna elementet, eller null om inget prefix har angetts. |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling/) { get; } | Returnerar föregående syskon-elementnod för detta element. null om detta element inte har några element-syskon som kommer före detta i dokumentträdet. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Returnerar noden som omedelbart föregår den angivna i dess förälders [`ChildNodes`](../node/childnodes/) lista, eller null om den angivna noden är den första i listan. |
| [ReadyState](../../aspose.svg.dom/document/readystate/) { get; } | Returnerar dokumentets lässtatus. "loading" medan dokumentet laddas, "interactive" när det har slutfört parsning men fortfarande laddar underresurser, och "complete" när det är helt laddat. |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking/) { get; set; } | Ett attribut som anger om felkontroll ska verkställas eller inte. När det är satt till false får implementationen välja att inte testa varje möjligt fel som normalt definieras för DOM‑operationer, och inte kasta någon DOMException vid DOM‑operationer eller rapportera fel när Document.normalizeDocument() används. Vid fel är beteendet odefinierat. Detta attribut är true som standard. |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets/) { get; } | En lista som innehåller alla stilmallar som uttryckligen länkas in eller bäddas in i ett dokument. För HTML‑dokument inkluderar detta externa stilmallar, inkluderade via HTML‑LINK‑elementet, samt inbäddade STYLE‑element. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Representerar textinnehållet i noden och dess undernoder. |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone/) { get; set; } | Ett attribut som anger, som en del av XML‑deklarationen, om detta dokument är fristående. Detta är false när det inte anges. |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion/) { get; set; } | Ett attribut som anger, som en del av XML‑deklarationen, versionsnumret för detta dokument. Om det inte finns någon deklaration och dokumentet stödjer "XML"‑funktionen är värdet "1.0". Om dokumentet inte stödjer "XML"‑funktionen är värdet alltid null. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Lägger till en nod i slutet av listan med barn till en angiven föräldranod. Om det angivna barnet är en referens till en befintlig nod i dokumentet, [`AppendChild`](../node/appendchild/) flyttar den från sin nuvarande position till den nya positionen (det finns inget krav på att ta bort noden från dess föräldranod innan den läggs till i någon annan nod). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Returnerar en kopia av den nod som denna metod anropades på. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Returnerar en kopia av den nod som denna metod anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute/)(*string*) | Denna metod skapar en ny attributnod och returnerar den. Det skapade objektet är en nod som implementerar klassen [`Attr`](../attr/). DOM‑implementeringen påtvingar inte vilken typ av attribut som kan läggas till ett specifikt element på detta sätt. |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens/)(*string, string*) | Denna metod skapar en ny attributnod och returnerar den. Det skapade objektet är en nod som implementerar klassen [`Attr`](../attr/). DOM‑implementeringen påtvingar inte vilken typ av attribut som kan läggas till ett specifikt element på detta sätt. |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection/)(*string*) | Skapar en CDATASection‑nod vars värde är den angivna strängen. |
| [CreateComment](../../aspose.svg.dom/document/createcomment/)(*string*) | Skapar en Comment‑nod med den angivna strängen. |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment/)() | Skapar ett nytt tomt [`DocumentFragment`](../documentfragment/) där DOM‑noder kan läggas till för att bygga ett offscreen‑DOM‑träd. |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype/)(*string, string, string, string*) | Metoden returnerar ett [`DocumentType`](../documenttype/)-objekt som antingen kan användas med [`CreateDocument`](../idomimplementation/createdocument/) vid dokumentskapande eller kan sättas in i dokumentet via metoder som [`InsertBefore`](../node/insertbefore/) eller [`ReplaceChild`](../node/replacechild/). |
| [CreateElement](../../aspose.svg.dom/document/createelement/)(*string*) | Skapar HTML‑elementet som anges av localName, eller ett HTMLUnknownElement om localName inte känns igen. |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns/)(*string, string*) | Skapar ett element med det angivna kvalificerade namnet och namnrymdens URI. |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference/)(*string*) | Skapar ett EntityReference‑objekt. Dessutom, om den refererade enheten är känd, görs barnlistan för EntityReference‑noden densamma som för motsvarande Entity‑nod. |
| [CreateEvent](../../aspose.svg.dom/document/createevent/)(*string*) | Skapar ett [`Event`](../../aspose.svg.dom.events/event/) av en typ som stöds av implementationen. |
| [CreateExpression](../../aspose.svg.dom/document/createexpression/)(*string, [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)*) | Skapar ett analyserat XPath-uttryck med upplösta namnrymder. Detta är användbart när ett uttryck kommer att återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksträngen till en mer effektiv intern form och förupplösa alla namnrymdsprefix som förekommer i uttrycket. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator)(*[Node](../node/)*) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_1)(*[Node](../node/), long*) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver/)(*[Node](../node/)*) | Anpassar vilken DOM-nod som helst för att lösa namnrymder så att ett XPath-uttryck enkelt kan utvärderas i förhållande till kontexten för den nod där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3-metoden `lookupNamespaceURI` på noder för att lösa namespaceURI från ett givet prefix med den aktuella informationen som finns i nodens hierarki när lookupNamespaceURI anropas, och löser även korrekt det implicita xml-prefixet. |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction/)(*string, string*) | Skapar en ProcessingInstruction-nod med det angivna namn- och datatsträngarna. |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode/)(*string*) | Skapar en Text-nod med den angivna strängen. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker)(*[Node](../node/)*) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_1)(*[Node](../node/), long*) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Skickar ett Event till den angivna [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De vanliga reglerna för händelsebehandling (inklusive fångst‑ och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
| [Evaluate](../../aspose.svg.dom/document/evaluate/)(*string, [Node](../node/), [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/), [XPathResultType](../../aspose.svg.dom.xpath/xpathresulttype/), object*) | Utvärderar en XPath-uttrycksträng och returnerar ett resultat av den angivna typen om möjligt. |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid/)(*string*) | Denna metod returnerar ett [`Element`](../element/)‑objekt som representerar elementet vars id‑egenskap matchar den angivna strängen. Eftersom element‑ID:n måste vara unika om de anges, är de ett praktiskt sätt att snabbt få åtkomst till ett specifikt element. |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname/)(*string*) | Denna metod returnerar ett array‑likt objekt med alla underordnade element som har alla de angivna klassnamnen. |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname/)(*string*) | Denna metod returnerar en [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) av element med det angivna taggnamnet. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens/)(*string, string*) | Returnerar en lista med element med det angivna taggnamnet som tillhör den angivna namnrymden. Hela dokumentet söks, inklusive rot‑noden. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Returnerar ett booleskt värde som indikerar om den givna [`Node`](../node/) har barnnoder eller inte. |
| [ImportNode](../../aspose.svg.dom/document/importnode/)(*[Node](../node/), bool*) | Importerar en nod från ett annat dokument till detta dokument, utan att ändra eller ta bort källnoden från originaldokumentet; denna metod skapar en ny kopia av källnoden. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Infogar noden före den befintliga barnnoden child. Om child är null infogas noden i slutet av listan med barn. Om child är ett DocumentFragment‑objekt infogas alla dess barn, i samma ordning, före child. Om barnet redan finns i trädet tas det först bort. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Denna metod kontrollerar om den angivna namespaceURI är standardnamnutrymmet eller inte. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Testar om två noder är lika. Denna metod testar likhet mellan noder, inte identitet (dvs. om de två noderna är referenser till samma objekt) vilket kan testas med Node.isSameNode(). Alla noder som är identiska kommer också att vara lika, även om omvända inte nödvändigtvis är sanna. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Metoden är ett äldre alias för den strikt lika operatorn ===. Det vill säga, den testar om två noder är identiska (med andra ord, om de refererar till samma objekt). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Slå upp namespace‑URI:n som är associerad med det givna prefixet, med början från denna nod. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Slå upp prefixet som är associerat med den givna namespace‑URI:n, med början från denna nod. Standard‑namnutrymmesdeklarationer ignoreras av denna metod. Se Namespace Prefix Lookup för detaljer om algoritmen som används av denna metod. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate)(*[RequestMessage](../../aspose.svg.net/requestmessage/)*) | Laddar dokumentet baserat på det angivna begärande objektet och ersätter det tidigare innehållet. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_8)(*string*) | Laddar dokumentet från den angivna Uniform Resource Locator (URL) till den aktuella instansen och ersätter det tidigare innehållet. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_2)(*[Url](../../aspose.svg/url/)*) | Laddar dokumentet från den angivna Uniform Resource Locator (URL) till den aktuella instansen och ersätter det tidigare innehållet. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_1)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | Laddar dokumentet baserat på det angivna begärande objektet och ersätter det tidigare innehållet. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_6)(*Stream, string*) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_4)(*Stream, [Url](../../aspose.svg/url/)*) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_13)(*string, CancellationToken*) | Laddar dokumentet från den angivna Uniform Resource Locator (URL) till den aktuella instansen och ersätter det tidigare innehållet. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_11)(*string, string*) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_9)(*string, [Url](../../aspose.svg/url/)*) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_3)(*[Url](../../aspose.svg/url/), CancellationToken*) | Laddar dokumentet från den angivna Uniform Resource Locator (URL) till den aktuella instansen och ersätter det tidigare innehållet. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_7)(*Stream, string, CancellationToken*) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_5)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_12)(*string, string, CancellationToken*) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_10)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | Laddar dokumentet asynkront baserat på det angivna begärande objektet. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_6)(*string, CancellationToken*) | Laddar dokumentet asynkront från den angivna Uniform Resource Locator (URL) till den aktuella instansen. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_1)(*[Url](../../aspose.svg/url/), CancellationToken*) | Laddar dokumentet asynkront från den angivna Uniform Resource Locator (URL) till den aktuella instansen. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_3)(*Stream, string, CancellationToken*) | Laddar dokumentet asynkront från angivet innehåll och använder baseUri för att lösa relativa resurser. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_2)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | Laddar dokumentet asynkront från angivet innehåll och använder baseUri för att lösa relativa resurser. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_5)(*string, string, CancellationToken*) | Laddar dokumentet asynkront från angivet innehåll och använder baseUri för att lösa relativa resurser. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_4)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | Laddar dokumentet asynkront från angivet innehåll och använder baseUri för att lösa relativa resurser. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Placera alla Text‑noder i hela djupet av delträdet under denna Node, inklusive attributnoder, i ett "normal" format där endast strukturen (t.ex. element, kommentarer, processinstruktioner, CDATA‑sektioner och entitetsreferenser) separerar Text‑noder, d.v.s. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (såsom XPointer [XPointer] uppslag) som beror på en specifik dokumentträdstruktur ska användas. Om parametern "normalize-characters" för DOMConfiguration‑objektet som är kopplat till Node.ownerDocument är true, kommer denna metod också att fullt ut normalisera tecknen i Text‑noderna. |
| [QuerySelector](../../aspose.svg.dom/document/queryselector/)(*string*) | Returnerar det första Elementet i dokumentet som matchar selektorn |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall/)(*string*) | Returnerar en NodeList med alla Element i dokumentet som matchar selektorn |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Tar bort en barnnod från DOM och returnerar den borttagna noden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| virtual [RenderTo](../../aspose.svg.dom/document/renderto/)(*[IDevice](../../aspose.svg.rendering/idevice/)*) | Denna metod används för att rendera innehållet i det aktuella dokumentet till en angiven grafisk enhet. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Ersätter barnnoden oldChild med newChild i listan över barn och returnerar noden oldChild. Om newChild är ett DocumentFragment‑objekt ersätts oldChild av alla DocumentFragment‑barn, som infogas i samma ordning. Om newChild redan finns i trädet tas den först bort. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Returnerar en sträng som representerar den här instansen. |
| [Write](../../aspose.svg.dom/document/write/)(*params string[]*) | Skriv en textsträng till ett dokumentflöde som öppnats med open(). Observera att funktionen kan producera ett dokument som inte nödvändigtvis styrs av en DTD och därför kan ge ett ogiltigt resultat i dokumentets sammanhang. |
| [WriteLn](../../aspose.svg.dom/document/writeln/)(*params string[]*) | Skriv en textsträng följd av ett radbrytningstecken till ett dokumentflöde som öppnats med open(). Observera att funktionen kan producera ett dokument som inte nödvändigtvis styrs av en DTD och därför kan ge ett ogiltigt resultat i dokumentets sammanhang. |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [OnAbort](../../aspose.svg.dom/document/onabort/) | Hämtar eller anger händelsehanterare för OnAbort‑händelsen. |
| event [OnBlur](../../aspose.svg.dom/document/onblur/) | Hämtar eller anger händelsehanterare för OnBlur‑händelsen. |
| event [OnCancel](../../aspose.svg.dom/document/oncancel/) | Hämtar eller anger händelsehanterare för OnCancel‑händelsen. |
| event [OnCanplay](../../aspose.svg.dom/document/oncanplay/) | Hämtar eller anger händelsehanterare för OnCanplay‑händelsen. |
| event [OnCanPlayThrough](../../aspose.svg.dom/document/oncanplaythrough/) | Hämtar eller anger händelsehanterare för OnCanPlayThrough‑händelsen. |
| event [OnChange](../../aspose.svg.dom/document/onchange/) | Hämtar eller anger händelsehanterare för OnChange‑händelsen. |
| event [OnClick](../../aspose.svg.dom/document/onclick/) | Hämtar eller anger händelsehanterare för OnClick‑händelsen. |
| event [OnCueChange](../../aspose.svg.dom/document/oncuechange/) | Hämtar eller anger händelsehanterare för OnCueChange‑händelsen. |
| event [OnDblClick](../../aspose.svg.dom/document/ondblclick/) | Hämtar eller anger händelsehanterare för OnDblClick‑händelsen. |
| event [OnDurationChange](../../aspose.svg.dom/document/ondurationchange/) | Hämtar eller anger händelsehanterare för OnDurationChange‑händelsen. |
| event [OnEmptied](../../aspose.svg.dom/document/onemptied/) | Hämtar eller anger händelsehanterare för OnEmptied‑händelsen. |
| event [OnEnded](../../aspose.svg.dom/document/onended/) | Hämtar eller anger händelsehanterare för OnEnded‑händelsen. |
| event [OnError](../../aspose.svg.dom/document/onerror/) | Hämtar eller anger händelsehanterare för OnError‑händelsen. |
| event [OnFocus](../../aspose.svg.dom/document/onfocus/) | Hämtar eller anger händelsehanterare för OnFocus‑händelsen. |
| event [OnInput](../../aspose.svg.dom/document/oninput/) | Hämtar eller anger händelsehanterare för OnInput-händelse. |
| event [OnInvalid](../../aspose.svg.dom/document/oninvalid/) | Hämtar eller anger händelsehanterare för OnInvalid-händelse. |
| event [OnKeyDown](../../aspose.svg.dom/document/onkeydown/) | Hämtar eller anger händelsehanterare för OnKeyDown-händelse. |
| event [OnKeyPress](../../aspose.svg.dom/document/onkeypress/) | Hämtar eller anger händelsehanterare för OnKeyPress-händelse. |
| event [OnKeyUp](../../aspose.svg.dom/document/onkeyup/) | Hämtar eller anger händelsehanterare för OnKeyUp-händelse. |
| event [OnLoad](../../aspose.svg.dom/document/onload/) | Hämtar eller anger händelsehanterare för OnLoad-händelse. |
| event [OnLoadedData](../../aspose.svg.dom/document/onloadeddata/) | Hämtar eller anger händelsehanterare för OnLoadedData-händelse. |
| event [OnLoadedMetadata](../../aspose.svg.dom/document/onloadedmetadata/) | Hämtar eller anger händelsehanterare för OnLoadedMetadata-händelse. |
| event [OnLoadStart](../../aspose.svg.dom/document/onloadstart/) | Hämtar eller anger händelsehanterare för OnLoadStart-händelse. |
| event [OnMouseDown](../../aspose.svg.dom/document/onmousedown/) | Hämtar eller anger händelsehanterare för OnMouseDown-händelse. |
| event [OnMouseEnter](../../aspose.svg.dom/document/onmouseenter/) | Hämtar eller anger händelsehanterare för OnMouseEnter-händelse. |
| event [OnMouseLeave](../../aspose.svg.dom/document/onmouseleave/) | Hämtar eller anger händelsehanterare för OnMouseLeave-händelse. |
| event [OnMouseMove](../../aspose.svg.dom/document/onmousemove/) | Hämtar eller anger händelsehanterare för OnMouseMove-händelse. |
| event [OnMouseOut](../../aspose.svg.dom/document/onmouseout/) | Hämtar eller anger händelsehanterare för OnMouseOut-händelse. |
| event [OnMouseOver](../../aspose.svg.dom/document/onmouseover/) | Hämtar eller anger händelsehanterare för OnMouseOver-händelse. |
| event [OnMouseUp](../../aspose.svg.dom/document/onmouseup/) | Hämtar eller anger händelsehanterare för OnMouseUp-händelse. |
| event [OnMouseWheel](../../aspose.svg.dom/document/onmousewheel/) | Hämtar eller anger händelsehanterare för OnMouseWheel-händelse. |
| event [OnPause](../../aspose.svg.dom/document/onpause/) | Hämtar eller anger händelsehanterare för OnPause-händelse. |
| event [OnPlay](../../aspose.svg.dom/document/onplay/) | Hämtar eller anger händelsehanterare för OnPlay-händelse. |
| event [OnPlaying](../../aspose.svg.dom/document/onplaying/) | Hämtar eller anger händelsehanterare för OnPlaying-händelse. |
| event [OnProgress](../../aspose.svg.dom/document/onprogress/) | Hämtar eller anger händelsehanterare för OnProgress-händelse. |
| event [OnRateChange](../../aspose.svg.dom/document/onratechange/) | Hämtar eller anger händelsehanterare för OnRateChange-händelse. |
| event [OnReadyStateChange](../../aspose.svg.dom/document/onreadystatechange/) | Hämtar eller anger händelsehanterare för OnReadyStateChange‑händelsen. |
| event [OnReset](../../aspose.svg.dom/document/onreset/) | Hämtar eller anger händelsehanterare för OnReset-händelse. |
| event [OnResize](../../aspose.svg.dom/document/onresize/) | Hämtar eller anger händelsehanterare för OnResize-händelse. |
| event [OnScroll](../../aspose.svg.dom/document/onscroll/) | Hämtar eller anger händelsehanterare för OnScroll-händelse. |
| event [OnSeeked](../../aspose.svg.dom/document/onseeked/) | Hämtar eller anger händelsehanterare för OnSeeked‑händelsen. |
| event [OnSeeking](../../aspose.svg.dom/document/onseeking/) | Hämtar eller anger händelsehanterare för OnSeeking‑händelsen. |
| event [OnSelect](../../aspose.svg.dom/document/onselect/) | Hämtar eller anger händelsehanterare för OnSelect‑händelsen. |
| event [OnShow](../../aspose.svg.dom/document/onshow/) | Hämtar eller anger händelsehanterare för OnShow‑händelsen. |
| event [OnStalled](../../aspose.svg.dom/document/onstalled/) | Hämtar eller anger händelsehanterare för OnStalled‑händelsen. |
| event [OnSubmit](../../aspose.svg.dom/document/onsubmit/) | Hämtar eller anger händelsehanterare för OnSubmit‑händelsen. |
| event [OnSuspend](../../aspose.svg.dom/document/onsuspend/) | Hämtar eller anger händelsehanterare för OnSuspend‑händelsen. |
| event [OnTimeUpdate](../../aspose.svg.dom/document/ontimeupdate/) | Hämtar eller anger händelsehanterare för OnTimeUpdate‑händelsen. |
| event [OnToggle](../../aspose.svg.dom/document/ontoggle/) | Hämtar eller anger händelsehanterare för OnToggle‑händelsen. |
| event [OnVolumeChange](../../aspose.svg.dom/document/onvolumechange/) | Hämtar eller anger händelsehanterare för OnVolumeChange‑händelsen. |
| event [OnWaiting](../../aspose.svg.dom/document/onwaiting/) | Hämtar eller anger händelsehanterare för OnWaiting‑händelsen. |

### Se även

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
