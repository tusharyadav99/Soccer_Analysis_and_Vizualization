# 🏆 Soccer Analytics Visualization ⚽

This repository provides a comprehensive analysis and visualization of the FIFA World Cup 2022 Final between Argentina and France. Using data from StatsBomb and leveraging the `mplsoccer` library, we explore various aspects of the match, including shots, passes, passing networks, and danger passes.

## 📂 Project Structure

- **`Soccer_Analytics_Visualization.ipynb`**: The main Jupyter Notebook containing all the analysis and visualizations.
- **`Outputs/`**: Directory containing the generated visualizations, such as shot maps, pass maps, passing networks, and heatmaps.

## 📊 Analysis Overview

### 1. Competition and Match Data
- **Competition**: FIFA World Cup 2022
- **Match**: Final - Argentina vs. France
- **Match ID**: `3869685`

### 2. Visualizations and Insights

#### 📝 Lineup Data
- Extracted player lineups for both teams, including jersey numbers and positions.

#### 🎯 Shot Maps
- **Argentina's Shots**: Visualized all shots taken by Argentina, highlighting goals in red.
- **France's Shots**: Visualized all shots taken by France, highlighting goals in blue.
- **Combined Shot Map**: Displayed shots from both teams on a single pitch for comparison.

#### 🛜 Passing Maps
- **Lionel Messi's Passes**: Visualized all passes made by Lionel Messi during the match.
- **Kylian Mbappé's Passes**: Visualized all passes made by Kylian Mbappé during the match.
- **Team Pass Maps**:
  - Argentina: Pass maps for all players.
  - France: Pass maps for all players.

#### 🔗 Passing Networks
- **Argentina's Passing Network**: Visualized the connections between players based on successful passes, with node sizes representing the number of passes made.
- **France's Passing Network**: Similar visualization for France.
- **Centralization Index**: Calculated to measure the extent to which one player dominated the passing network.

#### 🔥 Danger Passes
- Identified and visualized "danger passes" (passes leading to a shot within 15 seconds) for Argentina during the tournament.
- Created a heatmap to show the density of danger passes per game.

### 3. Key Findings
- **Argentina's Attack**: Lionel Messi played a central role in Argentina's attack, with a high number of successful passes and key contributions in the final third.
- **France's Counterattacks**: Kylian Mbappé's passes and movements were pivotal in France's counterattacking strategy.
- **Passing Networks**: Argentina's passing network showed a balanced distribution, while France's network was slightly more centralized around key players.
- **Danger Passes**: Argentina's danger passes were concentrated in the attacking third, highlighting their aggressive playstyle.

## 🛠️ Tools and Libraries
- **Python**: Programming language used for analysis.
- **mplsoccer**: Library for creating soccer visualizations.
- **pandas**: Data manipulation and analysis.
- **matplotlib**: Plotting library for visualizations.

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

