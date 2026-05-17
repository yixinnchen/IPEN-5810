# AI Narratives - Code and Results Submission

This folder contains only the code and final results for submission.
本文件夹只保留“代码”和“结果”

## Folder Structure

- `code/pipeline_scripts/`: Python scripts for the full data pipeline.
- `code/notebooks/`: Notebook showing the main AI narrative construction pipeline.
- `code/asset_pricing_notebooks/`: Notebooks for validation and asset-pricing analysis.
- `results/main_tables/`: Final CSV tables used in the analysis.
- `results/figures/`: Final descriptive figures.
- `results/asset_pricing/`: Asset-pricing regression, portfolio, DGTW, robustness, and report outputs.
- `results/presentation/`: Final presentation slides.

## Main Entry Point

If the original raw data are placed back into the project root, the full pipeline entry point is:

```bash
python3 code/pipeline_scripts/run_pipeline.py
```

Note: the original raw transcript / Compustat / CRSP data files are not included here because they are very large. The included CSV files under `results/` are the final generated outputs.

## Key Result Files

- `results/main_tables/firm_quarter_panel.csv`: Main firm-quarter panel.
- `results/main_tables/firm_year_panel.csv`: Firm-year panel.
- `results/main_tables/ai_sentence_level.csv`: AI sentence-level output.
- `results/main_tables/variable_dictionary.csv`: Variable definitions.
- `results/main_tables/data_quality_report.csv`: Data quality and merge report.
