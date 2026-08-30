---
title: "DocumentType-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.DocumentType-klass. DocumentType tillhandahåller ett gränssnitt till listan över entiteter som är definierade för dokumentet"
type: docs
weight: 2830
url: /sv/net/aspose.svg.dom/documenttype/
---
## DocumentType class

DocumentType tillhandahåller ett gränssnitt till listan över enheter som är definierade för dokumentet.

```csharp
public class DocumentType : Node
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DocumentType](documenttype/)(*string, string, string, string, [Document](../document/)*) | Initierar en ny instans av klassen `DocumentType`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Returnerar den absoluta bas-URL:en för dokumentet som innehåller noden. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Returnerar en levande [`NodeList`](../../aspose.svg.collections/nodelist/) av barnnoder för det angivna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Returnerar nodens första barn i trädet, eller null om noden saknar barn. |
| [InternalSubset](../../aspose.svg.dom/documenttype/internalsubset/) { get; } | Den interna delmängden som en sträng, eller null om den saknas. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Returnerar nodens sista barn. Om dess förälder är ett element är barnet vanligtvis ett elementnod, ett textnod eller ett kommentarnod. Den returnerar null om det inte finns några barn-element. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Returnerar den lokala delen av det kvalificerade namnet för denna nod. För noder av någon annan typ än [`ELEMENT_NODE`](../node/element_node/) och [`ATTRIBUTE_NODE`](../node/attribute_node/) samt noder skapade med en DOM Level 1‑metod, såsom [`CreateElement`](../document/createelement/), är detta alltid null. |
| [Name](../../aspose.svg.dom/documenttype/name/) { get; } | Namnet på DTD; d.v.s. namnet som omedelbart följer DOCTYPE-nyckelordet. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Returnerar elementets namnrymd‑URI, eller null om elementet inte är i en namnrymd. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Returnerar noden som omedelbart följer den angivna i deras förälders [`ChildNodes`](../node/childnodes/), eller returnerar null om den angivna noden är det sista barnet i förälderelementet. |
| override [NodeName](../../aspose.svg.dom/documenttype/nodename/) { get; } | Namnet på denna nod, beroende på dess typ. |
| override [NodeType](../../aspose.svg.dom/documenttype/nodetype/) { get; } | En kod som representerar typen av det underliggande objektet. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Returnerar eller anger värdet för den aktuella noden. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Returnerar top-nivå dokumentobjektet för noden. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Returnerar DOM-nodens förälder [`Element`](../element/), eller null om noden antingen saknar förälder eller om dess förälder inte är ett DOM-element. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Returnerar föräldern till den angivna noden i DOM-trädet. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Returnerar namnrymdsprefixet för det angivna elementet, eller null om inget prefix har angetts. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Returnerar noden som omedelbart föregår den angivna i dess förälders [`ChildNodes`](../node/childnodes/) lista, eller null om den angivna noden är den första i listan. |
| [PublicId](../../aspose.svg.dom/documenttype/publicid/) { get; } | Den offentliga identifieraren för den externa delmängden. |
| [SystemId](../../aspose.svg.dom/documenttype/systemid/) { get; } | Systemidentifieraren för den externa delmängden. Detta kan vara en absolut URI eller inte. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | Representerar textinnehållet i noden och dess undernoder. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | Lägger till en nod i slutet av listan med barn till en angiven föräldranod. Om det angivna barnet är en referens till en befintlig nod i dokumentet, [`AppendChild`](../node/appendchild/) flyttar den från sin nuvarande position till den nya positionen (det finns inget krav på att ta bort noden från dess föräldranod innan den läggs till i någon annan nod). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Returnerar en kopia av den nod som denna metod anropades på. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Returnerar en kopia av den nod som denna metod anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Skickar ett Event till den angivna [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De vanliga reglerna för händelsebehandling (inklusive fångst‑ och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Returnerar ett booleskt värde som indikerar om den givna [`Node`](../node/) har barnnoder eller inte. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | Infogar noden före den befintliga barnnoden child. Om child är null infogas noden i slutet av listan med barn. Om child är ett DocumentFragment‑objekt infogas alla dess barn, i samma ordning, före child. Om barnet redan finns i trädet tas det först bort. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Denna metod kontrollerar om den angivna namespaceURI är standardnamnutrymmet eller inte. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | Testar om två noder är lika. Denna metod testar likhet mellan noder, inte identitet (dvs. om de två noderna är referenser till samma objekt) vilket kan testas med Node.isSameNode(). Alla noder som är identiska kommer också att vara lika, även om omvända inte nödvändigtvis är sanna. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | Metoden är ett äldre alias för den strikt lika operatorn ===. Det vill säga, den testar om två noder är identiska (med andra ord, om de refererar till samma objekt). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Slå upp namespace‑URI:n som är associerad med det givna prefixet, med början från denna nod. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Slå upp prefixet som är associerat med den givna namespace‑URI:n, med början från denna nod. Standard‑namnutrymmesdeklarationer ignoreras av denna metod. Se Namespace Prefix Lookup för detaljer om algoritmen som används av denna metod. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Placera alla Text‑noder i hela djupet av delträdet under denna Node, inklusive attributnoder, i ett "normal" format där endast strukturen (t.ex. element, kommentarer, processinstruktioner, CDATA‑sektioner och entitetsreferenser) separerar Text‑noder, d.v.s. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (såsom XPointer [XPointer] uppslag) som beror på en specifik dokumentträdstruktur ska användas. Om parametern "normalize-characters" för DOMConfiguration‑objektet som är kopplat till Node.ownerDocument är true, kommer denna metod också att fullt ut normalisera tecknen i Text‑noderna. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | Tar bort en barnnod från DOM och returnerar den borttagna noden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | Ersätter barnnoden oldChild med newChild i listan över barn och returnerar noden oldChild. Om newChild är ett DocumentFragment‑objekt ersätts oldChild av alla DocumentFragment‑barn, som infogas i samma ordning. Om newChild redan finns i trädet tas den först bort. |
| override [ToString](../../aspose.svg.dom/documenttype/tostring/)() | Returnerar en sträng som representerar den här instansen. |

### Se även

* class [Node](../node/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
