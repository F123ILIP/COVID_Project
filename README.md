# COVID Project — Analysis & ML Forecasting

A compact project focused on **COVID‑19 data analysis** and **machine learning–based prediction** (forecasting the number of deaths / outcomes over time). The repository is structured around exploratory analysis and a reproducible modeling workflow.

> This repo currently points to a Google Colab notebook where the full analysis and experiments were executed.

## Goals
- Clean and analyze COVID time-series data
- Visualize trends and key indicators
- Build a predictive baseline model
- Communicate results clearly (plots + narrative)

## Run the project
### Option A — Google Colab (recommended)
Open the notebook:
- https://colab.research.google.com/drive/1VEfDf9X8FJF9YAahECp6XNcAcrn9QTD9

### Option B — Run locally (template)
> Adjust once the exact file structure is confirmed (scripts vs. notebooks).

1. Create environment
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # macOS/Linux
   .\.venv\Scripts\activate   # Windows
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Run
   ```bash
   python main.py
   ```

## What to expect
- Data cleaning + feature preparation
- Plots showing trends over time
- A baseline ML model with an evaluation section

## Reproducibility checklist
- [ ] Document dataset source + date range
- [ ] Fix random seeds
- [ ] Save preprocessing parameters
- [ ] Keep a single command / notebook to reproduce outputs

## Roadmap
- [ ] Add a brief dataset description (columns + units)
- [ ] Add baseline comparisons (naïve last value vs. ML)
- [ ] Add proper time-series validation (walk-forward)
- [ ] Export final plots to `/reports/` for easy viewing

## License
Choose a license (MIT is a good default). If you want, I can add one.