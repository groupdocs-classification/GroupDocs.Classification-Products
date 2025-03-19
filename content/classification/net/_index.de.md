---
############################# Statisch ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: de
product: "Classification"
product_tag: "classification"
platform: "Net"
platform_tag: "net"

############################# Dropdown ############################
supported_platforms:
  items:
    # supported_platforms Schleife
    - title: ".NET"
      tag: "net"

############################# Kopf ############################
head_title: ".NET API für Text- und Dokumentenklassifizierung"
head_description: "C# .NET API für Text- und Dokumentenklassifizierung mit IAB-2-, Dokument- und Stimmungs-Taxonomien. Klassifizieren Sie Inhalte in verschiedenen Formaten einschließlich PDF, DOC, DOCX, RTF und TXT."

############################# Header ############################
title: ".NET Text- und Dokumentenklassifizierungs-API"
description: "Klassifizieren Sie Texte und Dokumente in .NET-Anwendungen mit mehreren Taxonomien."
words:
  for: "für"

actions:
  main: "Testversion über NuGet herunterladen"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "Lizenzierung"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "Bereit loszulegen?"
  description: "Testen Sie GroupDocs.Classification-Funktionen kostenlos oder fordern Sie eine Lizenz an"

release:
  title: "Version {0} veröffentlicht"
  notes: "Siehe was neu ist"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "PDF mit IAB-2-Taxonomie in C# klassifizieren"
  more: "Weitere Beispiele"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // Erstellen Sie eine Instanz von Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // Klassifizieren Sie ein PDF-Dokument mit der IAB-2-Taxonomie
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // Geben Sie den besten Klassennamen und die Wahrscheinlichkeit aus
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Überblick ############################
overview:
  enable: true
  title: "GroupDocs.Classification Überblick"
  description: ".NET-Lösung für automatisierte Text- und Dokumentenklassifizierung mit verschiedenen Taxonomien."
  features:
    # Feature-Schleife
    - title: "Klassifizieren Sie Text und Dokumente mit C#"
      content: "Klassifizieren Sie Inhalte einfach mit IAB-2-, Dokument- und Stimmungs-Taxonomien mit GroupDocs.Classification für .NET."

    # Feature-Schleife
    - title: "Unterstützung für mehrere Dateiformate"
      content: "Verarbeiten Sie verschiedene Dokumenttypen einschließlich PDF, DOC, DOCX, RTF, TXT und mehr."

    # Feature-Schleife
    - title: "Flexible Klassifizierungsoptionen"
      content: "Wählen Sie die Anzahl der zurückzugebenden Ergebnisse und passen Sie die Präzision/Recall-Balance für die Dokument-Taxonomie an."

############################# Plattformen ############################
platforms:
  enable: true
  title: "Plattformunabhängigkeit"
  description: "GroupDocs.Classification für .NET unterstützt die folgenden Betriebssysteme, Frameworks und Paketmanager"
  items:
    # Plattform-Schleife
    - title: "Amazon"
      image: "amazon"
    # Plattform-Schleife
    - title: "Docker"
      image: "docker"
    # Plattform-Schleife
    - title: "Windows"
      image: "windows"
    # Plattform-Schleife
    - title: "Linux"
      image: "linux"
    # Plattform-Schleife
    - title: "macOS"
      image: "finder"
    # Plattform-Schleife
    - title: ".NET"
      image: "net"
    # Plattform-Schleife
    - title: "NuGet"
      image: "nuget"

############################# Dateiformate ############################
formats:
  enable: true
  title: "Unterstützte Dateiformate"
  description: |
    GroupDocs.Classification für .NET unterstützt Operationen mit den folgenden [Dateiformaten](https://docs.groupdocs.com/classification/net/supported-document-formats/).
  groups:
    # Gruppen-Schleife
    - color: "green"
      content: |
        ### Microsoft Office Formate
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # Gruppen-Schleife
    - color: "blue"
      content: |
        ### OpenDocument & andere Formate
        * **OpenOffice:** ODT, OTT
        * **Festes Layout:** PDF
        * **Andere:** TXT

############################# Funktionen ############################
features:
  enable: true
  title: "GroupDocs.Classification Funktionen"
  description: "Klassifizieren Sie Text und Dokumente mit fortschrittlichen Taxonomien und Optionen."

  items:
    # Funktions-Schleife
    - icon: "viewhtml"
      title: "Mehrere Taxonomien"
      content: "Unterstützt IAB-2-, Dokument- und Stimmungs-Taxonomien für vielseitige Klassifizierung."

    # Funktions-Schleife
    - icon: "rasterize"
      title: "Mehrsprachige Unterstützung"
      content: "Führen Sie Stimmungsklassifizierung sowohl in Englisch als auch in Chinesisch durch."

    # Funktions-Schleife
    - icon: "sourcecode"
      title: "Anpassbare Ergebnisse"
      content: "Geben Sie die Anzahl der zurückzugebenden Klassifizierungsergebnisse an."

    # Funktions-Schleife
    - icon: "transform"
      title: "Präzisionskontrolle"
      content: "Passen Sie die Präzision/Recall-Balance für die Dokument-Taxonomie-Klassifizierung an."

    # Funktions-Schleife
    - icon: "adjustment"
      title: "Mehrere Dateiformate"
      content: "Kompatibel mit verschiedenen Dokumentformaten einschließlich PDF, DOC, DOCX, RTF und TXT."

    # Funktions-Schleife
    - icon: "complex"
      title: "Einfache Integration"
      content: "Nahtlose Integration in jede .NET-Anwendung, einschließlich ASP.NET und Windows-Apps."

############################# Code-Beispiele ############################
code_samples:
  enable: true
  title: "Code-Beispiele"
  description: "Einige Anwendungsfälle typischer GroupDocs.Classification für .NET-Operationen"
  items:
    # Code-Beispiel-Schleife
    - title: "Text mit IAB-2-Taxonomie klassifizieren"
      content: |
        Dieses Beispiel zeigt, wie man Rohtext mit der IAB-2-Taxonomie klassifiziert:
        
        ```csharp {style=abap}
        // Erstellen Sie eine Klassifizierungsanfrage
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "Textklassifizierung testen"
        }, "3");

        // Erhalten Sie Klassifizierungsergebnisse
        var response = apiInstance.Classify(request);

        // Geben Sie die Ergebnisse aus
        Console.WriteLine(response.ToString());
        ```
        
    # Code-Beispiel-Schleife
    - title: "Stimmungsanalyse eines Dokuments"
      content: |
        Sie können eine Stimmungsanalyse von Dokumenten mit der Stimmungs-Taxonomie durchführen:
        
        ```csharp {style=abap}
        // Erstellen Sie eine Instanz von Classifier
        var classifier = new GroupDocs.Classification.Classifier();

        // Klassifizieren Sie ein Dokument mit der Stimmungs-Taxonomie
        var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Sentiment);

        // Geben Sie die Stimmung und Wahrscheinlichkeit aus
        Console.WriteLine($"Stimmung: {response.BestClassName}");
        Console.WriteLine($"Wahrscheinlichkeit: {response.BestClassProbability}");
        ```

---
