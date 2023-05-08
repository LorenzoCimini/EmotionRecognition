# EmotionRecognition

Files contained into the repository:
1. google_dataset, movie_lines and movie_conversations are the various datasets used within the project;
2. cornell_dataset_script: python script needed to process Cornell dataset. This script generates movie_conversations.txt;
3. EmotionsRecognizerWithBert
4. EmotionsRecognizerWithClassicalApproaches
5. movie_analysis: this notebook uses the model created in EmotionsRecognizerWithBert (which generates a directory '/model' that contains model's configuration). Thus this notebook must be esecuted after 'EmotionsRecognizerWithBert'.
