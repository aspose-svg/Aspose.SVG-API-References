---
title: "SVGListBase-1.Initialize"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGListBase Initialize-Methode. Löscht alle vorhandenen aktuellen Elemente aus der Liste und initialisiert die Liste neu, sodass sie das durch den Parameter angegebene einzelne Element enthält."
type: docs
weight: 80
url: /de/net/aspose.svg.collections/svglistbase-1/initialize/
---
## SVGListBase<T>.Initialize method

Löscht alle vorhandenen aktuellen Elemente aus der Liste und initialisiert die Liste neu, um das einzelne durch den Parameter angegebene Element zu halten.

```csharp
public T Initialize(T newItem)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newItem | T | Das Element, das das einzige Mitglied der Liste werden soll. |

### Rückgabewert

Das Element, das in die Liste eingefügt wird.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Wird ausgelöst, wenn die Liste nicht geändert werden kann. |

### Siehe auch

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
