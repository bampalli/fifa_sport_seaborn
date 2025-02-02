# FIFA Player Data Analysis using Seaborn

## 📌 Overview

This project is focused on **Exploratory Data Analysis (EDA)** of the **FIFA player dataset** using Python libraries such as `Seaborn` and `Matplotlib`. The dataset contains detailed information about professional football (soccer) players, including their **skills, market values, and performance metrics**.

The primary objective of this analysis is to **explore trends, identify key insights, and understand the relationships between different player attributes**. Through data visualization, we aim to extract meaningful insights that can help in understanding player performance, market trends, and key characteristics of top footballers.

## 📂 Dataset Details

The dataset consists of **18,207 player records** with **89 attributes**. These attributes cover various aspects of the players, such as their personal details, financial information, physical characteristics, and game-related skills.

### Key Features in the Dataset:

1. **Player Information:**

   - `Name`: Player's full name.
   - `Age`: Age of the player.
   - `Nationality`: Country the player represents.
   - `Club`: Current club of the player.
2. **Performance Metrics:**

   - `Overall`: Player's overall rating (out of 100).
   - `Potential`: Predicted peak rating.
   - `Skill Moves`: Number of skill moves a player can perform.
   - `Weak Foot`: Ability of the player to use both feet effectively.
3. **Financial Attributes:**

   - `Value`: Estimated market value of the player.
   - `Wage`: Weekly salary of the player.
   - `Release Clause`: The price at which a club can buy out a player's contract.
4. **Skill-Based Attributes:**

   - `Passing`: Accuracy and efficiency in passing.
   - `Dribbling`: Ability to maneuver with the ball.
   - `Shooting`: Player's ability to take accurate shots on goal.
   - `Defending`: Defensive strength and ability to stop opponents.
5. **Physical Attributes:**

   - `Sprint Speed`: How fast the player can run.
   - `Stamina`: Player's endurance during a match.
   - `Strength`: Physical ability to withstand pressure from opponents.
   - `Reactions`: Reflex speed and quick response to situations.
   - `Balance`: Stability and control while running and dribbling.

## 📊 Features & Analysis

The **Exploratory Data Analysis (EDA)** process includes:

1. **Data Preprocessing:**

   - Handling missing values and inconsistencies in the dataset.
   - Converting financial attributes (e.g., `€100M`) into numerical values.
   - Normalizing and transforming data for better visualization.
2. **Exploratory Data Analysis (EDA):**

   - **Distribution of Player Ratings:** Analyzing how player ratings are spread across different leagues and teams.
   - **Correlation Analysis:** Using heatmaps to identify relationships between player attributes (e.g., Does stamina affect performance?).
   - **Club-Level Comparisons:** Identifying which clubs have the most highly rated players.
   - **Age vs. Market Value Trends:** Analyzing how player value changes with age.
   - **Skill Set Comparisons:** Understanding variations in skills like passing, dribbling, and shooting among different players and leagues.
3. **Visualizations Using Seaborn & Matplotlib:**

   - **Histograms & KDE Plots:** To analyze rating distributions.
   - **Box Plots:** To visualize variations in attributes like wages and market values.
   - **Heatmaps:** To show correlations between different player attributes.
   - **Bar Charts:** Comparing top clubs based on player values.

## 🛠️ Installation

To set up this project on your local machine, install the required dependencies using:

```bash
pip install pandas seaborn matplotlib numpy jupyter
```

## 📜 Usage

To run the project, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Bampalli/fifa-analysis.git
   cd fifa-analysis
   ```
2. **Open the Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```
3. **Run the Notebook:**
   Open and execute `seaborn_sport.ipynb` to explore the dataset and visualizations.

## 🔥 Insights from the Analysis

- The most valuable players in the dataset are from elite clubs such as **Barcelona, Real Madrid, and Juventus**.
- **Player performance is strongly correlated with attributes like dribbling, finishing, and ball control.**
- The **market value of players tends to peak between ages 25-30**, showing that experience is a key factor in determining a player’s worth.
- Defensive attributes such as **tackling and interceptions are crucial for high-rated center-backs**, whereas **speed and dribbling are key for wingers**.
- The **goalkeeper attributes (e.g., reflexes, diving, and positioning) show unique patterns that differentiate them from outfield players.**

---

This `README.md` provides a **detailed and structured explanation** of the FIFA Player Data Analysis project, making it easy to understand, set up, and explore. 🚀
