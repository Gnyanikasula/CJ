# Court Judgment Prediction and Explanation (CJPE)

## Project Description

Court Judgment Prediction and Explanation (CJPE) is an innovative system designed to predict and explain court judgments using the Indian Legal Documents Corpus (ILDC). This project involves analyzing 35,000 Indian Supreme Court cases.

## Models Used

- **XLNet**: Fine-tuned on the ILDC dataset.
- **BiGRU**: Used after XLNet for improved prediction performance.

The best results were achieved by combining these models, resulting in an accuracy of nearly 77%.

## Repository Contents

- `BIGRU_final.ipynb`: Jupyter Notebook containing the implementation details of the BiGRU model.
- `RUN1_XL (4).ipynb`: Jupyter Notebook with the XLNet model training and fine-tuning process.
- `README.md`: This file.

## Results

The combination of XLNet and BiGRU achieved an accuracy of nearly 77%, highlighting the complexity of predicting court judgments.

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/Gnyanikasula/CJ.git
   ```
2. Navigate to the project directory:
   ```sh
   cd CJ
   ```
3. Open the Jupyter Notebooks to explore the code and results:
   - `BIGRU_final.ipynb`
   - `RUN1_XL (4).ipynb`

## Future Work

- Further fine-tuning of models.
- Exploring additional features and legal datasets.
- Enhancing the explanation module for better interpretability.

## Contact

For any inquiries or contributions, please reach out via [GitHub Issues](https://github.com/Gnyanikasula/CJ/issues).
