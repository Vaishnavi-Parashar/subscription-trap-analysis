# Subscription Trap Analysis

This project analyzes OTT subscription usage data using Python
to understand viewing behavior and identify hidden subscription traps.

## Dataset
- Source: Kaggle (Netflix Viewing Activity)
- Note: Dataset not uploaded due to licensing constraints

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Project Status
- Step 1: Dataset collection ✅
- Step 2: Data loading in Colab ✅
- Step 3: Column selection and cleaning ✅
## Netflix Analysis – Current Progress ✅

### Data Cleaning & Feature Engineering
- Converted watch duration from HH:MM:SS to minutes
- Removed sessions shorter than 1 minute to eliminate noise
- Final dataset contains 7,000+ meaningful viewing sessions

### Key Findings
- A small number of titles contribute disproportionately to total watch time
- Top titles like *Minnal Murali* and *CBI 5* dominate engagement
- This indicates potential subscription inefficiency where users pay for access but consume limited content

### Visualization
- Bar chart showing top 10 Netflix titles by total watch time
- Helps identify content driving actual subscription value

