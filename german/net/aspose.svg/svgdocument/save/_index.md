---
title: "SVGDocument.Save"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGDocument Save‑Methode. Speichert das Dokument in einer lokalen Datei, die durch `url` angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen benachbarten Ordner gespeichert, dessen Name aus output_file_name_files konstruiert wird. Endet die angegebene `url` mit .svgz, wird das Dokument als komprimierte SVGZ‑Datei gespeichert."
type: docs
weight: 90
url: /de/net/aspose.svg/svgdocument/save/
---
## Save(*[Url](../../url/)*) {#save_4}

Speichert das Dokument in die lokale Datei, die durch `url` angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen benachbarten Ordner gespeichert, dessen Name wie folgt konstruiert wird: output_file_name + "_files". Endet die angegebene `url` mit ".svgz", wird das Dokument als komprimierte SVGZ-Datei gespeichert.

```csharp
public void Save(Url url)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| URL | URL | Lokale URL zur Ausgabedatei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn die angegebene `url` keine gültige lokale Datei‑URL ist. |

### Siehe auch

* class [Url](../../url/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string*) {#save_8}

Speichert das Dokument in die lokale Datei, die durch `path` angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen benachbarten Ordner gespeichert, dessen Name wie folgt konstruiert wird: output_file_name + "_files". Endet die angegebene `url` mit ".svgz", wird das Dokument als komprimierte SVGZ-Datei gespeichert.

```csharp
public void Save(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Lokaler Pfad zur Ausgabedatei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn der angegebene `path` kein gültiger lokaler Dateipfad ist. |

### Siehe auch

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)*) {#save}

Speichert den Dokumentinhalt und die Ressourcen mithilfe des [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen‑Handler [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |

### Siehe auch

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_9}

Speichert das Dokument in die lokale Datei, die durch `path` angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen benachbarten Ordner gespeichert, dessen Name wie folgt konstruiert wird: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Lokaler Pfad zur Ausgabedatei. |
| saveFormat | SVGSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn der angegebene `path` kein gültiger lokaler Dateipfad ist. |
| ArgumentOutOfRangeException | Wird ausgelöst, wenn der angegebene *saveFormat*-Wert von der aktuellen Implementierung nicht erkannt wird. |

### Siehe auch

* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_1}

Speichert den Dokumentinhalt und die Ressourcen mithilfe des [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen‑Handler [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Wird ausgelöst, wenn der angegebene *saveFormat*-Wert von der aktuellen Implementierung nicht erkannt wird. |

### Siehe auch

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_10}

Speichert das Dokument als `.svg`‑Datei im lokalen Pfad, der durch *path* angegeben ist. Alle externen Ressourcen werden in einen benachbarten Ordner mit dem Namen `{output_file_name}_files` geschrieben.

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Absoluter oder relativer Pfad der Ziel‑`.svg`‑Datei. |
| saveOptions | SVGSaveOptions | Optionen, die die plain-SVG-Serialisierung steuern. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Ausgelöst, wenn *path* kein gültiger lokaler Dateipfad ist. |

### Siehe auch

* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_2}

Speichert den Dokumentinhalt und die Ressourcen mithilfe des [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen‑Handler [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | SVG-Speicheroptionen. |

### Siehe auch

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_5}

Speichert das Dokument in die lokale Datei, die durch `url` angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen benachbarten Ordner gespeichert, dessen Name wie folgt konstruiert wird: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| URL | URL | Lokale URL zur Ausgabedatei. |
| saveFormat | SVGSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Ausgelöst, wenn *url* keinen gültigen lokalen Dateistandort darstellt (z. B. ist null, relativ oder verweist auf ein Nicht-Datei‑Schema). |
| ArgumentOutOfRangeException | Ausgelöst, wenn der bereitgestellte *saveFormat*-Wert von der aktuellen Implementierung nicht erkannt wird. |

### Siehe auch

* class [Url](../../url/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_6}

Speichert das Dokument als `.svg`‑Datei unter *url*. Alle externen Ressourcen werden in einen benachbarten Ordner mit dem Namen `{output_file_name}_files` abgelegt.

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| URL | URL | Lokaler Pfad der Ziel‑`.svg`‑Datei. |
| saveOptions | SVGSaveOptions | Optionen, die die plain-SVG-Serialisierung steuern. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Ausgelöst, wenn *url* kein gültiger lokaler Dateipfad ist. |

### Siehe auch

* class [Url](../../url/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_7}

Speichert das Dokument als komprimierte `.svgz`‑Datei unter *url*. Alle externen Ressourcen werden in einen benachbarten Ordner mit dem Namen `{output_file_name}_files` abgelegt.

```csharp
public void Save(Url url, SVGZSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| URL | URL | Lokaler Pfad der Ziel‑`.svgz`‑Datei. |
| saveOptions | SVGZSaveOptions | Optionen, die die SVGZ-Serialisierung steuern. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Ausgelöst, wenn *url* kein gültiger lokaler Dateipfad ist. |

### Siehe auch

* class [Url](../../url/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_3}

Speichert den Dokumentinhalt und zugehörige Ressourcen mithilfe des angegebenen [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGZSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen-Handler zur Verwaltung von Dokumentressourcen, wie Dateisystem- oder speicherbasierter Speicherung. |
| saveOptions | SVGZSaveOptions | Optionen, die zusätzliche Speicherparameter festlegen, wie Vektorisierungspräferenzen. |

### Siehe auch

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_11}

Speichert das Dokument als komprimierte `.svgz`‑Datei im lokalen Pfad, der durch *path* angegeben ist. Alle externen Ressourcen werden in einen benachbarten Ordner mit dem Namen `{output_file_name}_files` geschrieben.

```csharp
public void Save(string path, SVGZSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Absoluter oder relativer Pfad der Ziel‑`.svgz`‑Datei. |
| saveOptions | SVGZSaveOptions | Optionen, die die SVGZ-Serialisierung steuern. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Ausgelöst, wenn *path* kein gültiger lokaler Dateipfad ist. |

### Siehe auch

* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
