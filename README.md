# Predicting Band Gaps of SnSe-Based Materials from Composition

Capstone project — Machine Learning for Materials and Metallurgical Engineering, UGC Malaviya Mission Teacher Training Programme (13–18 July 2026).

## Contents

- `band_gap_snse_materials.ipynb` — working notebook: queries the Materials Project for Sn-Se-based compounds, featurizes with matminer (Magpie), and trains classification (metal vs. insulator) and regression (band gap) models with 5-fold cross-validation.
- `SnSe_Capstone_Report.docx` — written report.
- `SnSe_Capstone_Slides.pptx` — presentation slides.
- `figures/` — result figures used in the report and slides.

## Group

| Name | Role | Institution |
|---|---|---|
| Dr. Prashant Shahi | Group Leader & Modeling Lead | Deen Dayal Upadhyaya Gorakhpur University |
| Mrs. Akanksha | Data Lead | Chaudhary Charan Singh University, Meerut |
| Dr. Santosh Kumar | Preprocessing Lead | Era University |
| Mrs. Alfiya Mahmood | Report Lead | Era University |
| Dr. Nagendra Kumar Singh | Presentation Lead | Era University |

## Running the notebook

Requires a free Materials Project API key (https://next-gen.materialsproject.org/api), set as the `MP_API_KEY` environment variable, plus `mp-api pymatgen matminer scikit-learn pandas matplotlib`.
