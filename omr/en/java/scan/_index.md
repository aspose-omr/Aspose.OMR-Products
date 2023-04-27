---
title: Java Scan Images to Perform OMR Operations
url: /java/scan/
description:  Java code to scan images including BMP, JPG, PNG, TIFF to perform OMR operations via Java library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Scan Images via Java" h2="Perform OMR operation by scanning images to recognize data for various scenarios such as MCQ answer sheets and surveys." >}}

{{% blocks/products/pf/feature-page-summary %}}

To **perform OMR Operations** for many applications such as data compilation, consumer surveys, time sheet / inventory counts, in the process of institutional research, community surveys, test assessment, membership subscribing forms etc [Aspose.OMR for Java](https://products.aspose.com/omr/java/) API is there to tackle workfolows easily. Developers can easily integrate and enhance it within their Java based applications as of their requirement with high accuracy. Recognition process is accurate and fast and it takes few seconds per image depending on image quality and size as well as other settings. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Scan Images with a Threshold Setting" %}}

There are certain scenarios when there is need to process an image several times by changing the threshold setting for the required result. API provides threshold setting to fine-tune the result of OMR as of the needs. Depending on the case, developers can set the value of the threshold from 0 to 100, where zero is default value. By increasing the value, results becomes more strict regarding the highlighting of the answers. TemplateProcessor [RecognizeImage method](https://apireference.aspose.com/java/omr/com.aspose.omr/TemplateProcessor#recognizeImage-java.lang.String-int-) takes threshold as the optional second parameter. Below is code with threshold settings.

{{% blocks/products/pf/feature-page-code h3="Java Code to Scan Images with a Threshold" %}}

{{< gist "aspose-com-gists" "00046127a0febf841d2b0a0df6e2b701" "scan-images-with-threshold-setting.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Scan Images with Recalculation" %}}

For better results instead of threshold method, API provides [Recalculate method](https://apireference.aspose.com/java/omr/com.aspose.omr/TemplateProcessor#recalculate-com.aspose.omr.RecognitionResult-) that takes the [RecognizeImage()](https://apireference.aspose.com/java/omr/com.aspose.omr/TemplateProcessor#recognizeImage-java.lang.String-) result and an optional threshold as parameters. It improves the efficiency of image processing and saves time. Developers can easily enhance the code as of their requiremnt. 

{{% blocks/products/pf/feature-page-code h3="Java Code to Scan Images with Recalculation" %}}

{{< gist "aspose-com-gists" "00046127a0febf841d2b0a0df6e2b701" "scan-images-with-recalculation.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Scan">}}
{{< /blocks/products/pf/feature-page-wrap >}}
