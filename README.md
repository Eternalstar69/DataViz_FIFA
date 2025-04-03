# DataViz_FIFA: Data Visualization of FIFA Players Dataset

## Project Description

This project explores and visualizes FIFA player data using Pandas, Seaborn, and Matplotlib.  
The focus is on analyzing player characteristics, club-specific trends, and salary distributions, with a specific look at Manchester United and Liverpool players.

## Dataset Information

- **Dataset Name:** `football_data.csv`
- **Format:** CSV
- **Key Features Analyzed:** Player wages, club affiliation, nationality, player attributes, and more.

### Key Columns in the Dataset
| Column Name              | Description |
|--------------------------|------------|
| `ID`                     | Unique Player ID |
| `Name`                   | Player Name |
| `Age`                    | Player's Age |
| `Club`                   | Player's Club |
| `Nationality`            | Country of Origin |
| `Wage`                   | Weekly Wage in Euros |
| `Value`                  | Estimated Player Market Value |
| `Release Clause`         | Release Clause Price |
| `International Reputation` | Player's Reputation Level |
| `Overall`                | Player's Overall Rating |
| `Potential`              | Predicted Potential Rating |
| `Preferred Foot`         | Left or Right Foot Dominance |
| `Year_joined`            | Year the Player Joined Their Club |

---

## Installation & Setup

### 1. Install Required Libraries
Ensure you have the necessary Python libraries installed:

```bash
pip install numpy pandas matplotlib seaborn
```

### 2. Clone the Repository
```bash
git clone https://github.com/your-username/DataViz_FIFA.git
cd DataViz_FIFA
```

### 3. Place the Dataset
Ensure `football_data.csv` is in the same directory as the script.

### 4. Run the Python Script
```bash
python script_name.py
```

---

## Exploratory Data Analysis & Visualizations

### Top 10 Nationalities Represented in FIFA
- A bar plot shows the top 10 countries with the most FIFA players.

### Manchester United vs. Liverpool Analysis
- Extracts data for Manchester United & Liverpool players.
- Sorts players by Wage & Market Value.
- Bar plot of the top 10 highest-paid players.

### Wage Distribution & Trends
- Histogram showing the distribution of player wages.
- Line chart of the average wage by year joined.
- Pie chart of preferred foot distribution.

### Correlation Heatmap
- A Seaborn heatmap displaying correlations between Age, Wage, Value, Reputation, and Performance Metrics.

### Boxplots & Category Comparisons
- Boxplots comparing Overall Rating, Potential, Weak Foot, and Skill Moves across clubs.
- Scatterplot (lmplot) showing Wage vs. Overall performance.
- Categorical bar plot showing Wage based on International Reputation.

### Swarm Plot: Reputation & Preferred Foot Impact on Wages
- A swarm plot visualizing the relationship between Reputation, Preferred Foot, and Wage across Manchester United and Liverpool.

---

## Sample Visualizations

- Top 10 Nationalities with Most Players  
- Top 10 Highest Paid Players in Manchester United & Liverpool  
- Correlation Heatmap of Player Attributes  
- Boxplots Comparing Club Ratings  
- Wage vs. Overall Performance (Scatterplot)  
- International Reputation vs. Wage (Bar & Swarm Plot)  

---

## Results & Key Insights

- England, Spain, and Germany dominate FIFA representation.  
- Manchester United & Liverpool players have significant wage variations.  
- Higher International Reputation often correlates with higher wages.  
- Preferred foot does not heavily impact wages.  
- Players with better overall ratings demand higher wages.  

---

## Author & Credits

- **Author:** EternalStar69 
- **GitHub:** https://github.com/Eternalstar69/
- **References:**  
  - FIFA Dataset  
  - Matplotlib & Seaborn Documentation  

---

## Future Improvements

- Extend analysis to other clubs.
- Use more advanced statistical models for player valuation.
- Create interactive visualizations using Plotly.

---
