---
title: "Enumeración ComponentTransferType"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Aspose.Svg.Builder.ComponentTransferType enum. Especifica el tipo de función de transferencia de componentes que se aplicará en el primitivo de filtro FeComponentTransfer de un SVG"
type: docs
weight: 170
url: /es/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

Especifica el tipo de función de transferencia de componentes que se aplicará en la primitiva de filtro FeComponentTransfer de un SVG.

```csharp
public enum ComponentTransferType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Identity | `0` | Representa ningún cambio en el gráfico de entrada. Este es el tipo predeterminado. |
| Table | `1` | Utiliza una tabla de búsqueda para definir la función dentro del filtro. |
| Discrete | `2` | Utiliza un conjunto de valores discretos para definir la función en el filtro. |
| Linear | `3` | Define una transformación lineal del componente dentro del filtro. |
| Gamma | `4` | Define una transformación de corrección gamma en el filtro. |

## Observaciones

El primitivo de filtro FeComponentTransfer permite la manipulación individual de los componentes de color (RGB y alfa) de los elementos gráficos utilizando diferentes tipos de funciones de transferencia. Cada tipo define un método distinto de cálculo para la transformación del componente de color dentro del filtro.

### Ver también

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
