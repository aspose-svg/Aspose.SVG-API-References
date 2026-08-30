---
title: "Clase SVGElementBuilderT"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Clase Aspose.Svg.Builder.SVGElementBuilder1T. Representa una clase base para crear elementos SVG del tipo T."
type: docs
weight: 1160
url: /es/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

Representa una clase base para construir elementos SVG de tipo *T*.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elemento SVG que este constructor es responsable de crear. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | Obtiene la lista de configuraciones que se aplicarán al elemento SVG. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | Agrega una configuración de atributo al elemento SVG. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Construye el elemento SVG y le aplica todas las configuraciones. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | Aplica configuraciones a un elemento SVG existente. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | Construye el elemento SVG como un SVGElement genérico. |

### Ver también

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
