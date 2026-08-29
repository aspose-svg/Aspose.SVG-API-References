---
title: "ReferrerPolicy Enum"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Builder.ReferrerPolicy enum. Указывает политику реферера, которая будет использоваться при получении ресурсов"
type: docs
weight: 1020
url: /ru/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

Указывает политику реферера, используемую при получении ресурсов.

```csharp
public enum ReferrerPolicy
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Политика реферера не установлена. |
| NoReferrer | `1` | Заголовок Referer не будет отправлен. |
| NoReferrerWhenDowngrade | `2` | Заголовок Referer не будет отправлен к источникам с более низким уровнем безопасности (HTTPS -&gt; HTTP). |
| SameOrigin | `3` | Заголовок Referer будет отправлен только для запросов того же происхождения. |
| Origin | `4` | Только источник документа будет отправлен в заголовке Referer. |
| StrictOrigin | `5` | Только источник документа будет отправлен в заголовке Referer для безопасных контекстов. |
| OriginWhenCrossOrigin | `6` | Полный URL будет отправлен в заголовке Referer для запросов того же происхождения, но только источник будет отправлен для кросс‑происхождений. |
| StrictOriginWhenCrossOrigin | `7` | Только источник документа будет отправлен в заголовке Referer для запросов того же происхождения, но заголовок не будет отправлен для кросс‑происхождений в небезопасных контекстах. |
| UnsafeUrl | `8` | Полный URL, включая путь и строку запроса, всегда будет отправлен в заголовке Referer. |

### См. также

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
