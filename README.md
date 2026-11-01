# Ass4 — Red Wine Outlier Detection

[Open the notebook in Google Colab](https://colab.research.google.com/github/manoai2007-lgtm/ass4-wine-outliers/blob/main/Ass4_Red_Wine_Outlier_Detection.ipynb)

An explained, executed notebook for Principles of AI, Ass4 / Lab 2 Question 2.

## Run
Open the Colab link and select **Runtime → Run all**. No dataset upload or API key is needed. To keep your own editable copy, use **File → Save a copy in Drive**.

The notebook uses Markdown headings and short explanations before each code cell:
- Import libraries, load and explore the data.
- Exclude `quality` from the numeric detection features.
- Detect outliers using IQR and Isolation Forest.
- Compare counts and percentages.
- Run nine parameter experiments, varying one parameter at a time.
- Explain the results in four lines and draw feature boxplots.

## Local run
Install `requirements.txt`, open the notebook in Jupyter, and run all cells. The included CSV matches the dataset supplied for the course. The notebook downloads the public UCI copy when the CSV is absent.

## Attribution
The workflow is adapted from the Section 4 code and teaching explanation prepared by **Eng. Samaa Abdelmohsen**, with functions and changes required by Ass4. Original Moodle handouts and private course files are not included.

Dataset: Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). *Wine Quality*. UCI Machine Learning Repository. https://doi.org/10.24432/C56S3T. Licensed under **CC BY 4.0**: https://creativecommons.org/licenses/by/4.0/ . Included data: red wine subset, unchanged.

Isolation Forest is the unsupervised estimator requested by the assignment, despite the question's informal “Random Forest” wording. Results are detections, not proof that observations are errors.
