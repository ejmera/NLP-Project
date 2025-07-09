# 🛍️ E-Commerce Review Analysis (NLP Project)

In this project, customer reviews are scraped from an e-commerce website and a Natural Language Processing (NLP) model is built to classify whether a review is **positive or negative**.

---

## 📁 Project Steps

### 1. Extracting and Saving Review Data

**`dataCode.ipynb`**  
Product reviews are scraped from an e-commerce site using web scraping techniques. Reviews for each product are saved in separate `.csv` files.

📌 Tools used: `Selenium`, `BeautifulSoup`, `pandas`

---

### 2. Merging CSV Files

**`2_csv_birlestirme.ipynb`**  
All the collected `.csv` files are merged into a single dataset by stacking them vertically to create a consolidated dataset.

📌 Tools used: `pandas`

---

### 3. Classifying Reviews Using NLP

**`3_nlp_model_egitimi.ipynb`**  
Using the cleaned dataset, an NLP model is trained to classify whether a review is **positive or negative**.

📌 Techniques used:
- Text preprocessing (punctuation removal, stopword removal, etc.)
- TF-IDF vectorization
- Logistic Regression (or another classifier)

---

## 🚀 How to Use

1. Run the notebooks in order using Jupyter Notebook  
2. Follow the steps from data collection to model training  
3. After training, test your own comments using the prediction function

---

## 🛠️ Required Libraries

```bash
pandas  
numpy  
scikit-learn  
nltk  
selenium  
bs4 (BeautifulSoup)

```
---

## 👤 Developer

**Enes Bulut**  
GitHub: [github.com/ejmera](https://github.com/ejmera)


---
## 📄 License

This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.



