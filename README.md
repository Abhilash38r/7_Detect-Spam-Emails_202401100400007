![Uploading ChatGPT Image Apr 22, 2025, 03_31_12 PM.png…]()


📧 Spam Email Detection using Structured Metadata

This project focuses on detecting spam emails using structured metadata instead of analyzing email content. It’s lightweight, efficient, and suitable for environments with privacy constraints or limited computational resources.


🧠 Project Overview

Spam emails are a constant nuisance in digital communication. Most spam detection systems rely on **Natural Language Processing (NLP)**, which can be computationally expensive and sometimes impractical.

This project offers a simpler yet effective alternative using only **structured features** such as:
- Number of links
- Number of attachments
- Sender reputation score
- Email length
- And other metadata fields

Using this metadata, we train a Decision Tree Classifier to distinguish spam from non-spam emails.


🎯 Goals

✅ Classify emails as Spam or Not Spam using structured features  
✅ Perform exploratory data analysis (EDA)  
✅ Create visualizations such as pie charts and bar graphs  
✅ Train and evaluate the performance of a ML model  
✅ Present results and screenshots for reporting


📦 Dataset

The dataset is provided in CSV format and contains the following columns:

| Column             | Description                              |
|--------------------|------------------------------------------|
| `num_links`        | Number of links in the email             |
| `num_attachments`  | Number of attached files                 |
| `sender_reputation`| A score indicating sender's trust level  |
| `email_length`     | Total length of the email                |
| `is_spam`          | Label: 1 for spam, 0 for not spam        |

> 📁 Dataset Filename: `487aeb72-382f-490e-a073-1f37dae1ec20.csv`


📊 Data Visualization

We used `matplotlib` and `seaborn` for creating:
- 📌 Pie Chart: Distribution of Spam vs Not Spam
- 📌 Bar Chart: Comparison of metadata features by spam class
- 📌 Confusion Matrix: Classification performance
- 📌 Accuracy Report: Precision, Recall, F1 Score



⚙️ Tools and Libraries Used

| Tool          | Purpose                              |
|---------------|--------------------------------------|
| Python        | Core programming language            |
| Pandas        | Data handling                        |
| Seaborn       | Visualization                        |
| Matplotlib    | Graphs & charts                      |
| Scikit-learn  | Machine learning                     |
| Google Colab  | Cloud-based Python notebook          |

📈 Model Summary

- Algorithm: `DecisionTreeClassifier` (sklearn)
- Input: Structured numerical and categorical features
- Output: Binary classification – Spam or Not Spam
- Accuracy Achieved: ~[Insert your accuracy here]%


📸 Screenshots (add image links if hosted)

- 📍 Pie Chart  
  ![Pie Chart](screenshots/pie_chart.png)

- 📍 Feature-wise Bar Graph  
  ![Bar Graph](screenshots/bar_graph.png)

- 📍 Confusion Matrix  
  ![Confusion Matrix](screenshots/confusion_matrix.png)

  ![ChatGPT Image Apr 22, 2025, 03_31_12 PM](https://github.com/user-attachments/assets/083f4f19-14d8-465b-8916-26297fae9211)

  ![Screenshot 2025-04-22 145042](https://github.com/user-attachments/assets/38aaee44-7ea8-4886-b9cb-aaa9b29afee4)

  ![Screenshot 2025-04-22 145115](https://github.com/user-attachments/assets/1f9d1113-0cbc-49ec-8bf0-f38af5b74c54)

  ![Screenshot 2025-04-22 145126](https://github.com/user-attachments/assets/185a23ee-125f-4e05-92d4-ccd0317e508a)

  ![Screenshot 2025-04-22 145135](https://github.com/user-attachments/assets/69aabdd3-ea4a-4732-b421-513cc08aab90)

  






🛠️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spam-email-detector.git
