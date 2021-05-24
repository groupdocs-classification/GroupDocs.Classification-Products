---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Classification"
product_tag: "classification"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "C# .NET Document & Text Classification and Sentiment Analysis API"
head_description: "Document and raw text classification with c# .NET APIs. Categorization with IAB-2 and Documents taxonomies and consumer sentiment analysis with a taxonomy Sentiment."

############################# Header ############################
title: ".NET Text & Documents Classification API"
description: "‎Empower your .NET applications with File & Text Classifier abilities using pre-defined tags or categories within IAB-2, Documents and Sentiment taxonomies."
button:
    enable: true

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Classification for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-classification-net.png"
        product: "GroupDocs.Classification"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Overview"

            # button loop
            - link: "#features"
              text: "Features"

            # button loop
            - link: "#support"
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/classification"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/classification/net"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/classification"
        link_learn: "https://docs.groupdocs.com/classification/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Classification for .NET is an intuitive C# Netstandard 2.0 API that helps you create powerful text and document classification/categorization applications in C#, ASP.NET, ‎and other .NET-based technologies. API supports four different types of taxonomies and offers advanced document and text classification by using IAB-2 for assigning standardized text categories, Documents taxonomy as developed by Aspose for different document types, or Sentiment (and Sentiment3) for the sentiment analysis. API analyzes text, sentences, even words and supports classifying a variety of industry-standard document formats including PDF, Microsoft Word, OpenDocument, RTF, and TXT. Sentiment analysis (classification) supports English, Chinese, Spanish, and German languages with language auto-detection. API can return positiveness probability which could be used for fine-grained sentiment analysis in C#.  

      GroupDocs.Classification for .NET uses its own document processing/classification engine and does not require any external tools to be installed on the system. It targets .NET platform to develop applications and supports all popular operating systems (Windows, Linux, macOS) where .NET frameworks (including .NET Core) can be installed.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Following is an overview of GroupDocs.Classification for .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Overview"
          content: |
            * Documents classification by path and stream
            * Classify raw text
            * **IAB-2**, **Documents**, **Sentiment**, and **Sentiment3** taxonomies supported
            * Supports multiple document formats
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Classification for .NET [supports a number of popular document formats](https://docs.groupdocs.com/classification/net/supported-document-formats/).

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word**: DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF‎‎

        right:
          enable: true
          table:
            # table loop
            - title: "Other Formats"
              content: |
                * **Fixed Layout**: PDF
                * **OpenDocument**: ODT, OTT
                * **Text**: TXT

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Classification for .NET supports following Operating Systems, Frameworks & Package Managers:‎
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Operating Systems"
              content: |
                * Windows 10 (x64)
                * Windows Desktop (x64)
                * Windows Server (x64)
                * Windows Azure
                * Mac OS X x64 (10.12+)
                * Linux

            # table loop
            - icon: "fas fa-code"
              title: "Supported Frameworks"
              content: |
                * .NET Core 2.0 or later
                * .NET Framework 4.7 or higher

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Package Manager"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Development Environments"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Features ############################
features:
    enable: true
    title: "Advanced Text & Documents Classification API Features"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: |
          Classify documents by path using **IAB‑2**, **Documents**, **Sentiment**, or **Sentiment3** taxonomies

      # feature loop
      - icon: "fas fa-eye"
        content: |
          Perform Raw Text Classification with **IAB‑2**, **Documents**, **Sentiment**, or **Sentiment3** taxonomies

      # feature loop
      - icon: "fas fa-bolt"
        content: "Sentiment Classification (Analysis) for English, Chinese, Spanish, and German"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Choose the number of classified results to return"

      # feature loop
      - icon: "fas fa-code"
        content: "Work with PDF, Docs, OpenOffice and Rich Text documents"

      # feature loop
      - icon: "fas fa-cloud"
        content: "100% Working Examples & Demos are Given to Quickly Learn the Supported Features"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Unlimited Free Technical Support Provided through Product Forums"

    more_feature:
      # more_feature_loop
      - title: "Precise Document Classification"
        content: |
          GroupDocs.Classification API supports classification for a variety of document formats. The below C# code example shows how to classify a PDF file from the current folder with Documents taxonomy by returning 3 best results.

          ```cs
          // Initialize general-purpose classifier (IAB-2, Documents, Sentiment Analysis).
          var classifier = new GroupDocs.Classification.Classifier();

          // Classify pdf file with Documents taxonomy and return the 3 most likely categories.
          var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Documents);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```
      # more_feature_loop
      - title: "Precise Text Classification"
        content: |
          GroupDocs.Classification API also supports text classification. Text classification can be performed with 4 different taxonomies: IAB-2, Documents, Sentiment, and Sentiment3. The below C# code example shows how to classify text with the default (IAB-2) taxonomy by returning the best result.

          ```cs
          // Initialize general-purpose classifier (IAB-2, Documents, Sentiment Analysis).
          var classifier = new GroupDocs.Classification.Classifier();

          // Classify text with IAB-2 taxonomy and return the the best category.
          var response = classifier.Classify("Classify text using the default IAB-2 taxonomy");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

      # more_feature_loop
      - title: "Precise Multilingual Sentiment Analysis"
        content: |
          GroupDocs.Classification for .NET allows to perform cross-domain Sentiment Analysis (Classification) in English, Chinese, Spanish, and German. GroupDocs.Classification for .NET will detect the proper language(s) automatically. Sentiment analysis API use cases are illustrated by the following C# code:

          ```cs
          // Initialize cross-domain multilingual sentiment classifier. 
          // SentimentClassifier supports multilingual classification with English, Chinese, Spanish, and German.
          var classifier = new GroupDocs.Classification.SentimentClassifier();

          // Sentiment analysis of the English text.
          var response = classifier.Classify("Experience is simply the name we give our mistakes");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");

          // Sentiment analysis of the Chinese text with the same classifier and Sentiment3 (Negative/Neutral/Positive) taxonomy.
          response = classifier.Classify("熟能生巧", taxonomy: Taxonomy.Sentiment3);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Classification offers document viewing APIs for other popular development environments"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Classification for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-classification-java.png"
          product: "GroupDocs.Classification"
          platform: "Java"
          link: "/classification/java"

############################# Back to top ###############################
back_to_top:
  enable: true
---