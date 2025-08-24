# Sentiment-Analysis
This project is a Natural Language Processing tool developed to automatically classify the sentiment of text data, such as customer reviews or social media posts. By leveraging a state-of-the-art, pre-trained model from the Hugging Face `transformers library, the tool can accurately determine whether a given text is Positive, Negative or Neutral

This project demonstrates foundational skills in data science and NLP, including:
-   Data loading and preprocessing.
-   Utilizing powerful machine learning models without extensive training from scratch.
-   Data analysis and visualization to interpret results.
-   Using a cloud-based environment (Google Colab) for efficient development.

## Tools and Technologies

-   **Python:** The core programming language for the project.
-   **Google Colab:** A cloud-based platform for running Jupyter notebooks, providing free access to GPUs for faster model execution.
-   **Hugging Face `transformers`:** A leading library for building NLP applications. We specifically used the `pipeline` feature with a pre-trained sentiment analysis model (`distilbert-base-uncased-finetuned-sst-2-english`).
-   **Pandas:** Used for data manipulation and analysis, particularly for handling CSV files.
-   **Matplotlib & Seaborn:** Libraries for creating insightful data visualizations (e.g., pie charts, bar charts).

## How to Run the Project

The project is contained within a single Google Colab notebook, making it easy to replicate.

1.  **Open the Notebook:** Click on the `Sentiment_Analysis_Project.ipynb` file in this repository. It will automatically open in Google Colab.
2.  **Connect to GPU:** (Optional but recommended) In Colab, go to `Runtime` -> `Change runtime type` -> `GPU`.
3.  **Run Cells:** Execute each code cell sequentially by clicking the play button next to it or by pressing `Shift + Enter`.
4.  **Observe Results:** The notebook will perform the following steps:
    -   Install required libraries.
    -   Load a sample dataset (or prompt you to upload your own).
    -   Run the sentiment analysis.
    -   Display the results and visualizations.

## Project Output

The final output is a clear classification of text sentiment, accompanied by a visual summary. Here is an example of the output:

**Sentiment Breakdown:**
- **Positive:** 66.7%
- **Negative:** 16.7%
- **Neutral:** 16.7%
