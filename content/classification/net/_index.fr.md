---
############################# Statique ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: fr
product: "Classification"
product_tag: "classification"
platform: "Net"
platform_tag: "net"

############################# Menu déroulant ############################
supported_platforms:
  items:
    # boucle supported_platforms
    - title: ".NET"
      tag: "net"

############################# En-tête ############################
head_title: "API .NET pour la classification de textes et de documents"
head_description: "API C# .NET pour la classification de textes et de documents utilisant les taxonomies IAB-2, Document et Sentiment. Classez le contenu dans divers formats, notamment PDF, DOC, DOCX, RTF et TXT."

############################# En-tête ############################
title: "API .NET de classification de textes et de documents"
description: "Classez les textes et les documents dans les applications .NET en utilisant plusieurs taxonomies."
words:
  for: "pour"

actions:
  main: "Télécharger l'essai via NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "Licences"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "Prêt à commencer ?"
  description: "Essayez gratuitement les fonctionnalités de GroupDocs.Classification ou demandez une licence"

release:
  title: "Version {0} publiée"
  notes: "Voir les nouveautés"
  downloads: "Téléchargements"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "Classer un PDF avec la taxonomie IAB-2 en C#"
  more: "Plus d'exemples"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // Créer une instance de Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // Classer un document PDF en utilisant la taxonomie IAB-2
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // Afficher le nom de la meilleure classe et sa probabilité
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Aperçu ############################
overview:
  enable: true
  title: "Aperçu de GroupDocs.Classification"
  description: "Solution .NET pour la classification automatisée de textes et de documents utilisant diverses taxonomies."
  features:
    # boucle de fonctionnalités
    - title: "Classer du texte et des documents avec C#"
      content: "Classez facilement le contenu en utilisant les taxonomies IAB-2, Document et Sentiment avec GroupDocs.Classification pour .NET."

    # boucle de fonctionnalités
    - title: "Prise en charge de plusieurs formats de fichiers"
      content: "Traitez divers types de documents, notamment PDF, DOC, DOCX, RTF, TXT et plus encore."

    # boucle de fonctionnalités
    - title: "Options de classification flexibles"
      content: "Choisissez le nombre de résultats à retourner et ajustez l'équilibre précision/rappel pour la taxonomie Documents."

############################# Plateformes ############################
platforms:
  enable: true
  title: "Indépendance de plateforme"
  description: "GroupDocs.Classification pour .NET prend en charge les systèmes d'exploitation, frameworks et gestionnaires de paquets suivants"
  items:
    # boucle de plateforme
    - title: "Amazon"
      image: "amazon"
    # boucle de plateforme
    - title: "Docker"
      image: "docker"
    # boucle de plateforme
    - title: "Windows"
      image: "windows"
    # boucle de plateforme
    - title: "Linux"
      image: "linux"
    # boucle de plateforme
    - title: "macOS"
      image: "finder"
    # boucle de plateforme
    - title: ".NET"
      image: "net"
    # boucle de plateforme
    - title: "NuGet"
      image: "nuget"

############################# Formats de fichiers ############################
formats:
  enable: true
  title: "Formats de fichiers pris en charge"
  description: |
    GroupDocs.Classification pour .NET prend en charge les opérations avec les [formats de fichiers](https://docs.groupdocs.com/classification/net/supported-document-formats/) suivants.
  groups:
    # boucle de groupe
    - color: "green"
      content: |
        ### Formats Microsoft Office
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # boucle de groupe
    - color: "blue"
      content: |
        ### Formats OpenDocument et autres
        * **OpenOffice:** ODT, OTT
        * **Mise en page fixe:** PDF
        * **Autres:** TXT

############################# Fonctionnalités ############################
features:
  enable: true
  title: "Fonctionnalités de GroupDocs.Classification"
  description: "Classez le texte et les documents en utilisant des taxonomies et des options avancées."

  items:
    # boucle de fonctionnalités
    - icon: "viewhtml"
      title: "Taxonomies multiples"
      content: "Prend en charge les taxonomies IAB-2, Document et Sentiment pour une classification polyvalente."

    # boucle de fonctionnalités
    - icon: "rasterize"
      title: "Prise en charge multilingue"
      content: "Effectuez une classification des sentiments en anglais et en chinois."

    # boucle de fonctionnalités
    - icon: "sourcecode"
      title: "Résultats personnalisables"
      content: "Spécifiez le nombre de résultats de classification à retourner."

    # boucle de fonctionnalités
    - icon: "transform"
      title: "Contrôle de la précision"
      content: "Ajustez l'équilibre précision/rappel pour la classification de la taxonomie Documents."

    # boucle de fonctionnalités
    - icon: "adjustment"
      title: "Formats de fichiers multiples"
      content: "Compatible avec divers formats de documents, notamment PDF, DOC, DOCX, RTF et TXT."

    # boucle de fonctionnalités
    - icon: "complex"
      title: "Intégration facile"
      content: "S'intègre facilement à toute application .NET, y compris ASP.NET et les applications Windows."

############################# Exemples de code ############################
code_samples:
  enable: true
  title: "Exemples de code"
  description: "Quelques cas d'utilisation d'opérations typiques de GroupDocs.Classification pour .NET"
  items:
    # boucle d'exemple de code
    - title: "Classer du texte en utilisant la taxonomie IAB-2"
      content: |
        Cet exemple montre comment classer du texte brut en utilisant la taxonomie IAB-2 :
        
        ```csharp {style=abap}
        // Créer une demande de classification
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "Essayer la classification de texte"
        }, "3");

        // Obtenir les résultats de classification
        var response = apiInstance.Classify(request);

        // Afficher les résultats
        Console.WriteLine(response.ToString());
        ```
        
    # boucle d'exemple de code
    - title: "Analyse de sentiment d'un document"
      content: |
        Vous pouvez effectuer une analyse de sentiment sur des documents en utilisant la taxonomie Sentiment :
        
        ```csharp {style=abap}
        // Créer une instance de Classifier
        var classifier = new GroupDocs.Classification.Classifier();

        // Classer un document en utilisant la taxonomie Sentiment
        var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Sentiment);

        // Afficher le sentiment et la probabilité
        Console.WriteLine($"Sentiment : {response.BestClassName}");
        Console.WriteLine($"Probabilité : {response.BestClassProbability}");
        ```

---
