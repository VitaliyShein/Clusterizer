# Кластеризатор
Инструмент для автоматической кластеризации документов с Google Диска. Анализирует содержимое файлов, создает вложения и группирует похожие документы в 3 папки.

# Инструкция
0) Основная программа находится в clusterizerwithlog (3).py
1) Ваши файлы должны находиться в папке с именем "inputData".
2) Данные для кластеризации обучения должны находиться в папке с именем "inputData"
3) Вам также следует изменить свой каталог прямо в коде

# Основные возможности
Поддерживаемые форматы: PDF, DOCX, TXT, PPTX, JPG, ПНГ, JPEG
Автоматическое определение языка (русский/английский)
Кластеризация с помощью K-Means
Автоматическое создание папок для каждого кластера

# Конфигурация
Количество кластеров: 3 (настраивается)
Модель внедрения: all-MiniLM-L6-v2
Журналы сохраняются на Google Диске в файле Clusterizer.log

# Clusterizer
A tool for automatic document clustering from Google Drive. Analyzes file content, generates embeddings, and groups similar documents into 3 folders.

# Instruction
0) The main program is located in clusterizerwithlog (3).py
1) Your files should be in a folder named "InputData"
2) Data for training clusterization should be in a folder named "InputData"
3) You should also change your directory straight in the code

# Key Features
Supported formats: PDF, DOCX, TXT, PPTX, JPG, PNG, JPEG
Automatic language detection (Russian/English)
Text summarization for cluster descriptions
K-Means clustering
Automatic folder creation for each cluster

# Configuration
Number of clusters: 3 (configurable)
Embedding model: all-MiniLM-L6-v2
Logs saved to Google Drive file named Clusterizer.log
