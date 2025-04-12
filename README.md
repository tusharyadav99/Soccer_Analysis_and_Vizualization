# 🏆 Soccer Analytics Visualization

This repository provides a comprehensive analysis and visualization of the FIFA World Cup 2022 Final between Argentina and France. Using data from StatsBomb and leveraging the `mplsoccer` library, we explore various aspects of the match, including shots, passes, passing networks, and danger passes.

---

## 📂 Project Structure

- **`Soccer_Analytics_Visualization.ipynb`**: The main Jupyter Notebook containing all the analysis and visualizations.
- **`Outputs/`**: Directory containing the generated visualizations, such as shot maps, pass maps, passing networks, and heatmaps.

---

## 📊 Analysis Overview

### 1. Competition and Match Data
- **Competition**: FIFA World Cup 2022
- **Match**: Final - Argentina vs. France
- **Match ID**: `3869685`

---

### 2. Visualizations and Insights

#### 📝 Lineup Data
- Extracted player lineups for both teams, including jersey numbers and positions.

#### **Pitch**

![pitch](https://github.com/user-attachments/assets/74eb011e-b248-499b-aae6-b75588e7b783)

---

#### 🎯 Shot Maps
- **Argentina's Shots**: Visualized all shots taken by Argentina, highlighting goals in red.

![argentina_shots](https://github.com/user-attachments/assets/e64104ba-0c16-4c06-bd7f-7d5bf19fc3d3)

- **France's Shots**: Visualized all shots taken by France, highlighting goals in blue.

![france_shots](https://github.com/user-attachments/assets/09cb678d-63d2-475e-ab5a-d9703b2e11aa)

- **Combined Shot Map**: Displayed shots from both teams on a single pitch for comparison.

![shot_plot](https://github.com/user-attachments/assets/6d38dd86-529f-4a11-ac56-9f773b87c7eb)

---

#### 🛜 Passing Maps
- **Lionel Messi's Passes**: Visualized all passes made by Lionel Messi during the match.

![messi_passes](https://github.com/user-attachments/assets/cd4d8a7d-fb91-4fba-bd43-420cabb4aa10)

- **Kylian Mbappé's Passes**: Visualized all passes made by Kylian Mbappé during the match.

![mbappe_passes](https://github.com/user-attachments/assets/6231867e-3aa0-4624-9444-25729b868180)

- **Team Pass Maps**:
  - Argentina: Pass maps for all players.
  - ![argentina_passes](https://github.com/user-attachments/assets/0207b22e-7a40-40e0-8cfa-3148c2f3d96e)

  - France: Pass maps for all players.
  - ![france_passes](https://github.com/user-attachments/assets/712310bf-e483-4064-aea9-8ce3fd0c7d15)

---

#### 🔗 Passing Networks
- **Argentina's Passing Network**: Visualized the connections between players based on successful passes, with node sizes representing the number of passes made.
    - ![argentina_network](https://github.com/user-attachments/assets/6df678d8-d492-4e4e-8e2f-f71103043638)

- **France's Passing Network**: Similar visualization for France.
    - ![france_network](https://github.com/user-attachments/assets/528461b5-d26e-4619-88ed-5a9774d7e219)

- **Centralization Index**: Calculated to measure the extent to which one player dominated the passing network.

#### 🔥 Danger Passes
- Identified and visualized "danger passes" (passes leading to a shot within 15 seconds) for Argentina during the tournament.
   - ![danger_passes](https://github.com/user-attachments/assets/dad8a915-4241-49e1-abeb-efee6d5f7af5)

- Created a heatmap to show the density of danger passes per game.
  - ![danger_passes_heatmap](https://github.com/user-attachments/assets/fc7311e3-1e09-4a10-9a59-a2310dd49e8e)

---

### 3. Key Findings
- **Argentina's Attack**: Lionel Messi played a central role in Argentina's attack, with a high number of successful passes and key contributions in the final third.
- **France's Counterattacks**: Kylian Mbappé's passes and movements were pivotal in France's counterattacking strategy.
- **Passing Networks**: Argentina's passing network showed a balanced distribution, while France's network was slightly more centralized around key players.
- **Danger Passes**: Argentina's danger passes were concentrated in the attacking third, highlighting their aggressive playstyle.

---

## 🛠️ Tools and Libraries
- **Python**: Programming language used for analysis.
- **mplsoccer**: Library for creating soccer visualizations.
- **pandas**: Data manipulation and analysis.
- **matplotlib**: Plotting library for visualizations.

---

## 📷 Outputs
All visualizations are saved in the `Outputs/` directory:
- `shot_plot.png`: Combined shot map for Argentina and France.
- `argentina_shots.png`: Argentina's shot map.
- `france_shots.png`: France's shot map.
- `messi_passes.png`: Lionel Messi's pass map.
- `mbappe_passes.png`: Kylian Mbappé's pass map.
- `argentina_passes.png`: Argentina's team pass map.
- `france_passes.png`: France's team pass map.
- `argentina_network.png`: Argentina's passing network.
- `france_network.png`: France's passing network.
- `danger_passes.png`: Scatter plot of danger passes.
- `danger_passes_heatmap.png`: Heatmap of danger passes.

---

## 🚀 How to Run

Follow these steps to run the project and generate the visualizations:

1. **Clone the Repository**  
   Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/tusharyadav99/Soccer_Analysis_and_Vizualization.git
   cd soccer-analytics-visualization
   ```
2. **Install Dependencies**
   Install the required Python libraries using `pip` :
   ```python
     !pip install statsbombpy
     !pip install mplsoccer
   ```
3. **Open the Jupyter Notebook**
   Launch the Jupyter Notebook and open the main analysis file:
   ```bash
     jupyter notebook Soccer_Analytics_Visualization.ipynb
   ```
4. **Run the Notebook**
   Execute the cells in the notebook sequentially to generate the visualizations and analysis.
5. **View Outputs**
   All generated visualizations will be saved in the `Outputs/` directory.
   You can view them directly or use them in your reports.

---

## 🛠 Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- Libraries: `mplsoccer`, `pandas`, `matplotlib`, `numpy`, `statsbombpy`

---

## 📚 References

- **[StatsBomb](https://statsbomb.com/)**: The primary data source for match events, player statistics, and competition details.
- **[mplsoccer](https://mplsoccer.readthedocs.io/)**: A Python library for creating soccer visualizations, including pitch plotting, heatmaps, and passing networks.
- **[Matplotlib](https://matplotlib.org/)**: A comprehensive library for creating static, animated, and interactive visualizations in Python.
- **[Pandas](https://pandas.pydata.org/)**: A powerful data analysis and manipulation library for Python, used for handling match and event data.
- **[NumPy](https://numpy.org/)**: A library for numerical computations in Python, used for data processing and calculations.
- **[FIFA World Cup 2022](https://www.fifa.com/tournaments/mens/worldcup/qatar2022)**: Official tournament details and match information.

---

## 📬 Contact

For any questions, suggestions, or feedback, feel free to reach out:

- **Email**: [Tushar Yadav](mailto:tyadav940@gmail.com)
- **GitHub**: [tusharyadav99](https://github.com/tusharyadav99/)
- **LinkedIn**: [Tushar Yadav](https://www.linkedin.com/in/your-linkedin-profile)

I would love to hear from you!

---

## ⚠️ Disclaimer

This project is intended for educational and informational purposes only. 

- All data used in this project is sourced from publicly available datasets provided by **StatsBomb**.
- Python codes are from [Soccermatic](https://soccermatics.readthedocs.io/en/latest/index.html) course
- The visualizations and analyses are based on the FIFA World Cup 2022 Final and are not affiliated with or endorsed by FIFA or any official governing body.
- Ensure proper attribution if reusing or sharing any part of this project.

Use this project responsibly and respect the terms of use of the data sources.

---
