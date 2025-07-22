Project Title: THE INK PULSE PROJECT

Project Description:
This project explores two topic modeling techniques—Latent Dirichlet Allocation (LDA) and BERTopic—on 78 weeks of INK data(an anonymous student led instagram platform). It extracts meaningful themes and visualizes key topics across weeks of student engagement.


Installation:
- Python 3.10+
- Required libraries:
    pip install -r requirements.txt

Key packages:
- sklearn (for LDA implementation)
- bertopic (for BERTopic modeling)
- umap-learn (for dimensionality reduction)
- hdbscan (for clustering)
- matplotlib (for visualization)
- nltk (for text preprocessing)
- wordcloud (for word cloud generation)
- pandas (for data handling)

Useful Files
The project uses three main data files:
1. The Hill Speaks Responses - Spreadsheet containing the raw INK student responses
2. weekly_raw_text_sequential.csv - Data split into 78 chronological weeks
3. weekly_translated_text(2).csv - Final preprocessed CSV with Pidgin translations


Usage:
1. Please upload all three files to your google colab environment before running any code.
2. Run the notebook cells sequentially to:
   - Load and preprocess the data
   - Train the LDA model
   - Train the BERTopic model
   - Generate visualizations
   - Evaluate model performance

An important note: Skip the Pidgin translator code section as it takes approximately 10 minutes to run. We have already processed this data, and the output is available in the `weekly_translated_text(2).csv file.


