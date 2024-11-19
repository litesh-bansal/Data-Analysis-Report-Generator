
# Data Analysis Report Generator

This repository contains a Jupyter Notebook that automates the creation of a professional PDF report from a given dataset. The report includes insights such as identifying missing values, categorizing data types, handling duplicate and constant columns, and generating visualizations for numerical and categorical columns.

## Features
- **Missing Value Analysis**: Identifies columns with missing values and their counts.
- **Data Type Categorization**: Categorizes columns into numerical and categorical types for better data understanding.
- **Duplicate and Constant Column Handling**:
  - Detects and removes duplicate columns.
  - Identifies and removes columns with constant values.
  - Provides a before-and-after summary.
- **Data Visualizations**:
  - Generates box plots for numerical columns to identify outliers.
  - Creates distribution charts for selected columns.
- **PDF Report Generation**: Outputs findings in a well-formatted, professional PDF report.

## Prerequisites
Make sure you have the following installed:
- Python 3.x
- Required libraries:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `fpdf`
  - `PyPDF2` (optional, for advanced PDF manipulations)

You can install the libraries using:
```bash
pip install pandas matplotlib seaborn fpdf PyPDF2
```

## How to Use
1. Clone the repository:
   ```bash
  
   git clone  https://github.com/litesh-bansal/Data-Analysis-Report-Generator.git
   cd data-analysis-report-generator
   ```
2. Open the Jupyter Notebook `Acadia.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
3. Upload your dataset in CSV format and specify its file path in the notebook.
4. Run the notebook to generate the PDF report.

## Example Workflow
1. Specify the input dataset and output file path:
   ```python
   data_path = "sample_data.csv"
   output_file = "generated_report.pdf"
   ```
2. Run all the cells in the notebook.
3. The PDF report will be saved to the specified location, containing:
   - Columns with missing values.
   - Data type categorization.
   - Box plots and distribution charts for numerical and categorical columns.
   - Summary of duplicate and constant column handling.

## Outputs
The generated PDF report includes:
- A summary of missing values.
- Categorized data types (numerical and categorical).
- Insights on duplicate and constant columns before and after removal.
- Visualizations of box plots and data distributions.

## Repository Structure
- `Acadia.ipynb`: The Jupyter Notebook for generating the data analysis report.
- `README.md`: This documentation file.
- Example datasets can be added for testing purposes.

## Contributing
Contributions are welcome! If you find any issues or have ideas for additional features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For any queries, feedback, or collaboration opportunities:
- **Litesh Kumar**
- Email: [k.litesh@iitg.ac.in](mailto:k.litesh@iitg.ac.in)
- LinkedIn: [Litesh Kumar](https://www.linkedin.com/in/litesh-kumar/)
- GitHub: [litesh-bansal](https://github.com/litesh-bansal)
```

---


