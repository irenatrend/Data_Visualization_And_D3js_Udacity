# Data Visualization and D3.js - Data Analyst Nanodegree (Udacity)

[The Story About Burning Man](https://htmlpreview.github.io/?https://github.com/irenatrend/Data_Visualization_And_D3js_Udacity/blob/master/index.html)
 
*...A picture is worth a thousand words...*

## Summary
Burning Man is an annual gathering that takes place at Black Rock City (a temporary community erected in the Black Rock Desert in Nevada). At Burning Man the
community explores various forms of artistic self-expression, created in celebration for the pleasure of all participants. The statistics below illustrate the 
growth in attendance of the Burning Man event as well as other facts and figures. Additionally the chart visualize the man height changes over 
the years and is displaying more info about ticket prices and ticket sales strategy. The event has experienced significant growth in popularity.

In this project the main goal was to tell the story about the Burning Man event. I was really interested to learn more about the event, as well as to 
visualize my findings and share the chart with my friends. Since I didn't find any dataset that will contain all the information I 
was interested in, I've decided to build it by myself. I did some research, defined the data set columns and categorized the information by myself. 

Researching and learning more and more about the event, and creating the dataset by myself was really interesting part of my project work. 
All the data was collected from couple of different sites. After classifying the data my idea was to visualize it on one page chart where I can 
display the attendance, ticket price, man height values over the years as well as other facts about the event growth.

## Design 
Line charts are particularly good for showing changes over time. A line chart plus scatter plot was a great choice to achieve simplicity. 
Using  comment arrows (static tooltips) with different color my point was to emphasize some special events and highlight the main one (font color: red). 
On the standard/regular tooltips which are displayed on hover  I was able to display more info about each year.

After collecting the feedback from the Udacity discussion forum and my coworkers I've decided to do the following changes to improve my initial chart design
[The Story About Burning Man version 1](https://htmlpreview.github.io/?https://github.com/irenatrend/Data_Visualization_And_D3js_Udacity/blob/master/index_1.html).
 
* Play around with arrow lengths and text placements to make all of the comments easier to read.
* Change the arrow color.
* Remove the sub-chart name in parentheses.
* Change font size of the axis labels "Year" and "Attendance" (could just be a tiny bit bigger font).
* Change the y axis format from K to full numbers.
* Change the location of the first drop in population.
* Make the y axis go to 90,000 - this will reduce the crowding of text in the top right.
* Bug – Firefox (When I click the selector for the chart types, nothing changes - I only see the attendance chart but the title does change).

I've decided not to change the series type from scatter to bar, since scatter plots were more clear design solution.

My next steps are: 

* Improve the data quality. Add or change current event descriptions if I find more valid data.
* Include animation if needed (At this phase of my visualization I didn't see the value of including animation, but probably in the future I can add some animation.) 
* Add more text around my chart before I share it officialy with my friends. 

Here is my final version: 
[The Story About Burning Man](https://htmlpreview.github.io/?https://github.com/irenatrend/Data_Visualization_And_D3js_Udacity/blob/master/index.html)


## Feedback

### Feedback 1
You've put together quite an interesting visualization. I like that you've put out unique notes on each of the different plots. The most interesting 
thing to me was that the attendance and ticket prices increased at fairly correlated rates; this suggests that there's still a lot of demand among 
those who want to participate in the festival and plenty of people who are willing to pay for their experience.

Aesthetically, I think the plot is quite good as well. The comment arrows are a little bit odd as being tilted slightly clockwise of vertical; 
it might be better for them to be vertical or tilted slightly towards the left. It might be good to try playing around with arrow lengths and 
text placements to make all of the comments easier to read. It is also a little bit odd for the tick marks on the vertical scale to scroll in 
and out because of how different the ranges are on each of the individual plots, but this is a very, very minor point. Otherwise, the visualization 
feels quite good to me already!


### Feedback 2 
Very nice looking visualization and I think the information is very clear.
When i click the selector for the chart types, nothing changes - I only see the attendance chart but the title does change. ( I use frefox -- haven't tried anything else

A few very minor thoughts. (an I am no expert!!!)

* The overall chart is so elegant that the sub-chart name in parentheses in the title seems like an afterthought. I think visually it belongs below or near the selector. Perhaps white on black in the big white space top left a bit below the selector.
* the axis labels "Year" and "Attendance" could just be a tiny bit bigger font
* abbreviating, the attendance with "k" may be a little too "techie" - may be just "50,000" will format fine (and also help make the point that it is a big number!!)
* I dont' think you need arrow heads -- or if you keep them make them much smaller - they seem to detract and don't really add anything. Perhaps also a lighter line for the marker lines.
* the first drop in population may be better below the line .. this will emphasize it and avoid the overwriting (for vehicle passes as well)
* Perhaps make the y axis go to 80,000 - this will reduce the crowding of text in the top right

Overall I think this is very informative and it looks great!!


### Feedback 3 
First off, great job. The visualization is impressive for a beginner. Since I’m supposed to give feedback, here’s my feedback:

1. One data point I felt you missed is, when did founders (6) form the BRC, LLC? It was originally only 2, when the rest 4 join?
(especially considering you listed that they sold their shares in 2013)

2. I noticed that you’ve used the similar type of chart/visualization for all 3 datapoints. (attendance, height & price). I like the visualization you’ve used & I think it goes well for attendance as it can spike up/down.. lay flat. But in order to tell a story with a picture, I would use a slightly different visualization for height & price:
  * Man Height: I would recommend using a bar chart type of graph. So, the bars go up/down as per the man height
  * Price: I would recommend using a circular/expanding circles chart based on ticket price & total revenue. Something to ticket price to total revenue ration. And I would show the ticket price info right on the cirle. 
  * Lastly, I would eliminate the arrows all together. Instead I would just have that information as hover over/click over to read when I place the cursor on the data point.
 
If you want to convey a critical point, I would just simply write next to the data point instead of at the arrow head.

Hope this helps!
Again, great job!


### Feedback 4
* Is there something you don't like in the graphic?
	- No
* Is there something you don’t understand in the graphic?
	- the only confusion or you can say unclear part the Man’s height chart
* Do you have any questions about the data?
	- Same as above.
* What do you think is the main takeaway from this visualization?
	- It show the growth of the “Burning Man” over the years.
	- Ability to use different variations is great.


## Resources 
* http://dimplejs.org/
* http://dimplejs.org/advanced_examples_viewer.html?id=advanced_custom_styling
* http://dimplejs.org/advanced_examples_viewer.html?id=advanced_bars_sketchy
* https://en.wikipedia.org/wiki/Burning_Man
* http://burningman.org/timeline/
* http://www.burn.life/blog/the-evolution-of-burning-man
* http://www.rgj.com/story/life/2015/03/03/burning-man-grown-beyond-founders-dreams/24343027/