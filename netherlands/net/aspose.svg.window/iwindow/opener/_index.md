---
title: "IWindow.Opener"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IWindow Opener eigenschap. Het opener IDL-attribuut op het Window‑object moet bij het ophalen het WindowProxy‑object van de browsing‑context retourneren waaruit de huidige browsing‑context is gecreëerd, zijn opener‑browsing‑context, als die bestaat, als deze nog beschikbaar is en als de huidige browsing‑context zijn opener niet heeft losgekoppeld; anders moet het null retourneren. Bij het instellen, als de nieuwe waarde null is, moet de huidige browsing‑context zijn opener loskoppelen; als de nieuwe waarde iets anders is, moet de user agent de interne methode DefineOwnProperty van het Window‑object aanroepen, waarbij de eigenschapsnaam opener wordt doorgegeven als de property‑key en de Property Descriptor Value value Writable true Enumerable true Configurable true als de eigenschapsdescriptor, waarbij value de nieuwe waarde is."
type: docs
weight: 60
url: /nl/net/aspose.svg.window/iwindow/opener/
---
## IWindow.Opener property

Het opener IDL-attribuut op het Window-object moet bij het opvragen het WindowProxy-object van de browsing context waaruit de huidige browsing context is gemaakt (de opener‑browsing‑context), als die bestaat, nog beschikbaar is en de huidige browsing context zijn opener niet heeft afgewezen; anders moet het null teruggeven. Bij het instellen, als de nieuwe waarde null is, moet de huidige browsing context zijn opener afwijzen; als de nieuwe waarde iets anders is, moet de user agent de interne methode [[DefineOwnProperty]] van het Window-object aanroepen, waarbij de eigenschapsnaam "opener" als sleutel wordt doorgegeven, en de Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als eigenschapsdescriptor, waarbij value de nieuwe waarde is.

```csharp
public IWindow Opener { get; }
```

### Property Value

De opener.

### Zie ook

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
