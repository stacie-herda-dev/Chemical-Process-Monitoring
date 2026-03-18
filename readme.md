# Kaggle Submission
## Overview
This project analyzes a chemical process monitoring dataset using a Jupyter Notebook. The main objective is to explore the data, engineer features, and build a machine learning model to predict efficiency loss in reactor operations. 

## Project Files
- **dataset.joblib**: Raw dataset saved for efficient loading and analysis.
- **Notebook.ipynb**: Jupyter Notebook containing all data processing, exploration, and modeling steps.
- **Notebook.html**: HTML export of the notebook for viewing in a browser.
- **Notebook.pdf**: PDF report version of the notebook for sharing or printing.
- **Model Files (`model_base_*.joblib`)**: Trained models.

## Requirements
Please consult the `requirements.txt` file.

## Getting Started
Follow these steps to set up and run the project:
1. Download the project file and unzip.
2. Create a Python virtual environment (recommended Python 3.9.6).
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
3. Install dependencies:
   
   `pip install -r requirements.txt`

   If you encounter errors, check your Python version and ensure system libraries are installed.
4. Launch Jupyter Notebook:
   
   `jupyter notebook Notebook.ipynb`
5. Run all cells to review results.

## Project Notes
- All data was preprocessed and cleaned before model training.
- Model performance metrics and visualizations are provided in the notebook.
- Run all cells in order to replicate results.
- Export options: Use `jupyter nbconvert` to generate HTML or PDF reports from the notebook.

   `python3 -m jupyter nbconvert --to html notebook.ipynb`

- Models are saved in the "/models" directory.
- For questions or extensions, see the notebook's conclusion and future work sections.

## Useful Links
- [Kaggle Competition Dataset](https://www.kaggle.com/datasets/rohit8527kmr7518/chemical-process-monitoring-time-series-dataset/data)

## License
This project is released under the Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0).

## Contact
- Email: stacie.herda@pm.me
