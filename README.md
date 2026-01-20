# IPL-2025-Exploratory-Data-Analysis
About Exploratory Data Analysis of IPL 2025 player and team performance using Python
# IPL 2025 Exploratory Data Analysis

# Overview

This project delivers a comprehensive exploratory data analysis (EDA) of the IPL 2025 season, systematically evaluating individual and team performance using detailed batting and bowling statistics. The analysis emphasizes rigorous data preparation, statistical aggregation, and clear visual interpretation to uncover performance trends and competitive insights,


while also serving as a structured exercise to strengthen practical data analysis and coding proficiency on a real-world sports dataset.

------
### Objectives
1. Identify the top five players with the highest total runs in the IPL 2025 season

2. Determine the team that secured the most wickets and rank the top five teams by total wickets taken

3. Analyze players who have played more than 10 matches, maintain a strike rate above 100, and lead in total sixes hit

4. Examine team batting performance to identify teams that have accumulated more than 2500 runs in the season

5. Compare the top six all-rounders based on runs scored, wickets taken, and combined overall performance metrics

-------
## Dataset
- Source: Kaggle (IPL 2025 dataset)
- Data includes player-level batting and bowling statistics for the IPL 2025 season.
- The dataset is not uploaded to this repository due to licensing considerations.  
  Please refer to the Kaggle link to access the data.

-------
### Methodology

- Cleaned and standardized batting and bowling datasets through rigorous type validation, missing-value handling, and consistent schema alignment to ensure analytical accuracy.

- Applied strict qualification criteria to eliminate small-sample distortion and retain only statistically meaningful performances:

- Batting analysis included players meeting a minimum threshold of matches, balls faced, and innings played.

- Bowling analysis considered only bowlers who met minimum overs and match participation requirements.

- Performed player-level aggregation to rank batters by total runs, strike rate, six-hitting ability, and match participation, enabling objective identification of elite performers.

- Computed team-level performance metrics using aggregate-first and weighted methodologies to accurately reflect collective output:

- Weighted Strike Rate to measure overall team batting efficiency relative to volume faced.

- Weighted Economy Rate and total wickets to evaluate bowling effectiveness and penetration.

- Isolated multi-dimensional contributors by integrating batting and bowling outputs to assess all-rounder impact through combined performance indices.

- Conducted comparative analysis across players and teams to benchmark top performers against season-wide distributions.

- Employed clear, purpose-driven visualizations to highlight rankings, contrasts, and performance trade-offs aligned with each research question.

--------
### Key Insights

- A small group of elite batters clearly separates from the rest of the league, accounting for a disproportionate share of total runs and consistently exceeding season-wide benchmarks in strike rate and boundary frequency.

- Wicket-taking is concentrated among a limited number of teams, with the top five bowling units demonstrating markedly higher penetration rates, underscoring the impact of collective bowling depth rather than reliance on individual performers.

- High-volume run accumulation at the team level is restricted to a select few sides, indicating that crossing the 2500-run threshold is strongly associated with stable top-order performance and sustained batting efficiency.

- Players meeting the dual criteria of experience (10+ matches) and high strike rates dominate six-hitting metrics, highlighting the relationship between match exposure, intent, and boundary conversion.

- All-rounder comparison reveals clear stratification: top performers contribute meaningfully in both disciplines, while others exhibit skewed profiles with dominance in either batting or bowling, reinforcing the value of balanced skill sets.

-------
### ## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

--------
### Conclusion 
This project demonstrated the critical value of deliberate analytical design—establishing well-defined questions, enforcing fair qualification criteria, and applying weighted metrics to prevent distorted conclusions. By prioritizing reasoning before implementation, the analysis avoided superficial averages and instead captured performance in its true competitive context. Beyond the insights drawn from IPL 2025 data, the work functioned as a full end-to-end EDA exercise, strengthening analytical discipline, metric selection judgment, and reproducible coding practices on a complex, real-world sports dataset.
