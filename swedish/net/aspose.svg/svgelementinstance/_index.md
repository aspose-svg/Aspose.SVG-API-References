---
title: "SVGElementInstance klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.SVGElementInstance klass. Rotobjektet för varje use-element skuggträd implementerar SVGUseElementShadowRoot-gränssnittet. Detta gränssnitt definierar för närvarande inga utökningar av egenskaperna och metoderna som definieras för ShadowRoot-gränssnittet och DocumentOrShadowRoot-mixin. Men trädet som är rotat vid denna nod är helt skrivskyddat ur författarskriptens perspektiv."
type: docs
weight: 5280
url: /sv/net/aspose.svg/svgelementinstance/
---
## SVGElementInstance class

Rotobjektet för varje use-element skuggträd implementerar gränssnittet SVGUseElementShadowRoot. Detta gränssnitt definierar för närvarande inga utökningar av egenskaperna och metoderna som definieras för gränssnittet ShadowRoot och mixinen DocumentOrShadowRoot. Däremot är trädet som är rotat vid denna nod helt skrivskyddat ur författarskriptens perspektiv.

```csharp
public class SVGElementInstance : ShadowRoot
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | Returnerar den absoluta bas-URL:en för dokumentet som innehåller noden. |
| [ChildElementCount](../../aspose.svg.dom/documentfragment/childelementcount/) { get; } | Returnerar det aktuella antalet elementnoder som är barn till detta element. 0 om detta element inte har några barnnoder av nodtyp 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | Returnerar en levande [`NodeList`](../../aspose.svg.collections/nodelist/) av barnnoder för det angivna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer. |
| [Children](../../aspose.svg.dom/documentfragment/children/) { get; } | Returnerar barn-elementen för det aktuella elementet. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | Returnerar nodens första barn i trädet, eller null om noden saknar barn. |
| [FirstElementChild](../../aspose.svg.dom/documentfragment/firstelementchild/) { get; } | Returnerar den första barn‑elementnoden för detta element. Null om detta element inte har några barn‑element. |
| [Host](../../aspose.svg.dom/shadowroot/host/) { get; } | Host är ett element som innehåller detta ShadowRoot. |
| [InnerHTML](../../aspose.svg.dom/documentfragment/innerhtml/) { get; set; } | Returnerar ett fragment av HTML eller XML som representerar elementets innehåll. Kan sättas för att ersätta elementets innehåll med noder som parsas från den givna strängen. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | Returnerar nodens sista barn. Om dess förälder är ett element är barnet vanligtvis ett elementnod, ett textnod eller ett kommentarnod. Den returnerar null om det inte finns några barn-element. |
| [LastElementChild](../../aspose.svg.dom/documentfragment/lastelementchild/) { get; } | Returnerar det sista barn-elementnodet för detta element. null om detta element inte har några barn-element. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | Returnerar den lokala delen av det kvalificerade namnet för denna nod. För noder av någon annan typ än [`ELEMENT_NODE`](../../aspose.svg.dom/node/element_node/) och [`ATTRIBUTE_NODE`](../../aspose.svg.dom/node/attribute_node/) samt noder skapade med en DOM Level 1‑metod, såsom [`CreateElement`](../../aspose.svg.dom/document/createelement/), är detta alltid null. |
| [Mode](../../aspose.svg.dom/shadowroot/mode/) { get; } | Läge som detta ShadowRoot opererar i. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | Returnerar elementets namnrymd‑URI, eller null om elementet inte är i en namnrymd. |
| [NextElementSibling](../../aspose.svg.dom/documentfragment/nextelementsibling/) { get; } | Returnerar nästa syskon-elementnod för detta element. null om detta element inte har några element-syskon som kommer efter detta i dokumentträdet. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | Returnerar noden som omedelbart följer den angivna i deras förälders [`ChildNodes`](../../aspose.svg.dom/node/childnodes/), eller returnerar null om den angivna noden är det sista barnet i förälderelementet. |
| override [NodeName](../../aspose.svg.dom/documentfragment/nodename/) { get; } | Namnet på denna nod, beroende på dess typ. |
| override [NodeType](../../aspose.svg.dom/documentfragment/nodetype/) { get; } | En kod som representerar typen av det underliggande objektet. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | Returnerar eller anger värdet för den aktuella noden. |
| [OuterHTML](../../aspose.svg.dom/documentfragment/outerhtml/) { get; set; } | Returnerar ett fragment av HTML eller XML som representerar elementet och dess innehåll. Kan sättas för att ersätta elementet med noder som parsas från den givna strängen. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | Returnerar top-nivå dokumentobjektet för noden. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | Returnerar DOM‑nodens förälder [`Element`](../../aspose.svg.dom/element/), eller null om noden antingen saknar förälder, eller om dess förälder inte är ett DOM‑Element. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | Returnerar föräldern till den angivna noden i DOM-trädet. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | Returnerar namnrymdsprefixet för det angivna elementet, eller null om inget prefix har angetts. |
| [PreviousElementSibling](../../aspose.svg.dom/documentfragment/previouselementsibling/) { get; } | Returnerar föregående syskon-elementnod för detta element. null om detta element inte har några element-syskon som kommer före detta i dokumentträdet. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | Returnerar noden som omedelbart föregår den angivna i dess förälders [`ChildNodes`](../../aspose.svg.dom/node/childnodes/)‑lista, eller null om den angivna noden är den första i listan. |
| override [TextContent](../../aspose.svg.dom/documentfragment/textcontent/) { get; set; } | Detta attribut returnerar textinnehållet för detta nod och dess underordnade. När det är definierat som null har en inställning ingen effekt. Vid inställning tas eventuella barn som detta nod kan ha bort och, om den nya strängen inte är tom eller null, ersätts den med ett enda Text node som innehåller strängen som attributet har satts till. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../../aspose.svg.dom/node/)*) | Lägger till en nod i slutet av listan med barn till ett specificerat föräldranod. Om det givna barnet är en referens till en befintlig nod i dokumentet, [`AppendChild`](../../aspose.svg.dom/node/appendchild/) flyttar den från sin nuvarande position till den nya positionen (det krävs inte att noden tas bort från sin föräldranod innan den läggs till i någon annan nod). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | Returnerar en kopia av den nod som denna metod anropades på. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | Returnerar en kopia av den nod som denna metod anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Skickar ett Event till den angivna [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De vanliga reglerna för händelsebehandling (inklusive fångst‑ och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | Returnerar ett booleskt värde som indikerar om den angivna [`Node`](../../aspose.svg.dom/node/) har barnnoder eller inte. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | Infogar noden före den befintliga barnnoden child. Om child är null infogas noden i slutet av listan med barn. Om child är ett DocumentFragment‑objekt infogas alla dess barn, i samma ordning, före child. Om barnet redan finns i trädet tas det först bort. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | Denna metod kontrollerar om den angivna namespaceURI är standardnamnutrymmet eller inte. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../../aspose.svg.dom/node/)*) | Testar om två noder är lika. Denna metod testar likhet mellan noder, inte identitet (dvs. om de två noderna är referenser till samma objekt) vilket kan testas med Node.isSameNode(). Alla noder som är identiska kommer också att vara lika, även om omvända inte nödvändigtvis är sanna. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../../aspose.svg.dom/node/)*) | Metoden är ett äldre alias för den strikt lika operatorn ===. Det vill säga, den testar om två noder är identiska (med andra ord, om de refererar till samma objekt). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | Slå upp namespace‑URI:n som är associerad med det givna prefixet, med början från denna nod. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | Slå upp prefixet som är associerat med den givna namespace‑URI:n, med början från denna nod. Standard‑namnutrymmesdeklarationer ignoreras av denna metod. Se Namespace Prefix Lookup för detaljer om algoritmen som används av denna metod. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | Placera alla Text‑noder i hela djupet av delträdet under denna Node, inklusive attributnoder, i ett "normal" format där endast strukturen (t.ex. element, kommentarer, processinstruktioner, CDATA‑sektioner och entitetsreferenser) separerar Text‑noder, d.v.s. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (såsom XPointer [XPointer] uppslag) som beror på en specifik dokumentträdstruktur ska användas. Om parametern "normalize-characters" för DOMConfiguration‑objektet som är kopplat till Node.ownerDocument är true, kommer denna metod också att fullt ut normalisera tecknen i Text‑noderna. |
| [QuerySelector](../../aspose.svg.dom/documentfragment/queryselector/)(*string*) | Returnerar det första Elementet i dokumentet som matchar selektorn |
| [QuerySelectorAll](../../aspose.svg.dom/documentfragment/queryselectorall/)(*string*) | Returnerar en NodeList med alla Element i dokumentet som matchar selektorn |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../../aspose.svg.dom/node/)*) | Tar bort en barnnod från DOM och returnerar den borttagna noden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../../aspose.svg.dom/eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de pågående åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../../aspose.svg.dom/eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de pågående åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../../aspose.svg.dom/eventtarget/) medan det bearbetar en händelse, kommer den inte att triggas av de pågående åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | Ersätter barnnoden oldChild med newChild i listan över barn och returnerar noden oldChild. Om newChild är ett DocumentFragment‑objekt ersätts oldChild av alla DocumentFragment‑barn, som infogas i samma ordning. Om newChild redan finns i trädet tas den först bort. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | Returnerar en sträng som representerar den här instansen. |

### Se även

* class [ShadowRoot](../../aspose.svg.dom/shadowroot/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
