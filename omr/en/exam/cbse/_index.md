---
title: Creating and reading machine-readable CBSE sheets
weight: 3920
url: /exam/cbse/
lang: en
langdirlevel: 2
locales: as,he,or,pa,ru,ar,fa,bg,cs,da,de,es,el,hu,hr,fr,nl,id,it,lt,lv,mk,pl,pt,ro,sk,sl,sv,sr,vi,th,tr,ko,ja,bn,gu,hi,kn,mr,ne,ta,te,ur,sd
description: Download a ready-made OMR CBSE sheet in PDF format for practicing and coaching. Process dozens of completed CBSE forms per minute.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="OMR CBSE Sheet" h2="Creating and reading machine-readable CBSE sheets" pfName="Aspose.OMR" subTitlepfName="Make OMR Exam CNSE Form" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/ocr/headers/aspose_ocr-for-net.svg">}}

{{< blocks/products/pf/main-container pfName="Aspose.OMR" subTitlepfName="Make OMR Exam CNSE Form" >}}


{{% blocks/products/pf/agp/content h2="Machine-readable CBSE sheet" %}}

<p>The Central Board of Secondary Education (CBSE) is the state-controlled board of education for public and private schools. Being one of the most prestigious and recognized boards of education in India, it conducts final examinations for 10th and 12th grades. The exams are held every year in March and the results are announced at the end of May. The CBSE exams are held in pen and paper mode, with participants filling in the bubbles corresponding to the correct answers with a blue or black ballpoint pen.</p>

<p>Manual reading and evaluation of each completed CBSE exam sheet is a tedious and error-prone process which wastes valuable time that can be devoted to coaching and practice. This is where Optical Mark Recognition (OMR) technology comes to the rescue. It allows for automatically processing dozens of manually filled forms in seconds. However, this usually requires specialized scoring devices that are not affordable for individual tutors and small / medium training courses. But don't worry, we can offer a solution for you!</p>

<p>Aspose.OMR is a powerful OMR API that can convert a regular computer into an optical reader / scoring machine for creating and grading any multiple-choice paper test. You do not even need a scanner – simply take a photo of a completed exam sheet in class and instantly get a result that can be automatically graded or imported into a database. The Aspose.OMR API is extremely simple, versatile, and cost effective—you only need minimal programming skills and a free IDE like Visual Studio Community Edition to use it.</p>

<p>CBSE exam changes from year to year. To practice it, you will need customizable forms (worksheets) that contain questions on examination subjects. Your students must attempt these worksheets daily for capturing important ideas in the long run. Aspose.OMR will help you customize exam forms for your educational process and get results quickly without wasting a lot of time that could be spent on the educational process. The sample form below shows how to use Aspose.OMR to design and create a CBSE worksheet on Science subject for practicing the exam at schools, institutes, and coaching centers.</p>

<div class="col-lg-12">
	<div class="row">
	<div class="col-4"><a href="/omr/exam/cbse/CBSEPage1.png"><img alt="" src="/omr/exam/cbse/CBSEPage1_520.webp" width="100%" title="Click to download"/></a></div>
	<div class="col-4"><a href="/omr/exam/cbse/CBSEPage2.png"><img alt="" src="/omr/exam/cbse/CBSEPage2_520.webp" width="100%" title="Click to download"/></a></div>
	<div class="col-4"><a href="/omr/exam/cbse/CBSEPage3.png"><img alt="" src="/omr/exam/cbse/CBSEPage3_520.webp" width="100%" title="Click to download"/></a></div>
    </div>
</div>

<p>You can completely customize the OMR form by changing the sources above and re-generating the sheet for your preferred paper type. You can change the number and order of questions and create subject-specific forms that are perfectly tailored to your curriculum.</p>

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="" %}}

To add it to your project, you just need to install the *Aspose.OMR* [NuGet](https://www.nuget.org/packages/aspose.omr) package in your project with the following command:

{{% blocks/products/pf/agp/code-block title="" offSpacer="true" %}}

```cs

  PM> Install-Package Aspose.OMR
 
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/feature-page-section  h2="Instructions" %}}
Follow the guidelines below on using, customizing, and reading the CBSE exam form with Aspose.OMR.

<h3>Filling out the CBSE sheet</h3>

<p>It is desirable to take the CBSE practice under the same conditions as the final exam. Thus, candidates must follow precise instructions during the training tests to familiarize themselves with the actual test expectations:</p>
<ul>
	<li>The examinations would take from 1.5 to 2 hours, depending on the pattern of the examination.</li>
	<li>15 minutes reading time is given to the students to read the question paper.</li>
	<li>Only one bubble should be filled per question.</li>
	<li>The bubble’s circle must be completely filled with a blue or black pen.</li>
	<li>Avoid any stray marks, especially those that cross the bubbles or a barcode.</li>
	<li>Once the examination ends, students are required to submit the answer sheets regardless of the number of answered questions.</li>
</ul>

<h3>Customizing the CBSE sheet</h3>

<p>CBSE sheets cover multiple subjects – from science and mathematics to music and literature. For training and practice purposes, each form can be adjusted, so the student not only remember the correct answers, but catch important ideas in the long run. With Aspose.OMR, you can easily modify the form to focus on certain areas of the test.</p>

<p><b>The customize the CBSE sheet:</b></p>

<ul type="1">
	<li>Open the CBSE form’s source code (CBSE.txt) with any plain text editor.</li>
	<li>Change the source code according to the [guidelines.](https://docs.aspose.com/omr/net/design-form/)</li>
	<li>Customize the paper size, bubble color, font, and other [global page settings.](https://docs.aspose.com/omr/net/generate-template/page-setup/)</li>
</ul>

<p><b>Once complete, run the following code to [generate](https://docs.aspose.com/omr/net/generate-template/) a printable template for the CBSE form:</b></p>

{{% blocks/products/pf/agp/code-block title="Build OMR CBSE Sheet Form with Aspose OMR engine" offSpacer="true" %}}

```cs
    
    Aspose.OMR.Api.OmrEngine omrEngine = new Aspose.OMR.Api.OmrEngine();
    Aspose.OMR.Generation.GlobalPageSettings globalPageSettings = new Aspose.OMR.Generation.GlobalPageSettings() {
	    PaperSize = Aspose.OMR.Generation.PaperSize.Letter,
	    BubbleColor = Aspose.OMR.Generation.Color.Red
    };
    Aspose.OMR.Generation.GenerationResult generationResult = omrEngine.GenerateTemplate("CBSE.txt", globalPageSettings);
    generationResult.Save("target-folder", "template");
    
```

{{% /blocks/products/pf/agp/code-block %}}


<p>Then simple print out the template.png file from the target folder and handle the papers to your students. You will also get the file with .OMR extension. Do not remove it – it will be required during recognition.</p>

<h3>Recognizing the completed CBSE sheet</h3>

<p>To recognize a hand-filled CBSE sheet, digitize it in one of the [supported formats](https://docs.aspose.com/omr/net/supported-file-formats/#filled-forms). There is no need for expensive hardware reader, such as Scantron. For best results, a basic office scanner or multifunction copier will suffice. If you do not have a scanner, you can simply take a picture of the form with any modern smartphone and upload the photo to your computer.</p>
<p>To read the completed CBSE sheet, use the following code:</p>

{{% blocks/products/pf/agp/code-block title="Recognize OMR CBSE filled exam sheet with Aspose OMR library" offSpacer="true" %}}

```cs
    
    Aspose.OMR.Api.OmrEngine omrEngine = new Aspose.OMR.Api.OmrEngine();
    // Load the recognition pattern for CBSE sheet template
    Aspose.OMR.Api.TemplateProcessor recognitionEngine = omrEngine.GetTemplateProcessor("template.omr");
    Aspose.OMR.Model.RecognitionResult recognitionResult = recognitionEngine.RecognizeImage("scanned-sheets/Sandeep-Vaishya.png");
    string result = recognitionResult.GetCsv();
    
```

{{% /blocks/products/pf/agp/code-block %}}

<p><a href="/omr/exam/cbse/cbse.zip"><b>template.omr </b></a> is so-called recognition pattern – a special file that is used to produce highly accurate results with the Aspose.OMR recognition engine. It is generated alongside the printable CBSE template,  make sure you do not delete or replace that file. </p>


{{% /blocks/products/pf/feature-page-section %}}


<!-- Powered By - Link to OMR App pages -->
{{% blocks/products/pf/feature-page-section %}}
<a href="https://products.aspose.app/omr/answer-sheet-designer/">
    <h4 style="font-size: 20pt;">
        Powered by Answer Sheet Designer - Make Custom OMR Form Online
    </h4>
</a>
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/agp/content h2="" %}}

<!--Feature-section Start-->
<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features"> </a>
  <div class="container">
     <h2 class="pr-ft">
    Benefits
   </h2>
   <p>
   </p>
   <div class="row">
   <div class="col">
        <em class="fa fa-file-text-o ico-blue fa-2x col-lg-2">
        </em>
        <p class="col-lg-10">
        Create CBSE OMR forms on any subject with a flexible and easy-to-use markup language.
        </p>
   </div>
   <div class="col">
        <em class="fa fa-image ico-blue fa-2x col-lg-2">
        </em>
        <p class="col-lg-10">
        Process dozens of completed forms per minute.
        </p>
   </div>
   </div>
   <div class="row">
   <div class="col">
        <em class="fa fa-globe ico-blue fa-2x col-lg-2">
        </em>
        <p class="col-lg-10">
        Superior recognition accuracy that can be further fine-tuned for perfect results even in difficult conditions.
        </p>
   </div>
   <div class="col">
        <em class="fa fa-language ico-blue fa-2x col-lg-2">
        </em>
        <p class="col-lg-10">
        No equipment needed. Use your existing office copier instead of an expensive Scantron device. You can even process photos taken with a smartphone.
        </p>
   </div>
   </div>
   <div class="row">
   <div class="col">
        <em class="fa fa-font ico-blue fa-2x col-lg-2">
        </em>
        <p class="col-lg-10">
        Personalize the forms with student’s info, QR codes, barcodes and images.
        </p>
   </div>
   <div class="col">
        <em class="fa fa-bold ico-blue fa-2x col-lg-2">
        </em>
        <p class="col-lg-10">
        Support for all popular paper sizes as well as a number of non-standard ones.
        </p>
   </div>
   </div>
    <div class="row">
   <div class="col">
        <em class="fa fa-image ico-blue fa-2x col-lg-2">
        </em>
        <p class="col-lg-10">
        Read the completed CBSE form into JSON, XML or CSV formats, which can be programmatically analyzed, scored and imported into any relational or NoSQL database.
        </p>
   </div>
   
   </div>
  </div>
</div>


{{% /blocks/products/pf/agp/content %}}

<!--Feature-section Start - plain list
{{% blocks/products/pf/feature-page-section  h2="Benefits" %}}

* Create CBSE OMR forms on any subject with a flexible and easy-to-use markup language.
* Process dozens of completed forms per minute.
* Superior recognition accuracy that can be further fine-tuned for perfect results even in difficult conditions.
* No equipment needed. Use your existing office copier instead of an expensive Scantron device. You can even process photos taken with a smartphone.
* Personalize the forms with student’s info, QR codes, barcodes and images.
* Support for all popular paper sizes as well as a number of non-standard ones.
* Read the completed CBSE form into JSON, XML or CSV formats, which can be programmatically analyzed, scored and imported into any relational or NoSQL database.

{{% /blocks/products/pf/feature-page-section %}}
-->

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Markup">}}


{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}
