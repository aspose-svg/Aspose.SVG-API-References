---
title: "TypeInfo Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.TypeInfo Klasse. Der TypeInfo repräsentiert einen Typ, der von Element- oder Attr-Knoten referenziert wird, die in den mit dem Dokument verbundenen Schemata angegeben sind"
type: docs
weight: 3280
url: /de/net/aspose.svg.dom/typeinfo/
---
## TypeInfo class

Die TypeInfo repräsentiert einen Typ, der von Element- oder Attr-Knoten referenziert wird und in den mit dem Dokument verknüpften Schemata angegeben ist.

```csharp
public class TypeInfo : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [TypeName](../../aspose.svg.dom/typeinfo/typename/) { get; } | Der Name eines für das zugehörige Element oder Attribut deklarierten Typs, oder null, wenn unbekannt. |
| [TypeNamespace](../../aspose.svg.dom/typeinfo/typenamespace/) { get; } | Ruft den Typ-Namespace ab. Der Namespace des für das zugehörige Element oder Attribut deklarierten Typs oder null, wenn das Element keine Deklaration hat oder keine Namespace-Informationen verfügbar sind. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [IsDerivedFrom](../../aspose.svg.dom/typeinfo/isderivedfrom/)(*string, string, ulong*) | Diese Methode gibt zurück, ob eine Ableitung zwischen der Referenztypdefinition, d.h. dem TypeInfo, auf dem die Methode aufgerufen wird, und der anderen Typdefinition, d.h. der als Parameter übergebenen, besteht. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.svg.dom/typeinfo/derivation_extension/) | Wenn das Schema des Dokuments ein XML‑Schema [XML Schema Part 1] ist, stellt diese Konstante die Ableitung durch Erweiterung dar. |
| const [DERIVATION_LIST](../../aspose.svg.dom/typeinfo/derivation_list/) | Wenn das Schema des Dokuments ein XML‑Schema [XML Schema Part 1] ist, stellt diese Konstante die Liste dar. |
| const [DERIVATION_RESTRICTION](../../aspose.svg.dom/typeinfo/derivation_restriction/) | Wenn das Schema des Dokuments ein XML‑Schema [XML Schema Part 1] ist, stellt diese Konstante die Ableitung durch Einschränkung dar, wenn komplexe Typen beteiligt sind, oder eine Einschränkung, wenn einfache Typen beteiligt sind. |
| const [DERIVATION_UNION](../../aspose.svg.dom/typeinfo/derivation_union/) | Wenn das Schema des Dokuments ein XML‑Schema [XML Schema Part 1] ist, stellt diese Konstante die Vereinigung dar, wenn einfache Typen beteiligt sind. |

### Siehe auch

* class [DOMObject](../domobject/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
