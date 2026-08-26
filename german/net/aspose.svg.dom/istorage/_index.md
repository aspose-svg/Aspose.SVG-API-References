---
title: "IStorage Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.IStorage Schnittstelle. Dieses Interface der Web‑Storage‑API bietet Zugriff auf die Sitzungs‑ oder Local‑Storage eines bestimmten Domänen. Siehe Web‑Storage‑Spezifikation https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /de/net/aspose.svg.dom/istorage/
---
## IStorage interface

Dieses Interface der Web-Storage-API bietet Zugriff auf die Sitzungs- oder Local-Storage einer bestimmten Domain. Siehe Web-Storage-Spezifikation: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | Gibt die Anzahl der Schlüssel/Wert-Paare zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | Entfernt alle Schlüssel/Wert-Paare, falls vorhanden. |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | Gibt den aktuellen Wert zurück, der dem angegebenen Schlüssel zugeordnet ist, oder null, wenn der angegebene Schlüssel nicht existiert. |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | Gibt den Namen des n‑ten Schlüssels zurück, oder null, wenn n größer oder gleich der Anzahl der Schlüssel/Wert-Paare ist. |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | Entfernt das Schlüssel/Wert-Paar mit dem angegebenen Schlüssel, falls ein solches Paar existiert. |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | Setzt den Wert des durch den Schlüssel identifizierten Paares auf value und erstellt ein neues Schlüssel/Wert-Paar, falls zuvor keines für den Schlüssel existierte. |

### Siehe auch

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
