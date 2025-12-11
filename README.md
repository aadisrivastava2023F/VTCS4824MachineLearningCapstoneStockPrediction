# Virginia Tech CS4824 Machine Learning Capstone – Short Term Stock Prediction Using Machine Learning

Hybrid deep learning project for CS 4824: predicting next day Apple (AAPL) stock price
movement using daily price indicators and Reddit world news headlines.

## Repository Structure

- `data/Combined_News_DJIA.csv` – original Kaggle news dataset
- `ML_Capstone_Final.ipynb` – main notebook with data processing,
  model training, and evaluation
- `requirements.txt` – Python dependencies

## How to Run (Google Colab, T4 GPU)

1. **Open the notebook in Colab**

   - Upload `ML_Capstone_Final.ipynb` to Google Colab, or open it directly from GitHub.

2. **Enable GPU (T4)**

   - In Colab, go to  
     `Runtime → Change runtime type → Hardware accelerator: GPU`  
     (T4 is the default GPU on Colab Pro/Free).

3. **Make sure the dataset is in `/content`**

   This project expects the file `Combined_News_DJIA.csv` to be located at:

   ```python
   /content/Combined_News_DJIA.csv

