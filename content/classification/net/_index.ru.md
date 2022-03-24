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
head_description: "Классификация документов и необработанного текста с помощью C# .NET API. Категоризация с помощью таксономий IAB-2 и Documents и анализ настроений потребителей с помощью таксономии Sentiment."

############################# Header ############################
title: ".NET API классификации текстов и документов"
description: "Расширьте возможности своих .NET-приложений с помощью возможностей классификатора файлов и текста, используя предопределенные теги или категории в таксономиях IAB-2, Documents и Sentiment.."
button:
    enable: true

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Classification for .NET"
        image: "/border/groupdocs-classification-net.svg"
        product: "GroupDocs.Classification"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Обзор"

            # button loop
            - link: "#features"
              text: "Функции"

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

############################# Обзор ############################
overview:
    enable: true
    content: |
      GroupDocs.Classification для .NET — это интуитивно понятный API C# Netstandard 2.0, который помогает создавать мощные приложения для классификации/категоризации текста и документов на C#, ASP.NET и других технологиях на основе .NET. API поддерживает четыре различных типа таксономий и предлагает расширенную классификацию документов и текстов с использованием IAB-2 для назначения стандартизированных текстовых категорий, таксономии документов, разработанной Aspose для различных типов документов, или Sentiment (и Sentiment3) для анализа настроений. API анализирует текст, предложения и даже слова и поддерживает классификацию различных стандартных форматов документов, включая PDF, Microsoft Word, OpenDocument, RTF и TXT. Анализ тональности (классификация) поддерживает английский, китайский, испанский и немецкий языки с автоматическим определением языка. API может возвращать вероятность положительности, которую можно использовать для детального анализа тональности в C#.

      GroupDocs.Classification для .NET использует собственный механизм обработки/классификации документов и не требует установки каких-либо внешних инструментов в системе. Он ориентирован на платформу .NET для разработки приложений и поддерживает все популярные операционные системы (Windows, линукс, macOS), в которых можно установить .NET framework (включая .NET Core).

    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Ниже приведен обзор GroupDocs.Classification для .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Обзор"
          content: |
            * Классификация документов по пути и потоку
            * Классифицировать необработанный текст
            * **IAB-2**, **Documents**, **Sentiment**, and **Sentiment3** taxonomies supported
            * Поддерживает несколько форматов документов
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Classification для .NET [поддерживает ряд популярных форматов документов] (https://docs.groupdocs.com/classification/net/supported-document-formats/).

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word**: DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF

        right:
          enable: true
          table:
            # table loop
            - title: "Другие форматы"
              content: |
                * **Fixed Layout**: PDF
                * **OpenDocument**: ODT, OTT
                * **Text**: TXT

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Classification for .NET поддерживает следующие Операционные системы, Frameworks & Менеджер пакетовs:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Операционные системы"
              content: |
                * Windows 10 (x64)
                * Рабочий стол Windows (x64)
                * Windows-сервер (x64)
                * Windows Azure
                * Mac OS X x64 (10.12+)
                * линукс

            # table loop
            - icon: "fas fa-code"
              title: "Поддерживаемые платформы"
              content: |
                * .NET Core 2.0 или новее
                * .NET Framework 4.7 или выше

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Менеджер пакетов"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Среды разработки"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * МоноДевелопмент

############################# Функции ############################
features:
    enable: true
    title: "Расширенные функции API классификации текстов и документов"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: |
          Классифицировать документы по пути, используя таксономии **IAB-2**, **Документы**, **Настроение** или **Настроение3**.

      # feature loop
      - icon: "fas fa-eye"
        content: |
          Выполните классификацию необработанного текста с помощью таксономий **IAB-2**, **Документы**, **Настроение** или **Настроение3**.

      # feature loop
      - icon: "fas fa-bolt"
        content: "Классификация тональности (анализ) для английского, китайского, испанского и немецкого языков"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Выберите количество классифицированных результатов для возврата"

      # feature loop
      - icon: "fas fa-code"
        content: "Работа с документами PDF, Docs, OpenOffice и Rich Text"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Предоставляются 100% рабочие примеры и демонстрации для быстрого изучения поддерживаемых функций"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Неограниченная бесплатная техническая поддержка через форумы по продуктам"

    больше_функций:
      # more_feature_loop
      - title: "Точная классификация документов"
        content: |
          API GroupDocs.Classification поддерживает классификацию различных форматов документов. В приведенном ниже примере кода C# показано, как классифицировать PDF-файл из текущей папки с помощью таксономии документов, возвращая 3 лучших результата.

          ```cs
          // Инициализировать классификатор общего назначения (IAB-2, Documents, Sentiment Analysis).
          var classifier = new GroupDocs.Classification.Classifier();

          // Классифицируйте PDF-файл с помощью таксономии документов и верните 3 наиболее вероятные категории.
          var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Documents);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```
      # more_feature_loop
      - title: "Precise Text Classification"
        content: |
          GroupDocs.Classification API also supports text classification. Text classification can be performed with 4 different taxonomies: IAB-2, Documents, Sentiment, and Sentiment3. The below C# code example shows how to classify text with the default (IAB-2) taxonomy by returning the best result.

          ```cs
          // Инициализировать классификатор общего назначения (IAB-2, Documents, Sentiment Analysis).
          var classifier = new GroupDocs.Classification.Classifier();

          // Классифицируйте текст с помощью таксономии IAB-2 и возвращайте лучшую категорию.
          var response = classifier.Classify("Classify text using the default IAB-2 taxonomy");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

      # more_feature_loop
      - title: "Precise Multilingual Sentiment Analysis"
        content: |
          GroupDocs.Classification для .NET позволяет выполнять междоменный анализ тональности (классификацию) на английском, китайском, испанском и немецком языках. GroupDocs.Classification для .NET автоматически определит нужный язык(и). Варианты использования API анализа настроений иллюстрируются следующим кодом C#:

          ```cs
          // Инициализировать междоменный многоязычный классификатор настроений.
          // SentimentClassifier поддерживает многоязычную классификацию на английском, китайском, испанском и немецком языках.
          var classifier = new GroupDocs.Classification.SentimentClassifier();

          // Анализ тональности английского текста.
          var response = classifier.Classify("Experience is simply the name we give our mistakes");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");

          // Анализ тональности китайского текста с тем же классификатором и таксономией Sentiment3 (Negative/Neutral/Positive).
          response = classifier.Classify("熟能生巧", taxonomy: Taxonomy.Sentiment3);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Classification предлагает API для просмотра документов для других популярных сред разработки."

    solution:
        # solution loop
        - img_alt: "GroupDocs.Classification for Java"
          image: "/border/groupdocs-classification-java.svg"
          product: "GroupDocs.Classification"
          platform: "Java"
          link: "/classification/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
