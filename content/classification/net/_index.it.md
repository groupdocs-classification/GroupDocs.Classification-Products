---
############################# Static ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: it
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
head_title: "API .NET per la classificazione di testi e documenti"
head_description: "API C# .NET per la classificazione di testi e documenti utilizzando le tassonomie IAB-2, Documento e Sentimento. Classifica contenuti in vari formati tra cui PDF, DOC, DOCX, RTF e TXT."

############################# Header ############################
title: "API .NET per la classificazione di testi e documenti"
description: "Classifica testi e documenti nelle applicazioni .NET utilizzando molteplici tassonomie."
words:
  for: "per"

actions:
  main: "Scarica la prova tramite NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "Licenze"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "Pronto per iniziare?"
  description: "Prova gratuitamente le funzionalità di GroupDocs.Classification o richiedi una licenza"

release:
  title: "Versione {0} rilasciata"
  notes: "Scopri le novità"
  downloads: "Download"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "Classifica PDF con la tassonomia IAB-2 in C#"
  more: "Altri esempi"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // Crea un'istanza di Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // Classifica un documento PDF utilizzando la tassonomia IAB-2
    var response = classifier.Classify("documento.pdf", ".", 3, Taxonomy.Iab2);

    // Stampa il nome della migliore classe e la probabilità
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Panoramica di GroupDocs.Classification"
  description: "Soluzione .NET per la classificazione automatizzata di testi e documenti utilizzando varie tassonomie."
  features:
    # feature loop
    - title: "Classifica testi e documenti con C#"
      content: "Classifica facilmente i contenuti utilizzando le tassonomie IAB-2, Documento e Sentimento con GroupDocs.Classification per .NET."

    # feature loop
    - title: "Supporto per molteplici formati di file"
      content: "Elabora vari tipi di documenti inclusi PDF, DOC, DOCX, RTF, TXT e altri."

    # feature loop
    - title: "Opzioni di classificazione flessibili"
      content: "Scegli il numero di risultati da restituire e regola il bilanciamento precisione/richiamo per la tassonomia Documenti."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indipendenza dalla piattaforma"
  description: "GroupDocs.Classification per .NET supporta i seguenti sistemi operativi, framework e gestori di pacchetti"
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
  title: "Formati di file supportati"
  description: |
    GroupDocs.Classification per .NET supporta operazioni con i seguenti [formati di file](https://docs.groupdocs.com/classification/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Formati Microsoft Office
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### Formati OpenDocument e altri
        * **OpenOffice:** ODT, OTT
        * **Layout fisso:** PDF
        * **Altri:** TXT

############################# Features ############################
features:
  enable: true
  title: "Funzionalità di GroupDocs.Classification"
  description: "Classifica testi e documenti utilizzando tassonomie e opzioni avanzate."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Molteplici tassonomie"
      content: "Supporta le tassonomie IAB-2, Documento e Sentimento per una classificazione versatile."

    # feature loop
    - icon: "rasterize"
      title: "Supporto multilingua"
      content: "Esegui la classificazione del sentimento sia in inglese che in cinese."

    # feature loop
    - icon: "sourcecode"
      title: "Risultati personalizzabili"
      content: "Specifica il numero di risultati di classificazione da restituire."

    # feature loop
    - icon: "transform"
      title: "Controllo della precisione"
      content: "Regola il bilanciamento precisione/richiamo per la classificazione della tassonomia Documenti."

    # feature loop
    - icon: "adjustment"
      title: "Molteplici formati di file"
      content: "Compatibile con vari formati di documento inclusi PDF, DOC, DOCX, RTF e TXT."

    # feature loop
    - icon: "complex"
      title: "Facile integrazione"
      content: "Si integra facilmente con qualsiasi applicazione .NET, incluse le app ASP.NET e Windows."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Esempi di codice"
  description: "Alcuni casi d'uso di tipiche operazioni di GroupDocs.Classification per .NET"
  items:
    # code sample loop
    - title: "Classifica testo utilizzando la tassonomia IAB-2"
      content: |
        Questo esempio mostra come classificare testo grezzo utilizzando la tassonomia IAB-2:
        
        ```csharp {style=abap}
        // Crea una richiesta di classificazione
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "Prova la classificazione del testo"
        }, "3");

        // Ottieni i risultati della classificazione
        var response = apiInstance.Classify(request);

        // Stampa i risultati
        Console.WriteLine(response.ToString());
        ```
        
    # code sample loop
    - title: "Analisi del sentimento di un documento"
      content: |
        Puoi eseguire l'analisi del sentimento sui documenti utilizzando la tassonomia Sentimento:
        
        ```csharp {style=abap}
        // Crea un'istanza di Classifier
        var classifier = new GroupDocs.Classification.Classifier();

        // Classifica un documento utilizzando la tassonomia Sentimento
        var response = classifier.Classify("documento.pdf", ".", 3, Taxonomy.Sentiment);

        // Stampa il sentimento e la probabilità
        Console.WriteLine($"Sentimento: {response.BestClassName}");
        Console.WriteLine($"Probabilità: {response.BestClassProbability}");
        ```

---
