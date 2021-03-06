#kickstarter-analysis
---
#Overview of Project
---
Our client Louise has found that her recent play “Fever” Has come close to the intended goal in a short amount of time and is curious to see if there was a correlation to when the launch date was set. Looking at the data it seems that the play itself was not successful, so I am also curious to see if the data shows a drop off during this time.
![Fever_data1.png](Fever_data1.png)

#Analysis and Challenges
---
Through the process of this new journey on excel I would try to find my own short cuts failing at some points and learning from my mistakes.  While working with the data at first, I realized I did not save the work I have done previously causing me to redo the data mistakenly using year() command earlier then intended when trying to convert the original date (EX: 1461857045). Realizing my mistake, I quickly fixed it while also creating a little cheat sheet for the future. 

---
Working on the next table and graph “Outcomes Based on Goal” was a tedious process that had no automation I could find. Meaning putting all the countifs() for every scenario was put on me, a feeble human prone to mistakes. With this I tried my best to cheat the system finding shortcuts like copy past. At the end of it all I found myself with a few mistakes seeing that I was supposed to put sub categorize “Plays” going back I just copied paste “’,Kickstarter!R:R, "plays"’.  I only assume we will learn a process in the next model that will make this process easier.

#Results
---
Looking at graph A which tells us the theaters outcomes (success, failed and cancelled) based on the launch date we can see that May would probably be the best time to launch a Kickstarter. Now looking at when the play Fever launched above. In this case it was June, one month after the highest recorded value. We can see that even though it went shooting up like the client said it was not able to see the light of day being $400 lower than the original goal. It would be a good option to have a graph that displays the “Theater’s Outcome Based on Deadline” which could shed more light to this problem. Lastly October seems to have no cancels what’s so ever but has a spike in failed which could mean that people were more ambitious this month rather then canceling their shows they ended up failing. There is also a slight increase on success which means not all missing canceled failed. 
![fever_data2.png](fever_data2.png)
![Theater_Outcomes_vs_Launch2.0.png](Theater_Outcomes_vs_Launch2.0.png)

---
Looking at “Outcomes based on Goals(graph B)” we can first state that both lines corelate witch each other because its all based on percentages. Which means when success goes up, failure will go down and vice versa  (ex: when success is 50% fails will be 50%). Thinking this is the case having two lines for separate values that tells the same thing doesn’t really help tell the story. Meaning only one line in this case should be enough. We can also see that 45,000 seems to be an unreasonable goal having 100% of shows failed. This graph does create problems not actually having numbers and only percentages. This graph does show the fact that the play fever could have also shot up because of the goal given. Displaying one of the highest percentages based on a goal of $1,000 to $5,000 which in this case the goal was $2,885.
![Outcome_Base_on_Goal2.0.PNG](Outcome_Base_on_Goal2.0.PNG)
 
