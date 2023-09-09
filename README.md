# Semantic-Question-Comparator

With so many people searching for solutions online, it's normal to come across identical issues phrased in different ways. These recurrent queries might cause a less effective search for answers and create extra obligations on content authors who feel obligated to respond to several variations of the same topic. Identifying these 'canonical' questions is important to the project since it enhances the overall experience for both question seekers and content developers. The system rapidly guides users to existing answers by assessing the similarity between pairs of inquiries, thus enhancing the efficiency of information retrieval.

## Table of Contents

- [Description](#description)
- [Technologies](#technologies)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [Contact](#contact)

---

## Description

Semantic-Question-Comparator is a Python-based project that utilizes natural language processing (NLP) techniques to determine the semantic similarity between two questions. It leverages popular Python libraries such as scikit-learn, fuzzywuzzy, and BeautifulSoup (bs4) for data preprocessing, feature extraction, and web scraping.

The project employs both basic and advanced features, including tokenization and stopword removal, to enhance the accuracy of semantic similarity assessment. Machine learning algorithms, such as Random Forest and XGBoost, are employed to make these semantic comparisons.

The project is deployed as a web application using Streamlit and hosted on Heroku, making it accessible to users who want to compare the semantic similarity of their questions effortlessly.

---

## Technologies

- Python
- scikit-learn
- <a href = "https://chairnerd.seatgeek.com/fuzzywuzzy-fuzzy-string-matching-in-python/">fuzzywuzzy</a>
- BeautifulSoup (bs4)
- Streamlit
- Heroku
- XGBoost
---

## Features

- Semantic similarity assessment of two input questions.
- Preprocessing steps include tokenization and stopwords removal.
- Utilizes machine learning algorithms for accurate comparison.
- User-friendly web interface for easy interaction.

---

## Dataset

The Semantic-Question-Comparator project utilizes a diverse dataset of question pairs to train and evaluate its semantic similarity models. This dataset is referenced as [train.csv](https://www.kaggle.com/c/quora-question-pairs)

---

## Installation

To run this project locally, follow these steps:

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the application with `app.py`.

---

## Usage

1. Enter two questions in the provided input fields.
2. Click the "Compare" button to analyze their semantic similarity.
3. The app will display the similarity score and insights into the comparison.

---

## Deployment

The project is deployed on Heroku.

To deploy your own instance:

1. Sign up for a Heroku account if you don't have one.
2. Follow Heroku's deployment guidelines to deploy your Streamlit app.

---

## Contributing

Contributions to this project are welcome! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push the branch to your forked repository (`git push origin feature/your-feature-name`).
5. Create a pull request.

---

## Contact

- Sarvagya
- Email: <a href = "mailto: pandeysarvagya128@gmail.com">pandeysarvagya128@gmail.com</a>
- LinkedIn: <a href = "www.linkedin.com/in/sarvagya-pandey-1b54b3226">Sarvagya Pandey</a>
- GitHub: <a href = "https://github.com/pandeysarvagya">@pandeysarvagya</a>
