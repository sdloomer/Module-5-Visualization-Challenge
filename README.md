# Module-5-Visualization-Challenge
Analysis
Looking at the analysis generated, we can observe a few conclusions. One of the most obvious, tumor volume increases with subject weight, is very clearly shown on the scatter plot and its linear regression model depicted below. The correlation coefficient was calculated to be 0.84, nearly 1.0, which suggests a strong dependence.

Selecting a few drug treatments to run an analysis on, we can also observe that of the four, two of them, Capomulin and Ramicane, were more effective, with tumor volumes almost half the size as those subjects on Infubinol and Ceftamin. This is shown by the boxplot generated below. However, it should also be noted that both of these more effective drugs, Capomulin and Ramicane, had the most observed timepoints observed out of all the drug treatments.

When a single mouse was selected to observe tumor volume per timepoint, we can see that volume actually lessened over time with sharp droppoints (most likely by the administrations of the drug treatment), but began to rise again. If we were to chart similar graphs for all mice, perhaps we might see similar results.

Acknowledgments
I received immense support from my classmate Taylor Ward, who helped me with a few lines of code I was having some trouble with. I had read some instructions incorrectly, and after she pointed this out to me, thoughtfully provided me with a stepping stone line to help me with one of my dataframe merges. I also received help from TA Sanoo on the for loop for determining any outliers for the boxplot, and he helpfully provided me with this line: loc[merged_data["Drug Regimen"] == drug, 'Tumor Volume (mm3)'] that I used in Cell 14 to reduce my previous four .loc lines to just one.