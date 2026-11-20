# Zomato Data Analysis using Python
Exploratory Data Analysis (EDA) of a Zomato restaurant dataset to understand
restaurant categories, customer votes, ratings, online ordering, table booking
and cost for two people.
## Project Overview
This project cleans and analyses 148 restaurant records using Python. It answers
ten analytical questions with Pandas summaries and Matplotlib/Seaborn charts.
## Dataset
| Field | Description |
|---|---|
| Restaurant Name | Name of the restaurant |
| Online_Order | Online ordering available (Yes/No) |
| Book_Table | Table booking available (Yes/No) |
| Rate | Rating in x/5 format |
| Votes | Number of customer votes |
| Approx_Cost(For Two People) | Approximate cost for two |
| Listed_In(Type) | Category: Buffet, Cafes, Dining, other |

Size: 148 rows × 7 columns. No missing values or duplicate rows.
## Tools Used
Python · Jupyter Notebook · Pandas · NumPy · Matplotlib · Seaborn
## Data Cleaning
- Converted `Rate` from text (e.g. `4.1/5`) to a numeric value
- Standardised column names to upper case
- Renamed the cost column to `APPROX_COST`
- Checked for missing values and duplicates
## Questions Answered
1. Total votes by restaurant type
2. How many restaurants offer table booking
3. Top five restaurants by votes
4. Relationship between ratings and votes
5. Average rating by restaurant type
6. Most common restaurant type
7. Distribution of ratings
8. Average cost for two by restaurant type
9. Online ordering vs ratings
10. Online ordering across restaurant types
## Key Insights
- Dining makes up 74.3% of records and has the most votes (20,363).
- Table booking is uncommon: only 8 records (5.4%).
- Empire Restaurant has the most votes (4,884), followed by Meghana Foods (4,401).
- Ratings and votes show a moderate positive correlation (r ≈ 0.49).
- The "other" category has the highest mean rating (3.91); Buffet has the highest
  mean cost for two (671.43).
- Records with online ordering average 3.86 vs 3.49 without it.
## Limitations
Results describe only these 148 records and should not be generalised to all
Zomato restaurants. The "other" and Buffet categories have very few records.

## Author
**Rohini M. R.** · Data Analyst (aspiring) ·
