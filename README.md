# Clustering-Beyond-the-Classroom-NLP-Driven-Insights-into-Curriculum-Standards-K-12

**Project Overview**  
This Python-based project leverages state-of-the-art NLP techniques to classify and cluster K–12 curriculum standards into appropriate grade-level groupings. By fine-tuning transformer-based language models such as DistilBERT, RoBERTa, and GPT-2, this project explores how different clustering schemes (from individual grades to broad content-based categories) influence classification accuracy. The ultimate goal is to provide insights that may guide curriculum design and alignment.

**Key Features**  
Transformer-Based Models: Utilizes DistilBERT, RoBERTa, and GPT-2 for text classification tasks.  
Multiple Clustering Schemes: Tests various clustering approaches (individual grades, practical groupings, content-based) to identify patterns and improve classification accuracy.  
Comprehensive Metrics: Evaluates models using accuracy, precision, recall, and F1-score, alongside confusion matrices and probability outputs for deeper insights.

**Technologies Used**  
Python: Core logic for data processing and model fine-tuning.  
Hugging Face Transformers: Pretrained model integration and sequence classification pipelines.  
PyTorch: Model training, evaluation, and tensor operations.  
Datasets & Evaluate: Data handling and metric computation.

**Setup and Running the Project**  
Clone the repository:
git clone https://github.com/angelinedorvil/Clustering-Beyond-the-Classroom-NLP-Driven-Insights-into-Curriculum-Standards-K-12

**Challenges and Learning Outcomes**  
Implementing this project required dealing with long sequence handling, exploring various clustering schemes, managing imbalanced datasets, and implementing ensemble methods. Through iterative experimentation, improvements were made in model selection, hyperparameter tuning, and data preprocessing strategies. This process enhanced understanding of NLP pipelines, model performance trade-offs, and the sensitivity of classification accuracy to curriculum structuring.

**Future Directions**  
Experiment with More Architectures: Investigate other transformer models (e.g., T5, XLNet) for potentially improved performance.  
Refine Clustering Schemes: Incorporate domain knowledge or similarity-based clustering to refine grade-level groupings.  
Multilingual/Multisubject Expansion: Extend the approach to non-English curricula or other subject domains.

**Contribution**  
Contributions, suggestions, and pull requests are welcome! Whether refining the clustering logic or integrating new models, collaborative efforts can help this project evolve into a more robust tool for analyzing educational standards.
