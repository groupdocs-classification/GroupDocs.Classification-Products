---
############################# Static ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: pt
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
head_title: "API .NET para Classificação de Texto e Documentos"
head_description: "API C# .NET para classificação de texto e documentos usando taxonomias IAB-2, Documento e Sentimento. Classifique conteúdo em vários formatos, incluindo PDF, DOC, DOCX, RTF e TXT."

############################# Header ############################
title: "API de Classificação de Texto e Documentos para .NET"
description: "Classifique textos e documentos em aplicações .NET usando múltiplas taxonomias."
words:
  for: "para"

actions:
  main: "Baixar Teste via NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "Licenciamento"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "Pronto para Começar?"
  description: "Experimente os recursos do GroupDocs.Classification gratuitamente ou solicite uma licença"

release:
  title: "Versão {0} lançada"
  notes: "Veja o que há de novo"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "Classificar PDF com Taxonomia IAB-2 em C#"
  more: "Mais exemplos"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // Crie uma instância do Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // Classifique um documento PDF usando a taxonomia IAB-2
    var response = classifier.Classify("documento.pdf", ".", 3, Taxonomy.Iab2);

    // Imprima o nome da melhor classe e a probabilidade
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Visão Geral do GroupDocs.Classification"
  description: "Solução .NET para classificação automatizada de texto e documentos usando várias taxonomias."
  features:
    # feature loop
    - title: "Classificar Texto e Documentos com C#"
      content: "Classifique facilmente conteúdo usando taxonomias IAB-2, Documento e Sentimento com GroupDocs.Classification para .NET."

    # feature loop
    - title: "Suporte para Múltiplos Formatos de Arquivo"
      content: "Processe vários tipos de documentos, incluindo PDF, DOC, DOCX, RTF, TXT e mais."

    # feature loop
    - title: "Opções Flexíveis de Classificação"
      content: "Escolha o número de resultados a retornar e ajuste o equilíbrio entre precisão e recall para a taxonomia de Documentos."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independência de plataforma"
  description: "GroupDocs.Classification para .NET suporta os seguintes sistemas operacionais, frameworks e gerenciadores de pacotes"
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
  title: "Formatos de arquivo suportados"
  description: |
    GroupDocs.Classification para .NET suporta operações com os seguintes [formatos de arquivo](https://docs.groupdocs.com/classification/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Formatos Microsoft Office
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### Formatos OpenDocument e Outros
        * **OpenOffice:** ODT, OTT
        * **Layout Fixo:** PDF
        * **Outros:** TXT

############################# Features ############################
features:
  enable: true
  title: "Recursos do GroupDocs.Classification"
  description: "Classifique texto e documentos usando taxonomias e opções avançadas."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Múltiplas Taxonomias"
      content: "Suporta taxonomias IAB-2, Documento e Sentimento para classificação versátil."

    # feature loop
    - icon: "rasterize"
      title: "Suporte Multi-idioma"
      content: "Realize classificação de sentimento em inglês e chinês."

    # feature loop
    - icon: "sourcecode"
      title: "Resultados Personalizáveis"
      content: "Especifique o número de resultados de classificação a retornar."

    # feature loop
    - icon: "transform"
      title: "Controle de Precisão"
      content: "Ajuste o equilíbrio entre precisão e recall para classificação da taxonomia de Documentos."

    # feature loop
    - icon: "adjustment"
      title: "Múltiplos Formatos de Arquivo"
      content: "Compatível com vários formatos de documento, incluindo PDF, DOC, DOCX, RTF e TXT."

    # feature loop
    - icon: "complex"
      title: "Fácil Integração"
      content: "Integre-se perfeitamente com qualquer aplicação .NET, incluindo ASP.NET e aplicativos Windows."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Amostras de código"
  description: "Alguns casos de uso de operações típicas do GroupDocs.Classification para .NET"
  items:
    # code sample loop
    - title: "Classificar Texto usando Taxonomia IAB-2"
      content: |
        Este exemplo mostra como classificar texto bruto usando a taxonomia IAB-2:
        
        ```csharp {style=abap}
        // Crie uma solicitação de classificação
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "Tente classificação de texto"
        }, "3");

        // Obtenha os resultados da classificação
        var response = apiInstance.Classify(request);

        // Imprima os resultados
        Console.WriteLine(response.ToString());
        ```
        
    # code sample loop
    - title: "Análise de Sentimento de um Documento"
      content: |
        Você pode realizar análise de sentimento em documentos usando a taxonomia de Sentimento:
        
        ```csharp {style=abap}
        // Crie uma instância do Classifier
        var classifier = new GroupDocs.Classification.Classifier();

        // Classifique um documento usando a taxonomia de Sentimento
        var response = classifier.Classify("documento.pdf", ".", 3, Taxonomy.Sentiment);

        // Imprima o sentimento e a probabilidade
        Console.WriteLine($"Sentimento: {response.BestClassName}");
        Console.WriteLine($"Probabilidade: {response.BestClassProbability}");
        ```
---
