# Predicting Band Gaps of SnSe-Based Materials from Composition

Capstone project — Machine Learning for Materials and Metallurgical Engineering, UGC Malaviya Mission Teacher Training Programme (13–18 July 2026).

## Contents

- `band_gap_snse_materials.ipynb` — working notebook (follows the official FDP capstone notebook template structure): queries the Materials Project for Sn-Se-based compounds, featurizes with matminer (Magpie), and trains classification (metal vs. insulator) and regression (band gap) models with 5-fold cross-validation.
- `SnSe_Capstone_Report.docx` — written report, following the official FDP capstone report template.
- `SnSe_Capstone_Slides.pptx` — presentation slides, following the official FDP capstone presentation template.
- `figures/` — result figures used in the report, slides, and notebook.

## Group

| Role |
|---|
| Group Leader & Modeling Lead |
| Data Lead |
| Preprocessing Lead |
| Report Lead |
| Presentation Lead |

## Running the notebook

Requires a free Materials Project API key (https://next-gen.materialsproject.org/api), set as the `MP_API_KEY` environment variable, plus `mp-api pymatgen matminer scikit-learn pandas matplotlib seaborn`.
