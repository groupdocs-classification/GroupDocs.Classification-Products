---
############################# Статичний ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: uk
product: "Classification"
product_tag: "classification"
platform: "Net"
platform_tag: "net"

############################# Розкривний список ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"

############################# Заголовок ############################
head_title: ".NET API для класифікації текстів і документів"
head_description: "C# .NET API для класифікації текстів і документів з використанням таксономій IAB-2, Document та Sentiment. Класифікуйте контент у різних форматах, включаючи PDF, DOC, DOCX, RTF та TXT."

############################# Хедер ############################
title: ".NET API для класифікації текстів і документів"
description: "Класифікуйте тексти та документи у .NET-додатках за допомогою кількох таксономій."
words:
  for: "для"

actions:
  main: "Завантажити пробну версію через NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "Ліцензування"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "Готові розпочати?"
  description: "Спробуйте функціонал GroupDocs.Classification безкоштовно або замовте ліцензію"

release:
  title: "Випущена версія {0}"
  notes: "Дізнайтеся, що нового"
  downloads: "Завантаження"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "Класифікація PDF за таксономією IAB-2 у C#"
  more: "Більше прикладів"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```
    // Створіть екземпляр Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // Класифікуйте PDF-документ за таксономією IAB-2
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // Виведіть найкращу назву класу та ймовірність
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Огляд ############################
overview:
  enable: true
  title: "Огляд GroupDocs.Classification"
  description: ".NET-рішення для автоматичної класифікації текстів і документів за допомогою різних таксономій."
  features:
    # feature loop
    - title: "Класифікація текстів і документів за допомогою C#"
      content: "Легко класифікуйте контент за таксономіями IAB-2, Document та Sentiment з GroupDocs.Classification для .NET."

    # feature loop
    - title: "Підтримка декількох форматів файлів"
      content: "Обробляйте різні типи документів, включаючи PDF, DOC, DOCX, RTF, TXT тощо."

    # feature loop
    - title: "Гнучкі параметри класифікації"
      content: "Вибирайте кількість результатів для повернення та налаштовуйте баланс точності/повноти для таксономії Documents."

############################# Платформи ############################
platforms:
  enable: true
  title: "Незалежність від платформи"
  description: "GroupDocs.Classification для .NET підтримує наступні операційні системи, фреймворки та менеджери пакетів."
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

############################# Формати файлів ############################
formats:
  enable: true
  title: "Підтримувані формати файлів"
  description: |
    GroupDocs.Classification для .NET підтримує операції з наступними [форматами файлів](https://docs.groupdocs.com/classification/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Формати Microsoft Office
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### OpenDocument та інші формати
        * **OpenOffice:** ODT, OTT
        * **Фіксовані макети:** PDF
        * **Інші:** TXT

############################# Функціонал ############################
features:
  enable: true
  title: "Функціонал GroupDocs.Classification"
  description: "Класифікуйте тексти та документи за допомогою розширених таксономій і параметрів."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Різноманітні таксономії"
      content: "Підтримка таксономій IAB-2, Document та Sentiment для універсальної класифікації."

    # feature loop
    - icon: "rasterize"
      title: "Підтримка багатьох мов"
      content: "Виконуйте класифікацію настроїв англійською та китайською мовами."

    # feature loop
    - icon: "sourcecode"
      title: "Налаштовувані результати"
      content: "Вкажіть кількість результатів класифікації для повернення."

    # feature loop
    - icon: "transform"
      title: "Контроль точності"
      content: "Налаштуйте баланс точності/повноти для класифікації за таксономією Documents."

    # feature loop
    - icon: "adjustment"
      title: "Різні формати файлів"
      content: "Сумісність з різними форматами документів, включаючи PDF, DOC, DOCX, RTF і TXT."

    # feature loop
    - icon: "complex"
      title: "Проста інтеграція"
      content: "Легко інтегрується з будь-яким .NET-додатком, включаючи ASP.NET і Windows-додатки."

############################# Приклади коду ############################
code_samples:
  enable: true
  title: "Приклади коду"
  description: "Деякі варіанти використання типових операцій GroupDocs.Classification для .NET."
  items:
    # code sample loop
    - title: "Класифікація тексту за таксономією IAB-2"
      content: |
        Цей приклад показує, як класифікувати сирий текст за допомогою таксономії IAB-2:
        
        ```
        // Створіть запит на класифікацію
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "Спробуйте класифікацію тексту."
        }, "3");

        // Отримайте результати класифікації.
        var response = apiInstance.Classify(request);

        // Виведіть результати.
        Console.WriteLine(response.ToString());
        ```
        
    # code sample loop
    - title: "Аналіз настроїв документа."
      content: |
        Ви можете виконувати аналіз настроїв документів за допомогою таксономії Sentiment:
        
        ```
        // Створіть екземпляр Classifier.
        var classifier = new GroupDocs.Classification.Classifier();

        // Класифікуйте документ за таксономією Sentiment.
        var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Sentiment);

        // Виведіть настрій і ймовірність.
        Console.WriteLine($"Настрій:{response.BestClassName}");
        Console.WriteLine($"Ймовірність:{response.BestClassProbability}");
        ```

---
