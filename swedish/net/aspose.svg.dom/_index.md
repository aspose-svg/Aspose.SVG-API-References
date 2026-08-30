---
title: "Aspose.Svg.Dom"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom Document Object Model‑namnutrymmet tillhandahåller ett API som representerar och interagerar med alla HTML‑, XML‑ eller SVG‑dokument. DOM är en dokumentmodell som laddas i webbläsaren och representerar dokumentet som ett nodträd där varje nod representerar en del av dokumentet, t.ex. ett element, en textsträng eller en kommentar."
type: docs
weight: 70
url: /sv/net/aspose.svg.dom/
---
Namnrummet **Aspose.Svg.Dom (Document Object Model)** tillhandahåller ett API som representerar och interagerar med alla HTML-, XML- eller SVG-dokument. DOM är en dokumentmodell som laddas i webbläsaren och representerar dokumentet som ett nodträd, där varje nod motsvarar en del av dokumentet (t.ex. ett element, en textsträng eller en kommentar).

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Attr](./attr/) | Attr‑gränssnittet representerar ett attribut i ett Element‑objekt. Vanligtvis definieras de tillåtna värdena för attributet i ett schema som är kopplat till dokumentet. |
| [CDATASection](./cdatasection/) | CDATA‑sektioner används för att undkomma textblock som innehåller tecken som annars skulle betraktas som markup. |
| [CharacterData](./characterdata/) | CharacterData utökar Node med en uppsättning attribut och metoder för att komma åt teckendata i DOM. |
| [Comment](./comment/) | Arver från CharacterData och representerar innehållet i en kommentar, d.v.s. alla tecken mellan den inledande ''. |
| [Document](./document/) | Document representerar hela HTML‑, XML‑ eller SVG‑dokumentet. Konceptuellt är det roten i dokumentträdet och ger primär åtkomst till dokumentets data. |
| [DocumentFragment](./documentfragment/) | DocumentFragment är ett \"lättviktigt\" eller \"minimalistiskt\" Document‑objekt. Det är mycket vanligt att vilja kunna extrahera en del av ett dokuments träd eller skapa ett nytt fragment av ett dokument. |
| [DocumentType](./documenttype/) | DocumentType tillhandahåller ett gränssnitt till listan över enheter som är definierade för dokumentet. |
| [DOMException](./domexception/) | DOMException‑gränssnittet representerar en onormal händelse (kallad ett undantag) som uppstår som ett resultat av att anropa en metod eller komma åt en egenskap i ett webb‑API. Detta är i princip hur felvillkor beskrivs i webb‑API:er. |
| [DOMObject](./domobject/) | DOMObject‑typen används för att representera ett basobjekt för hela Document Object Model. För Java och ECMAScript är DOMObject bunden till Object‑typen. |
| [Element](./element/) | Element‑gränssnittet representerar ett element i ett HTML‑ eller XML‑dokument. |
| [Entity](./entity/) | Representerar en känd entitet, antingen parsad eller oparsad, i ett XML‑dokument. |
| [EntityReference](./entityreference/) | EntityReference‑noder kan användas för att representera en entitetsreferens i trädet. |
| [EventTarget](./eventtarget/) | Den [`EventTarget`](../aspose.svg.dom/eventtarget/) gränssnittet implementeras av alla noder i en implementation som stöder DOM‑händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika kastmetoder på en instans av Node‑gränssnittet. Gränssnittet möjliggör registrering och borttagning av händelselyssnare på ett [`EventTarget`](../aspose.svg.dom/eventtarget/) samt sändning av händelser till det [`IEventTarget`](../aspose.svg.dom.events/ieventtarget/). |
| [Node](./node/) | Node‑gränssnittet är den primära datatypen för hela Document Object Model. Det representerar en enskild nod i dokumentträdet. |
| [Notation](./notation/) | Representerar en notation som deklarerats i DTD. |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction representerar en \"processinstruktion\", som används i XML för att behålla processor‑specifik information i dokumentets text. |
| [QualifiedName](./qualifiedname/) | Representerar ett HTML‑kvalificerat namn. |
| [ShadowRoot](./shadowroot/) | ShadowRoot är en rot‑nod i ett skuggträd. |
| [Text](./text/) | Text‑gränssnittet ärver från CharacterData och representerar det textuella innehållet (benämnt teckendata i XML) för ett Element eller Attr. |
| [TypeInfo](./typeinfo/) | TypeInfo representerar en typ som refereras från Element‑ eller Attr‑noder, specificerad i de scheman som är kopplade till dokumentet. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Ett webbläsningssammanhang är en miljö där [`Document`](../aspose.svg.dom/document/)‑objekt presenteras för användaren. |
| [IChildNode](./ichildnode/) | Definierar [`IChildNode`](../aspose.svg.dom/ichildnode/)‑gränssnittet som bör implementeras av [`Node`](../aspose.svg.dom/node/) som kan ha en förälder. |
| [IDOMImplementation](./idomimplementation/) | DOMImplementation‑gränssnittet tillhandahåller ett antal metoder för att utföra operationer som är oberoende av någon specifik instans av Document Object Model. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Representerar ett gränssnitt som måste ärvas av alla element som stöder systemhändelsehantering |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Definierar [`IChildNode`](../aspose.svg.dom/ichildnode/) som inte är [`DOCUMENT_TYPE_NODE`](../aspose.svg.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | Definierar [`IParentNode`](../aspose.svg.dom/iparentnode/) som inte är av Element-typ. |
| [IParentNode](./iparentnode/) | Definierar [`IParentNode`](../aspose.svg.dom/iparentnode/)‑gränssnittet som implementeras av alla möjliga föräldrar. |
| [IStorage](./istorage/) | Detta gränssnitt i Web Storage‑API:t ger åtkomst till en specifik domäns session‑ eller lokal lagring. Se Web Storage‑specifikationen: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Lägen där ShadowRoot kan operera. |
