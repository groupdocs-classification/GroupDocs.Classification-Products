---
############################# Static ############################
layout: "family"
date:  2025-03-17T15:57:00
draft: false

product: "Classification"
product_tag: "classification"

lang: es

############################# Head ############################
head_title: "API .NET para clasificación de documentos y texto y análisis de sentimientos"
head_description: "Potente biblioteca .NET para clasificación de documentos y texto utilizando taxonomías IAB-2, Documento y Sentimiento. Compatible con múltiples formatos de archivo e idiomas."

############################# Header ############################
title: "Solución de clasificación de documentos y texto"
description: |
  Clasifique fácilmente documentos y texto utilizando varias taxonomías con nuestra API .NET.

  Realice análisis de sentimientos y categorice contenido en múltiples formatos de archivo e idiomas.

  Integre capacidades avanzadas de clasificación en sus aplicaciones .NET con solo unas pocas líneas de código.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "Elija su plataforma"
  title: "Independencia de plataforma"
  description: "GroupDocs.Classification para .NET es compatible con los siguientes sistemas operativos y marcos:"
  details_link_title: "Más información"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Classification para .NET
      color: "blue"
      tag: "net"
      link: "/classification/net/"
      features_link: "https://docs.groupdocs.com/classification/net/system-requirements/"
      features:
          # features loop
          - rows: "3"
            content: |
                    .NET Core 2.0 o posterior  .NET Framework 4.7 o superior
      
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
                    Más de 10 formatos de archivo

############################# Features ###############################
features:
  enable: true
  title: "Características principales de GroupDocs.Classification"
  description: "Esta solución le ayuda a clasificar documentos y texto utilizando varias taxonomías, realizar análisis de sentimientos e integrar capacidades avanzadas de clasificación en sus aplicaciones .NET."

  items:
    # items loop
    - icon: "classify"
      title: "Múltiples taxonomías"
      content: "Clasifique utilizando taxonomías IAB-2, Documento y Sentimiento."

    # items loop
    - icon: "format"
      title: "Amplio soporte de formatos"
      content: "Procese varios formatos de documento, incluyendo DOC, DOCX, PDF y más."

    # items loop
    - icon: "analyze"
      title: "Análisis de sentimientos"
      content: "Realice clasificación de sentimientos para texto en inglés y chino."

    # items loop
    - icon: "integrate"
      title: "Fácil integración"
      content: "Integre capacidades de clasificación con solo unas pocas líneas de código."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Clasifique documentos con facilidad"
  description: "Ejemplos de código de GroupDocs.Classification"
  items:
    # code sample loop
    - title: "Clasificar PDF con taxonomía IAB-2"
      content: |
       GroupDocs.Classification le permite clasificar fácilmente documentos PDF utilizando la taxonomía IAB-2. Simplemente especifique la ruta del documento, el número deseado de resultados y el tipo de taxonomía para obtener los resultados de clasificación.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp
            // Crear una instancia del Clasificador
            var classifier = new GroupDocs.Classification.Classifier();

            // Clasificar el documento
            var response = classifier.Classify("documento.pdf", ".", 3, Taxonomy.Iab2);

            // Imprimir la mejor clase y su probabilidad
            Console.WriteLine($"Mejor clase: {response.BestClassName}, Probabilidad: {response.BestClassProbability}");
            ```

############################# Supported Formats ###############################
formats:
  enable: true
  title: "Compatible con más de 10 formatos de archivo"
  description: "GroupDocs.Classification funciona con varios formatos de documento populares"

############################# Metrics ###############################
metrics:
  enable: true
  title: "Métricas e información detalladas"
  description: "Sumérjase en nuestras métricas detalladas para obtener una visión completa de nuestro rendimiento y crecimiento."

  items:
    # items loop
    - number: "10+"
      title: "Formatos compatibles"
      content: "Admitimos más de 10 de los formatos de documento más utilizados."

    # items loop
    - number: "3"
      title: "Taxonomías compatibles"
      content: "Clasifique contenido utilizando taxonomías IAB-2, Documento y Sentimiento."

    # items loop
    - number: "2"
      title: "Idiomas para análisis de sentimientos"
      content: "Realice clasificación de sentimientos en inglés y chino."

    # items loop
    - number: "4.7+"
      title: "Soporte de .NET Framework"
      content: "Compatible con .NET Framework 4.7 o superior y .NET Core 2.0 o posterior."

############################# Actions ###############################
actions:
  enable: true
  title: "¿Listo para comenzar?"
  description: "Pruebe las funciones de GroupDocs.Classification gratis en su plataforma."

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# FAQ ###############################
faq:
  enable: true
  title: "Preguntas frecuentes"
  description: "Respuestas a preguntas comunes sobre GroupDocs.Classification."

  items:
    # items loop
    - question: "¿Qué tipos de documentos puedo clasificar con GroupDocs.Classification?"
      answer: "GroupDocs.Classification admite varios formatos de documento, incluyendo Microsoft Word (DOC, DOCX, RTF), OpenOffice (ODT), PDF y archivos de texto plano (TXT)."

    # items loop
    - question: "¿Puedo usar GroupDocs.Classification para análisis de sentimientos?"
      answer: "Sí, GroupDocs.Classification admite análisis de sentimientos tanto para texto en inglés como en chino, permitiéndole determinar el sentimiento de documentos o fragmentos de texto."

    # items loop
    - question: "¿Es posible integrar GroupDocs.Classification en mi aplicación .NET existente?"
      answer: "¡Absolutamente! GroupDocs.Classification ofrece una API fácil de usar que se puede integrar fácilmente en sus aplicaciones .NET con solo unas pocas líneas de código. Está diseñada para funcionar sin problemas con sus flujos de trabajo existentes."

############################# Cloud Links ###############################
cloud_links:
  enable: false

############################# App links ###############################
app_links:
  enable: false
---