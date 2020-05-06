# Groupby_practice

Use groupby Pandas function on min_wage_dataset.

You can find the US Minimum Wage by State from 1968 to 2017 dataset [here](https://www.kaggle.com/lislejoem/us-minimum-wage-by-state-from-1968-to-2017)

## Description of the data:

Year: Year of data

State: State/Territory of data

Table_Data: The scraped, unclean data from the US Department of Labor.

Footnote: The footnote associated with Table_Data, provided by the US Department of Labor.

High.Value: As there were some values in Table_Data that had multiple values (usually associated with footnotes), this is the higher of the two values in the table. It could be useful for viewing the proposed minimum wage, because in most cases, the higher value meant that all persons protected under minimum wage laws eventually had minimum wage set at that value.

Low.Value: This is the same as High.Value, but has the lower of the two values. This could be useful for viewing the effective minimum wage at the year of setting the minimum wage, as peoples protected under such minimum wage laws made that value during that year (although, in most cases, they had a higher minimum wage after that year).

CPI.Average: This is the average Consumer Price Index associated with that year. It was used to calculate 2018-equivalent values.

High.2018: This is the 2018-equivalent dollars for High.Value.

Low.2018: This is the 2018-equivalent dollars for Low.Value.