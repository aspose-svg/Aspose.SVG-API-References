---
title: "SVGDocument.Save"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGDocument Save‑metod. Sparar dokumentet till en lokal fil som anges av `url`. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn konstrueras som output_file_name_files. Om den angivna `url` slutar med .svgz sparas dokumentet som en komprimerad SVGZ‑fil"
type: docs
weight: 90
url: /sv/net/aspose.svg/svgdocument/save/
---
## Save(*[Url](../../url/)*) {#save_4}

Sparar dokumentet till en lokal fil som anges av `url`. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn byggs upp som: output_file_name + \"_files\". Om den angivna `url` slutar med \".svgz\" sparas dokumentet som en komprimerad SVGZ‑fil.

```csharp
public void Save(Url url)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | URL | Lokal URL till utdatafil. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `url` inte är en giltig lokal fil‑URL. |

### Se även

* class [Url](../../url/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string*) {#save_8}

Sparar dokumentet till en lokal fil som anges av `path`. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn byggs upp som: output_file_name + \"_files\". Om den angivna `url` slutar med \".svgz\" sparas dokumentet som en komprimerad SVGZ‑fil.

```csharp
public void Save(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Lokal sökväg till utdatafil. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `path` inte är en giltig lokal filsökväg. |

### Se även

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)*) {#save}

Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Resurshanteraren [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |

### Se även

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_9}

Sparar dokumentet till en lokal fil som anges av `path`. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn byggs upp som: output_file_name + \"_files\".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Lokal sökväg till utdatafil. |
| saveFormat | SVGSaveFormat | Format som dokumentet sparas i. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `path` inte är en giltig lokal filsökväg. |
| ArgumentOutOfRangeException | Kastas när det angivna *saveFormat*-värdet inte känns igen av den aktuella implementationen. |

### Se även

* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_1}

Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Resurshanteraren [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | Format som dokumentet sparas i. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Kastas när det angivna *saveFormat*-värdet inte känns igen av den aktuella implementationen. |

### Se även

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_10}

Sparar dokumentet som en `.svg`‑fil till den lokala sökväg som anges av *path*. Alla externa resurser skrivs till en syskonsmapp med namnet `{output_file_name}_files`.

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Absolut eller relativ sökväg till målfilen `.svg`. |
| saveOptions | SVGSaveOptions | Alternativ som styr enkel SVG-serialisering. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om *path* inte är en giltig lokal filsökväg. |

### Se även

* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_2}

Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Resurshanteraren [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | SVG-sparalternativ. |

### Se även

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_5}

Sparar dokumentet till en lokal fil som anges av `url`. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn byggs upp som: output_file_name + \"_files\".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | URL | Lokal URL till utdatafil. |
| saveFormat | SVGSaveFormat | Format som dokumentet sparas i. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *url* inte representerar en giltig lokal filplats (t.ex. är null, relativ eller pekar på ett icke‑fil‑schema). |
| ArgumentOutOfRangeException | Kastas när det angivna värdet *saveFormat* inte känns igen av den aktuella implementeringen. |

### Se även

* class [Url](../../url/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_6}

Sparar dokumentet som en `.svg`‑fil till *url*. Alla externa resurser placeras i en syskonsmapp med namnet `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | URL | Lokal sökväg till målfilen `.svg`. |
| saveOptions | SVGSaveOptions | Alternativ som styr enkel SVG-serialisering. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om *url* inte är en giltig lokal filsökväg. |

### Se även

* class [Url](../../url/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_7}

Sparar dokumentet som en komprimerad `.svgz`‑fil till *url*. Alla externa resurser placeras i en syskonsmapp med namnet `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGZSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | URL | Lokal sökväg till målfilen `.svgz`. |
| saveOptions | SVGZSaveOptions | Alternativ som styr SVGZ‑serialisering. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om *url* inte är en giltig lokal filsökväg. |

### Se även

* class [Url](../../url/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_3}

Sparar dokumentinnehållet och tillhörande resurser med den angivna [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGZSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Resurshanteraren för att hantera dokumentresurser, såsom filsystem eller minnesbaserad lagring. |
| saveOptions | SVGZSaveOptions | Alternativ som specificerar ytterligare sparparametrar, såsom vektoriseringpreferenser. |

### Se även

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_11}

Sparar dokumentet som en komprimerad `.svgz`‑fil till den lokala sökväg som anges av *path*. Alla externa resurser skrivs till en syskonsmapp med namnet `{output_file_name}_files`.

```csharp
public void Save(string path, SVGZSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Absolut eller relativ sökväg till målfilen `.svgz`. |
| saveOptions | SVGZSaveOptions | Alternativ som styr SVGZ‑serialisering. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om *path* inte är en giltig lokal filsökväg. |

### Se även

* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
