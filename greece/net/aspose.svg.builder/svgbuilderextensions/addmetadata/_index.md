---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions AddMetadata. Προσθέτει μια διαμόρφωση στοιχείου metadata στον builder. Το στοιχείο metadata χρησιμοποιείται για την προσθήκη metadata στο περιεχόμενο SVG"
type: docs
weight: 390
url: /el/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

Προσθέτει μια διαμόρφωση στοιχείου 'metadata' στον κατασκευαστή. Το στοιχείο 'metadata' χρησιμοποιείται για την προσθήκη μεταδεδομένων στο περιεχόμενο SVG.

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| TElement | Ο τύπος που αντιπροσωπεύει το στοιχείο 'metadata' στο μοντέλο SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'metadata'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
