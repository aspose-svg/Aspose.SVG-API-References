---
title: Class DocumentLoadErrorEvent
second_title: Aspose.SVG för .NET API Referens
description: Aspose.Svg.Dom.Events.DocumentLoadErrorEvent klass. DenDocumentLoadErrorEvent inträffar när den begärda resursen inte är tillgänglig.
type: docs
weight: 900
url: /sv/net/aspose.svg.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

Den`DocumentLoadErrorEvent` inträffar när den begärda resursen inte är tillgänglig.

```csharp
public class DocumentLoadErrorEvent : ErrorEvent
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Används för att indikera om en händelse är en bubblande händelse eller inte. Om händelsen kan bubbla är värdet sant, annars är värdet false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Används för att indikera om en händelse kan förhindras eller inte. Om standardåtgärden kan förhindras är värdet sant, annars är värdet false. |
| [ColNo](../../aspose.svg.dom.events/errorevent/colno/) { get; } | Attributet colno måste returnera värdet som det initierades till. När objektet skapas måste detta attribut initieras till noll. Det representerar kolumnnumret där felet inträffade i skriptet. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Används för att indikera[`IEventTarget`](../ieventtarget/) vars[`IEventListener`](../ieventlistener/) s bearbetas för närvarande. Detta är särskilt användbart under fångst och bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Returnerar true om preventDefault() anropades medan det annullerbara attributvärdet är sant, och annars false. |
| [Error](../../aspose.svg.dom.events/errorevent/error/) { get; } | Felattributet måste returnera värdet som det initierades till. När objektet skapas måste detta attribut initieras till null. Där så är lämpligt sätts det till objektet som representerar felet (t.ex. undantagsobjektet i fallet med ett ouppfångat DOM-undantag). |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Används för att indikera vilken fas av händelseflödet som för närvarande utvärderas. |
| [FileName](../../aspose.svg.dom.events/errorevent/filename/) { get; } | Filnamnsattributet måste returnera värdet som det initierades till. När objektet skapas måste detta attribut initieras till den tomma strängen. Det representerar den absoluta webbadressen till skriptet där felet ursprungligen inträffade. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted-attributet måste returnera värdet som det initierades till. När en händelse skapas måste attributet initieras till false. |
| [LineNo](../../aspose.svg.dom.events/errorevent/lineno/) { get; } | Lineno-attributet måste returnera värdet som det initierades till. När objektet skapas måste detta attribut initieras till noll. Det representerar radnumret där felet inträffade i skriptet. |
| [Message](../../aspose.svg.dom.events/errorevent/message/) { get; } | Meddelandeattributet måste returnera värdet som det initierades till. När objektet skapas måste detta attribut initieras till den tomma strängen. Det representerar felmeddelandet. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Används för att indikera[`IEventTarget`](../ieventtarget/) som händelsen ursprungligen skickades till. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Används för att ange tidpunkten (i millisekunder i förhållande till epok) då händelsen skapades. På grund av det faktum att vissa system kanske inte tillhandahåller denna information, kanske värdet av timeStamp inte är tillgängligt för alla händelser. När inte tillgängligt , kommer ett värde på 0 att returneras. Exempel på epoktid är tidpunkten för systemets start eller 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | Namnet på händelsen (skiftlägeskänsligt). Namnet måste vara ett XML-namn. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | Den[`InitEvent`](../event/initevent/) metod används för att initiera värdet av en[`Event`](../event/) skapad genom [`IDocumentEvent`](../idocumentevent/) gränssnitt. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas,[`PreventDefault`](../event/preventdefault/) metod används för att indikera att händelsen ska avbrytas, vilket betyder att någon standardåtgärd som normalt vidtas av implementeringen som ett resultat av händelsen inte kommer att inträffa. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar händelsen från att nå alla händelseavlyssnare som är registrerade efter den aktuella och när den skickas i ett träd förhindras även händelsen från att nå andra objekt. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | Den[`StopPropagation`](../event/stoppropagation/) metod används för att förhindra ytterligare spridning av en händelse under händelseflödet. |

### Se även

* class [ErrorEvent](../errorevent/)
* namnutrymme [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* hopsättning [Aspose.SVG](../../)


