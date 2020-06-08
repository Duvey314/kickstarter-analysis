# kickstarter-analysis
Performing preliminary analysis on kickstarter data to uncover trends related to a theatre production.

The file Kickstarter Analysis contains the preliminary analysis on the kickstarter data as well as some exploration of excel functions like pivot tables, vlookups, central tendency, and visualizations. 

The file module solutions contains the data for the conclusions below. 

### challenge

After the initial analysis I looked at how two variable seperated effected the outcome of the kickstarter.

### How does the goal effect the outcome?

This analyis looks specifically at the play subcategory and how the funraising goal effects the outcome. To analyze the data I started by seperating the goal amounts into ~$5000 bins. Then I further divided the data using the outcome of the kickstarter: *successful, failed, or canceled*. I then plotted the outcome per goal amount by percentage as seen in the figure below.


![Outcome Based on Goal Amount](https://github.com/Duvey314/kickstarter-analysis/blob/master/Outcome%20Based%20on%20Goal.PNG)

As you can see in the figure, the goal amount highly influences the outcome of the kickstarter. When the goal is less than $1000, there is a 75% success rate. This is a fairly reliable estimate becasue there are nearly 200 data points for this range. On the other end of the spectrum, from $25,000 and up the corelation is a bit more complicated as we only have 40 data points for this range out of a total of 1000+ data points. What we can say though is that after $25,000 only one out of every three kickstarters was successful. 

### How does the date launched effect the oucome?

This analysis looks at the theater parent category which includes plays, musicals, and places (building a performance space). I made a pivot chart to examine how the month the kickstarter was launched effects the outcome. I the plotted this using the raw numbers rather than the percentage.

![Outcome Based on Launch Date](https://github.com/Duvey314/kickstarter-analysis/blob/master/Outcome%20Based%20on%20Launch%20Date.PNG)

Looking at the graph there are a few things that jump out immediately. The first is that May seems to be the best month to start a kickstarter and December seems to be the worst. The reason for this is not clear from the data directly. A few things that could contribute is that tax returns are from Feb to Aril so an influx of cash could make people a little more generous. The second is that in December most people are saving money for holiday presents. These are just guesses based on the time of year and there is no direct corelation to the data. Other data sources such as a survey of what people spend their tax return on or a survey of caegorical spending by month could help bridge the data gap.
