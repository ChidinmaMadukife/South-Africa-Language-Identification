# South Africa Language Identification Hackathon

## Project Overview

South Africa is a multicultural society characterized by its rich linguistic diversity. Language is an indispensable tool that contributes to the social, cultural, intellectual, economic, and political life of South African society. With 11 official languages, each guaranteed equal status, many South Africans are multilingual, speaking at least two or more official languages. This multilingual nature underscores the importance of systems and devices that can communicate in multiple languages.

In this project, we tackled the challenge of identifying which of South Africa's 11 official languages a given text is written in. This is an example of NLP’s Language Identification, a task aimed at determining the natural language in which a piece of text is written.

## Project Steps

- **1. Data Cleaning**: I carried out data cleaning on the original data by removing unnecessary characters and stripping punctuation to ensure the data was suitable for modeling.
- **2. Exploratory Data Analysis**: Conducted EDA to gain insights into the data and understand the distribution of languages within the dataset.
- **3. Text Data Transformation**: Converted the text data into numerical representations through vectorization technique using CountVectorizer, to prepare it for modeling. And used Label encoding for the target variable.
- **4. Model Building and Evaluation**: Built and evaluated several classifiers, including SVC, Naive Bayes, Logistic Regression, and Random Forest. Naive Bayes demonstrated the best performance. The model parameters were fine-tuned using GridSearchCV to optimize accuracy.

## Key Insights from EDA

- The language distribution chart showed that languages such as **English (eng)** and **Zulu (zul)** had higher representation.
- **Ndebele (nbl)** and **Swati (ssw)** were among the languages with fewer data points, indicating a slightly lower prevalence in the dataset.
- This balanced distribution ensured robust model training without significant bias.

  **Here is a visual representation of the distribution**

  ![Language Distribution](https://github.com/ChidinmaMadukife/South-Africa-Language-Identification/blob/main/Images/Language%20Distribution.png)

## Conclusion

In this project, a language identification model was developed to identify the language of text samples from South Africa’s official languages. By applying machine learning techniques and NLP preprocessing, I achieved promising results in accurately determining the language of given texts. This project showcases the potential of NLP and machine learning in solving complex language identification tasks, emphasizing the value of technological solutions in a linguistically diverse society.

- The EDA phase provided valuable information on language distribution.
- Model performance was evaluated using the Mean F1-Score, ensuring reliability for language identification tasks.

**Applications:**

- Content categorization.
- Multilingual analytics.
- Enhancing user experiences in language-based systems and devices.

## References

- [Build Language Detection Model With NLP | Natural Language Processing Applications | Great Learning](https://www.youtube.com/watch?v=YB7XXDXIusg)
- [NLP tools for language detection](https://www.youtube.com/watch?v=JJdJePbmCyw)
- [4 NLP Libraries for Automatic Language Identification of Text Data In Python](https://towardsdatascience.com/4-nlp-libraries-for-automatic-language-identification-of-text-data-in-python-cbc6bf66477)

