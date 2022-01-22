---
title: Create OMR Template using Text Markup via Java
url: /java/create/
description:  Create OMR template using different markup like text and JSON via Java library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create OMR Template via Java" h2="Generate OMR template .omr files and images by using simple text markup." >}}

{{% blocks/products/pf/feature-page-summary %}}

Create OMR templates for data collection and analysisfor tests, surveys and other plain paper forms using [Aspose.OMR for Java](https://products.aspose.com/omr/java) API. It is flexible and developers can easily design template. Tempaltes can be designed as of application nature such as surveys, course and conference evaluations, safety forms, ballot pappers, test assessment exam and quizzes and then application will be able to process billions of forms in just few sconds of time span.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Create OMR Template with Text Markup" %}}

For generating OMR template, API provides OmrEngine [GenerateTemplate method](https://apireference.aspose.com/java/omr/com.aspose.omr/OmrEngine#generateTemplate-java.lang.String-) having markup text file path as parameter. It returns a [GenerationResult object](https://apireference.aspose.com/java/omr/com.aspose.omr/GenerationResult) contating the template image and template. 

Here is the text markup used for the below code.


?text=Name__________________________________ Date____________

?grid=ID sections_count=8 

#What is OMR API main function? 

 () OCR () Capture human-marked data () There is no main function () Enhance images 

#Can OMR API process photos as well? 

 () Yes, indeed! () No 

#OMR API is available on any platform, because it is: 

 () Cross-platform code () Cloud service 

#OMR API works with any kind of OMR forms: tests, exams, questionnaires, surveys, etc.

 () Yes, indeed! () No 

#Excellent recognition results can be achieved only for filled bubbles at least for: 

() 40% () 60% () 75% () 98% 

#Do you have to mark up every question on the page? 

(Yes) Yes, that will help a lot! (No) No 

#Rate your preference from 0 to 9 with “0” being preference towards performance and “9” being preference towards flexibility.

 (0) (1) (2) (3) (4) (5) (6) (7) (8) (9) 

#I found API to be a useful tool. (5 - strongly agree, 1 - strongly disagree)

 (5) (4) (3) (2) (1)

?text= Answer sheet section 
?answer_sheet=MainQuestions elements_count=10 columns_count=5

?text=Sign________________________________

{{% blocks/products/pf/feature-page-code h3="Java Code to Generate OMR Template" %}}

{{< gist "aspose-com-gists" "c52215e5081014275b1c4cc0051c0e99" "create-omr-template-using-txt-markup.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}