---
############################# Static ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: en
product: "Classification"
product_tag: "classification"
platform: "Net"
platform_tag: "net"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"

############################# Head ############################
head_title: ".NET API for Text and Document Classification"
head_description: "C# .NET API for text and document classification using IAB-2, Document, and Sentiment taxonomies. Classify content in various formats including PDF, DOC, DOCX, RTF, and TXT."

############################# Header ############################
title: ".NET Text and Document Classification API"
description: "Classify texts and documents in .NET applications using multiple taxonomies."
words:
  for: "for"

actions:
  main: "Download Trial via NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "Licensing"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "Ready to Get Started?"
  description: "Try GroupDocs.Classification features for free or request a license"

release:
  title: "Version {0} released"
  notes: "See what's new"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "Classify PDF with IAB-2 Taxonomy in C#"
  more: "More examples"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // Create an instance of Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // Classify a PDF document using IAB-2 taxonomy
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // Print the best class name and probability
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Classification Overview"
  description: ".NET solution for automated text and document classification using various taxonomies."
  features:
    # feature loop
    - title: "Classify Text and Documents with C#"
      content: "Easily classify content using IAB-2, Document, and Sentiment taxonomies with GroupDocs.Classification for .NET."

    # feature loop
    - title: "Support for Multiple File Formats"
      content: "Process various document types including PDF, DOC, DOCX, RTF, TXT, and more."

    # feature loop
    - title: "Flexible Classification Options"
      content: "Choose the number of results to return and adjust precision/recall balance for Documents taxonomy."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platform independence"
  description: "GroupDocs.Classification for .NET supports the following operating systems, frameworks, and package managers"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: ".NET"
      image: "net"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "Supported file formats"
  description: |
    GroupDocs.Classification for .NET supports operations with the following [file formats](https://docs.groupdocs.com/classification/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office Formats
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### OpenDocument & Other Formats
        * **OpenOffice:** ODT, OTT
        * **Fixed Layout:** PDF
        * **Other:** TXT

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Classification Features"
  description: "Classify text and documents using advanced taxonomies and options."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Multiple Taxonomies"
      content: "Supports IAB-2, Document, and Sentiment taxonomies for versatile classification."

    # feature loop
    - icon: "rasterize"
      title: "Multi-Language Support"
      content: "Perform sentiment classification in both English and Chinese."

    # feature loop
    - icon: "sourcecode"
      title: "Customizable Results"
      content: "Specify the number of classification results to return."

    # feature loop
    - icon: "transform"
      title: "Precision Control"
      content: "Adjust precision/recall balance for Documents taxonomy classification."

    # feature loop
    - icon: "adjustment"
      title: "Multiple File Formats"
      content: "Compatible with various document formats including PDF, DOC, DOCX, RTF, and TXT."

    # feature loop
    - icon: "complex"
      title: "Easy Integration"
      content: "Seamlessly integrate with any .NET application, including ASP.NET and Windows apps."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Code samples"
  description: "Some use cases of typical GroupDocs.Classification for .NET operations"
  items:
    # code sample loop
    - title: "Classify Text using IAB-2 Taxonomy"
      content: |
        This example shows how to classify raw text using the IAB-2 taxonomy:
        
        ```csharp {style=abap}
        // Create a classification request
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "Try Text classification"
        }, "3");

        // Get classification results
        var response = apiInstance.Classify(request);

        // Print the results
        Console.WriteLine(response.ToString());
        ```
        
    # code sample loop
    - title: "Sentiment Analysis of a Document"
      content: |
        You can perform sentiment analysis on documents using the Sentiment taxonomy:
        
        ```csharp {style=abap}
        // Create an instance of Classifier
        var classifier = new GroupDocs.Classification.Classifier();

        // Classify a document using Sentiment taxonomy
        var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Sentiment);

        // Print the sentiment and probability
        Console.WriteLine($"Sentiment: {response.BestClassName}");
        Console.WriteLine($"Probability: {response.BestClassProbability}");
        ```

---
