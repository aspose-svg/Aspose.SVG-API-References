---
title: "SVGDocument.Save"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGDocument Save‑methode. Slaat het document op in een lokaal bestand gespecificeerd door url. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map waarvan de naam wordt geconstrueerd als output_file_name _files. Als de opgegeven url eindigt op .svgz, wordt het document opgeslagen als een gecomprimeerd SVGZ‑bestand"
type: docs
weight: 90
url: /nl/net/aspose.svg/svgdocument/save/
---
## Save(*[Url](../../url/)*) {#save_4}

Slaat het document op naar het lokale bestand dat is opgegeven door `url`. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". Als de opgegeven `url` eindigt op ".svgz", wordt het document opgeslagen als een gecomprimeerd SVGZ‑bestand.

```csharp
public void Save(Url url)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Lokale URL naar uitvoerbestand. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als de opgegeven `url` geen geldige lokale bestand‑URL is. |

### Zie ook

* class [Url](../../url/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string*) {#save_8}

Slaat het document op naar het lokale bestand dat is opgegeven door `path`. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". Als de opgegeven `url` eindigt op ".svgz", wordt het document opgeslagen als een gecomprimeerd SVGZ‑bestand.

```csharp
public void Save(string path)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | String | Lokaal pad naar uitvoerbestand. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als het opgegeven `path` geen geldig lokaal bestandspad is. |

### Zie ook

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)*) {#save}

Slaat de documentinhoud en bronnen op met behulp van de [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resourceHandler | ResourceHandler | De resource‑handler [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |

### Zie ook

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_9}

Slaat het document op naar een lokaal bestand dat is opgegeven door `path`. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt geconstrueerd als: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | String | Lokaal pad naar uitvoerbestand. |
| saveFormat | SVGSaveFormat | Formaat waarin het document wordt opgeslagen. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als het opgegeven `path` geen geldig lokaal bestandspad is. |
| ArgumentOutOfRangeException | Wordt opgegooid wanneer de opgegeven *saveFormat*-waarde niet wordt herkend door de huidige implementatie. |

### Zie ook

* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_1}

Slaat de documentinhoud en bronnen op met behulp van de [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resourceHandler | ResourceHandler | De resource‑handler [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | Formaat waarin het document wordt opgeslagen. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentOutOfRangeException | Wordt opgegooid wanneer de opgegeven *saveFormat*-waarde niet wordt herkend door de huidige implementatie. |

### Zie ook

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_10}

Slaat het document op als een `.svg`-bestand naar het lokale pad dat is opgegeven door *path*. Alle externe bronnen worden weggeschreven naar een map naast het bestand met de naam `{output_file_name}_files`.

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | String | Absolute of relatieve pad naar het doel-`.svg`-bestand. |
| saveOptions | SVGSaveOptions | Opties die de plain-SVG-serialisatie regelen. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid als *path* geen geldig lokaal bestandspad is. |

### Zie ook

* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_2}

Slaat de documentinhoud en bronnen op met behulp van de [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resourceHandler | ResourceHandler | De resource‑handler [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | SVG-opslagopties. |

### Zie ook

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_5}

Slaat het document op naar een lokaal bestand dat is opgegeven door `url`. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt geconstrueerd als: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Lokale URL naar uitvoerbestand. |
| saveFormat | SVGSaveFormat | Formaat waarin het document wordt opgeslagen. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer *url* geen geldige lokale bestandslocatie vertegenwoordigt (bijv. is null, relatief, of wijst naar een niet-bestandsschema). |
| ArgumentOutOfRangeException | Wordt gegooid wanneer de opgegeven *saveFormat*-waarde niet wordt herkend door de huidige implementatie. |

### Zie ook

* class [Url](../../url/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_6}

Slaat het document op als een `.svg`-bestand naar *url*. Alle externe bronnen worden geplaatst in een map naast het bestand met de naam `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Lokaal pad van het doel-`.svg`-bestand. |
| saveOptions | SVGSaveOptions | Opties die de plain-SVG-serialisatie regelen. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid als *url* geen geldig lokaal bestandspad is. |

### Zie ook

* class [Url](../../url/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_7}

Slaat het document op als een gecomprimeerd `.svgz`-bestand naar *url*. Alle externe bronnen worden geplaatst in een map naast het bestand met de naam `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGZSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Lokaal pad van het doel-`.svgz`-bestand. |
| saveOptions | SVGZSaveOptions | Opties die de SVGZ-serialisatie regelen. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid als *url* geen geldig lokaal bestandspad is. |

### Zie ook

* class [Url](../../url/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_3}

Slaat de documentinhoud en bijbehorende bronnen op met behulp van de opgegeven [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGZSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resourceHandler | ResourceHandler | De resourcehandler om documentbronnen te beheren, zoals bestandssysteem- of geheugenopslag. |
| saveOptions | SVGZSaveOptions | Opties die extra opslagparameters specificeren, zoals vectorisatievoorkeuren. |

### Zie ook

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_11}

Slaat het document op als een gecomprimeerd `.svgz`-bestand naar het lokale pad dat is opgegeven door *path*. Alle externe bronnen worden weggeschreven naar een map naast het bestand met de naam `{output_file_name}_files`.

```csharp
public void Save(string path, SVGZSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | String | Absolute of relatieve pad naar het doel-`.svgz`-bestand. |
| saveOptions | SVGZSaveOptions | Opties die de SVGZ-serialisatie regelen. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid als *path* geen geldig lokaal bestandspad is. |

### Zie ook

* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
