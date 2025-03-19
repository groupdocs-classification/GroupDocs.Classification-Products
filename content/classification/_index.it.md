---
############################# Static ############################
layout: "family"
date:  2025-03-17T15:57:00
draft: false

product: "Classification"
product_tag: "classification"

lang: it

############################# Head ############################
head_title: "API .NET per la classificazione di documenti e testi e l'analisi del sentiment"
head_description: "Potente libreria .NET per la classificazione di documenti e testi utilizzando le tassonomie IAB-2, Document e Sentiment. Supporta molteplici formati di file e lingue."

############################# Header ############################
title: "Soluzione per la classificazione di documenti e testi"
description: |
  Classifica facilmente documenti e testi utilizzando varie tassonomie con la nostra API .NET.

  Esegui l'analisi del sentiment e categorizza i contenuti in diversi formati di file e lingue.

  Integra funzionalità di classificazione avanzate nelle tue applicazioni .NET con poche righe di codice.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "Scegli la tua piattaforma"
  title: "Indipendenza dalla piattaforma"
  description: "GroupDocs.Classification per .NET è compatibile con i seguenti sistemi operativi e framework:"
  details_link_title: "Scopri di più"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Classification per .NET
      color: "blue"
      tag: "net"
      link: "/classification/net/"
      features_link: "https://docs.groupdocs.com/classification/net/system-requirements/"
      features:
          # features loop
          - rows: "3"
            content: |
                    .NET Core 2.0 o successivo  .NET Framework 4.7 o superiore
      
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
                    Oltre 10 formati di file

############################# Features ###############################
features:
  enable: true
  title: "Caratteristiche principali di GroupDocs.Classification"
  description: "Questa soluzione ti aiuta a classificare documenti e testi utilizzando varie tassonomie, eseguire l'analisi del sentiment e integrare funzionalità di classificazione avanzate nelle tue applicazioni .NET."

  items:
    # items loop
    - icon: "classify"
      title: "Tassonomie multiple"
      content: "Classifica utilizzando le tassonomie IAB-2, Document e Sentiment."

    # items loop
    - icon: "format"
      title: "Ampio supporto di formati"
      content: "Elabora vari formati di documenti tra cui DOC, DOCX, PDF e altri."

    # items loop
    - icon: "analyze"
      title: "Analisi del sentiment"
      content: "Esegui la classificazione del sentiment per testi in inglese e cinese."

    # items loop
    - icon: "integrate"
      title: "Facile integrazione"
      content: "Integra le funzionalità di classificazione con poche righe di codice."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Classifica i documenti con facilità"
  description: "Esempi di codice di GroupDocs.Classification"
  items:
    # code sample loop
    - title: "Classifica PDF con la tassonomia IAB-2"
      content: |
       GroupDocs.Classification ti permette di classificare facilmente documenti PDF utilizzando la tassonomia IAB-2. Specifica semplicemente il percorso del documento, il numero desiderato di risultati e il tipo di tassonomia per ottenere i risultati della classificazione.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp
            // Crea un'istanza del Classifier
            var classifier = new GroupDocs.Classification.Classifier();

            // Classifica il documento
            var response = classifier.Classify("documento.pdf", ".", 3, Taxonomy.Iab2);

            // Stampa la classe migliore e la sua probabilità
            Console.WriteLine($"Classe migliore: {response.BestClassName}, Probabilità: {response.BestClassProbability}");
            ```

############################# Supported Formats ###############################
formats:
  enable: true
  title: "Supporta oltre 10 formati di file"
  description: "GroupDocs.Classification funziona con vari formati di documenti popolari"

############################# Metrics ###############################
metrics:
  enable: true
  title: "Metriche e approfondimenti dettagliati"
  description: "Immergiti nelle nostre metriche dettagliate per una visione completa delle nostre prestazioni e della nostra crescita."

  items:
    # items loop
    - number: "10+"
      title: "Formati supportati"
      content: "Supportiamo oltre 10 dei formati di documenti più utilizzati."

    # items loop
    - number: "3"
      title: "Tassonomie supportate"
      content: "Classifica i contenuti utilizzando le tassonomie IAB-2, Document e Sentiment."

    # items loop
    - number: "2"
      title: "Lingue per l'analisi del sentiment"
      content: "Esegui la classificazione del sentiment in inglese e cinese."

    # items loop
    - number: "4.7+"
      title: "Supporto .NET Framework"
      content: "Compatibile con .NET Framework 4.7 o superiore e .NET Core 2.0 o successivo."

############################# Actions ###############################
actions:
  enable: true
  title: "Pronto per iniziare?"
  description: "Prova gratuitamente le funzionalità di GroupDocs.Classification sulla tua piattaforma."

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# FAQ ###############################
faq:
  enable: true
  title: "Domande frequenti"
  description: "Risposte alle domande comuni su GroupDocs.Classification."

  items:
    # items loop
    - question: "Quali tipi di documenti posso classificare con GroupDocs.Classification?"
      answer: "GroupDocs.Classification supporta vari formati di documenti tra cui Microsoft Word (DOC, DOCX, RTF), OpenOffice (ODT), PDF e file di testo semplice (TXT)."

    # items loop
    - question: "Posso utilizzare GroupDocs.Classification per l'analisi del sentiment?"
      answer: "Sì, GroupDocs.Classification supporta l'analisi del sentiment sia per testi in inglese che in cinese, permettendoti di determinare il sentiment di documenti o frammenti di testo."

    # items loop
    - question: "È possibile integrare GroupDocs.Classification nella mia applicazione .NET esistente?"
      answer: "Assolutamente! GroupDocs.Classification offre un'API user-friendly che può essere facilmente integrata nelle tue applicazioni .NET con poche righe di codice. È progettata per funzionare senza problemi con i tuoi flussi di lavoro esistenti."

############################# Cloud Links ###############################
cloud_links:
  enable: false

############################# App links ###############################
app_links:
  enable: false
---
