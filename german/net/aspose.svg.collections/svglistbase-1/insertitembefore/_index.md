---
title: SVGListBase1.InsertItemBefore
second_title: Aspose.SVG für .NET-API-Referenz
description: SVGListBase methode. Fügt an der angegebenen Position ein neues Element in die Liste ein. Das erste Element ist die Nummer 0.
type: docs
weight: 90
url: /de/net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Fügt an der angegebenen Position ein neues Element in die Liste ein. Das erste Element ist die Nummer 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newItem | T | Das Element, das in die Liste eingefügt werden soll. |
| index | UInt64 | Der Index des Elements, vor dem das neue Element eingefügt werden soll. Das erste Element hat die Nummer 0. Wenn der Index gleich 0 ist, wird das neue Element am Anfang der Liste eingefügt. Wenn der Index größer oder gleich numberOfItems ist, wird das neue Element an das Ende der Liste angehängt. |

### Rückgabewert

Das eingefügte Element.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Wird ausgelöst, wenn die Liste nicht geändert werden kann. |

### Siehe auch

* class [SVGListBase&lt;T&gt;](../)
* namensraum [Aspose.Svg.Collections](../../svglistbase-1/)
* Montage [Aspose.SVG](../../../)


