---
title: Scan PNG Images using C#
description: C# code to scan PNG images for cases like Answer Sheet Images or MCQ Answer Sheets 
url: /net/scan/png/
family: omr
platformtag: net
feature: scan
informat: PNG
outformat:
otherformats: TIFF JPEG GIF BMP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Scan PNG Images via C#" h2="Perform OMR operation by scanning PNG images to recognize or extract data for cases such as MCQ answer sheets and surveys." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.OMR for .NET](https://products.aspose.com/omr/net/) is an optical mark recognition API for generating and recognizing answer sheets of MCQ papers, quiz tests, feedback forms like surveys and all type of balloting forms. Programmers can easily integrate API within their OMR software solutions or building applications from scratch such as grade or GPA calculator, grade percentage or generating answer sheets. API supports multiple image formats including JPEG, PNG, GIF, TIFF and BMP.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Scan PNG Images" %}}
1. Create [OmrEngine class](https://apireference.aspose.com/omr/net/aspose.omr.api/omrengine) object.
2. Using the object, get the omr file path and assign to [TemplateProcessor](https://apireference.aspose.com/omr/net/aspose.omr.api/templateprocessor).
3. Define the PNG image path and use [RecognizeImage method](https://apireference.aspose.com/omr/net/aspose.omr.api/templateprocessor/methods/recognizeimage) to get the result.
4. Write the result into CSV by defining its path and using [RecognitionResult.GetCsv Method](https://apireference.aspose.com/omr/net/aspose.omr.model/recognitionresult/methods/getcsv) while writing into file. 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET OMR API" %}}
Install from command line as ```nuget install Aspose.OMR``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.OMR```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/omr/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This sample code shows how to scan PNG images via C#" offSpacer="" %}}

{{< gist "aspose-com-gists" "1e7ebb667a6dca37fc30292c0b41da72" "scan-png-image-for-omr-operation.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Other Images Scan Options" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/omr/net/scan/tiff/" name="Scan TIFF Image" description="Tagged Image File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/omr/net/scan/jpeg/" name="Scan JPEG Image" description="Joint Photographic Expert Group" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/omr/net/scan/gif/" name="Scan GIF Image" description="Graphical Interchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/omr/net/scan/bmp/" name="Scan BMP Image" description="Bitmap Image Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}