---
title: "ICSSStyleDeclaration Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.ICSSStyleDeclaration Schnittstelle. Die CSSStyleDeclaration Schnittstelle stellt einen einzelnen CSS-Deklarationsblock dar. Diese Schnittstelle kann verwendet werden, um die aktuell in einem Block gesetzten Stil‑Eigenschaften zu bestimmen oder Stil‑Eigenschaften explizit innerhalb des Blocks zu setzen."
type: docs
weight: 2640
url: /de/net/aspose.svg.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

Das CSSStyleDeclaration-Interface repräsentiert einen einzelnen CSS-Deklarationsblock. Dieses Interface kann verwendet werden, um die derzeit in einem Block gesetzten Stil-Eigenschaften zu ermitteln oder um Stil-Eigenschaften explizit innerhalb des Blocks festzulegen.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssstyledeclaration/csstext/) { get; set; } | Die parsbare Textdarstellung des Deklarationsblocks (ohne die umgebenden geschweiften Klammern). Das Setzen dieses Attributs führt zur Analyse des neuen Wertes und zum Zurücksetzen aller Eigenschaften im Deklarationsblock, einschließlich des Entfernens oder Hinzufügens von Eigenschaften. |
| [Item](../../aspose.svg.dom.css/icssstyledeclaration/item/) { get; } | Wird verwendet, um die Eigenschaften abzurufen, die in diesem Deklarationsblock explizit gesetzt wurden. Die Reihenfolge der mit dieser Methode abgerufenen Eigenschaften muss nicht der Reihenfolge entsprechen, in der sie gesetzt wurden. Diese Methode kann verwendet werden, um über alle Eigenschaften in diesem Deklarationsblock zu iterieren. |
| [Length](../../aspose.svg.dom.css/icssstyledeclaration/length/) { get; } | Die Anzahl der Eigenschaften, die in diesem Deklarationsblock explizit gesetzt wurden. Der gültige Indexbereich ist 0 bis Länge‑1 inklusive. |
| [ParentRule](../../aspose.svg.dom.css/icssstyledeclaration/parentrule/) { get; } | Die CSS-Regel, die diesen Deklarationsblock enthält, oder null, wenn diese CSSStyleDeclaration nicht an eine CSSRule angehängt ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertycssvalue/)(*string*) | Wird verwendet, um die Objektrepräsentation des Wertes einer CSS‑Eigenschaft abzurufen, wenn sie innerhalb dieses Deklarationsblocks explizit gesetzt wurde. Diese Methode gibt null zurück, wenn es sich bei der Eigenschaft um eine Kurzschreibweise handelt. Werte von Kurzschreibungs‑Eigenschaften können nur als Zeichenketten abgerufen und geändert werden, wobei die Methoden getPropertyValue und setProperty verwendet werden. |
| [GetPropertyPriority](../../aspose.svg.dom.css/icssstyledeclaration/getpropertypriority/)(*string*) | Wird verwendet, um die Priorität einer CSS‑Eigenschaft (z. B. das "important"-Qualifizierungsmerkmal) abzurufen, wenn die Eigenschaft in diesem Deklarationsblock explizit gesetzt wurde. |
| [GetPropertyValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertyvalue/)(*string*) | Wird verwendet, um den Wert einer CSS‑Eigenschaft abzurufen, wenn sie innerhalb dieses Deklarationsblocks explizit gesetzt wurde. |
| [RemoveProperty](../../aspose.svg.dom.css/icssstyledeclaration/removeproperty/)(*string*) | Wird verwendet, um eine CSS‑Eigenschaft zu entfernen, wenn sie innerhalb dieses Deklarationsblocks explizit gesetzt wurde. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty)(*string, string*) | Wird verwendet, um einen Eigenschaftswert mit Standardpriorität innerhalb dieses Deklarationsblocks zu setzen. Die Standardpriorität ist nicht "important", d. h. String.Empty. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(*string, string, string*) | Wird verwendet, um einen Eigenschaftswert und eine Priorität innerhalb dieses Deklarationsblocks zu setzen. |

### Siehe auch

* interface [ICSS2Properties](../icss2properties/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
