---
############################# Static ############################
layout: "family"
date:  2025-03-17T15:57:00
draft: false

product: "Classification"
product_tag: "classification"

lang: ru

############################# Head ############################
head_title: ".NET API для классификации документов и текста, а также анализа тональности"
head_description: "Мощная библиотека .NET для классификации документов и текста с использованием таксономий IAB-2, Document и Sentiment. Поддерживает множество форматов файлов и языков."

############################# Header ############################
title: "Решение для классификации документов и текста"
description: |
  Легко классифицируйте документы и текст, используя различные таксономии с помощью нашего .NET API.

  Выполняйте анализ тональности и категоризируйте контент в различных форматах файлов и на разных языках.

  Интегрируйте расширенные возможности классификации в ваши .NET приложения всего несколькими строками кода.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "Выберите вашу платформу"
  title: "Независимость от платформы"
  description: "GroupDocs.Classification для .NET совместим со следующими операционными системами и фреймворками:"
  details_link_title: "Узнать больше"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Classification для .NET
      color: "blue"
      tag: "net"
      link: "/classification/net/"
      features_link: "https://docs.groupdocs.com/classification/net/system-requirements/"
      features:
          # features loop
          - rows: "3"
            content: |
                    .NET Core 2.0 или выше  .NET Framework 4.7 или выше
      
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
                    10+ форматов файлов

############################# Features ###############################
features:
  enable: true
  title: "Ключевые особенности GroupDocs.Classification"
  description: "Это решение помогает классифицировать документы и текст, используя различные таксономии, выполнять анализ тональности и интегрировать расширенные возможности классификации в ваши .NET приложения."

  items:
    # items loop
    - icon: "classify"
      title: "Множество таксономий"
      content: "Классификация с использованием таксономий IAB-2, Document и Sentiment."

    # items loop
    - icon: "format"
      title: "Широкая поддержка форматов"
      content: "Обработка различных форматов документов, включая DOC, DOCX, PDF и другие."

    # items loop
    - icon: "analyze"
      title: "Анализ тональности"
      content: "Выполнение классификации тональности для английского и китайского текста."

    # items loop
    - icon: "integrate"
      title: "Простая интеграция"
      content: "Интеграция возможностей классификации всего несколькими строками кода."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Легкая классификация документов"
  description: "Примеры кода GroupDocs.Classification"
  items:
    # code sample loop
    - title: "Классификация PDF с таксономией IAB-2"
      content: |
       GroupDocs.Classification позволяет легко классифицировать PDF документы, используя таксономию IAB-2. Просто укажите путь к документу, желаемое количество результатов и тип таксономии, чтобы получить результаты классификации.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp
            // Создание экземпляра Classifier
            var classifier = new GroupDocs.Classification.Classifier();

            // Классификация документа
            var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

            // Вывод лучшего класса и его вероятности
            Console.WriteLine($"Лучший класс: {response.BestClassName}, Вероятность: {response.BestClassProbability}");
            ```

############################# Supported Formats ###############################
formats:
  enable: true
  title: "Поддерживает более 10 форматов файлов"
  description: "GroupDocs.Classification работает с различными популярными форматами документов"

############################# Metrics ###############################
metrics:
  enable: true
  title: "Подробные метрики и аналитика"
  description: "Погрузитесь в наши детальные метрики для всестороннего обзора нашей производительности и роста."

  items:
    # items loop
    - number: "10+"
      title: "Поддерживаемые форматы"
      content: "Мы поддерживаем более 10 наиболее широко используемых форматов документов."

    # items loop
    - number: "3"
      title: "Поддерживаемые таксономии"
      content: "Классификация контента с использованием таксономий IAB-2, Document и Sentiment."

    # items loop
    - number: "2"
      title: "Языки для анализа тональности"
      content: "Выполнение классификации тональности на английском и китайском языках."

    # items loop
    - number: "4.7+"
      title: "Поддержка .NET Framework"
      content: "Совместимость с .NET Framework 4.7 или выше и .NET Core 2.0 или выше."

############################# Actions ###############################
actions:
  enable: true
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Classification бесплатно на вашей платформе."

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# FAQ ###############################
faq:
  enable: true
  title: "Часто задаваемые вопросы"
  description: "Ответы на распространенные вопросы о GroupDocs.Classification."

  items:
    # items loop
    - question: "Какие типы документов я могу классифицировать с помощью GroupDocs.Classification?"
      answer: "GroupDocs.Classification поддерживает различные форматы документов, включая Microsoft Word (DOC, DOCX, RTF), OpenOffice (ODT), PDF и обычные текстовые файлы (TXT)."

    # items loop
    - question: "Могу ли я использовать GroupDocs.Classification для анализа тональности?"
      answer: "Да, GroupDocs.Classification поддерживает анализ тональности как для английского, так и для китайского текста, позволяя определять тональность документов или текстовых фрагментов."

    # items loop
    - question: "Возможно ли интегрировать GroupDocs.Classification в мое существующее .NET приложение?"
      answer: "Абсолютно! GroupDocs.Classification предлагает удобный API, который можно легко интегрировать в ваши .NET приложения всего несколькими строками кода. Он разработан для бесшовной работы с вашими существующими рабочими процессами."

############################# Cloud Links ###############################
cloud_links:
  enable: false

############################# App links ###############################
app_links:
  enable: false
---
