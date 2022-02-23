# 2021 F1 Drivers share of their team points across career

This short project aimed to calculate their share in their team's points for each driver on the 2021 F1 grid across their entire careers.

# Data Collection

All the data needed for this project was collected by myself going through tables of as I figured that for such a small sample size it would be the easiest solution instead of writing code to collect data using a relevant API such as [Ergast Developer API](http://ergast.com/mrd/). What was also significant is taking into account the scenarios in which a driver changed their team in the middle of the season. As the points for that driver during that season had to be split in two parts one for each period spent in a different team.

# Data Cleaning

As in some of the seasons there are drivers/teams that do not score any points those had to be taken into account in the result calculation process. As we could get a situation in which a driver who scored a single point had 100% of his team's points as his team-mate did not score any points. Thus, I decided that only the seasons in which the team scored at least 5 points and both drivers on the team scored at least a point counted.

# Final Results
![drivers](https://user-images.githubusercontent.com/40291469/150645037-3d4fdeba-2459-44e1-b56b-f20a85c92971.jpg)
