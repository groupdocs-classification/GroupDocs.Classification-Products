---
############################# Статический ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: ru
product: "Classification"
product_tag: "classification"
platform: "Net"
platform_tag: "net"

############################# Выпадающее меню ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"

############################# Заголовок ############################
head_title: ".NET API для классификации текста и документов"
head_description: "C# .NET API для классификации текста и документов с использованием таксономий IAB-2, Document и Sentiment. Классифицируйте контент в различных форматах, включая PDF, DOC, DOCX, RTF и TXT."

############################# Заголовок страницы ############################
title: ".NET API для классификации текста и документов"
description: "Классифицируйте тексты и документы в приложениях .NET с использованием нескольких таксономий."
words:
  for: "для"

actions:
  main: "Скачать пробную версию через NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "Лицензирование"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "Готовы начать?"
  description: "Испытайте функции GroupDocs.Classification бесплатно или запросите лицензию"

release:
  title: "Выпущена версия {0}"
  notes: "Узнайте, что нового"
  downloads: "Загрузки"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "Классификация PDF с таксономией IAB-2 в C#"
  more: "Больше примеров"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```
    // Создайте экземпляр Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // Классифицируйте PDF-документ с использованием таксономии IAB-2
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // Выведите название лучшего класса и вероятность
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Обзор ############################
overview:
  enable: true
  title: "Обзор GroupDocs.Classification"
  description: ".NET решение для автоматической классификации текста и документов с использованием различных таксономий."
  features:
    # feature loop
    - title: "Классификация текста и документов с помощью C#"
      content: "Легко классифицируйте контент с использованием таксономий IAB-2, Document и Sentiment с помощью GroupDocs.Classification для .NET."

    # feature loop
    - title: "Поддержка множества форматов файлов"
      content: "Обрабатывайте различные типы документов, включая PDF, DOC, DOCX, RTF, TXT и другие."

    # feature loop
    - title: "Гибкие параметры классификации"
      content: "Выбирайте количество возвращаемых результатов и регулируйте баланс точности/полноты для таксономии Documents."

############################# Платформы ############################
platforms:
  enable: true
  title: "Независимость платформы"
  description: "GroupDocs.Classification для .NET поддерживает следующие операционные системы, фреймворки и менеджеры пакетов."
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

############################# Форматы файлов ############################
formats:
  enable: true
  title: "Поддерживаемые форматы файлов"
  description: |
    GroupDocs.Classification для .NET поддерживает операции с следующими [форматами файлов](https://docs.groupdocs.com/classification/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Форматы Microsoft Office
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### Форматы OpenDocument & Другие форматы
        * **OpenOffice:** ODT, OTT
        * **Фиксированные макеты:** PDF
        * **Другие:** TXT

############################# Функции ############################
features:
  enable: true
  title: "Функции GroupDocs.Classification"
  description: "Классифицируйте текст и документы с использованием передовых таксономий и параметров."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Множество таксономий"
      content: "Поддержка таксономий IAB-2, Document и Sentiment для универсальной классификации."

    # feature loop
    - icon: "rasterize"
      title: "Многоязычная поддержка"
      content: "Выполняйте классификацию настроений на английском и китайском языках."

    # feature loop
    - icon: "sourcecode"
      title: "Настраиваемые результаты"
      content: "Укажите количество возвращаемых результатов классификации."

    # feature loop
    - icon: "transform"
      title: "Контроль точности классификации"
      content: "Регулируйте баланс точности/полноты для классификации по таксономии Documents."

    # feature loop
    - icon: "adjustment"
      title: "Множество форматов файлов"
      content: "Совместимость с различными форматами документов, включая PDF, DOC, DOCX, RTF и TXT."

    # feature loop
    - icon: "complex"
      title: "Легкая интеграция"
      content: "Бесшовная интеграция с любым приложением .NET, включая ASP.NET и Windows-приложения."

############################# Примеры кода ############################
code_samples:
  enable: true
  title: Примеры кода
  description:
     Некоторые примеры использования типичных операций GroupDocs.Classification для .NET.
    
items:
   # code sample loop 
   -title:"Классификация текста через IAB-2

---