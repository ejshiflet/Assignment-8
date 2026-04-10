# Assignment-8

Purpose: The purpose of this project is to use different type of plots from the seaborn library to visualize data in ways that may show trends or patterns. This was done with the given file and the public planets dataset.

Methods:
sns.scatterplot: Places a dot for every data point. Used to see the relationship (correlation) between two numbers, like distance vs. time.
sns.lineplot: Connects data points with a line. Usually used to show trends over time, like how many planets were found each year.
sns.histplot: Groups numbers into "bins" to show the shape of the data.
sns.boxplot: Shows the spread of data. The "box" represents the middle 50%, the line inside is the average (median), and dots outside are outliers.
sns.barplot: Uses rectangles to show a calculated value (like a sum or average) for different categories.
sns.heatmap: Uses colors instead of bars to represent numbers. Darker or warmer colors usually mean higher values.
sns.catplot: A function that can create multiple sub-plots in one go.
.melt(): Flips "wide" data into "long" data. This is required for Seaborn to color-code by category.
.quantile(): Finds the cutoff points for the top and bottom 1% of data. It’s used here to remove outliers so the graph doesn't look squashed.
.dropna(): Removes empty or "NaN" values so the math doesn't break during plotting.

Implementation: The graphs were implemented using the following methods and the data from Exercise_Data.csv and the public planets data set.

Part 1 Graph Explanations:
1. The heatplot can be used to draw a conclusion that the participants had higher pulse rates as time went on. Thats why there is more red in the bottom right corner.
2. This catplot shows that when partipants have a low fat diet and run, they have a higher pulse rates. The no fat diet shows that when running the participants have extremely high pulse rates.

Part 2 Graph Explanations:
1. Radial Velocity has low distance but can have a long period. While transit has low orbit but an have high distance.
2. This shows that planet discovery peaked around 2011.
3. This shows that when jupiter mass is low it has the highest frequency.
4. This shows that when the orbital period is lowest, frequency will be very high.
5. This shows that radial velocity has the largest range of mass when finding planets.
6. This shows that radial velocity has the most planet discoveries.
