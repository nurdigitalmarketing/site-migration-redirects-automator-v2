
# Automatic Website Migration Tool

This project is an automatic website migration tool developed by [LeeFootSEO](https://twitter.com/LeeFootSEO) and adapted by [NUR® Digital Marketing](https://www.nur.it) to provide a better user interface with instructions in Italian.

## Description

The tool is designed to simplify website data migration. It uses advanced matching models to compare and match data between two versions of the site: "Live" and "Staging". The main features include:

- Upload CSV or Excel files for both versions of the site.
- Match specified columns to compare data.
- Display results with similarity scores and distribution.
- Export results to an Excel file.

## Features

- **File Upload**: Upload CSV or Excel files for "Live" and "Staging" site data.
- **Column Selection**: Select columns to match between the two files.
- **Matching Models**: Choose from different matching models (TF-IDF, Edit Distance, RapidFuzz).
- **Result Visualization**: View similarity scores and score distribution in interactive charts.
- **Result Export**: Export matching results to an Excel file.

## Instructions

### File Preparation

1. **Scan the Sites**:
   - Scan the "Live" and "Staging" sites using Screaming Frog SEO Spider.
   - Export the data as CSV files.

2. **Upload the Files**:
   - Upload the CSV files of the "Live" and "Staging" sites using the file uploads in the app.

3. **Select Columns**:
   - Select the columns you want to match. By default, the app looks for columns named `Address`, `H1-1`, and `Title 1`.

4. **Process the Files**:
   - Click the "Process Files" button to start the matching process.

5. **Export Results**:
   - Once processed, a download link for the output file containing the matching results will be provided.

## Requirements

- Python 3.7+
- Python libraries:
  - `streamlit`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `plotly`
  - `polyfuzz`
  - `xlsxwriter`
  - `chardet`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/website-migration-tool.git
   cd website-migration-tool
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Credits

This tool was originally created by [LeeFootSEO](https://twitter.com/LeeFootSEO) and adapted by [NUR® Digital Marketing](https://www.nur.it) to provide a better user interface with instructions in Italian.

## Contact

- **LeeFootSEO**: [Twitter](https://twitter.com/LeeFootSEO), [Website](https://leefoot.co.uk)
- **NUR® Digital Marketing**: [Website](https://www.nur.it)

Need an app? Want to run this as a managed service? [Contact us!](mailto:hello@leefoot.co.uk)
