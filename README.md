# Summary

In this project, I want to compare the performance for different players by dimple.js based on the dataset "baseball_data.csv". After exploring the dataset, I find that the player performance is correlated to player's height. I bin data into three parts: short, medium and tall. Then I use bar plot to presesent the player performance and clearly we can see a trend that short players have higher average performance. 

# Design

Player Height is x-axis and Player Performance is y-axis: I try to explore the relationship between height vs player performance, weight vs player performance, BMI vs player performance. I find that player performance is not very correlated to weight. But I do find some relationship between player performance and height. So I use height as x-axis and avg as y-axis. 

Bin the data into three parts "short", "medium" and "tall": When I explore the relationship between avg and height, I use scatter plot first, then the trend is not quite clear. So I tried to bin data into wider bins. When I bined data into "short", "medium" and "tall" by player's height, I find that the trend is very clear. 

Bar plot: Here bar plot can show the trend clearly, much better than point plot and line plot. 

I also add some text for my visualization because it can help the reader understand the definition of "Short","Medium" and "Tall". 

In my initial design, I tried to split the data by handedness. It turned out that this didn't give a more interesting story. So in my final design, I just bin the data without regards to handedness. 

In my initial design, I used some animation. From the feedback, I realized that the animation was changing quickly and it was hard for reader to analyze the data. So in my final design, I just use simple interaction. It's simple but it's more clear. 


# Feedback

### Feedback 1(on the initial design):
The chart is a bit over plotted. Most of the data is in the middle height and weight range, so it's more likely that a high batting average will occur there. There are also some data points hidden behind other data points, so it's difficult to see if there is a trend or it's just that the big circles are covering the small ones. 

### Feedback 2(on the initial design):

The animation keeps going and never stops, so I never get a chance as chart reader to look at the data and analyze the visualization. If there is going to be a transition, make sure the user also gets the chance to look at the data on his or her own.


### Feedback 3(on the initial design):

If there's a difference between R, L and B, it's difficult to see. It seems like there might be some sort of difference between B and the other handedness because the points move slightly down and to the left, but I'm not sure what that really means.

### Feedback 4(on the final design):
In the visualization, I notice that player's height is divided into "Short","Medium" and "Tall". Also by the text on the right hand side, I generally know the height range for "Short","Medium" and "Tall". The y-axis is player's performance. From the bar plot, I can say that short players have higher performance than tall players. This visualization is clear to me. 
### Feedback 5(on the final design):
This visualization is interesting to me. From the graph, I can tell that short players have higher performance than tall players, which is kind of surprising to me. Because I though tall players always have some advantage over short players in sports field. For me, the only question is that how many data the author uses in this graph. Is the data enough to get such a conclusion? is there statistical evidence to support this conclusion?
### Feedback 6(on the final design):
I would say this final design is much better than the initial design. Even though the initial design used some fancy techniques, the story is not clear. Also it had some problems. I can see a clear story from this final design that short players have higher performance than tall players. Also I like the hover design and it's kind of cute. Maybe the author can add some more fancy features to the graph. 


# Resources

1. https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.chart#addSeries
2. http://dimplejs.org/examples_viewer.html?id=bars_horizontal_floating
