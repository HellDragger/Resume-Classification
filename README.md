# Resume Classification Project

This repository contains code for a machine learning project that classifies resumes into various categories based on the content extracted from PDF files. The project utilizes several machine learning models to predict the category of a resume, providing insights into the effectiveness of different algorithms for text classification tasks.

## Project Overview

The project involves several steps:
- Extracting text from PDF files.
- Preprocessing text data by segmenting into different resume sections such as Experience, Education, and Skills.
- Cleaning text data by removing punctuation, lowercasing, and removing stop words.
- Feature engineering using TF-IDF vectorization.
- Training multiple machine learning models.
- Evaluating model performance using accuracy metrics, confusion matrices, and ROC curves.

## Repository Structure

- `Resume_Dataset/data`: Directory containing resume PDF files organized by category.
- `requirements.txt`: Lists the Python dependencies for the project.

## Installation

To set up the project environment, follow these steps:

```bash
git clone https://github.com/your-username/resume-classification.git
cd resume-classification
pip install -r requirements.txt
```

## Models

The project evaluates the following models:
- Logistic Regression
- Random Forest
- Decision Tree
- SVM
- Multinomial Naive Bayes
- K-Nearest Neighbors

## Results

Model performance is summarized in the Jupyter Notebook `Resume_Classification.ipynb`, which provides detailed accuracy scores, classification reports, and visualizations of ROC curves and confusion matrices.

## Contributing

Contributions to this project are welcome. To contribute, please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## Authors

- **Aryan Sharma** - [HellDragger](https://github.com/HellDragger)
- **Aarohi Panicker** - [aarohisp](https://github.com/aarohisp)
- **Chris Dcosta** - [YourUsername](https://github.com/YourUsername)
- **Mudit Garg** - [YourUsername](https://github.com/MuditxGarg/)
