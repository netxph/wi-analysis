# Software Development Capability Analysis
## by Marc Vitalis


## Dataset

The data consists of information regarding 5-year worth of workitems (1466 records) of a Software Development Team, which contains the timestamps of the stages of the development of workitem (new, doing, done), the developer who worked on the workitem and some additional information that describes the release where the workitem belongs to.

## Summary of Findings

I focused my study on finding the teams capability, the relationship of forecasted work and the actual work done, the distribution of work, and the capability of the individual resources. Plotting the relationship of the estimate and the actual work, I can't find any relationship, however, I noticed that they almost all group up on 1-20 days of work item and 1-40 points of estimate. The correlation is at low 0.34, and removing the waterfall era, it further reduced to 0.098, that means they have almost no relationship at all. Then, I observed the work distribution, to check the effect of the estimates. Waterfall and early months of hybrid era, we can see a very random spikes and dips of workitems. As the early era provided me noisy patterns, I started focusing on observing on the latter era. I learned that stories took twice as long as bugs to finish work. I plotted the work distribution with the provided workitem weight, I can now observe a better view of teams capability. The team is improving its capability through months with exception of the sudden peak last December 2018.

The team is also struggling with quality as bugs are a constant item per month having more items than stories. I also observed the teams' individual capability and they are almost on the same level, this maybe due to the fact that the team is doing pair programming.


## Key Insights for Presentation

For the presentation, I'd like to focus more on visualizing the teams capability and check if the team is improving throughout the years.

I start by introducing the cycle time (actual work) and exploring it's distribution, then tried to relate the estimation to perhaps normalize the size of stories. However, I found no relationship between estimation and actual work.

Aftrer that, I observed the teams work distribution per month to see if there's a balance, and perhaps to find reason why. The latter era shows a bit of consistency, but before that, the data show no pattern.

I then started exploring the capability of the team, zooming in on the individual capability. It's consistent that on latter era, the team and individual capabilities' continues to improve and kinda flatline in the last four months. There is however a huge spike last December 2018.