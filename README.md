# Clusterizer
A tool for automatic document clustering from Google Drive. Analyzes file content, generates embeddings, and groups similar documents into folders.

# Instruction
1) Your files shold be in a folder named "InputData"
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
