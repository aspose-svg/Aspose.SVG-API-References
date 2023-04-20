---
title: SVGDocument.Save
second_title: Référence de l'API Aspose.SVG pour .NET
description: SVGDocument méthode. Enregistre le document dans le fichier local spécifié parURL . Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent dont le nom sera construit comme  output_file_name  _files.
type: docs
weight: 90
url: /fr/net/aspose.svg/svgdocument/save/
---
## Save(Url) {#save_3}

Enregistre le document dans le fichier local spécifié par`URL` . Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(Url url)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| url | Url | URL locale vers le fichier de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`URL` n'est pas une URL de fichier local valide. |

### Voir également

* class [Url](../../url/)
* class [SVGDocument](../)
* espace de noms [Aspose.Svg](../../svgdocument/)
* Assemblée [Aspose.SVG](../../../)

---

## Save(string) {#save_6}

Enregistre le document dans le fichier local spécifié par`chemin` . Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès local au fichier de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`chemin` n'est pas un chemin de fichier local valide. |

### Voir également

* class [SVGDocument](../)
* espace de noms [Aspose.Svg](../../svgdocument/)
* Assemblée [Aspose.SVG](../../../)

---

## Save(IOutputStorage) {#save}

Enregistre le contenu et les ressources du document dans le stockage de sortie.

```csharp
public void Save(IOutputStorage outputStorage)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStorage | IOutputStorage | Le stockage de sortie[`IOutputStorage`](../../../aspose.svg.io/ioutputstorage/). |

### Voir également

* interface [IOutputStorage](../../../aspose.svg.io/ioutputstorage/)
* class [SVGDocument](../)
* espace de noms [Aspose.Svg](../../svgdocument/)
* Assemblée [Aspose.SVG](../../../)

---

## Save(string, SVGSaveFormat) {#save_7}

Enregistre le document dans le fichier local spécifié par`chemin` . Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès local au fichier de sortie. |
| saveFormat | SVGSaveFormat | Format dans lequel le document est enregistré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`chemin` n'est pas un chemin de fichier local valide. |

### Voir également

* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* espace de noms [Aspose.Svg](../../svgdocument/)
* Assemblée [Aspose.SVG](../../../)

---

## Save(IOutputStorage, SVGSaveFormat) {#save_1}

Enregistre le contenu et les ressources du document dans le stockage de sortie.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStorage | IOutputStorage | Le stockage de sortie[`IOutputStorage`](../../../aspose.svg.io/ioutputstorage/). |
| saveFormat | SVGSaveFormat | Format dans lequel le document est enregistré. |

### Voir également

* interface [IOutputStorage](../../../aspose.svg.io/ioutputstorage/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* espace de noms [Aspose.Svg](../../svgdocument/)
* Assemblée [Aspose.SVG](../../../)

---

## Save(string, SVGSaveOptions) {#save_8}

Enregistre le document dans le fichier local spécifié par`chemin` . Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès local au fichier de sortie. |
| saveOptions | SVGSaveOptions | Options d'enregistrement SVG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`chemin` n'est pas un chemin de fichier local valide. |

### Voir également

* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* espace de noms [Aspose.Svg](../../svgdocument/)
* Assemblée [Aspose.SVG](../../../)

---

## Save(IOutputStorage, SVGSaveOptions) {#save_2}

Enregistre le contenu et les ressources du document dans le stockage de sortie.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStorage | IOutputStorage | Le stockage de sortie[`IOutputStorage`](../../../aspose.svg.io/ioutputstorage/). |
| saveOptions | SVGSaveOptions | Options d'enregistrement SVG. |

### Voir également

* interface [IOutputStorage](../../../aspose.svg.io/ioutputstorage/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* espace de noms [Aspose.Svg](../../svgdocument/)
* Assemblée [Aspose.SVG](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

Enregistre le document dans le fichier local spécifié par`URL` . Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| url | Url | URL locale vers le fichier de sortie. |
| saveFormat | SVGSaveFormat | Format dans lequel le document est enregistré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`URL` n'est pas une URL de fichier local valide. |

### Voir également

* class [Url](../../url/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* espace de noms [Aspose.Svg](../../svgdocument/)
* Assemblée [Aspose.SVG](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

Enregistre le document dans le fichier local spécifié par`URL` . Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| url | Url | URL locale vers le fichier de sortie. |
| saveOptions | SVGSaveOptions | Options d'enregistrement SVG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`URL` n'est pas une URL de fichier local valide. |

### Voir également

* class [Url](../../url/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* espace de noms [Aspose.Svg](../../svgdocument/)
* Assemblée [Aspose.SVG](../../../)


