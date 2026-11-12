# Data-Manipulation-with-pandas
Learn how to inspect DataFrames and perform fundamental manipulations, including sorting rows, subsetting, and adding new columns
# Data Manipulation with Pandas

In this project, I practiced working with DataFrames in Python using the `pandas` library. I used a dataset about homelessness across US states to explore, filter, and sort the data.

## What I did in this project:
- Loaded the dataset (`homelessness.csv`) and inspected its structure.
- Created a new column (`indiv_per_10k`) to calculate the number of homeless individuals per 10,000 people in each state.
- Filtered the data to keep only the states with more than 20 homeless individuals per 10,000 people.
- Sorted the results from highest to lowest and selected the state names and rates.

## Key Findings (Results):
The analysis showed 7 areas with the highest homelessness rates per 10,000 people:
1. **District of Columbia** (~53.7 per 10k) — highest by far
2. **Hawaii** (~29.1 per 10k)
3. **California** (~27.6 per 10k)
4. **Oregon** (~26.6 per 10k)
5. **Nevada** (~23.3 per 10k)
6. **Washington** (~21.8 per 10k)
7. **New York** (~20.4 per 10k)

## Files in this repository:
- `df_analysis.py`: My Python script containing all the data manipulation steps.
- `homelessness.csv`: The dataset I used for this practice.

## Tools used:
- Python
- Pandas
- VS Code

## How to run it:
1. Download both files into the same folder.
2. Make sure you have pandas installed (`pip install pandas`).
3. Run `df_analysis.py` to see the output in your terminal.
