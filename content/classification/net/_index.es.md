---
############################# Static ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: es
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
head_title: "API de .NET para Clasificación de Texto y Documentos"
head_description: "API de C# .NET para clasificación de texto y documentos utilizando taxonomías IAB-2, Documento y Sentimiento. Clasifica contenido en varios formatos incluyendo PDF, DOC, DOCX, RTF y TXT."

############################# Header ############################
title: "API de Clasificación de Texto y Documentos para .NET"
description: "Clasifica textos y documentos en aplicaciones .NET utilizando múltiples taxonomías."
words:
  for: "para"

actions:
  main: "Descargar Prueba a través de NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "Licenciamiento"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "¿Listo para Empezar?"
  description: "Prueba las funciones de GroupDocs.Classification gratis o solicita una licencia"

release:
  title: "Versión {0} lanzada"
  notes: "Ver las novedades"
  downloads: "Descargas"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "Clasificar PDF con Taxonomía IAB-2 en C#"
  more: "Más ejemplos"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // Crear una instancia de Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // Clasificar un documento PDF usando la taxonomía IAB-2
    var response = classifier.Classify("documento.pdf", ".", 3, Taxonomy.Iab2);

    // Imprimir el nombre de la mejor clase y la probabilidad
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Descripción General de GroupDocs.Classification"
  description: "Solución .NET para la clasificación automatizada de texto y documentos utilizando varias taxonomías."
  features:
    # feature loop
    - title: "Clasificar Texto y Documentos con C#"
      content: "Clasifica fácilmente contenido utilizando taxonomías IAB-2, Documento y Sentimiento con GroupDocs.Classification para .NET."

    # feature loop
    - title: "Soporte para Múltiples Formatos de Archivo"
      content: "Procesa varios tipos de documentos incluyendo PDF, DOC, DOCX, RTF, TXT y más."

    # feature loop
    - title: "Opciones de Clasificación Flexibles"
      content: "Elige el número de resultados a devolver y ajusta el balance de precisión/recuperación para la taxonomía de Documentos."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independencia de plataforma"
  description: "GroupDocs.Classification para .NET soporta los siguientes sistemas operativos, frameworks y gestores de paquetes"
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
  title: "Formatos de archivo soportados"
  description: |
    GroupDocs.Classification para .NET soporta operaciones con los siguientes [formatos de archivo](https://docs.groupdocs.com/classification/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Formatos de Microsoft Office
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### Formatos OpenDocument y Otros
        * **OpenOffice:** ODT, OTT
        * **Diseño Fijo:** PDF
        * **Otros:** TXT

############################# Features ############################
features:
  enable: true
  title: "Características de GroupDocs.Classification"
  description: "Clasifica texto y documentos utilizando taxonomías y opciones avanzadas."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Múltiples Taxonomías"
      content: "Soporta taxonomías IAB-2, Documento y Sentimiento para una clasificación versátil."

    # feature loop
    - icon: "rasterize"
      title: "Soporte Multi-Idioma"
      content: "Realiza clasificación de sentimientos tanto en inglés como en chino."

    # feature loop
    - icon: "sourcecode"
      title: "Resultados Personalizables"
      content: "Especifica el número de resultados de clasificación a devolver."

    # feature loop
    - icon: "transform"
      title: "Control de Precisión"
      content: "Ajusta el balance de precisión/recuperación para la clasificación de taxonomía de Documentos."

    # feature loop
    - icon: "adjustment"
      title: "Múltiples Formatos de Archivo"
      content: "Compatible con varios formatos de documento incluyendo PDF, DOC, DOCX, RTF y TXT."

    # feature loop
    - icon: "complex"
      title: "Fácil Integración"
      content: "Se integra perfectamente con cualquier aplicación .NET, incluyendo ASP.NET y aplicaciones Windows."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Ejemplos de código"
  description: "Algunos casos de uso de operaciones típicas de GroupDocs.Classification para .NET"
  items:
    # code sample loop
    - title: "Clasificar Texto usando Taxonomía IAB-2"
      content: |
        Este ejemplo muestra cómo clasificar texto sin formato utilizando la taxonomía IAB-2:
        
        ```csharp {style=abap}
        // Crear una solicitud de clasificación
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "Intentar clasificación de texto"
        }, "3");

        // Obtener resultados de clasificación
        var response = apiInstance.Classify(request);

        // Imprimir los resultados
        Console.WriteLine(response.ToString());
        ```
        
    # code sample loop
    - title: "Análisis de Sentimiento de un Documento"
      content: |
        Puedes realizar análisis de sentimiento en documentos utilizando la taxonomía de Sentimiento:
        
        ```csharp {style=abap}
        // Crear una instancia de Classifier
        var classifier = new GroupDocs.Classification.Classifier();

        // Clasificar un documento usando la taxonomía de Sentimiento
        var response = classifier.Classify("documento.pdf", ".", 3, Taxonomy.Sentiment);

        // Imprimir el sentimiento y la probabilidad
        Console.WriteLine($"Sentimiento: {response.BestClassName}");
        Console.WriteLine($"Probabilidad: {response.BestClassProbability}");
        ```

---
