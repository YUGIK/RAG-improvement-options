# Исследование методов повышения эффективности системы RAG и генерации ответов с использованием LLM

## Описание

Этот репозиторий содержит проект по обработке и анализу текстовых данных с использованием современных NLP-инструментов. Основное назначение - автоматизация извлечения информации из PDF-документов, преобразование текста и генерация эмбеддингов с помощью моделей трансформеров. Проект ориентирован на практическое применение методов машинного обучения для работы с неструктурированными текстовыми данными.

## Основные возможности

- Извлечение текста из PDF-файлов с помощью `PyPDF2` и `pdfminer.six`
- Генерация эмбеддингов предложений через `sentence-transformers`
- Хранение и поиск эмбеддингов с использованием векторной базы данных `ChromaDB`
- Использование современных моделей трансформеров (`transformers`, `torch`)


## Установка

Перед запуском убедитесь, что у вас установлен Python 3.10+.
Установите необходимые зависимости:

pip install chromadb sentence-transformers pypdf2 requests pdfminer pdfminer.six -U ipywidgets==7.7.1  

## Используемые библиотеки

- `chromadb` - векторная база данных для хранения эмбеддингов
- `sentence-transformers` - генерация эмбеддингов предложений
- `pypdf2`, `pdfminer.six` - извлечение текста из PDF
- `torch`, `transformers` - работа с нейросетевыми моделями
- `requests` - загрузка данных по HTTP

## Быстрый старт

1. Поместите PDF-файлы, которые хотите обработать, в рабочую папку.
2. Запустите Jupyter Notebook `NLP_GEN_Project_Smirnov_Y_A.ipynb`.
3. Следуйте инструкциям в ноутбуке для извлечения текста, генерации эмбеддингов и поиска по базе.

## Автор

Юрий Смирнов

---

Если у вас есть вопросы или предложения по улучшению проекта, создайте issue или отправьте pull request.
