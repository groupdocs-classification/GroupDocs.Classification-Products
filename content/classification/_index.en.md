---
############################# Static ############################
layout: "family"
date:  2025-03-17T15:57:00
draft: false

product: "Classification"
product_tag: "classification"

lang: en

############################# Head ############################
head_title: ".NET API for Document & Text Classification and Sentiment Analysis"
head_description: "Powerful .NET library for document and text classification using IAB-2, Document, and Sentiment taxonomies. Supports multiple file formats and languages."

############################# Header ############################
title: "Document & Text Classification Solution"
description: |
  Easily classify documents and text using various taxonomies with our .NET API.

  Perform sentiment analysis and categorize content across multiple file formats and languages.

  Integrate advanced classification capabilities into your .NET applications with just a few lines of code.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "Choose your platform"
  title: "Platform independence"
  description: "GroupDocs.Classification for .NET is compatible with the following operating systems and frameworks:"
  details_link_title: "Learn more"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Classification for .NET
      color: "blue"
      tag: "net"
      link: "/classification/net/"
      features_link: "https://docs.groupdocs.com/classification/net/system-requirements/"
      features:
          # features loop
          - rows: "3"
            content: |
                    .NET Core 2.0 or later  .NET Framework 4.7 or higher
      
          # features loop
          - rows: "4"
            content: |
                    Windows Desktop (x64)  Windows Server (x64)  Windows Azure  Mac OS X x64 (10.12+)
      
          # features loop
          - rows: "3"
            content: |
                    Microsoft Visual Studio  JetBrains Rider  MonoDevelop
      
          # features loop
          - rows: "1"
            content: |
                    10+ file formats

############################# Features ###############################
features:
  enable: true
  title: "GroupDocs.Classification key features"
  description: "This solution helps you classify documents and text using various taxonomies, perform sentiment analysis, and integrate advanced classification capabilities into your .NET applications."

  items:
    # items loop
    - icon: "classify"
      title: "Multiple taxonomies"
      content: "Classify using IAB-2, Document, and Sentiment taxonomies."

    # items loop
    - icon: "format"
      title: "Wide format support"
      content: "Process various document formats including DOC, DOCX, PDF, and more."

    # items loop
    - icon: "analyze"
      title: "Sentiment analysis"
      content: "Perform sentiment classification for English and Chinese text."

    # items loop
    - icon: "integrate"
      title: "Easy integration"
      content: "Integrate classification capabilities with just a few lines of code."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Classify documents with ease"
  description: "GroupDocs.Classification code examples"
  items:
    # code sample loop
    - title: "Classify PDF with IAB-2 Taxonomy"
      content: |
       GroupDocs.Classification allows you to easily classify PDF documents using the IAB-2 taxonomy. Simply specify the document path, desired number of results, and taxonomy type to get classification results.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp
            // Create an instance of the Classifier
            var classifier = new GroupDocs.Classification.Classifier();

            // Classify the document
            var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

            // Print the best class and its probability
            Console.WriteLine($"Best class: {response.BestClassName}, Probability: {response.BestClassProbability}");
            ```

############################# Supported Formats ###############################
formats:
  enable: true
  title: "Supports 10+ file formats"
  description: "GroupDocs.Classification works with various popular document formats"

############################# Metrics ###############################
metrics:
  enable: true
  title: "In-depth metrics and insights"
  description: "Dive into our detailed metrics for a comprehensive view of our performance and growth."

  items:
    # items loop
    - number: "10+"
      title: "Supported Formats"
      content: "We support over 10 of the most widely used document formats."

    # items loop
    - number: "3"
      title: "Supported Taxonomies"
      content: "Classify content using IAB-2, Document, and Sentiment taxonomies."

    # items loop
    - number: "2"
      title: "Languages for Sentiment Analysis"
      content: "Perform sentiment classification in English and Chinese."

    # items loop
    - number: "4.7+"
      title: ".NET Framework Support"
      content: "Compatible with .NET Framework 4.7 or higher and .NET Core 2.0 or later."

############################# Actions ###############################
actions:
  enable: true
  title: "Ready to Get Started?"
  description: "Try GroupDocs.Classification features for free on your platform."

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# FAQ ###############################
faq:
  enable: true
  title: "Frequently Asked Questions"
  description: "Answers to common questions about GroupDocs.Classification."

  items:
    # items loop
    - question: "What types of documents can I classify with GroupDocs.Classification?"
      answer: "GroupDocs.Classification supports various document formats including Microsoft Word (DOC, DOCX, RTF), OpenOffice (ODT), PDF, and plain text (TXT) files."

    # items loop
    - question: "Can I use GroupDocs.Classification for sentiment analysis?"
      answer: "Yes, GroupDocs.Classification supports sentiment analysis for both English and Chinese text, allowing you to determine the sentiment of documents or text snippets."

    # items loop
    - question: "Is it possible to integrate GroupDocs.Classification into my existing .NET application?"
      answer: "Absolutely! GroupDocs.Classification offers a user-friendly API that can be easily integrated into your .NET applications with just a few lines of code. It's designed to seamlessly work with your existing workflows."

############################# Cloud Links ###############################
cloud_links:
  enable: false

############################# App links ###############################
app_links:
  enable: false
---