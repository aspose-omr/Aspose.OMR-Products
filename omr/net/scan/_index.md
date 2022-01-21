---
title: C# Scan Images to Perform OMR Operations
url: /net/scan/
description:  C# code to scan images including BMP, JPG, PNG, TIFF for cases like Answer Sheet Images or MCQ Answer Sheets via .NET library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Scan Images via C#" h2="Perform OMR operation by scanning images to extract data for various cases including MCQ answer sheets and surveys." >}}

{{% blocks/products/pf/feature-page-summary %}}

To **perform OMR Operations** for creating and recognizing MCQ answer sheets, quiz tests, various type of feedback forms and surveys [Aspose.OMR for .NET](https://products.aspose.com/omr/net/) API is there to tackle workfolows easily. Developers can easily integrate it within their .NET based applications to recognize fully customizable forms, scanned images and even photos with high accuracy. For recognition from the scanned images, Template markup contains graphical mapping of the elements. Recognition process is accurate and fast, takes few seconds per image depending on different varients such as image quality and size. This allows processing large numbers of forms in short span of time.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Scan Images with Recalculation" %}}

There are certain cases where there is need to process an image several times by changing the threshold setting for the desired result. Then there is need to call [RecognizeImage()](https://apireference.aspose.com/omr/net/aspose.omr.api/templateprocessor/methods/recognizeimage) method again and again. For such cases API have the ability to perform recalculation on the image in recognition process and provides [Recalculate method](https://apireference.aspose.com/omr/net/aspose.omr.api/templateprocessor/methods/recalculate) that takes the [RecognizeImage()](https://apireference.aspose.com/omr/net/aspose.omr.api/templateprocessor/methods/recognizeimage) result and an optional threshold as parameters. It improves the efficiency of image processing and saves time. Developers can easily enhance the code as of their needs. 

{{% blocks/products/pf/feature-page-code h3="C# Code to Scan Images with Recalculation" %}}

{{< gist "aspose-com-gists" "1e7ebb667a6dca37fc30292c0b41da72" "scan-images-with-recalculation.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Scan Images with Barcode Recognition" %}}

API has ability to scan images as well as recognize barcodes during OMR operation by default. Barcode value is added at the end of the CSV file. For it required things are the template where special markers will be drawn over user’s form and the images to perform OMR operation on. Process is load the OMR template with full path using [GetTemplateProcessor](https://apireference.aspose.com/omr/net/aspose.omr.api/omrengine/methods/gettemplateprocessor) of [OmrEngine class](https://apireference.aspose.com/omr/net/aspose.omr.api/omrengine). scan the images via TemplateProcessor [RecognizeImage method](https://apireference.aspose.com/omr/net/aspose.omr.api.templateprocessor/recognizeimage/methods/1) and use the RecognitionResult [GetCsv](https://apireference.aspose.com/omr/net/aspose.omr.model/recognitionresult/methods/getcsv) method to get the results into CSV. 

{{% blocks/products/pf/feature-page-code h3="C# Code to Scan Images with Barcode Recognition" %}}

{{< gist "aspose-com-gists" "1e7ebb667a6dca37fc30292c0b41da72" "scan-images-with-barcode-recognition.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Scan">}}