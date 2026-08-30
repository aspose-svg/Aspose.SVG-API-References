---
title: "Enumeración BlendMode"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Enumeración Aspose.Svg.Builder.BlendMode. Especifica los modos de fusión disponibles para combinar imágenes o elementos en SVG"
type: docs
weight: 80
url: /es/net/aspose.svg.builder/blendmode/
---
## BlendMode enumeration

Especifica los modos de fusión disponibles para combinar imágenes o elementos en SVG.

```csharp
public enum BlendMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Normal | `0` | Muestra la imagen de origen tal cual, sin ninguna fusión. |
| Multiply | `1` | Multiplica los colores de la imagen de origen y del fondo. El resultado es una imagen más oscura. |
| Screen | `2` | Ilumina las partes oscuras de la imagen de origen y deja sin cambios las partes claras. |
| Overlay | `3` | Combina los modos de fusión Multiplicar y Pantalla para realzar el contraste. |
| Darken | `4` | Oscurece el fondo según los colores de la imagen de origen. |
| Lighten | `5` | Aclara el fondo según los colores de la imagen de origen. |
| ColorDodge | `6` | Ilumina el fondo para reflejar la imagen de origen. |
| ColorBurn | `7` | Oscurece el fondo para reflejar la imagen de origen. |
| HardLight | `8` | Crea un efecto de luz dura basado en el brillo de la imagen de origen. |
| SoftLight | `9` | Crea un efecto de luz suave basado en el brillo de la imagen de origen. |
| Difference | `10` | Resalta las diferencias entre la imagen de origen y el fondo. |
| Exclusion | `11` | Crea un efecto similar a Difference, pero con menor contraste. |
| Hue | `12` | Utiliza el tono de la imagen de origen combinado con la luminancia y saturación del fondo. |
| Saturation | `13` | Utiliza la saturación de la imagen de origen combinada con el tono y la luminancia del fondo. |
| Color | `14` | Utiliza el tono y la saturación de la imagen de origen combinados con la luminancia del fondo. |
| Luminosity | `15` | Utiliza la luminancia de la imagen de origen combinada con el tono y la saturación del fondo. |

## Observaciones

Los modos de fusión en SVG se utilizan para determinar cómo se combinan dos capas entre sí. Este enum ofrece una variedad de opciones que controlan cómo se mezclan los colores de las capas combinadas y producen diferentes efectos visuales.

### Ver también

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
