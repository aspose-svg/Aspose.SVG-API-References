---
title: "IWindow.Opener"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IWindow Opener Eigenschaft. Das opener IDL-Attribut des Window-Objekts muss beim Lesen das WindowProxy-Objekt des Browsing‑Kontexts zurückgeben, aus dem der aktuelle Browsing‑Kontext erstellt wurde, also seinen Opener‑Browsing‑Kontext, falls ein solcher existiert, noch verfügbar ist und der aktuelle Browsing‑Kontext seinen Opener nicht abgegeben hat; andernfalls muss null zurückgegeben werden. Beim Schreiben, wenn der neue Wert null ist, muss der aktuelle Browsing‑Kontext seinen Opener abgeben; ist der neue Wert etwas anderes, muss der User Agent die interne Methode DefineOwnProperty des Window-Objekts aufrufen und dabei den Eigenschaftsnamen opener als Schlüssel sowie den Property Descriptor  Value value Writable true Enumerable true Configurable true  als Eigenschaftsbeschreibung übergeben, wobei value der neue Wert ist."
type: docs
weight: 60
url: /de/net/aspose.svg.window/iwindow/opener/
---
## IWindow.Opener property

Das opener-IDL-Attribut des Window-Objekts muss beim Auslesen das WindowProxy-Objekt des Browsing‑Kontexts zurückgeben, aus dem der aktuelle Browsing‑Kontext erstellt wurde (sein opener‑Browsing‑Kontext), falls ein solcher existiert, noch verfügbar ist und der aktuelle Browsing‑Kontext seinen opener nicht aufgegeben hat; andernfalls muss es null zurückgeben. Beim Setzen, wenn der neue Wert null ist, muss der aktuelle Browsing‑Kontext seinen opener aufgeben; ist der neue Wert ein anderer Wert, muss der User‑Agent die interne Methode [[DefineOwnProperty]] des Window-Objekts aufrufen, wobei der Property‑Name "opener" als Schlüssel übergeben wird und der Property‑Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als Descriptor verwendet wird, wobei value der neue Wert ist.

```csharp
public IWindow Opener { get; }
```

### Property Value

Der Opener.

### Siehe auch

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
