---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions AddFeMerge. Προσθέτει μια διαμόρφωση στοιχείου feMerge στον κατασκευαστή. Αυτό το στοιχείο επιτρέπει την ταυτόχρονη εφαρμογή εφέ φίλτρου αντί για διαδοχική."
type: docs
weight: 240
url: /el/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

Προσθέτει μια διαμόρφωση στοιχείου 'feMerge' στον δημιουργό. Αυτό το στοιχείο επιτρέπει την ταυτόχρονη εφαρμογή εφέ φίλτρου αντί για διαδοχική.

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Η ενέργεια διαμόρφωσης για το στοιχείο 'feMerge'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
