
##  How to Explore the Project

1. **Open Files by Meeting Date**
   - Go to folders named with the date of each working session.
   - Relevant `.ipynb`, `.zarr`, or `.csv` files are inside.

2. **Read the PDF Document for Workflow**
   - 📄 Open `pdf/workflow_summary.pdf` to understand:
     - How product descriptions are mapped to CPC sectors
     - How LCA data is normalized and integrated
     - Cut-off and hybridization process

3. **Check Jupyter Notebooks (`.ipynb`)**
   - Open notebooks via **Google Colab** or **JupyterLab**
   - Example: `notebooks/update_Q_matrix.ipynb` includes:
     - Loading original `Q_matrix` from `2022.zarr`
     - Updating with sector-specific micro-LCA coefficients
     - Saving the updated matrix to Google Drive

##  Requirements

```bash
pip install numpy cupy zarr pandas matplotlib

