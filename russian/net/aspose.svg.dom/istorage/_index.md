---
title: "Интерфейс IStorage"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Dom.IStorage. Этот интерфейс Web Storage API предоставляет доступ к сеансу или локальному хранилищу конкретного домена. См. спецификацию Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /ru/net/aspose.svg.dom/istorage/
---
## IStorage interface

Этот интерфейс Web Storage API предоставляет доступ к сеансовому или локальному хранилищу конкретного домена. См. спецификацию Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | Возвращает количество пар ключ/значение. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | Удаляет все пары ключ/значение, если они есть. |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | Возвращает текущее значение, связанное с указанным ключом, или null, если такой ключ не существует. |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | Возвращает имя n‑го ключа, или null, если n больше или равно количеству пар ключ/значение. |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | Удаляет пару ключ/значение с указанным ключом, если такая пара существует. |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | Устанавливает значение пары, идентифицированной ключом, в value, создавая новую пару ключ/значение, если ранее такой пары не существовало. |

### См. также

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
