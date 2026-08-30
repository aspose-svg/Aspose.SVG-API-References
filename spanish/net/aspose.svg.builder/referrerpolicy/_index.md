---
title: "Enumeración ReferrerPolicy"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Aspose.Svg.Builder.ReferrerPolicy enum. Especifica la política de referencia que se usará al obtener recursos."
type: docs
weight: 1020
url: /es/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

Especifica la política de referidor que se utilizará al obtener recursos.

```csharp
public enum ReferrerPolicy
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | No se ha establecido ninguna política de referencia. |
| NoReferrer | `1` | El encabezado Referer no se enviará. |
| NoReferrerWhenDowngrade | `2` | El encabezado Referer no se enviará a orígenes con menor seguridad (HTTPS -&gt; HTTP). |
| SameOrigin | `3` | El encabezado Referer se enviará solo para solicitudes del mismo origen. |
| Origin | `4` | Solo el origen del documento se enviará como encabezado Referer. |
| StrictOrigin | `5` | Solo el origen del documento se enviará como encabezado Referer para contextos seguros. |
| OriginWhenCrossOrigin | `6` | La URL completa se enviará como encabezado Referer para solicitudes del mismo origen, pero solo el origen para solicitudes de origen cruzado. |
| StrictOriginWhenCrossOrigin | `7` | Solo el origen del documento se enviará como encabezado Referer para solicitudes del mismo origen, pero no se enviará encabezado para solicitudes de origen cruzado en contextos inseguros. |
| UnsafeUrl | `8` | La URL completa, incluido el camino y la cadena de consulta, siempre se enviará como encabezado Referer. |

### Ver también

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
