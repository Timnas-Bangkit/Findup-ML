# Findup-ML

Findup-ML is a machine learning project designed to handle various tasks related to resume (CV) processing and evaluation. This repository includes tools and models for parsing CVs, scoring them, and measuring text similarity.

## Features

### 1. **CV Parser**
- **Purpose**: Extracts and processes text from CVs.
- **Implementation**: Includes a notebook `parsing_text_model.ipynb` that demonstrates the parsing process.

### 2. **CV Scoring**
- **Purpose**: Scores CVs based on defined metrics or criteria.
- **Implementation**: The scoring logic is implemented in the notebook `CV_Scoring_Model.ipynb`.

### 3. **Text Similarity**
- **Purpose**: Measures the similarity between two pieces of text, useful for matching job descriptions with CV content.
- **Implementation**: The notebook `Text_Similarity_Model.ipynb` showcases the similarity computation.

## Project Structure

```
Findup-ML/
|
|-- .git/                     # Git repository metadata
|-- CV Parser/                # Contains CV parsing logic
|   |-- parsing_text_model.ipynb
|   |-- README.md
|
|-- CV Scoring/               # Contains CV scoring logic
|   |-- CV_Scoring_Model.ipynb
|
|-- Text Similarity/          # Contains text similarity logic
    |-- Text_Similarity_Model.ipynb
```

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Timnas-Bangkit/API-CC.git
   cd Findup-ML
   ```

2. **Install Dependencies**:
   Ensure you have Python and Jupyter Notebook installed. Use the following command to install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Notebooks**:
   Open each notebook in the corresponding folder and execute the cells to see the models in action.

   Example:
   ```bash
   jupyter notebook CV\ Parser/parsing_text_model.ipynb
   ```

## Usage

1. **CV Parser**:
   - Load a CV file into the notebook.
   - Run the notebook to parse and extract key information.

2. **CV Scoring**:
   - Input a CV and the required scoring parameters.
   - Run the notebook to obtain a score for the CV.

3. **Text Similarity**:
   - Input two pieces of text (e.g., job description and CV content).
   - Run the notebook to compute the similarity score.

## Contributing

Contributions are welcome! Please create a pull request with detailed explanations of the proposed changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
