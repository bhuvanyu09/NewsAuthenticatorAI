# NewsAuthenticatorAI



# Fake News and Scam Detector 📰🕵️‍♂️

A web application powered by **Streamlit** and **Machine Learning** to detect fake news and scams. This tool leverages a logistic regression model trained on textual data to classify news articles as **real** or **fake**.

---

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## About the Project
Fake news and scams are prevalent in today's digital world. This project aims to mitigate their impact by providing an easy-to-use web interface that allows users to verify the authenticity of news articles.

### Key Objectives:
1. Accurately classify news articles as fake or real.
2. Offer an interactive web interface for ease of use.
3. Provide an extendable framework for scam detection.

---

## Features
- **Text Preprocessing**: Uses stemming, stopword removal, and TF-IDF vectorization for textual data.
- **Interactive Interface**: Built with Streamlit for a seamless user experience.
- **Logistic Regression Model**: Trained to detect fake news with high accuracy.
- **Modular Design**: Includes separate files for fake news detection and scam detection.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Pandas: Data manipulation
  - NumPy: Numerical computation
  - Scikit-learn: Machine learning
  - NLTK: Natural language processing
  - Streamlit: Web application development

---

## Dataset
The dataset for this project includes:
- Columns: `author`, `title`, `content`, and `label`
- **label**: Binary classification (0 = Real, 1 = Fake)

The dataset is preprocessed to handle missing values and combined `author` and `title` fields for better feature extraction.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Fake-News-Detector.git
   cd Fake-News-Detector
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the `train.csv` dataset and place it in the project directory.

---

## Usage
1. Launch the web application:
   ```bash
   streamlit run app.py
   ```
2. Enter a news article in the input box.
3. The system will classify the news as **Real** or **Fake**.

---

## Project Structure
- **`app.py`**: Main Streamlit application for fake news detection.
- **`fake_news_model.ipynb`**: Jupyter Notebook for model training and testing.
- **`train.csv`**: Dataset used for training and evaluation.
- **`requirements.txt`**: List of dependencies for the project.

---

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and submit a pull request.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contact
- **Author**: Bhuvanyu Geel  
- **Email**: [bhuvanyug@gmail.com](mailto:bhuvanyug@gmail.com)  
- **GitHub**: [bhuvanyu09](https://github.com/bhuvanyu09)

---

