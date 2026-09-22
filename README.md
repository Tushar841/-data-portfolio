# Smartphone Usage Insights

## Question
How do people use their smartphones, and do age, gender, or city change it?

## Data
1,000 users across five US cities, ages 18 to 59. Columns include daily screen
time, total app usage, number of apps, and hours in social, productivity, and
gaming apps.

## What I did
- Cleaned the data with Python and Power Query: standardized text, checked for
  missing values and duplicates (none found).
- Found that 39.3% of users log more app hours than screen hours, which is
  impossible, and flagged those records instead of deleting them.
- Added age groups, screen-time bands, and category shares.
- Built an interactive dashboard with filters for gender, city, and age group.

## Findings
- Average screen time is 7.7 hours a day; 32.6% of users spend 10 or more hours.
- Usage is nearly the same across groups: cities differ by 0.7 hours and age
  groups by 0.5 hours.
- Social, productivity, and gaming each average about 2.5 hours a day.
- Recommendation: target users by behavior, not demographics, and fix the
  tracking logic behind the inconsistent hour records.

## Tools
Python (Pandas), Power Query, DAX, Power BI

## Live dashboard
[Open the dashboard](https://tushar841.github.io/data-portfolio/)
