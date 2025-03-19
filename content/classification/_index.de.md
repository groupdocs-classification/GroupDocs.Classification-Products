---
############################# Static ############################
layout: "family"
date:  2025-03-17T15:57:00
draft: false

product: "Classification"
product_tag: "classification"

lang: de

############################# Head ############################
head_title: ".NET-API für Dokument- und Textklassifizierung sowie Stimmungsanalyse"
head_description: "Leistungsstarke .NET-Bibliothek für Dokument- und Textklassifizierung mit IAB-2-, Dokument- und Stimmungstaxonomien. Unterstützt mehrere Dateiformate und Sprachen."

############################# Header ############################
title: "Lösung für Dokument- und Textklassifizierung"
description: |
  Klassifizieren Sie Dokumente und Texte einfach mit verschiedenen Taxonomien mithilfe unserer .NET-API.

  Führen Sie Stimmungsanalysen durch und kategorisieren Sie Inhalte über mehrere Dateiformate und Sprachen hinweg.

  Integrieren Sie fortschrittliche Klassifizierungsfunktionen in Ihre .NET-Anwendungen mit nur wenigen Codezeilen.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "Wählen Sie Ihre Plattform"
  title: "Plattformunabhängigkeit"
  description: "GroupDocs.Classification für .NET ist mit folgenden Betriebssystemen und Frameworks kompatibel:"
  details_link_title: "Erfahren Sie mehr"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Classification für .NET
      color: "blue"
      tag: "net"
      link: "/classification/net/"
      features_link: "https://docs.groupdocs.com/classification/net/system-requirements/"
      features:
          # features loop
          - rows: "3"
            content: |
                    .NET Core 2.0 oder höher  .NET Framework 4.7 oder höher
      
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
                    Über 10 Dateiformate

############################# Features ###############################
features:
  enable: true
  title: "Hauptfunktionen von GroupDocs.Classification"
  description: "Diese Lösung hilft Ihnen, Dokumente und Texte mit verschiedenen Taxonomien zu klassifizieren, Stimmungsanalysen durchzuführen und fortschrittliche Klassifizierungsfunktionen in Ihre .NET-Anwendungen zu integrieren."

  items:
    # items loop
    - icon: "classify"
      title: "Mehrere Taxonomien"
      content: "Klassifizierung mit IAB-2-, Dokument- und Stimmungstaxonomien."

    # items loop
    - icon: "format"
      title: "Breite Formatunterstützung"
      content: "Verarbeitung verschiedener Dokumentformate einschließlich DOC, DOCX, PDF und mehr."

    # items loop
    - icon: "analyze"
      title: "Stimmungsanalyse"
      content: "Durchführung von Stimmungsklassifizierung für englische und chinesische Texte."

    # items loop
    - icon: "integrate"
      title: "Einfache Integration"
      content: "Integration von Klassifizierungsfunktionen mit nur wenigen Codezeilen."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Dokumente einfach klassifizieren"
  description: "GroupDocs.Classification Codebeispiele"
  items:
    # code sample loop
    - title: "PDF mit IAB-2-Taxonomie klassifizieren"
      content: |
       Mit GroupDocs.Classification können Sie PDF-Dokumente einfach mit der IAB-2-Taxonomie klassifizieren. Geben Sie einfach den Dokumentpfad, die gewünschte Anzahl von Ergebnissen und den Taxonomietyp an, um Klassifizierungsergebnisse zu erhalten.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp
            // Erstellen Sie eine Instanz des Classifiers
            var classifier = new GroupDocs.Classification.Classifier();

            // Klassifizieren Sie das Dokument
            var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

            // Geben Sie die beste Klasse und ihre Wahrscheinlichkeit aus
            Console.WriteLine($"Beste Klasse: {response.BestClassName}, Wahrscheinlichkeit: {response.BestClassProbability}");
            ```

############################# Supported Formats ###############################
formats:
  enable: true
  title: "Unterstützt über 10 Dateiformate"
  description: "GroupDocs.Classification arbeitet mit verschiedenen gängigen Dokumentformaten"

############################# Metrics ###############################
metrics:
  enable: true
  title: "Detaillierte Metriken und Einblicke"
  description: "Tauchen Sie ein in unsere detaillierten Metriken für einen umfassenden Überblick über unsere Leistung und unser Wachstum."

  items:
    # items loop
    - number: "10+"
      title: "Unterstützte Formate"
      content: "Wir unterstützen über 10 der am häufigsten verwendeten Dokumentformate."

    # items loop
    - number: "3"
      title: "Unterstützte Taxonomien"
      content: "Klassifizieren Sie Inhalte mit IAB-2-, Dokument- und Stimmungstaxonomien."

    # items loop
    - number: "2"
      title: "Sprachen für Stimmungsanalyse"
      content: "Führen Sie Stimmungsklassifizierung in Englisch und Chinesisch durch."

    # items loop
    - number: "4.7+"
      title: ".NET Framework-Unterstützung"
      content: "Kompatibel mit .NET Framework 4.7 oder höher und .NET Core 2.0 oder höher."

############################# Actions ###############################
actions:
  enable: true
  title: "Bereit loszulegen?"
  description: "Testen Sie die Funktionen von GroupDocs.Classification kostenlos auf Ihrer Plattform."

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# FAQ ###############################
faq:
  enable: true
  title: "Häufig gestellte Fragen"
  description: "Antworten auf häufige Fragen zu GroupDocs.Classification."

  items:
    # items loop
    - question: "Welche Arten von Dokumenten kann ich mit GroupDocs.Classification klassifizieren?"
      answer: "GroupDocs.Classification unterstützt verschiedene Dokumentformate, einschließlich Microsoft Word (DOC, DOCX, RTF), OpenOffice (ODT), PDF und Textdateien (TXT)."

    # items loop
    - question: "Kann ich GroupDocs.Classification für Stimmungsanalysen verwenden?"
      answer: "Ja, GroupDocs.Classification unterstützt Stimmungsanalysen für englische und chinesische Texte und ermöglicht es Ihnen, die Stimmung von Dokumenten oder Textausschnitten zu bestimmen."

    # items loop
    - question: "Ist es möglich, GroupDocs.Classification in meine bestehende .NET-Anwendung zu integrieren?"
      answer: "Absolut! GroupDocs.Classification bietet eine benutzerfreundliche API, die sich leicht mit nur wenigen Codezeilen in Ihre .NET-Anwendungen integrieren lässt. Sie ist darauf ausgelegt, nahtlos mit Ihren bestehenden Workflows zusammenzuarbeiten."

############################# Cloud Links ###############################
cloud_links:
  enable: false

############################# App links ###############################
app_links:
  enable: false
---