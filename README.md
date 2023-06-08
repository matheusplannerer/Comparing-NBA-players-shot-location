# Visualizing data with python
In week 3 of the University of Michigan's Foundations of Sports Analytics: Data, Representation, and Models in Sports we have looked at different ways of visualizing data. The assignment for this week is in two parts. First, use the NBA 2017 data to create some plots to compare individual players, and second, use the IPL innings data to comparing scoring rates of teams in different games.

## Part 1 - Comparing NBA players shot location
1. Load the data containing the NBA shot log for the 2016/17 season that we used earlier

2. Use the same code that we used to project all shots onto a half court by defining shot[‘halfcourt_x’] and shot[‘halfcourt_y’]

3. Now define subsets for the following players: Kevin Durant, Dwight Howard, DeAndre Jordan and Russell Westbrook.

4. Create plots of their shots in the same way that we did for Steph Curry and LeBron James: copy the code we used and just change the names. Show the plots of Russell Westbrook and Kevin Durant side by side. In order to make sure that the two plots have the same ranges, for each subplot add the lines:

- plt.xlim(500,950)
- plt.ylim(0,500)

5. Create the plot of DeAndre Jordan and Dwight Howard side by side

6. Create the plot of Brook Lopez and Robin Lopez side by side

## Part II - IPL innings data to comparing scoring rates of teams in different games (this was very challenging as I have zero Cricket knowledge)
1. Load the data for the IPL ball by ball (IPLbyb) and run the two functions that allow you to plot the game run/wicket curves for each game, and to plot multiple games alongside each other.

2. Now generate the plots for the pair of games between
a) Kings XI Punjab and Delhi Daredevils
b) Kolkata Knight Riders and Royal Challengers Bangalore
c) Sunrisers and Rajasthan Royals
d) Chennai Super Kings and Kolkata Knight Riders

