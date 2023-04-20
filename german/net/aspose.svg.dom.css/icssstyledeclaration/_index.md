---
title: Interface ICSSStyleDeclaration
second_title: Aspose.SVG für .NET-API-Referenz
description: Aspose.Svg.Dom.Css.ICSSStyleDeclaration koppel. Die CSSStyleDeclarationSchnittstelle repräsentiert einen einzelnen CSSDeklarationsblock. Diese Schnittstelle kann verwendet werden um die Stileigenschaften zu bestimmen die derzeit in einem Block festgelegt sind oder um Stileigenschaften explizit innerhalb des Blocks festzulegen.
type: docs
weight: 640
url: /de/net/aspose.svg.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

Die CSSStyleDeclaration-Schnittstelle repräsentiert einen einzelnen CSS-Deklarationsblock. Diese Schnittstelle kann verwendet werden, um die Stileigenschaften zu bestimmen, die derzeit in einem Block festgelegt sind, oder um Stileigenschaften explizit innerhalb des Blocks festzulegen.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssstyledeclaration/csstext/) { get; set; } | Die parsbare Textdarstellung des Deklarationsblocks (ohne die umgebenden geschweiften Klammern). Das Setzen dieses Attributs führt zur Analyse des neuen Werts und zum Zurücksetzen aller Eigenschaften im Deklarationsblock, einschließlich des Entfernens oder Hinzufügens von Eigenschaften. |
| [Item](../../aspose.svg.dom.css/icssstyledeclaration/item/) { get; } | Wird verwendet, um die Eigenschaften abzurufen, die explizit in diesem Deklarationsblock festgelegt wurden. Die Reihenfolge der mit dieser Methode abgerufenen Eigenschaften muss nicht der Reihenfolge entsprechen, in der sie festgelegt wurden. Mit dieser Methode kann über alle Eigenschaften in diesem Deklarationsblock iteriert werden. |
| [Length](../../aspose.svg.dom.css/icssstyledeclaration/length/) { get; } | Die Anzahl der Eigenschaften, die explizit in diesem Deklarationsblock gesetzt wurden. Der Bereich gültiger Indizes reicht von 0 bis einschließlich Länge-1. |
| [ParentRule](../../aspose.svg.dom.css/icssstyledeclaration/parentrule/) { get; } | Die CSS-Regel, die diesen Deklarationsblock enthält, oder null, wenn diese CSSStyleDeclaration nicht an eine CSSRule angehängt ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | Wird verwendet, um die Objektdarstellung des Werts einer CSS-Eigenschaft abzurufen, wenn sie explizit innerhalb dieses Deklarationsblocks festgelegt wurde. Diese Methode gibt null zurück, wenn die Eigenschaft eine abgekürzte Eigenschaft ist. Auf abgekürzte Eigenschaftswerte kann nur mit den Methoden getPropertyValue und setProperty zugegriffen und sie als Zeichenfolgen geändert werden. |
| [GetPropertyPriority](../../aspose.svg.dom.css/icssstyledeclaration/getpropertypriority/)(string) | Wird verwendet, um die Priorität einer CSS-Eigenschaft abzurufen (z. B. den „wichtigen“ Qualifizierer), wenn die Eigenschaft explizit in diesem Deklarationsblock gesetzt wurde. |
| [GetPropertyValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | Wird verwendet, um den Wert einer CSS-Eigenschaft abzurufen, wenn er explizit innerhalb dieses Deklarationsblocks festgelegt wurde. |
| [RemoveProperty](../../aspose.svg.dom.css/icssstyledeclaration/removeproperty/)(string) | Wird verwendet, um eine CSS-Eigenschaft zu entfernen, wenn sie explizit in diesem Deklarationsblock festgelegt wurde. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | Wird verwendet, um einen Eigenschaftswert mit Standardpriorität innerhalb dieses Deklarationsblocks festzulegen. Standardpriorität ist nicht „wichtig“, dh String.Empty |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | Wird verwendet, um einen Eigenschaftswert und eine Priorität innerhalb dieses Deklarationsblocks festzulegen. |

### Siehe auch

* interface [ICSS2Properties](../icss2properties/)
* namensraum [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* Montage [Aspose.SVG](../../)


