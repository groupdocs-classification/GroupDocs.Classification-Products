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
head_title: "API de análisis de opiniones y clasificación de documentos y textos de C# .NET"
head_description: "Clasificación de documentos y texto sin procesar con las API c# .NET. Categorización con taxonomías IAB-2 y Documentos y análisis de sentimiento del consumidor con una taxonomía Sentimiento."

############################# Header ############################
title: ".API de clasificación de documentos y texto NET"
description: "Potencie sus aplicaciones .NET con capacidades de Clasificador de archivos y texto mediante etiquetas o categorías predefinidas dentro de las taxonomías IAB-2, Documentos y Sentimientos.."
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
              text: "Visión de conjunto"

            # button loop
            - link: "#features"
              text: "Características"

            # button loop
            - link: "#support"
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/classification"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/classification/net"
              text: "Precios"

    right:
        link_download: "https://downloads.groupdocs.com/classification"
        link_learn: "https://docs.groupdocs.com/classification/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Visión de conjunto ############################
overview:
    enable: true
    content: |
      GroupDocs.Classification para .NET es una API C# Netstandard 2.0 intuitiva que lo ayuda a crear potentes aplicaciones de clasificación/categorización de documentos y texto en C#, ASP.NET y otras tecnologías basadas en .NET. La API admite cuatro tipos diferentes de taxonomías y ofrece una clasificación avanzada de documentos y textos mediante el uso de IAB-2 para asignar categorías de texto estandarizadas, la taxonomía de documentos desarrollada por Aspose para diferentes tipos de documentos o Sentiment (y Sentiment3) para el análisis de opiniones. La API analiza texto, oraciones e incluso palabras y admite la clasificación de una variedad de formatos de documentos estándar de la industria, incluidos PDF, Microsoft Word, OpenDocument, RTF y TXT. El análisis de opinión (clasificación) admite los idiomas inglés, chino, español y alemán con detección automática de idioma. La API puede devolver una probabilidad de positividad que podría usarse para un análisis de opinión detallado en C#.

      GroupDocs.Classification para .NET utiliza su propio motor de procesamiento/clasificación de documentos y no requiere la instalación de ninguna herramienta externa en el sistema. Se dirige a la plataforma .NET para desarrollar aplicaciones y es compatible con todos los sistemas operativos populares (Windows, Linux, macOS) donde se pueden instalar marcos .NET (incluido .NET Core).
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          A continuación se muestra una descripción general de GroupDocs.Classification para .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Visión de conjunto"
          content: |
            * Clasificación de documentos por ruta y flujo
            * Clasificar texto sin formato
            * **IAB-2**, **Documents**, **Sentiment**, and **Sentiment3** taxonomies supported
            * Soporta múltiples formatos de documentos
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Classification para .NET [admite varios formatos de documentos populares](https://docs.groupdocs.com/classification/net/supported-document-formats/).

        left:
          enable: true
          table:
            # table loop
            - title: "oficina de Microsoft"
              content: |
                * **Word**: DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF

        right:
          enable: true
          table:
            # table loop
            - title: "Otros formatos"
              content: |
                * **Fixed Layout**: PDF
                * **OpenDocument**: ODT, OTT
                * **Text**: TXT

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Classification for .NET apoya siguiendoSistemas operativos, Frameworks & Gerente de empaquetacións:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistemas operativos"
              content: |
                * Windows 10 (x64)
                * Windows Desktop (x64)
                * Windows Server (x64)
                * Windows Azure
                * Mac OS X x64 (10.12+)
                * Linux

            # table loop
            - icon: "fas fa-code"
              title: "Marcos compatibles"
              content: |
                * .NET Core 2.0 or later
                * .NET Framework 4.7 or higher

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Gerente de empaquetación"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Entornos de desarrollo"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Características ############################
features:
    enable: true
    title: "Características avanzadas de la API de clasificación de documentos y texto"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: |
          Clasifique los documentos por ruta utilizando las taxonomías **IAB-2**, **Documentos**, **Opinión** o **Opinión3**

      # feature loop
      - icon: "fas fa-eye"
        content: |
          Realice la clasificación de texto sin formato con las taxonomías **IAB‑2**, **Documentos**, **Opinión** o **Opinión3**

      # feature loop
      - icon: "fas fa-bolt"
        content: "Clasificación de sentimiento (análisis) para inglés, chino, español y alemán"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Elija el número de resultados clasificados para devolver"

      # feature loop
      - icon: "fas fa-code"
        content: "Trabaje con documentos PDF, Docs, OpenOffice y Rich Text"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Se brindan ejemplos y demostraciones 100% funcionales para aprender rápidamente las funciones admitidas"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Soporte técnico gratuito ilimitado proporcionado a través de foros de productos"

    more_feature:
      # more_feature_loop
      - title: "Clasificación precisa de documentos"
        content: |
          GroupDocs.Classification API admite la clasificación para una variedad de formatos de documentos. El siguiente ejemplo de código C# muestra cómo clasificar un archivo PDF de la carpeta actual con la taxonomía de Documentos al obtener los 3 mejores resultados.

          ```cs
          // Inicializa el clasificador de propósito general (IAB-2, Documentos, Análisis de sentimiento).
          var classifier = new GroupDocs.Classification.Classifier();

          // Clasifique el archivo pdf con la taxonomía de Documentos y devuelva las 3 categorías más probables.
          var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Documents);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```
      # more_feature_loop
      - title: "Precise Text Classification"
        content: |
          La API GroupDocs.Classification también admite la clasificación de texto. La clasificación de texto se puede realizar con 4 taxonomías diferentes: IAB-2, Documents, Sentiment y Sentiment3. El siguiente ejemplo de código C# muestra cómo clasificar el texto con la taxonomía predeterminada (IAB-2) devolviendo el mejor resultado.

          ```cs
          // Inicializa el clasificador de propósito general (IAB-2, Documentos, Análisis de sentimiento).
          var classifier = new GroupDocs.Classification.Classifier();

          // Clasifica el texto con la taxonomía IAB-2 y devuelve la mejor categoría.
          var response = classifier.Classify("Classify text using the default IAB-2 taxonomy");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

      # more_feature_loop
      - title: "Precise Multilingual Sentiment Analysis"
        content: |
          GroupDocs.Classification para .NET permite realizar análisis de opinión (clasificación) entre dominios en inglés, chino, español y alemán. GroupDocs.Classification para .NET detectará automáticamente los idiomas adecuados. Los casos de uso de la API de análisis de sentimientos se ilustran con el siguiente código C#:

          ```cs
          // Inicializa el clasificador de opiniones multilingüe entre dominios.
          // SentimentClassifier admite la clasificación multilingüe con inglés, chino, español y alemán.
          var classifier = new GroupDocs.Classification.SentimentClassifier();

          // Análisis de sentimiento del texto en inglés.
          var response = classifier.Classify("Experience is simply the name we give our mistakes");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");

          // Análisis de sentimiento del texto chino con el mismo clasificador y taxonomía Sentimiento3 (Negativo/Neutro/Positivo).
          response = classifier.Classify("熟能生巧", taxonomy: Taxonomy.Sentiment3);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Classification ofrece API de visualización de documentos para otros entornos de desarrollo populares"

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
