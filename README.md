
# Goyal & Welch (2008) — Equity Premium Prediction (Replication)

This repo contains a cleaned, GitHub-friendly Jupyter notebook with step-by-step solutions and short interpretations.

## Files
- notebooks/goyal_welch_2008_replication.ipynb — the main notebook

## How to run
1. Create a virtual environment (recommended)
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter lab
   ```
   or
   ```bash
   jupyter notebook
   ```

## Notes
- Outputs were cleared before upload to keep git diffs clean.
- After cloning, run the notebook to regenerate outputs.
## Data (manual download)

This project uses the **Goyal–Welch predictor dataset**. The file is not bundled in the repository and must be downloaded manually.

### How to download
1. Download the dataset from the source used in the notebook.
2. Save it into the project folder:
   - `data/` (recommended), or the same folder the notebook expects.
3. Make sure the filename matches what the notebook is looking for (see the first “Data loading” cell).

### Important note about dates / sample period
The dataset is periodically updated. **The date you download the file can change the end of the sample**, which may slightly change:
- the analysis window
- the out-of-sample evaluation period
- reported performance metrics

To keep results reproducible, record the download date you used:
- Download date used in this run: **YYYY-MM-DD**
- Sample end date in the notebook output: **YYYY-MM** (or exact date shown)

If you download a newer version, expect the analysis period to extend and some numbers to update accordingly.
