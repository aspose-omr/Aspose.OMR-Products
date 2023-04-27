---
title: C# Create OMR Template using Text and JSON Markup
url: /net/create/
description:  C# code to create OMR template using text and JSON markup via .NET library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create OMR Template via C#" h2="Generate OMR template .omr files and images by using text and JSON markup with .NET based applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

Create OMR templates for collecting data from tests, surveys and other plain paper forms using [Aspose.OMR for .NET](https://products.aspose.com/omr/net/) API. An easy to use API for developers to design template from different markups. Design the tempalte as of application type such as surveys, course and conference evaluations, ballot pappers, safety forms, test assessment exam and quizzes and then with the help of API process billions of forms in just few sconds of time span.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Create OMR Template with Text Markup" %}}


For creating OMR template, API provides [OmrEngine class](https://apireference.aspose.com/omr/net/aspose.omr.api/omrengine) [GenerateTemplate](https://apireference.aspose.com/omr/net/aspose.omr.api/omrengine/methods/generatetemplate) method have the text markup as parameter. And it returns a [GenerationResult object](https://apireference.aspose.com/omr/net/aspose.omr.generation/generationresult). Call the Save method having the template parameter. Developers can utilize [different element](https://docs.aspose.com/omr/net/template-generation/txt/elements-description/) to design and create template of their choice.

Here is an example of template with images as well as ChoiceBox and AnswerSheet.

?image=SourceImage.jpg


?text=Name__________________________________ Date____________


#What is OMR API main function?

	() OCR	() Capture human-marked data
	() There is no main function	() Enhance images
#Can OMR API process not only scans, but also photos?

	() Yes, indeed!	() No
#OMR API is available on any platform, because it is:

	() Cross-platform code	() Cloud service
#OMR API works with any kind of OMR forms: tests, exams, questionnaires, surveys, etc.

	() Yes, indeed!	() No
#Excellent recognition results can be achieved only for filled bubbles at least for:

	() 40%	() 60%	() 75%	() 98%
#Does OMR API support bubbles mapping to any key names?

	() No	() Partially	() Yes, any key names
#Do you have to mark up every question on the page?

	(Yes) Yes, that will help a lot! (No) No
#Rate your preference from 0 to 9 with "0" being preference towards performance and "9" being preference towards flexibility.

	(0) (1) (2) (3) (4) (5) (6) (7) (8) (9)
#I found aspose omr to be a useful tool. (5 - strongly agree, 1 - strongly disagree)

	(5) (4) (3) (2) (1)

?text=Answer sheet section

?answer_sheet=MainQuestions
	elements_count=50
	columns_count=5

{{% blocks/products/pf/feature-page-code h3="C# Code to Generate OMR Template" %}}

{{< gist "aspose-com-gists" "5d0b96a6ec34a40c8aa17fd7897292d5" "create-omr-template-with-image-using-text-markup.cs" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create OMR Template with Json Markup" %}}


For creating OMR template with JSON Markup, Process is same as of Text Markup other define the JSON markup and pass it to [GenerateTemplate](https://apireference.aspose.com/omr/net/aspose.omr.api/omrengine/methods/generatetemplate) method as parameter. 

Here is an example of JSON Markup for below code.

{
	"element_type": "Template",
	"children": [{
		"element_type": "Page",
		"children": [{
			"element_type": "AnswerSheet",
			"elements_count": 100
		}]
	}]
}

{{% blocks/products/pf/feature-page-code h3="C# Code to Generate OMR Template using JSON Markup" %}}

{{< gist "aspose-com-gists" "5d0b96a6ec34a40c8aa17fd7897292d5" "generate-omr-template-using-json-markup.cs" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Markup">}}
{{< /blocks/products/pf/feature-page-wrap >}}