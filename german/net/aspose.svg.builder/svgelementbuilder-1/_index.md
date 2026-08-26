---
title: "SVGElementBuilderT Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGElementBuilder1T Klasse. Stellt eine Basisklasse zum Erstellen von SVG-Elementen des Typs T dar."
type: docs
weight: 1160
url: /de/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

Stellt eine Basisklasse zum Erstellen von SVG-Elementen des Typs *T* dar.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des SVG-Elements, für dessen Erstellung dieser Builder verantwortlich ist. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | Ruft die Liste der Konfigurationen ab, die auf das SVG-Element angewendet werden sollen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | Fügt dem SVG-Element eine Attributkonfiguration hinzu. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Erstellt das SVG-Element und wendet alle Konfigurationen darauf an. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | Wendet Konfigurationen auf ein bestehendes SVG-Element an. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | Erstellt das SVG-Element als generisches SVGElement. |

### Siehe auch

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
