# Python Helper Bot 🤖

This Jupyter Notebook helps you find the correct Python method based on your description.

It uses **NLTK** to analyze user input and suggest matching Python functions with examples.

---

## 💡 How it works
1. You describe what you want (e.g., "I want to find the biggest number")
2. The bot tokenizes your sentence and uses WordNet to understand your intent
3. It suggests a matching Python method like `max()`, `len()`, `sort()`, etc.

---

## 🧪 Example
**Input:**  
`I want a method to reverse a list`

**Output:**  
`Suggested method: reverse()`  
`Example: [1, 2, 3][::-1]  # returns [3, 2, 1]`

---

## 📦 Requirements
- Python 3.x
- nltk

---

## 🚀 How to Run
1. Install required packages:
   ```bash
   pip install nltk
   ```

2. Open `pythonBOT.ipynb` in Jupyter Notebook and run all cells.

---

## 🔖 Author
Made with ❤️ by Layan
