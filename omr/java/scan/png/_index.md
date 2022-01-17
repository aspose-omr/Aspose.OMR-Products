---
title: Scan PNG Images using Java
description: Java code to scan PNG images for cases like Answer Sheet Images or MCQ Answer Sheets 
url: /java/scan/png/
family: omr
platformtag: java
feature: scan
informat: PNG
outformat:
otherformats: TIFF JPEG GIF BMP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Scan PNG Images via Java" h2="Perform OMR operation on PNG images to recognize or extract data for cases such as MCQ answer sheets and surveys." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.OMR for Java](https://products.aspose.com/omr/java/) is an optical mark recognition API for recognizing and creating customized answer sheets of MCQ papers, quiz tests, feedback forms like surveys and all type of balloting forms. Programmers can easily integrate API within their OMR software solutions or building applications from scratch such as grade or GPA calculator, grade percentage or generating answer sheets. API supports multiple image formats including JPG, PNG, GIF, TIFF and BMP.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Scan PNG Images" %}}
1. Create [OmrEngine class](https://apireference.aspose.com/java/omr/com.aspose.omr/OmrEngine) object.
2. Using the object, get the omr file path and assign to [TemplateProcessor](https://apireference.aspose.com/java/omr/com.aspose.omr/TemplateProcessor).
3. Define the PNG image path and use [RecognizeImage method](https://apireference.aspose.com/java/omr/com.aspose.omr/TemplateProcessor#recognizeImage-java.lang.String-) to get the result.
4. Write the result into CSV by defining its path and using [RecognitionResult.GetCsv Method](https://apireference.aspose.com/omr/java/com.aspose.omr/RecognitionResult#getCsv--) while writing into file. Or can use [getJson()](https://apireference.aspose.com/omr/java/com.aspose.omr/RecognitionResult#getJson--).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java OMR API" %}}
You can easily use Aspose.OMR for Java directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-omr) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This sample code shows how to scan PNG images via Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "00046127a0febf841d2b0a0df6e2b701" "scan-png-images-for-omr-operation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Scan Answer Sheet Live Demos" sectionDescription="[Scan Answer Sheet](https://products.aspose.app/omr/scan-answer-sheet) right now by visiting our Live Demos website." >}}

        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your file, and apply relevant settings." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}
		
{{< /blocks/products/pf/agp/demobox >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Images Scan Options" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/omr/java/scan/tiff/" name="Scan TIFF Image" description="Tagged Image File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/omr/java/scan/jpeg/" name="Scan JPEG Image" description="Joint Photographic Expert Group" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/omr/java/scan/gif/" name="Scan GIF Image" description="Graphical Interchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/omr/java/scan/bmp/" name="Scan BMP Image" description="Bitmap Image Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}