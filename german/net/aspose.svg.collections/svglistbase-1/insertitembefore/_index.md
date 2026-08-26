---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGListBase InsertItemBefore-Methode. Fügt ein neues Element an der angegebenen Position in die Liste ein. Das erste Element hat die Nummer 0"
type: docs
weight: 90
url: /de/net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase<T>.InsertItemBefore method

Fügt ein neues Element an der angegebenen Position in die Liste ein. Das erste Element hat die Nummer 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newItem | T | Das Element, das in die Liste eingefügt werden soll. |
| index | UInt64 | Der Index des Elements, vor dem das neue Element eingefügt werden soll. Das erste Element hat die Nummer 0. Ist der Index gleich 0, wird das neue Element am Anfang der Liste eingefügt. Ist der Index größer oder gleich numberOfItems, wird das neue Element am Ende der Liste angehängt. |

### Rückgabewert

Das eingefügte Element.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Wird ausgelöst, wenn die Liste nicht geändert werden kann. |

### Siehe auch

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
