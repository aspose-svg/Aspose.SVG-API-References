---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "TypeInfo IsDerivedFrom Methode. Diese Methode gibt zurück, ob eine Ableitung zwischen der Referenz‑Typdefinition, d.h. dem TypeInfo, auf dem die Methode aufgerufen wird, und der anderen Typdefinition, d.h. der als Parameter übergebenen, besteht."
type: docs
weight: 30
url: /de/net/aspose.svg.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Diese Methode gibt zurück, ob eine Ableitung zwischen der Referenztypdefinition, d.h. dem TypeInfo, auf dem die Methode aufgerufen wird, und der anderen Typdefinition, d.h. der als Parameter übergebenen, besteht.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeNamespaceArg | String | der Namensraum der anderen Typdefinition |
| typeNameArg | String | der Name der anderen Typdefinition. |
| derivationMethod | UInt64 | der Typ der Ableitung und die zwischen zwei Typen angewendeten Bedingungen, wie in der Liste der Konstanten dieser Schnittstelle beschrieben. |

### Rückgabewert

Wenn das Schema des Dokuments ein DTD ist oder kein Schema dem Dokument zugeordnet ist, gibt diese Methode stets false zurück. Wenn das Schema des Dokuments ein XML Schema ist, gibt die Methode true zurück, wenn die Referenz‑Typdefinition gemäß dem Ableitungsparameter von der anderen Typdefinition abgeleitet ist. Ist der Parameterwert 0 (kein Bit ist für den Parameter derivationMethod auf 1 gesetzt), gibt die Methode true zurück, wenn die andere Typdefinition durch Rekursion einer beliebigen Kombination aus {base type definition}, {item type definition} oder {member type definitions} von der Referenz‑Typdefinition aus erreicht werden kann.

### Siehe auch

* class [TypeInfo](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
