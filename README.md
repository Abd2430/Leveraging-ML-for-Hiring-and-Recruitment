
# Resume Shortlisting System [NLP and ML]

This project is inspired by the paper _"Hiring and Recruitment Process Using Machine Learning"_ and aims to automate and optimize the resume screening process. It applies natural language processing (NLP) and machine learning techniques to evaluate and rank job candidates based on their resumes.

---

## 📌 Project Overview

Recruiters often face challenges in manually screening and ranking a large number of resumes. This system provides an ML-based solution to:

- Extract relevant skills and qualifications from resumes
- Match them with job role requirements
- Rank candidates based on proficiency and certification
- Output results in a structured format to aid HR decision-making

---

## 🧠 Core Features

- Resume parsing and keyword matching
- Skill evaluation using TF-IDF (Term Frequency-Inverse Document Frequency)
- Candidate ranking based on skill match and course completion
- Output of ranked candidates in Excel/CSV format
- Visualization of results using Matplotlib

---

## 🛠️ Tools & Technologies

- **Language:** Python  
- **Libraries:** Pandas, Scikit-learn, Matplotlib, NLTK, SpaCy, NumPy  
- **Environment:** Jupyter Notebook  
- **Data Formats:** .txt, .csv, .xlsx (resumes or structured inputs)

---

## ⚙️ How It Works

1. **Input Stage:**
   - Candidates upload their resume (PDF or text)
   - System checks for keywords related to required skills (e.g., "machine learning", "Python")

2. **Preprocessing:**
   - NLP is used to extract text and clean it
   - TF-IDF is applied to identify key skills and courses mentioned

3. **Ranking Algorithm:**
   - Assigns scores based on skill match, experience, and coursework
   - Candidates are sorted based on total scores

4. **Output:**
   - Ranks displayed in Excel format
   - Graphs showing distribution of skills and ranking insights

---

## 📊 Example Visual Output

- Bar chart of top 10 ranked candidates
- Pie chart of common skills
- Line chart comparing experience vs. score

_(Add these visuals from your actual project once generated)_

---

## 🚀 Future Improvements

- Resume upload via web interface (Flask/Streamlit)
- Integration with LinkedIn APIs for profile evaluation
- Deep learning for contextual understanding
- Bias and fairness evaluation in ranking

---

## 📚 Reference

Paper: _Hiring and Recruitment Process Using Machine Learning_  
[IEEE Xplore - Dahlia Sam et al., 2023](https://ieeexplore.ieee.org/document/10084133)

---

## 👨‍💻 Author

**Shaik Abdullah**  
Connect with me on [LinkedIn](https://www.linkedin.com/in/shaik-abdullah)  
Explore more projects on [GitHub](https://github.com/Abd2430)
