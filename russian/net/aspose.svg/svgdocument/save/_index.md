---
title: "SVGDocument.Save"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGDocument Save. Сохраняет документ в локальный файл, указанный в url. Все ресурсы, используемые в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как output_file_name  _files. Если указанный url заканчивается на .svgz, документ будет сохранён как сжатый файл SVGZ"
type: docs
weight: 90
url: /ru/net/aspose.svg/svgdocument/save/
---
## Save(*[Url](../../url/)*) {#save_4}

Сохраняет документ в локальный файл, указанный параметром `url`. Все ресурсы, используемые в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: имя_выходного_файла + \"_files\". Если указанный `url` заканчивается на \".svgz\", документ будет сохранён как сжатый файл SVGZ.

```csharp
public void Save(Url url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL выходного файла. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, если указанный `url` не является действительным локальным URL файла. |

### См. также

* class [Url](../../url/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string*) {#save_8}

Сохраняет документ в локальный файл, указанный параметром `path`. Все ресурсы, используемые в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: имя_выходного_файла + \"_files\". Если указанный `url` заканчивается на \".svgz\", документ будет сохранён как сжатый файл SVGZ.

```csharp
public void Save(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Локальный путь к выходному файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, если указанный `path` не является действительным локальным путём к файлу. |

### См. также

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)*) {#save}

Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |

### См. также

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_9}

Сохраняет документ в локальный файл, указанный в `path`. Все ресурсы, используемые в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Локальный путь к выходному файлу. |
| saveFormat | SVGSaveFormat | Формат, в котором сохраняется документ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, если указанный `path` не является действительным локальным путём к файлу. |
| ArgumentOutOfRangeException | Выбрасывается, когда указанное значение *saveFormat* не распознаётся текущей реализацией. |

### См. также

* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_1}

Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | Формат, в котором сохраняется документ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Выбрасывается, когда указанное значение *saveFormat* не распознаётся текущей реализацией. |

### См. также

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_10}

Сохраняет документ в виде файла `.svg` в локальный путь, указанный *path*. Любые внешние ресурсы записываются в соседнюю папку с именем `{output_file_name}_files`.

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Абсолютный или относительный путь к целевому файлу `.svg`. |
| saveOptions | SVGSaveOptions | Параметры, которые управляют сериализацией plain-SVG. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, если *path* не является допустимым локальным путём к файлу. |

### См. также

* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_2}

Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | Параметры сохранения SVG. |

### См. также

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_5}

Сохраняет документ в локальный файл, указанный в `url`. Все ресурсы, используемые в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL выходного файла. |
| saveFormat | SVGSaveFormat | Формат, в котором сохраняется документ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *url* не представляет допустимое локальное расположение файла (например, он равен null, относительный или указывает на схему, отличную от файловой). |
| ArgumentOutOfRangeException | Выбрасывается, когда предоставленное значение *saveFormat* не распознаётся текущей реализацией. |

### См. также

* class [Url](../../url/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_6}

Сохраняет документ в виде файла `.svg` по адресу *url*. Все внешние ресурсы помещаются в соседнюю папку с именем `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный путь к целевому файлу `.svg`. |
| saveOptions | SVGSaveOptions | Параметры, которые управляют сериализацией plain-SVG. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, если *url* не является допустимым локальным путём к файлу. |

### См. также

* class [Url](../../url/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_7}

Сохраняет документ в виде сжатого файла `.svgz` по адресу *url*. Все внешние ресурсы помещаются в соседнюю папку с именем `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGZSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный путь к целевому файлу `.svgz`. |
| saveOptions | SVGZSaveOptions | Параметры, которые управляют сериализацией SVGZ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, если *url* не является допустимым локальным путём к файлу. |

### См. также

* class [Url](../../url/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_3}

Сохраняет содержимое документа и связанные ресурсы, используя указанный [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGZSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов для управления ресурсами документа, такими как файловая система или хранилище в памяти. |
| saveOptions | SVGZSaveOptions | Параметры, определяющие дополнительные параметры сохранения, такие как предпочтения векторизации. |

### См. также

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_11}

Сохраняет документ в виде сжатого файла `.svgz` в локальный путь, указанный *path*. Любые внешние ресурсы записываются в соседнюю папку с именем `{output_file_name}_files`.

```csharp
public void Save(string path, SVGZSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Абсолютный или относительный путь к целевому файлу `.svgz`. |
| saveOptions | SVGZSaveOptions | Параметры, которые управляют сериализацией SVGZ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, если *path* не является допустимым локальным путём к файлу. |

### См. также

* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
