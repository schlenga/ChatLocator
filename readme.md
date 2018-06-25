# ChatLocator

**Content**

- Analysis of chat history
- Combining with Google location history

*Due to the private nature of the data, I removed all data files and names. I also didn't upload the resulting map, because the location history Google provides is very detailed.*


## This is a little analysis of the WhatsApp history with my girlfriend.

### Analysis of Chat History
In the notebook [ChatStat](blob/master/ChatStat.ipynb), I take a quick look at the temporal aspect of our chats. 

Here's the cumulative sum of messages sent *by date*:

![Cumulative Sum of Messages](SumOfMessages.png)

Can you guess when we started dating?


But at what *time of the day* did we chat? Who sent whom when how many messages? Here's the plot:

![Messages by Time](ClockPlot.png)

Let's also check out how many messages we sent (in total) per *day of the week*, separated into messages I *received* and messages I *sent*:

![Messages by Day](DailyPlot.png)

### Combination with Google Location
In the second notebook, [MapChat](blob/master/MapChat.ipynb), I combine these data with my Google location history and plot a heatmap where I chatted with my girlfriend. Here's a screen shot:

![Screen Shot of the Heatmap-Map](SampleScreenshot.png)
