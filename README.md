# Compare-Baseball-Player-Statics-Using-Visualizationa

## Project Description
- In this project, i´m going to wrangle, analyze, and visualize Statcast historical data to compare Mr. Judge and another (extremely large) teammate of his, Giancaro Stanton.

## INSTRUCTIONS
1. How many of each event did Judge and Stanton have in 2017?
Save your answer as two Pandas Series: judge_events_2017 and stanton_events_2017. The events should be the index, and the event counts should be in descending order.

2. Which player hit home runs slightly lower and harder?
Visualize the launch_speed versus launch_angle for each players' home runs with one plot for each player. Save the plots under fig1 and ax1.
Save either "Stanton" or "Judge" to a variable named player_hr.

3. Compare the pitch velocity, or release_speed, for both players using plots. Which player hit their home runs off of faster pitches (has the highest median)? Save either "Stanton" or "Judge" to a variable named player_fast. 

4. Construct a 2D histogram for each player that visualizes the home run strike zones, ignoring zones 11, 12, 13, and 14 for simplicity.Create a new filtered DataFrame for each player called judge_strike_hr and stanton_strike_hr. Use the custom functions provided to assign coordinates to the data; save these as new columns zone_x and zone_y in the new DataFrames.

## Key Features
- Connect to a CSV file 
- Improving data visualization in python
- Pandas, Matplotlib and Seaborn tools

## Files
- `Compare-Baseball-Player-Statics-Using-Visualization.ipynb` → main Jupyter notebook with the code and analysis
-Readme.md file

## Author
- Enrique Velasquez
