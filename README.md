# Exploring NASA's Planetary Exploration Budgets Through SQL Analysis.

## Executive Summary:
An analysis of the historical budget allocations for space missions, adjusted for inflation, categorized by destination and fiscal year using SQL. The analysis aims to uncover trends in funding across different space exploration destinations over time, providing valuable insights into NASA's budgetary priorities and strategic focus.

## Public Dataset:
https://www.planetary.org/space-policy/planetary-exploration-budget-dataset

## Methodology:
The analysis involved the following steps:
1.	Data Retrieval: Data was sourced from the mission_budgets, inflation, and mission_details tables within the NASA database.
2.	Data Joining: We joined the tables based on common keys to provide a comprehensive view of mission costs, adjusted for inflation.
3.	Data Grouping: We grouped the data by fiscal year and destination to calculate the total adjusted cost for each category.
4.	Data Analysis: We ordered the results and visualized to facilitate trend analysis and interpretation.
The bar plots were generated using Python’s “Matplotlib” library.

## Results:
The analysis yielded comprehensive insights into NASA's planetary exploration budgets, revealing trends in funding allocation over time. Key findings include:
1.	Total Cost: The total adjusted cost of all planetary missions over time amounted to $41,406 million USD.
2.	Inflation Adjustment: After adjusting for inflation, the total adjusted cost was calculated to be $41,447 million USD.
3.	Most Expensive Mission: The Europa Clipper emerged as NASA's most expensive mission, with an adjusted total cost of $5,283.81 million USD.
4.	Annual Spending: Yearly expenditure showcased fluctuations, reflecting changes in mission priorities and external factors.
5.	Expenditure by Destination: Analysis of spending by destination highlighted NASA's diverse exploration efforts, with significant investments in the Moon, Mars, and outer planets.
6.	Changes Over Time: Trends over time revealed shifts in NASA's exploration focus, from a lunar-centric approach to a more diversified portfolio encompassing various celestial bodies.

## Overall Interpretations:
## Interpretations of the findings revealed:
1.	Lunar Dominance: Significant funding during the Apollo era highlights the importance of lunar exploration.
2.	Mars Exploration: Consistent investment in Mars missions reflects sustained interest and exploration efforts on the red planet.
3.	Outer Planets Focus: Intermittent peaks in investment indicate flagship missions to outer planets like Jupiter and Saturn.
4.	Venus Exploration: Lesser funding for Venus missions suggests a lower priority compared to Mars and outer planets.
5.	Trend Shifts: Evolving trends highlight NASA's dynamic approach to planetary exploration, adapting to technological advancements and scientific discoveries.
## Conclusion
The report reveals a clear pattern of space exploration funding, with a shift from a lunar-centric approach in the early years to a broader focus on various solar system bodies. The sustained interest in Mars and periodic investments in outer planet missions reflect strategic priorities in space exploration. The data underscores the importance of adjusting for inflation to accurately assess historical budget trends.
