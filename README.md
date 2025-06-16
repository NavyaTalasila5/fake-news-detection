# fake-news-detection

Machine learning project to detect whether a news article is fake or real based on its textual content using natural language processing (NLP) and classification algorithms.

## Dataset

- Files: Fake.csv, True.csv  
- Description: The dataset contains two separate CSV files — one with fake news and one with real news articles. Both were combined into a single labeled dataset.  
- Target variable: label (0 = Fake, 1 = Real)

## Tools and Libraries

- Python  
- Jupyter Notebook  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  
- TF-IDF Vectorization  

## Project Structure

fake-news-detection  
- Fake.csv  
- True.csv  
- fake_news_detection.ipynb  
- README.md  
- requirements.txt  

## Models Compared

- Logistic Regression  
- Naive Bayes  
- Random Forest Classifier (Best)  

## Evaluation Metrics

- Accuracy Score  
- Confusion Matrix  
- Classification Report  

## Results

The **Random Forest Classifier** gave the best performance on the test set.

| Model               | Accuracy  |
|---------------------|-----------|
| Logistic Regression | 0.982     |
| Naive Bayes         | 0.932     |
| **Random Forest**   | **0.988** |

## Final Output

The final model was trained using the Random Forest Classifier.  
A classification report and confusion matrix were generated to evaluate model performance.

## How to Run

1. Clone this repository  
2. Ensure both `Fake.csv` and `True.csv` are in the same folder as the notebook  
3. Open `fake_news_detection.ipynb` in Jupyter Notebook or Google Colab  
4. Run all cells in order  

## Author

Talasila Navya Annapurna  

GitHub: https://github.com/NavyaTalasila5  

LinkedIn: https://www.linkedin.com/in/navya-talasila-3134a1325/
