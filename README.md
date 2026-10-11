This project evaluates the reliability of Large Language Models (LLMs) in structured data analysis by comparing their responses with results obtained using Python-based analytical libraries.

The study uses a deliberately unclean café sales dataset containing data quality issues such as missing values, invalid entries, negative values, and duplicate records.

Research Objectives

- Evaluate the accuracy of ChatGPT and Google Gemini on structured data analysis tasks.
- Establish Python-based ground truth using pandas and other analytical libraries.
- Compare model-generated answers with independently calculated results.
- Visualize differences and identify potential reliability issues.

Project Structure

- "data/" — Original and dirty café sales datasets.
- "notebooks/" — Data cleaning, descriptive analysis, and model comparison notebooks.
- "results/" — Ground-truth and comparison CSV files.
- "graphs/" — Visualizations of analytical results and model errors.
- "model_answers/" — Prompts and responses from ChatGPT and Google Gemini.

Methodology

1. Prepare and inspect the dataset.
2. Identify and document data quality issues.
3. Clean the data using Python.
4. Calculate ground-truth statistics and totals.
5. Ask ChatGPT and Gemini the same analytical questions.
6. Compare their answers with the Python results.
7. Visualize numerical differences and discuss findings.

Tools and Technologies

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- ChatGPT
- Google Gemini

Reproducibility

The notebooks contain the analysis workflow and comparison code. Review the notebook instructions and dataset paths before running the cells.

Research Status

This repository contains the implementation and experimental materials for a comparative study. Conclusions about model reliability should be based on the recorded experimental results.

License

No license has been selected yet. Until a license is added, reuse of this project's materials is not automatically permitted.
