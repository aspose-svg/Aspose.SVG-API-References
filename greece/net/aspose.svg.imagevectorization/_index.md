---
title: "Aspose.Svg.ImageVectorization"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Το Aspose.Svg.ImageVectorization namespace περιέχει κλάσεις για τη διανυσματοποίηση εικόνων raster και τη μετατροπή τους σε έγγραφα SVG. Αυτή η διαδικασία περιλαμβάνει τη μείωση των bitmap σε γεωμετρικά σχήματα που αποτελούνται από στοιχεία μονοπατιού και την αποθήκευσή τους ως SVG. Το namespace περιλαμβάνει κλάσεις για την κατασκευή τμημάτων μονοπατιού, την απλοποίηση και εξομάλυνση σημείων ίχνους και τη διαμόρφωση επιλογών διανυσματοποίησης."
type: docs
weight: 190
url: /el/net/aspose.svg.imagevectorization/
---
Ο χώρος ονομάτων **Aspose.Svg.ImageVectorization** περιέχει κλάσεις για τη διανυσματοποίηση ραστερ εικόνων και τη μετατροπή τους σε έγγραφα SVG. Αυτή η διαδικασία περιλαμβάνει τη μείωση των bitmap σε γεωμετρικά σχήματα που αποτελούνται από στοιχεία διαδρομής και την αποθήκευσή τους ως SVG. Ο χώρος ονομάτων περιλαμβάνει κλάσεις για την κατασκευή τμημάτων διαδρομής, την απλοποίηση και εξομάλυνση σημείων ίχνους, καθώς και τη διαμόρφωση επιλογών διανυσματοποίησης.

## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [BezierPathBuilder](./bezierpathbuilder/) | Το [`BezierPathBuilder`](../aspose.svg.imagevectorization/bezierpathbuilder/) κλάση είναι υπεύθυνη για την κατασκευή μιας καμπύλης Bezier από ένα δεδομένο σύνολο σημείων. Προσεγγίζει ένα ίχνος σημείων με μια καμπύλη Bezier, βελτιστοποιώντας τον αριθμό των τμημάτων ώστε να ταιριάζει στενά με το αρχικό ίχνος ενώ ελαχιστοποιεί την πολυπλοκότητα. |
| [ImageTraceSimplifier](./imagetracesimplifier/) | Η κλάση ImageTraceSimplifier είναι υπεύθυνη για τη μείωση του αριθμού των σημείων σε μια καμπύλη που προσεγγίζεται από μια σειρά σημείων ίχνους. |
| [ImageTraceSmoother](./imagetracesmoother/) | Η κλάση ImageTraceSimplifier είναι υπεύθυνη για την εξομάλυνση του αριθμού των σημείων σε μια καμπύλη που προσεγγίζεται από μια σειρά σημείων ίχνους. Αυτή η κλάση υλοποιεί την προσέγγιση του πλησιέστερου γείτονα. |
| [ImageVectorizer](./imagevectorizer/) | Αυτή η κλάση ImageVectorizer μετατρέπει εικόνες raster όπως PNG, JPG, GIF, BMP κ.λπ... και επιστρέφει το SVGDocument. Με τον όρο διανυσματοποίηση εννοούμε τη διαδικασία μείωσης των bitmap σε γεωμετρικά σχήματα που αποτελούνται από στοιχεία διαδρομής και αποθηκεύονται ως SVG. |
| [ImageVectorizerConfiguration](./imagevectorizerconfiguration/) | Η κλάση [`ImageVectorizerConfiguration`](../aspose.svg.imagevectorization/imagevectorizerconfiguration/) ορίζει μια διαμόρφωση μεθόδων και επιλογών διανυσματοποίησης εικόνας. Η διαμόρφωση χρησιμοποιείται για την αρχικοποίηση ενός ImageVectorizer και παρέχει τις επιλογές διαμόρφωσης για τη διανυσματοποίηση εικόνων. |
| [SplinePathBuilder](./splinepathbuilder/) | Η κλάση [`SplinePathBuilder`](../aspose.svg.imagevectorization/splinepathbuilder/) σχεδιάστηκε για την κατασκευή μιας ομαλής διαδρομής μετατρέποντας τις κεντρικές καμπύλες Catmull–Rom σε καμπύλες Bezier. Παρέχει μια μέθοδο για τη δημιουργία μιας διαδρομής που παρεμβάλλεται ομαλά μέσω ενός συνόλου σημείων, προσφέροντας μια ισορροπία μεταξύ πιστότητας στα σημεία και ομαλότητας της καμπύλης. |
| [StencilConfiguration](./stencilconfiguration/) | Η κλάση [`StencilConfiguration`](../aspose.svg.imagevectorization/stencilconfiguration/) ορίζει μια διαμόρφωση επιλογών εφέ στένσιλ. |
## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [IImageTraceSimplifier](./iimagetracesimplifier/) | Η διεπαφή IImageTraceSimplifier είναι υπεύθυνη για τη μείωση των σημείων στην ίχνη. |
| [IImageTraceSmoother](./iimagetracesmoother/) | Η διεπαφή IImageTraceSmoother είναι υπεύθυνη για την εξομάλυνση της ίχνης. |
| [IPathBuilder](./ipathbuilder/) | Η διεπαφή IPathBuilder είναι υπεύθυνη για την κατασκευή τμημάτων διαδρομής [`SVGPathSeg`](../aspose.svg.paths/svgpathseg/) από τη λίστα των σημείων της ίχνης. |
## Απαρίθμηση

| Απαρίθμηση | Περιγραφή |
| --- | --- |
| [StencilType](./stenciltype/) | Η απαρίθμηση [`StencilType`](../aspose.svg.imagevectorization/stenciltype/) ορίζει τύπους στένσιλ. |
