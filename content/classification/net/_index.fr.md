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
head_title: "API de classification de documents et de textes C# .NET et d'analyse des sentiments"
head_description: "Classification de documents et de texte brut avec les API c# .NET. Catégorisation avec les taxonomies IAB-2 et Documents et analyse du sentiment des consommateurs avec une taxonomie Sentiment."

############################# Header ############################
title: ".API de classification de textes et de documents NET"
description: "Renforcez vos applications .NET avec des capacités de classificateur de fichiers et de textes à l'aide de balises ou de catégories prédéfinies dans les taxonomies IAB-2, Documents et Sentiment."
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
              text: "Aperçu"

            # button loop
            - link: "#features"
              text: "Caractéristiques"

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

############################# Aperçu ############################
overview:
    enable: true
    content: |
      L'analyse des sentiments de texte et la classification de texte sont deux technologies puissantes qui peuvent être utilisées pour extraire des informations significatives à partir de données textuelles non structurées et ont de nombreuses applications pratiques dans diverses industries. Ces techniques peuvent être appliquées dans un large éventail de cas d'utilisation, de la surveillance des médias sociaux à l'analyse des commentaires des clients, en passant par la catégorisation des articles d'actualité, la détection des spams, et bien plus encore.
      
      L'analyse des sentiments est le processus d'identification du ton émotionnel d'un morceau de texte. Le but de l'analyse des sentiments est d'extraire des informations subjectives du texte pour comprendre l'opinion ou l'état émotionnel de l'auteur. Cette technologie peut être appliquée à la surveillance des médias sociaux, à l'analyse des commentaires des clients, à la gestion de la réputation de la marque et bien plus encore pour classer les commentaires ou les mentions en catégories positives, négatives ou neutres.
      
      La classification de texte est le processus de catégorisation du texte en classes ou catégories prédéfinies. Cette technologie peut être utilisée pour organiser de grandes collections de documents texte ou pour filtrer les informations non pertinentes d'un flux de données texte. La classification du texte peut être basée sur différents critères, tels que la sémantique, le sentiment ou les catégories IAB (Interactive Advertising Bureau). La classification basée sur l'IAB est utilisée pour catégoriser le texte en fonction des catégories de l'IAB. Cette approche est souvent utilisée dans la publicité pour classer le contenu pour le ciblage publicitaire. Par exemple, un développeur de logiciels peut utiliser la classification basée sur l'IAB pour classer le contenu du site Web dans différentes catégories, telles que les arts et le divertissement, la santé et la forme physique ou les voyages.
      
      La catégorisation de documents est un cas d'utilisation courant pour la classification de texte qui implique l'organisation de documents en différentes catégories en fonction de leur contenu. Cela peut être utile dans divers secteurs, tels que le droit, la finance et la santé, où il existe une grande quantité de données non structurées qui doivent être organisées et analysées. Une façon de mettre en œuvre la catégorisation des documents consiste à utiliser GroupDocs.Classification, une puissante bibliothèque de classification de texte qui prend en charge un large éventail de formats de documents, notamment PDF, DOC, DOCX, RTF et TXT. Notre solution est construite sur des algorithmes d'apprentissage automatique qui la rendent très précise et fiable, vous permettant de prendre des décisions plus intelligentes en fonction de vos données textuelles. En tant que développeur de logiciels, vous pouvez utiliser l'analyse des sentiments de texte et la classification de texte pour créer une large gamme d'applications comme un outil de surveillance des médias sociaux qui suit les mentions de marque et les catégorise par sentiment, un agrégateur de nouvelles qui catégorise les articles par sujet, un filtre de courrier indésirable qui utilise la classification de texte pour identifier et filtrer les spams ou extraire d'autres informations significatives à partir de données textuelles non structurées et créer des applications qui apportent de la valeur aux utilisateurs.
      
      L'une des meilleures caractéristiques de GroupDocs.Classification est sa flexibilité. Cela signifie que vous pouvez classer du texte avec presque n'importe quel type de document. Une autre grande fonctionnalité de GroupDocs.Classification est son API conviviale. Avec seulement quelques lignes de code, vous pouvez intégrer notre bibliothèque dans votre propre application et commencer immédiatement à classer du texte. Notre API est facile à utiliser et bien documentée, vous pouvez donc être opérationnel en un rien de temps. En utilisant GroupDocs.Classification pour la catégorisation des documents, les entreprises peuvent économiser du temps et des ressources en automatisant le processus d'organisation et d'analyse de leurs documents. Cela peut conduire à des flux de travail plus efficaces, à une meilleure prise de décision et, en fin de compte, à de meilleurs résultats commerciaux.
       
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Voici un aperçu de GroupDocs.Classification pour .NET :
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Aperçu"
          content: |
            * Classement des documents par chemin et flux
            * Classer le texte brut
            * **IAB-2**, **Documents**, **Sentiment**, and **Sentiment3** taxonomies supported
            * Prend en charge plusieurs formats de documents
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Classification pour .NET [prend en charge un certain nombre de formats de documents courants](https://docs.groupdocs.com/classification/net/supported-document-formats/).

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
            - title: "Autres formats"
              content: |
                * **Fixed Layout**: PDF
                * **OpenDocument**: ODT, OTT
                * **Text**: TXT

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Classification for .NET prend en charge la suite Systèmes d'exploitation, Frameworks & Directeur chargé d'emballages:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Systèmes d'exploitation"
              content: |
                * Windows 10 (x64)
                * Bureau Windows (x64)
                * Serveur Windows (x64)
                * windows Azure
                * Mac OS X x64 (10.12+)
                * Linux

            # table loop
            - icon: "fas fa-code"
              title: "Cadres pris en charge"
              content: |
                * .NET Core 2.0 ou version ultérieure
                * .NET Framework 4.7 ou supérieur

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Directeur chargé d'emballage"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Environnements de développement"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# Caractéristiques ############################
features:
    enable: true
    title: "Fonctionnalités avancées de l'API de classification de textes et de documents"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: |
          Différents types de prise en charge de la classification, y compris l'**analyse des sentiments**, les **documents** et la classification **IAB**.

      # feature loop
      - icon: "fas fa-eye"
        content: |
          Effectuez une classification de texte brut avec les taxonomies **IAB‑2**, **Documents**, **Sentiment** ou **Sentiment3**

      # feature loop
      - icon: "fas fa-bolt"
        content: "Capacités d'analyse des sentiments qui permettent aux entreprises d'analyser le ton émotionnel du texte pour l'anglais, le chinois, l'espagnol et l'allemand"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Capacités IAB (Interactive Advertising Bureau), permettant aux entreprises de classer leur contenu selon la taxonomie IAB"
        
      # feature loop
      - icon: "fas fa-copy"
        content: "Capacités de classification de documents pour détecter si le document est une facture, une lettre, un CV, un papier, etc."

      # feature loop
      - icon: "fas fa-code"
        content: "Large gamme de formats de documents pris en charge, y compris PDF, DOC, DOCX, RTF et TXT ainsi que du texte brut"
        
      # feature loop
      - icon: "fas fa-eye"
        content: "Comme implémenté à l'aide de Managed C#, GroupDocs.Classification peut être utilisé avec n'importe quel langage .NET comme C#, VB.NET et J#"
        
      # feature loop
      - icon: "fas fa-eye"
        content: "Intégration facile avec tout type d'application, qu'il s'agisse d'une application Web ASP.NET ou d'une application Windows"

      # feature loop
      - icon: "fas fa-cloud"
        content: "100 % d'exemples de travail et de démonstrations sont donnés pour apprendre rapidement les fonctionnalités prises en charge"
        
      # feature loop
      - icon: "fas fa-bolt"
        content: "Algorithmes ML avancés pour garantir une grande précision dans les résultats de classification et prise en charge du multithreading pour améliorer les performances"
        
      # feature loop
      - icon: "fas fa-copy"
        content: "API conviviale facile à utiliser et à intégrer à d'autres applications logicielles"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Assistance technique gratuite et illimitée fournie via les forums de produits"

    more_feature :
      # more_feature_loop
      - title: "Classification précise des documents"
        content: |
          L'API GroupDocs.Classification prend en charge la classification pour une variété de formats de documents. L'exemple de code C# ci-dessous montre comment classer un fichier PDF à partir du dossier actuel avec la taxonomie Documents en renvoyant les 3 meilleurs résultats.

          ```cs
          // Initialiser le classificateur à usage général (IAB-2, Documents, Sentiment Analysis).
          var classifier = new GroupDocs.Classification.Classifier();

          // Classer le fichier pdf avec la taxonomie des documents et renvoyer les 3 catégories les plus probables.
          var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Documents);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```
      # more_feature_loop
      - title: "Classification précise du texte"
        content: |
          L'API GroupDocs.Classification prend également en charge la classification de texte. La classification de texte peut être effectuée avec 4 taxonomies différentes : IAB-2, Documents, Sentiment et Sentiment3. L'exemple de code C# ci-dessous montre comment classer le texte avec la taxonomie par défaut (IAB-2) en renvoyant le meilleur résultat.

          ```cs
          // Initialise le classificateur à usage général (IAB-2, Documents, Sentiment Analysis).
          var classifier = new GroupDocs.Classification.Classifier();

          // Classifie le texte avec la taxonomie IAB-2 et renvoie la meilleure catégorie.
          var response = classifier.Classify("Classify text using the default IAB-2 taxonomy");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

      # more_feature_loop
      - title: "Analyse précise des sentiments multilingues"
        content: |
          GroupDocs.Classification pour .NET permet d'effectuer une analyse des sentiments inter-domaines (Classification) en anglais, chinois, espagnol et allemand. GroupDocs.Classification pour .NET détectera automatiquement la ou les langues appropriées. Les cas d'utilisation de l'API d'analyse des sentiments sont illustrés par le code C# suivant :
          ```cs
          // Initialiser le classificateur de sentiments multilingue inter-domaines.
          // SentimentClassifier supports multilingual classification with English, Chinese, Spanish, and German.
          var classifier = new GroupDocs.Classification.SentimentClassifier();

          //Analyse des sentiments du texte anglais.
          var response = classifier.Classify("Experience is simply the name we give our mistakes");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");

          // Analyse des sentiments du texte chinois avec le même classificateur et la taxonomie Sentiment3 (négatif/neutre/positif).
          response = classifier.Classify("熟能生巧", taxonomy: Taxonomy.Sentiment3);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Classification propose des API de visualisation de documents pour d'autres environnements de développement populaires"

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
