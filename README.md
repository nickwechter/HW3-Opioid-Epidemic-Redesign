# HW3-Opioid-Epidemic-Redesign

For this assignment I found a chart that I thought could be redesigned to more effectively communicate its message.
Check out the sequence below to see how I approached the process!

### The Original Image
> ![Original Image](https://www.cdc.gov/drugoverdose/images/epidemic/2018-3-Wave-Lines-Mortality.png)
> Source: https://www.cdc.gov/drugoverdose/epidemic/index.html

I believe that the 3 lines representing 3 major categories of opioids do a great job at communicating the rise of certain types of opioid related overdoses. However, relevant information to the opioid epidemic could be more efficiently commmunicated with a few relativley simple redesigns. I chose to focus my redesigns on enforcing these two aspects of the chart: 
1. The severity of the Opioid Epidemic.
2. Enforcing the "waves" of relevant classes of Opioids

### WireFrame Redesigns

##### Aggregate Deaths Stacked Line Chart
> <div class="flourish-embed flourish-chart" data-src="visualisation/4381883"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

#### Proportions of Opioid Categories
> <div class="flourish-embed flourish-chart" data-src="visualisation/4382543"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

#### Binned Proportions of Opioid Categories
> <div class="flourish-embed flourish-chart" data-src="visualisation/4382008"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Process
As the wireframes showed, I spent a good amount of time experimenting with different portrayals of the data, and seeing how different formats extentuated different aspects of the opioid epidemic. One thing that was important to the impact of the message, to me, was changing from the deaths per 100,000 metric used in the original to just using the pure amounts of deaths. I also experimented with displaying the aggregate deaths (in which the Y axis represented the total amount of overdose deaths, including previous years), but I thought that this metric made it harder to view the trends of the different "waves" of categories of opioids. I also experimented with binning the years of different waves of the opioid epidemic (as shown in the "Binned Proportions..." wireframe), but the different time scales of the waves made it hard to maintain the continuous, increasing, curves that help make the graphic so powerful. 

### Final Redesign
<div class="flourish-embed flourish-chart" data-src="visualisation/4369492"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Back To The Homepage
https://nickwechter.github.io/Wecht-DataViz/
For the final redesign, I decided to use a stacked line chart displaying the overdose deaths associated with the three categories of opioids. Stacking the lines made it harder to discern the dominant trend occuring during each wave; to address this I colored each segment of the chart the same color as the relevant opioids line. My goal was that this would naturally draw the viewers attention to the appropriate curve and extentuate each "waves" new pattern. 

Because I thought that the sheer volume of the running total of opioid related overdoses was so powerful, I created a hidden data collumn storing this information, so that viewers could have access to it as the interacted with the chart. I also included the total overdose deaths on the right of the chart with the line labels. My decision to use a stacked line chart instead of 3 independent lines was to also strengthen the message of how many lives are effected by this epidemic. I thought that communicating not only how each line spiked independently, but also how the lines aggregated was important to include. 
