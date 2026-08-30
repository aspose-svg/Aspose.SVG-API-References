---
title: "IStorage-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.IStorage-gränssnitt. Detta gränssnitt i Web Storage‑API:t ger åtkomst till en specifik domäns session‑ eller lokala lagring. Se Web Storage‑specifikationen https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /sv/net/aspose.svg.dom/istorage/
---
## IStorage interface

Detta gränssnitt i Web Storage‑API:t ger åtkomst till en specifik domäns session‑ eller lokal lagring. Se Web Storage‑specifikationen: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | Returnerar antalet nyckel/värde‑par. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | Tar bort alla nyckel/värde‑par, om det finns några. |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | Returnerar det aktuella värdet som är associerat med den angivna nyckeln, eller null om den angivna nyckeln inte finns. |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | Returnerar namnet på den n:te nyckeln, eller null om n är större än eller lika med antalet nyckel/värde-par. |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | Tar bort nyckel/värde-paret med den angivna nyckeln, om ett nyckel/värde-par med den angivna nyckeln finns. |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | Sätter värdet för paret identifierat av nyckeln till värdet, och skapar ett nytt nyckel/värde-par om inget tidigare fanns för nyckeln. |

### Se även

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
